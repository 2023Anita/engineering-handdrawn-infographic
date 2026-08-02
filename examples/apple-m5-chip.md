# 示例：Apple M5 芯片功能模块图

这是一个“功能模块示意”案例，不把图像模型生成的布局描述成 Apple 未公开的晶体管级物理版图。

```text
使用 $engineering-handdrawn-infographic 生成一张竖版手绘工程科普信息图。

主题：MacBook Air M5 芯片的功能组成
中央设备：局部打开的 Apple silicon 风格 M5 芯片封装，只在封装中央写 M5，不要 Apple 标志
标签数量：6
标签：
1. 10核 CPU
2. 最高10核 GPU
3. GPU 神经网络加速器
4. 16核神经网络引擎
5. 统一内存 · 153GB/s
6. 媒体引擎
原理说明：
CPU负责通用计算，GPU负责图形与并行任务；
神经网络加速器和16核神经网络引擎提升设备端AI；
统一内存高速共享数据，媒体引擎处理视频编解码。
补充约束：不要把 N1 无线芯片、SSD、Thunderbolt 端口、摄像头或电池画成 M5 内部模块；这是公开规格的功能模块示意，不是真实晶体管版图。
```

参考资料：Apple 官方 [MacBook Air with M5](https://www.apple.com/newsroom/2026/03/apple-introduces-the-new-macbook-air-with-m5/) 与 [M5 芯片说明](https://www.apple.com/ca/newsroom/2025/10/apple-unleashes-m5-the-next-big-leap-for-apple-silicon/)。
