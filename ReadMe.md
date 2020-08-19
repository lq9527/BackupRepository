# BackupRepository ReadMe

## IncrementLint.zip
- 原著作以及githup地址
https://github.com/tianwailaike61/IncrementLint
- 原理：gradle 插件，实现对lint 的增量检查；

```
官方没有提供制定文件的lint检测，全是全量的；
这里利用git diff 找出增量的文件；
在通过修改lint的源码，把文件加进去，实现的

原作者的项目IncrementLint，运行有bug，特此修改了下，在此做一个备份，供以后自己查询使用
```