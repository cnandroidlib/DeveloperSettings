DeveloperSettings
============
用于快速启动开发者选项中一些常用的功能，需要root权限
之前使用的是[Trinea](https://github.com/Trinea)的[开发助手](http://www.trinea.cn/android/android-develop-and-debug-tools/)，本来想在这之上适配 Android 7.0 新增加的Tile，后面发现未开源就开发了这个，目前功能没那么多，只增加了我自己常用的。
<img src="https://github.com/XuDaojie/DeveloperSettings/blob/master/image/device-2017-03-07-181044.png" width="480" height="800">
        
<!-- ![](https://github.com/XuDaojie/DeveloperSettings/blob/master/image/device-2017-03-07-181044.png) -->
<!-- ![](https://github.com/XuDaojie/DeveloperSettings/blob/master/image/device-2017-03-07-181131.png) -->
<!-- ![](https://github.com/XuDaojie/DeveloperSettings/blob/master/image/device-2017-03-07-181244.png) -->
<!-- ![](https://github.com/XuDaojie/DeveloperSettings/blob/master/image/device-2017-03-07-181502.png) -->


## 原理
直接参考了 Android 源码中设置的代码，对于里面使用到的隐藏Api，目前使用反射和Shell方式调用。

## Thanks
[aosp-packages/apps/Settings](https://android.googlesource.com/a/platform/packages/apps/Settings/+/android-7.1.1_r14)
[AndroidXRef](http://androidxref.com/7.1.1_r6/xref/packages/apps/Settings/src/com/android/settings/DevelopmentSettings.java#updateShowTouchesOptions)
[Trinea/android-common](https://github.com/Trinea/android-common/blob/master/src/cn/trinea/android/common/util/ShellUtils.java#L9)

