# 提交到git的Ruby脚本
使用简单方便,不用一遍一遍的进行 git add .   git commit   git  push  ,一切自动完成

## Example

把文件夹中的  fastlane文件复制到项目的根目录
cd到项目执行 下面命令
1. 提交到git  (本地和远程)
复制:**提到本地git1**文件 或者**提到远程git2**文件
```
   fastlane ManagerLib message:本次所修改的描述
```
   
2. 提交私有库或者公有库
复制:**提交到公有库github3**文件 或者**提交到私有库4**文件
```
 fastlane ManagerLib tag:0.1.0(标签号) target:项目的名字
```
## Requirements

## Author

WangZichen, 327574878@qq.com




