# Day1 Git的使用指南
## 基础命令
# 一: 创建仓库文件夹

## linux系统和unix系统下的文件夹创建
````Cmder
λ mkdir gitDemo     创建一个名为gitDemo的文件夹
λ cd  gitDemo       进入gitDemo文件夹
λ pwd               显示当前文件夹
````
# 二: 初始化git项目
````Cmder
λ git init                把打开的当前目录初始化成git可以管理的目录

````
# 三: 把文件添加到版本库
````Cmder
λ git add  readme.md      使用git add命令把readme.md文件添加到git仓库
````
# 四: 新建分支
````Cmder
λ git branch  dev      创建一个新的分支
````
# 五: 切换分支
````Cmder
λ git checkout  master      切换到主分支
````
# 五: 关闭速度优先模式并合并分支
````Cmder
λ git merge  --no-ff -m"先关闭默认得关闭速度优先模式再合并分支"      
````