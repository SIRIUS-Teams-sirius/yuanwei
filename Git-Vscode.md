## Link
SSH+Git+Gitee+Vscode: https://www.bilibili.com/video/BV1Fw4m1C7Tq?vd_source=981bb01520cc6145b619be991ee03206
## Github上配置SSH Key
https://blog.csdn.net/weixin_42310154/article/details/118340458?fromshare=blogdetail&sharetype=blogdetail&sharerId=118340458&sharerefer=PC&sharesource=YOUNICE_YU&sharefrom=from_link
## Git
git clone --depth 数字 决定克隆深度
### 对子模块进行递归的更新
git submodule update --init --recursive
### 查看状态，确定一下是否有没有track的子模块
git status
### 查看代码是谁改的
git config --global user.email " "
git config --global user.name " "
### 需要使用代码，但是不能直接在上面进行修改 在原有代码的基础上创建自己的代码 会创建新的分支（会克隆原有代码）
git checkout -b yuanwei/1210_test
## Vscode中 Git Graph插件的使用
git add xx.py
git commit -m "[planner]: add st boundary pre decider test" 添加评论
git push --set-upstream origin 文件名
##撤回
git reset --soft HEAD^
git push -f

##进阶功能
### 切换远程仓库
git remote -v (查看)
git remote add origin git@gitee.com... (添加新的远程分支)
git fetch --fetch

## 同其他人合作使用的命令
git merge 用于合并2个分支的历史合并
git rebase 是另一种合并更改的方式
## git 详细使用方法link
https://slides.tonycrane.cc/PracticalSkillsTutorial/2023-fall-ckc/lec2/#/4/7

## 把某一分支的特定提交引入当前分支
git cherry-pick <commit_hash>

#Tmux
apt-get install tmux
tmux new -s xxx
tmux kill-server
tmux kill-session -t xx



