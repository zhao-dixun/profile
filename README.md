# profile #
profile for me

#### SSH keys ####
* rsa key pair
```
ssh-keygen -t rsa -C "dixun.zhao@qq.com" -f ~/.ssh/github_rsa
```

* ssh config
```
+-----------------------------------------------------------------------+
|	Host github.com				# 关键词		|
|		HostName github.com		# 主机地址		|
|		User git			# 用户名		|
|		IdentityFile ~/.ssh/github_rsa	# 私钥地址		|
+-----------------------------------------------------------------------+
```

* ssh github.com
```
ssh -T git@github.com
```

