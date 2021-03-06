
# 2021 ZJU Computer Organization Student Repo

## 指导说明

* [Vivado安装说明（Win10）](./guide/Vivado的安装（Win10）.md)
  * 我下载不了安装器 => [Vivado Win10 Installer](https://pan.zju.edu.cn/share/2bf8125409716e04257aec3515)
* Vivado的个人版是需要自己注册Xilinx的账户然后登陆的。
* 由于众所周知的问题，Vivado的下载地址需要一些特殊的手段才能比较快地访问到，不过Installer的下载过程应该是比较顺畅的。

## Lab2问题

* xdc引脚约束文件应该放进**Constraints**中，而不是**Design Sources**里。
* `key_x`是什么信号，这个信号与`key_col`一样吗？
    * 这两个信号不一样。`key_col`从板级引脚中传过来，是不稳定的信号。通过在InputAntiJitter里整形后输出的`key_x`便是稳定的信号了。

