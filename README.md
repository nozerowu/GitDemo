# Git 使用与学习
## 基于GIT权威指南
### Git初始化

#### 登录
1. git config --golbal user.name 'Nozero'
1. git config --golbal user.email 3921342@qq.com
#### 设置命令别名
1. sudo git config --system alias.st status
1. sudo git config --system alias.ci commit
1. sudo git config --system alias.co checkout
1. sudo git config --system alias.br branch
#### 开启颜色
1. git config --global color.ui true
#### 创建一个库
1. mkdir GitDemo
1. cd GitDemo
1. git init
> 也可以直接 git init GitDemo()
#### 将其它git网站中的git到本地
1. 选择本地目录，在GitHub Desktop上添加本地项目。
1. 在码云GIT上新建项目。
1. 命令行使用git remote add origin GIT地址 将本地项目与码云GIT项目建立关系。
1. 先使用命令git pull origin master 同步代码。
1. 使用命令git push origin master 将本地代码推送到远程项目。
1. 在GitHub Desktop上尽情地提交、同步吧！





