# 什么是git?
  git分布式版本控制系统 它可以在任何的时间点将我们的文件、文档的状态作为更新保存起来，也可以在任何时间点，将更新记录恢复回来

# git工作流程
  工作区=>暂存区=>git仓库

# git 命令
  git --version 查看git版本
  git init 定义文件夹为git仓库

## 提交人信息
  git config --global user.name xxx提交人姓名
  git config --global user.email xxx@xx.com 
  git config --list 查看git配置信息
  git status 查看工作区状态

## git连接仓库
  git remote add origin https://xxxx...
  git remote -v 查看已经连接的远程仓库

## git代码提交
  git add . 
  git commit -am "xxxxx"
  git push origin(仓库名) master(分支)
