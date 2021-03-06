**中文｜[English](https://github.com/exthmui/android/blob/exthm-11/README_EN.md)**

# exTHmUI

## 什么是 exTHmUI ？

![exthm logo](https://i.niupic.com/images/2020/06/16/8gWB.png)

这是一个由国内东方众自行发起制作、以东方 Project 元素为特色的类原生 Android 项目，基于 [LineageOS](https://github.com/LineageOS)

> exthm-10 EOL 时间为 2021 年底，届时请迁移至 exthm-11 或更新的分支
> 很抱歉让大家失望了 qwq
> 因为一些原因我们未能实现当初基于 AOSP 的想法，因此本分支将继续基于 LineageOS 开发

## 同步源码

> repo 是一种用于管理多个 Git 仓库的工具

要开始编译 exTHmUI，你需要熟悉 Repo 和 Git

要开始同步源码，请使用这些命令

```shell
repo init -u https://github.com/exthmui/android.git -b exthm-11
repo sync
```

您也可以使用如下命令来初始化仓库，这样可以节省磁盘空间

```shell
repo init -u https://github.com/exthmui/android.git -b exthm-11 --depth=1
repo sync
```

### 开始编译

```shell
. build/envsetup.sh
lunch exthm_[您的设备代号]-userdebug
mka bacon
```

## 向 exTHmUI 贡献提交

我们欢迎开发者通过 [Gerrit](https://www.gerritcodereview.com/) 参与到 exTHmUI 的开发中，请访问 [exTHmUI Code Review](https://review.exthmui.cn/)

## 查阅 wiki

如果对详细的系统介绍和编译有兴趣，欢迎访问我们的 [Wiki](https://wiki.exthmui.cn/)
