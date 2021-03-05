
# 2021 ZJU Computer Organization Student Repo

## 指导说明

* [Vivado安装说明（Win10）](./guide/Vivado的安装（Win10）.md)
  * 我下载不了安装器 => [Vivado Win10 Installer](https://pan.zju.edu.cn/share/2bf8125409716e04257aec3515)

## Lab2问题

* `key_x`是什么信号，这个信号与`key_col`一样吗？
    * 这两个信号不一样。`key_col`从板级引脚中传过来，是不稳定的信号。通过在InputAntiJitter里整形后输出的`key_x`便是稳定的信号了。

