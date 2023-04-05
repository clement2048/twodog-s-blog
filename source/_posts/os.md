---
title: os
date: 2023-04-04 14:59:14
tags:
---





##### 进程相关命令

###### 1.taskset命令

这里只说一下各个参数的含义：
1.0：这里说的应该是运行在0号虚拟cpu上；

2.<n>:

```shell
ps ax|wc -
taskset -c 0 ./sched <n> <total> <resol>
```

