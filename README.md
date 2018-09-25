# Android Debug Bridge On Android

在你的Android设备上使用Android Debug Bridge（包括Fastboot）

# 这是什么？

Android Debug Bridge，简称ADB。

这是一套 Android 调试工具，可以对任何 Android 设备进行 Debug 级操作。

包括一些非常危险的操作，Android Debug Bridge都能完成。

你甚至能在 Android Debug Bridge 上直接使用设备的 Shell，而且能直接进行比普通的 Android Shell 权限要求更高的操作。

这也催生了一些有趣的玩法，如:Brevent （黑阈），IceBox（冰箱），Island（岛）

这个 Magisk Module 就可以让你在你的 Android Shell 上（如:NeoTerm,Termux,TermialEmu）运行 Android Debug Bridge。

而且，Fastboot 工具也随该模块自带。

# 如何使用？

安装此模块后，打开你的 Android 终端，在里面输入: `adb [command]` 即可使用 Android Debug Bridge。

输入: `fastboot [command]` 即可使用 Fastboot 工具。

具体怎么用，我想你还是 [百度](https://www.baidu.com) 或 [Google HK](https://www.google.com.hk) 一下吧。

毕竟我教不会。

# 一些有趣的玩法……

其实你可以使用该 Fastboot 工具，给其他的 Android 设备进行刷机（解锁bootloader，刷Recovery，甚至救砖）操作。当然了，你要有一根可以连接两台手机的线。（手动滑稽）

而且你可以用该 ADB 工具，给其他的 Android 设备进行调试。（再次手动滑稽）

其实，只要你想的出来，它都可以做，真的。（最后一次滑稽）

# 如果你想在 Android 端调试 Android 设备，这个模块一定适合你!
