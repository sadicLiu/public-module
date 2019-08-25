# submodule
[参考教程](https://www.jianshu.com/p/9000cd49822c)

## 使用前提

- `submodule` 允许你将一个Git仓库当作另外一个Git仓库的子目录. 
这允许你克隆另外一个仓库到你的项目中并且保持你的提交相对独立.

## 添加子模块

- `git submodule add git@github.com:sadicLiu/public-module.git public`, 此命令将远程仓库克隆到
本地public文件夹中
- 添加子模块后运行 `git status`, 可以看到目录有增加1个文件.gitmodules, 这个文件用来保存子模块的信息.

## 查看子模块

- `git submodule`


