ColorOS堆叠信号

把 ColorOS 的双排（堆叠）信号样式做出来：主卡大信号 + 副卡小信号叠在同一槽位，左上角显示 2G/3G/4G/5G 制式标。

· 双卡：上下两排（主卡大信号 + 副卡小信号）
· 单卡：满高素材，不叠副卡
· 制式标按 getDataNetworkType() 自动切换 2G/3G/4G/5G
· 颜色跟随状态栏时钟，深浅色/锁屏自动适配
· 仅注入 com.android.systemui，ColorOS 15/16 通用
