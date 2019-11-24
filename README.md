# profile

profile for me

## SSH keys

- rsa key pair

```bash
ssh-keygen -t rsa -C "dixun.zhao@qq.com" -f ~/.ssh/github_rsa
```

- ssh config

```bash
    Host github.com                     # 关键词
        HostName github.com             # 主机地址
        User git                        # 用户名
        IdentityFile ~/.ssh/github_rsa  # 私钥地址
```

- ssh github.com

```bash
ssh -T git@github.com
```

## Visual Studio Code

- [vs code](https://code.visualstudio.com)

## Sublime Text

- [sublime test](http://www.sublimetext.com)

- [package control](https://github.com/wbond/package_control)

- os x

```bash
defaults write com.sublimetext.3 ApplePressAndHoldEnabled -bool false
```

- settings

```json
{
  "font_size": 13,
  "ignored_packages": [],
  "vintage_start_in_command_mode": true
}
```

- key map

```json
[
  { "keys": ["super+k", "super+u"], "command": "" },
  { "keys": ["super+k", "super+l"], "command": "" },

  { "keys": ["super+shift+x"], "command": "upper_case" },
  { "keys": ["super+shift+c"], "command": "lower_case" },

  { "keys": ["ctrl+shift+down"], "command": "" },
  { "keys": ["ctrl+v"], "command": "select_lines", "args": { "forward": true } }
]
```
