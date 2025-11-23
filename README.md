# 简介

本仓库为 USTC 编译工程 2025 的课程实验仓库。在本学期的编译实验中，你们将构建一个从词法分析器开始到后端代码生成的JIANMU编译器。

你们需要 fork 此 repo 到自己的仓库下，随后在自己的仓库中完成实验。


## 测试脚本使用方法

eval_lab2.sh: 
    没有参数，直接运行即可，结果会生成在 eval_result 下

如何编译：
``` bash
# 如果你想安装到usr/local/bin
cmake -B build && cmake --install build
# 否则 执行以下指令
cmake -B build && cmake --build build
```

无论哪种命令，你都可以在 build/ 下找到 cminusfc 等可执行文件
