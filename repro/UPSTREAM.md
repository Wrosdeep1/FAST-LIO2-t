# 上游基线记录

- 记录日期：2026-10-26（Asia/Shanghai）
- 项目仓库：https://github.com/Wrosdeep1/FAST-LIO2-t.git
- 上游仓库：https://github.com/hku-mars/FAST_LIO.git
- 上游分支：ROS2（区分大小写）
- 上游提交：cc3c9e8b1469b33b8072764d6db2348ed6dc597f
- 基线标签：upstream-ros2-20261026
- 基线可达提交数：124
- 克隆方式：完整克隆，非浅克隆
- 子模块：include/ikd-Tree
- 子模块仓库：https://github.com/hku-mars/ikd-Tree.git
- 子模块固定提交：e2e3f4e9d3b95a9e66b1ba83dc98d4a05ed8a3c4
- 本仓库原始初始化提交：705b2040f768c148fddb848629faf812a41d5f85

## 远程配置

- origin：Wrosdeep1/FAST-LIO2-t
- upstream：hku-mars/FAST_LIO
- 项目主分支：main

初始化合并保留双方提交历史，未修改算法源码。上游 README 保留在根 README 中。

## 本机环境与验证状态

本次初始化时检测到 WSL 2、Ubuntu 22.04 和 /opt/ros/humble。
这些信息仅为环境存在性检查，不代表依赖齐全或编译运行成功。
本次未安装依赖、未编译、未下载数据、未运行算法。

数据来源、具体传感器配置及验证通过的运行命令待首次实验时记录。

## 检查基线

在仓库根目录执行：

```bash
git show --no-patch upstream-ros2-20261026
git submodule status --recursive
git remote -v
```

在另一台机器重新克隆后，可重新添加上游远程：

```bash
git remote add upstream https://github.com/hku-mars/FAST_LIO.git
git fetch upstream
```
