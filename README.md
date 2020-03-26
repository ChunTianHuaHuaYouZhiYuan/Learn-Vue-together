# Git 日常

```
git config 
git clone
git add 
git commit -m 'init'
git commit -m 'add git comand'  提交到仓库之中保存
```
## 添加html文件
```
git add .   //添加所有文件 到暂存区  
```
git status // 查看版本当前状态
git reset HEAD // 退回上次的修改内容

git log //查案详细的版本
git reflog   //查看 所有分支的版本

git rest --hard HEAD^  //进行版本的切换
git rest --hard HEAD^^ //切换上一次版本 后面加多个 尖角号
git rest --hard HEAD~1 //切换到某一次的版本状态