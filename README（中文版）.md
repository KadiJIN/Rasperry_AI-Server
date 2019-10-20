# 笔记
基于树莓派的小型AI服务器
## 项目动机
2019年夏天开始在PRISME实验室的实习，着手一个将人工智能应用（检测潜在的糖尿病足）移植到安卓系统（针对于安卓手机）下的项目，接触到深度学习。
整个手机应用是本地离线的，算法将在手机上运行计算。对应地，产生了学习在线应用的想法，将算法放到rasperry上运行。
## 树莓派
树莓派官网有新手教程。推荐的OS-Resbian 适合新手，有基础的图形界面，命令行，蓝牙无线驱动，python。完整版有各种适合新手的IDE，也可以选择不装。
目前来看，Resbian不是我想要的OS,占用内存有点高，影响性能。
## 操作系统
选择哪一种操作系统来运行人工智能服务？
## Tensorflow API
Tensorflow 提供了针对嵌入式系统的API——TensorFlow Lite interpreter，同时也提供了只包含Tensorflow Lite runtime的包。因此我们可以不用下载整个TF库来运行人工智能模型。  
参考网站：[Python quickstrat](https://www.tensorflow.org/lite/guide/python)
