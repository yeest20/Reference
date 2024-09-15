# 如何上传代码到github
 - #string 表示string要被替换成为具体内容
## 全新文件上传
1. 在github上新建一个repository
2. 在命令行中进入到要上传的文件夹
`cd #filename`
3. 初始化git
`git init`
4. 添加要上传的文件（夹）到makefile文件
`git add #filename`
5. 提交
`git commit -m "#versionName"`
versionName: 版本命名
6. 分支创建
`git branch -M main`
7. 连接repository
`git remote add origin git@github.com:#userName/repositoryName.git`
**Prob: NO 密钥配对** 
userName:github用户名
repositoryName:存储库名
8. 上传
`git push -u origin main`

## 更新repository
1. 添加新文件
`git add #filename`
2. 提交
`git commit -m "#version"`
3. 连接repository
`git remote add origin git@github.com:#userName/repositoryName.git`
4. 上传
`git push -u origin main`
**Prob: NO 上传不同分支方式**
