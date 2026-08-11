# 手帐模拟器

一个可以“自己写”的单文件 HTML 手帐模拟器：文字按笔迹逐字出现，下划线、画圈、方框、荧光标记和饼图沿着轨迹完成，手和笔始终跟随当前笔尖。

## 直接运行

双击 [`手帐模拟器.html`](./手帐模拟器.html) 即可打开。无需构建工具、服务器或第三方依赖。

左侧可以编辑标题、引导句、知识点动作和饼图数据；点击“应用并重播”后，底部时间轴会逐帧播放新的手帐内容。

## 演示内容

当前示例用轻松的手帐语气比较 Codex 与 Claude：

- Codex：会开终端的行动派
- Claude：耐心的长文编辑
- 同档月费、额度消耗和返工成本的趣味化复盘

价格仅作为美元月费示意，地区、方案和额度以官方页面为准：

- [OpenAI ChatGPT 定价](https://openai.com/chatgpt/pricing)
- [Anthropic Claude 方案说明](https://support.anthropic.com/en/articles/11049762-choosing-a-claude-ai-plan)

## 截图与录屏

![最终演示画面](./output/playwright/codex-claude-cost-demo-poster.png)

- [MP4 无声演示](./output/playwright/codex-claude-cost-demo.mp4)
- [逐阶段截图](./output/playwright/screenshots/)

录屏参数：1440×1000、30 fps、约 37 秒、H.264、无音频。视频由当前 HTML 页面逐帧捕获生成，不是预渲染视频。

## 目录

```text
手帐模拟器/
├── 手帐模拟器.html
├── assets/
│   └── hand-pen-generated-v1.png
└── output/playwright/
    ├── codex-claude-cost-demo.mp4
    ├── codex-claude-cost-demo-poster.png
    └── screenshots/
```

