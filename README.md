# profile #
profile for me

#### SSH keys ####
* rsa key pair
```
ssh-keygen -t rsa -C "dixun.zhao@qq.com" -f ~/.ssh/github_rsa
```

* ssh config
```
    Host github.com                     # 关键词
        HostName github.com             # 主机地址
        User git                        # 用户名
        IdentityFile ~/.ssh/github_rsa  # 私钥地址
```

* ssh github.com
```
ssh -T git@github.com
```

#### SUBLIME TEXT 3 ####
* package control 
`View > Show Console`
```
import urllib.request,os,hashlib; h = '6f4c264a24d933ce70df5dedcf1dcaee' + 'ebe013ee18cced0ef93d5f746d80ef60'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```

* settings 
```
{
    "font_size": 13,
    "ignored_packages": [],
    "vintage_start_in_command_mode": true
}
```

* os x
```
defaults write com.sublimetext.3 ApplePressAndHoldEnabled -bool false
```
