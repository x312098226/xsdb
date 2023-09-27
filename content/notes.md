+++
title = 'Hugo笔记'
date = 2023-09-19T17:44:16+08:00
draft = true
+++

1. hugo 版本
```shell
hugo version
hugo v0.118
```
1. 生成网站
```shell
hugo new site [path] [name]
```

1. 新建文章
```shell
hugo new [path] [name]
```

1. 本地启动测试
```shell
#  --disableFastRender 强制生成新网站
hugo server [--disableFastRender]
```

1. 重新构建
```shell
# 只用hugo不带参数，不会清除已删除的文件
hugo  --cleanDestinationDir
```