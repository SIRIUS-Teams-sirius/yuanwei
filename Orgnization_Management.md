Resource: 【【GitHub Orgnization】用组织和子模块高效管理团队】https://www.bilibili.com/video/BV1Fi4y1m7gp?vd_source=981bb01520cc6145b619be991ee03206

## 更新子模块到main里的命令操作

~~~c
git submodule update --remote
git commit -a //会出现一个文件 写入update submodule 文件名即可
git push origin main //更新主仓库
~~~

## 从git快速下载左右文件（递归克隆仓库）

~~~C
git clone --recursive https://github.com/example/example.git //递归克隆仓库
git submodule update --remote//更新子模块
~~~

