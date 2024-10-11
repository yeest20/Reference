# samba 文件共享

## 分享端
### 安装samba
`sudo apt insall samba`
`sudo apt insall samba-common-bin`

### 设置
1. 设置共享文件
- `sudo vim /etc/samba/smb.conf`
- 在文件末尾添加
`[name(共享文件名)]`
`path = [共享文件路径]`
设置权限
`writeable = yes ` 
`browseable = yes`
`public = no`
2. 增加用户
- sudo smbpasswd -a YEE

  
## 客户端
### windows
打开文件管理器，添加网络路径
`\\IP\filePah`

