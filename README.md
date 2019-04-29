# gitstudy
git学习
:sunglasses:
## 任何一门技术的学习都不是一日之功！脚踏实地一点点的积累练习比什么都强。
sourcetree test!
## 如果要把.gitignore 里忽略的文件强制添加上去，可以使用  
git add -f .project  
git gitconfig -l 列出所有配置项  
## 查看提交历史  
git log  
## -p 选项展开显示每次提交的内容差异，用 -2 则仅显示最近的两次更新  
git log -p -2  
[git提交历史](https://git-scm.com/book/zh/v1/Git-%E5%9F%BA%E7%A1%80-%E6%9F%A5%E7%9C%8B%E6%8F%90%E4%BA%A4%E5%8E%86%E5%8F%B2)  
## 定义别名  
git config --global alias.ci commit  
也可以在文件.gitconfig 中直接添加别名，这个需要退出分支，在当前用户主目录  
或者vim ~/.gitconfig 编辑
## 存储凭证  
git config --global credential.help vincred  
查看仓库使用的协议  
git remote -v  
## 生成RSA秘钥对  
ssh-Keygen -t rsa -C "you email"  
在github网站添加公约  
使用ssh协议，克隆仓库或者添加远程连接

## 查看全部git子命令
git help -a   
## 逐行查看文件的修改历史  
git blame <file name>   
## 从100行开始，查看10行，逐行查看修改的历史  
git blame -L 100,110 <file name>  
## 列出打算清除的档案  
git clean -n  
## 真正的删除  
git clean -f  
## 连.gitignore中忽略的档案也清除  
git clean -x -f

## git status ，显示简单提示
git status -->git status -sb  
## 添加，删除，编辑，移动，改名  
git add .  
## **一个文件多个提交**  









