# OperationSystem
2023操作系统学一学

## 1 计算机系统概述
### 1.1 操作系统的基本概念
- 01.说明库函数与系统调用的区别和联系

> 库函数是语言或应用程序的一部分，可以运行在用户空间中。而系统调用是操作系统的一部分，是内核为用户提供的程序接口，运行在内核空间中，而且许多库函数都会使用系统调用来实现功能。未使用系统调用的库函数，其执行效率通常要比系统调用高。这是因为使用系统调用时，需要上下文的切换以及状态的转换（从用户态转为核心态）。
