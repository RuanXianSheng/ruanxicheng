Host github
HostName ssh.github.com ”git服务的地址“
User xxxx ”用户名称“
IdentityFile ”替换为上面生成的ssh文件（私🔑）“
# PreferredAuthentications publickey ”（开启后表示优先使用公🔑还是私🔑）“
Port 443 ”联机的端口“
 
Host gitee
HostName ssh.github.com "git@github.com:RuanXianSheng"
User ruanxiansheng
IdentityFile id_rsa.pub
# PreferredAuthentications publickey