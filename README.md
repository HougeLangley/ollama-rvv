
# ollama-rvv

曾经我的想法是将修改的内容提交上游，但是目前基于以下一些特殊情况，我只能先 fork 原 ollama 重新做一个版本：

1. 目前 rvv 虽然已经有成型的版本，但是目前了解到的情况包括了多种版本的 rvv，包括且不限于玄铁的 xthadvector rvv1.0-11000, rvv1.0-12000，最新的 rvv1.0。因此在上游化的时候不得已会出现非常离奇的情况。我将试图维护这些乱七八糟的东西，尽力而为，希望早日统一。

2. 目前 RISC-V 不仅有 rvv 这样的适量扩展指令集，还有 OEM 厂商增加了类似 ime 这样的整数矩阵扩展指令集。这样的指令集因为需要 OEM 特定的 SDK 进行构建，所以这里就只能作罢。

那么目前的希望是，能够维护一个支持不同 rvv 扩张的 ollama 版本，原则上会一周更新一次。
