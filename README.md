ColorOS 16 双排（堆叠）信号

把 ColorOS 17 的双排信号样式移植到 ColorOS 16：主卡大信号 + 副卡小信号叠在同一个槽位，并在左上角显示 2G/3G/4G/5G 制式标。

· 双卡：C17 原生素材上下两排
· 单卡：满高素材，不叠副卡
· 制式标按 getDataNetworkType() 自动切换 2G/3G/4G/5G
· 颜色跟随状态栏时钟，深浅色/锁屏自动适配
· 不需要系统框架作用域，仅注入 com.android.systemui
