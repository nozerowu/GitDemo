# Git 使用与学习
## 基于GIT权威指南
### Git初始化

#### 登录
1. git config --golbal user.name 'Nozero'
1. git config --golbal user.email 3921342@qq.com

#### 设置命令别名
1. git config --system alias.st status
1. git config --system alias.ci commit
1. git config --system alias.co checkout
1. git config --system alias.br branch

#### 开启颜色
1. git config --global color.ui true

#### 创建一个库
1. mkdir GitDemo
1. cd GitDemo
1. git init
> 也可以直接 git init GitDemo()

#### 删除一个远程库
1. git remote rm origin

#### 显示远程库
1. git remote -v

#### 添加一个远程库
1. git remote add origin git@github.com:nozerowu/GitDemo

#### 第一次push
1. git push -u origin master



#### 重置
1. git reset HEAD
1. git reset --filename
1. git reset --soft HEAD^
1. git push force
> HEAD可以理解为头指针，是当前工作区的“基础版本”

#### 保存当前工作进度
1. git stash
1. git stash list

#### 恢复工作进度 
1. git stash pop

#### 里程碑
1. git tag v0.1.1
1. git push origin v0.1.1 #

#### 将其它git网站中的git到本地
1. 选择本地目录，在GitHub Desktop上添加本地项目。
1. 在码云GIT上新建项目。
1. 命令行使用git remote add origin GIT地址 将本地项目与码云GIT项目建立关系。
1. 先使用命令git pull origin master 同步代码。
1. 使用命令git push origin master 将本地代码推送到远程项目。
1. 在GitHub Desktop上尽情地提交、同步吧！

#### git基础操作





