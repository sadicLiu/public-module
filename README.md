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

## 更新子模块

- 更新项目内子模块到最新版本: `git submodule update`
- 更新子模块为远程项目的最新版本: `git submodule update --remote`

## 克隆包含子模块的项目

1. 递归克隆整个项目
   ```git
   git clone git@github.com:sadicLiu/public-module.git public --recursive
   ```
2. 先克隆父项目, 再克隆子项目
   - 克隆父项目
   - 查看子模块: `git submodule`
   - 初始化子模块: `git submodule init`
   - 更新子模块: `git submodule update`
   
   
   
   
   



