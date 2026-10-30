ColorOS堆叠信号 1.2

把 ColorOS 17 的双排（堆叠）信号样式带到 ColorOS 15 / 16：主卡大信号 + 副卡小信号叠在同一槽位，左上角显示 2G/3G/4G/5G 制式标。只替换信号图标的绘制内容，不动布局、不新增 view。

· 双卡：上下两排（主卡大信号 + 副卡四颗小点）
· 单卡：满高素材，不叠副卡
· 制式标按当前数据网络自动切换 2G/3G/4G/5G，WiFi 连接时自动隐藏
· 颜色完全交给系统（转发 setImageTintList / setColorFilter），通知栏、控制中心、App 内、桌面四处均与电池、网速逐像素一致
· 随分辨率 / 显示大小自动缩放，与同一排图标齐高
· 网速刷新周期由原厂 4 秒提升到 1 秒
· 仅注入 com.android.systemui，ColorOS 15 / 16 通用

下载：ColorOSStackSig-v1.2.apk

安装后请在 LSPosed 里启用，作用域勾选「系统界面」（com.android.systemui），然后重启系统界面。

源码：https://github.com/Hoerire/ColorOS-SignalStack
