# 超算实训（HPC）
<div class="badges">
<span class="badge cs-badge">大一短学期</span>
<span class="badge cs-badge">课程综合实践 Ⅰ</span>
</div>

## 课程学习内容
浙江大学超算队 [ZJUSCT](https://www.zjusct.io) 开设的短学期课程，为超算的入门性质课程，除此之外课程成绩将作为超算队纳新选拔的主要依据。

课程包含知识性的计算机体系结构与网络 (由超算队老师讲解)、讲座类型的超算相关话题介绍以及实践性的高性能计算代码实现与 Lab 介绍（由超算队队员讲解）。

 Lab 基本围绕课程内容设计，涵盖了超算比赛中会遇到的典型问题:

- Lab 1: 虚拟机模拟搭建小型集群
- Lab 2: Numpy 与向量化
- Lab 3: GPU 编程基础与优化
- Lab 4: 并行计算与 CPU 通用矩阵乘法
- Lab 5: 机器学习与训练系统

另有大作业，一般是在国内的三大超算比赛 (CPC/ICPC/PAC) 选择一个组队参赛，最后进行统一的展示并进行打分（主要参考初赛最终的优化效果）。

由于计算机科学与技术培养方案中并行计算和 GPGPU 编程等课程并未真正开设，本课程可能是唯一能学到这些知识的本科课程（除了翁恺老师的竺院 C 程会讲一些基本的并行编程）。从实用性方面来说，在本课程中也会学到如 Linux 命令行操作、基础 python 使用和机器学习入门等内容，即使不以参加超算队作为目标，了解这些知识对日后的课程学习也有比较大的帮助。而对于有意向加入超算队的同学来说，本课程也是选拔的重要环节，超算队将在课程结束后根据成绩和面试进行纳新。

除此之外，本课程会提供超算平台和显卡资源供 Lab 使用，在三项国内比赛中也有机会接触到申威/AMD/Intel的新硬件。


## 分数构成

所有分数由 Lab 和大作业组成，没有其他成分。部分 Lab 会有一些加分的 Bonus 。由于具有选拔性质，本课程的 Lab 较为硬核，但从往年的结果来看，至少一半的同学可以得到 90 分以上的成绩。


## 先修要求
良好的 C 基础，可以提前了解一下 Linux 的使用。除了基本的 C 语言编程之外本课程授课都是从零基础开始（注意 Numpy 的使用并不要求预修 python）。本课的实验平台基于 Linux，提前熟悉 Linux 命令行的使用做实验会更轻松一些。


## 任课老师
课程挂名为陈建海老师，由超算队指导老师和超算队队员（基本上是大二到大四的本科生）共同授课，内容比例约 1:1。整体来说氛围比较活跃，会建一个没有老师的匿名群用于答疑和吐槽，Lab 均由队员批改，会照顾学生们的实际情况（虽然有难度但会给够时间+努力捞人）。

## 参考资料

- [HPC101 2022 Labs](https://www.zjusct.io/HPC101-Labs-2022/)
- [2022年小学期广告](https://www.cc98.org/topic/5332030)
- 使用 Windows 的同学可以了解一下 WSL (Windows Subsystem for Linux)，可以支持在 Windows 里直接使用一个 Linux 的命令行而不用安装虚拟机。虽然本课程没有在自己的电脑上使用 Linux 环境的需求，但是对于日后有需求的课程（如数据库、操作系统）来说 WSL + VSCode 的体验要比虚拟机好不少