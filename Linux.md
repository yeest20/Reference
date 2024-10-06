# Linux 命令行
### 文件属性与权限
`chgrp` 修改文件用户组
`chown` 修改文件拥有者
`chmod` 修改文件权限    
- r : 4   w : 2   x: 1
- u:user g:group o-others a-all
+:加入 -:移除 =:设置
 r w x:权限 
### 目录
 `cd` 切换目录
 `pwd` 当前目录 
 -P：显示真实目录，而不是链接
 `mkdir`创建目录
 -m:设置权限
 -p:递归创建
`rmdir`删除空目录
-p:递归删除上层空目录
`PATH`执行文件路径的变量
`cp`:复制
`rm`删除
`mv`移动
`basename`文件名
`dirname` 目录名
### 文件
##### 查看
`cat`第一行开始查看
`tac`最后开始查看
`nl`同时输出行号
`more`一页一页显示
`less`同more，但可前翻页
`head`前几页
`tail`末尾几页
`od`以二进制方式读取
##### 定位
1. 下载locate命令
`sudo apt-get install mlocate`
2. 定位文件
`locate [finename]`
### 进程
1. 查看进程
`ps`
2. 杀死进程
`kill PID`
### 查看man手册
1. 查看x手册
`man x`
2. 查看手册
`man -k x`  模糊查找
`man -f x` 精确查找
### 系统控制
1. 写硬盘
`sync`
2. 获取root权限
`su / sudo -i`
3. 系统控制（关机）
`systemctl -[options]`
`halt`:系统停止
`poweroff`:关机
`reboot` 重启
`suspend`: 休眠
