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
