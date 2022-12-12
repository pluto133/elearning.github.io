```markdown
C:\Users\Administrator>ssh -T git@github.com
Enter passphrase for key 'C:\Users\Administrator/.ssh/id_ed25519':
git@github.com: Permission denied (publickey).

C:\Users\Administrator>ssh -T git@github.com
Enter passphrase for key 'C:\Users\Administrator/.ssh/id_ed25519':

C:\Users\Administrator>ssh-keygen -t rsa -C "fanmike@126.com"
Generating public/private rsa key pair.
Enter file in which to save the key (C:\Users\Administrator/.ssh/id_rsa):
Created directory 'C:\Users\Administrator/.ssh'.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in C:\Users\Administrator/.ssh/id_rsa.
Your public key has been saved in C:\Users\Administrator/.ssh/id_rsa.pub.
The key fingerprint is:
SHA256:QVwT8qxu3f2qI8GaKSnJadZutqilOTTA7LIDVZKjRjE fanmike@126.com
The key's randomart image is:
+---[RSA 3072]----+
| E..   .o.+.     |
| .= .  ..+ .     |
|+. +    . o      |
|o+.      o       |
|oo      S.       |
|o.o    . .o. .   |
|oo o.+ .o+... .  |
|o .+B.*.+ . .  . |
| .+=.=oo   ..o...|
+----[SHA256]-----+

C:\Users\Administrator>ssh -T git@github.com
load pubkey "C:\\Users\\Administrator/.ssh/id_rsa": Permission denied
The authenticity of host 'github.com (20.205.243.166)' can't be established.
ECDSA key fingerprint is SHA256:p2QAMXNIC1TJYWeIOttrVc98/R1BUFWu3/LiyKgUfQM.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com,20.205.243.166' (ECDSA) to the list of known hosts.
Hi pluto133! You've successfully authenticated, but GitHub does not provide shell access.

```
Git使用ssh协议配置Github远程仓库避免踩坑指南 windows

[link](ttp://t.zoukankan.com/hejing195-p-14699939.html)
