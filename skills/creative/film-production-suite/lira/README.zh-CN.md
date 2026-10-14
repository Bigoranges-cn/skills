# LIRA 中文介绍

## 功能

LIRA 是面向 AI 图像生成与编辑的提示词优化 Skill。它采用 4D 流程（解构、诊断、开发、交付），覆盖角色、场景、道具、参考图和局部编辑，并针对 Higgsfield Soul 2.0、Soul Cinema、Nano Banana Pro、Seedream 4.5、GPT Image 2 等模型给出路由建议。

## 使用方法

把原文件内容作为 Skill 指令加载，然后提供目标画面、用途、目标模型、画幅、参考图情况和必须保留的元素。若是图像编辑，应同时明确“要改变什么”和“必须保持什么”。该 Skill 默认要求最终提示词用英文，解释可随用户语言。

## 平台限制

Soul ID、AI Cast、NBP、Seedream 与 GPT Image 2 的能力和参数属于特定平台。用于即梦时，应保留人物身份特征、构图、光线、材质、色彩与改动范围等自然语言信息，删除或改写平台专有参数；即梦是否支持参考图、身份一致性和局部编辑，以当前产品界面为准。

## 原文件与来源

- 原文件：[skill.md](./skill.md)
- 上游路径：`lira/skill.md`
- 上游 Blob：`1e5c80731d5f6ccd0d2e803678598da42ce835e7`
- 固定版本：[`da8e7876d7b166451473d8f2ef2ad06c74395804`](https://github.com/GAGAA-HUE/ASHUO-claude-skills/commit/da8e7876d7b166451473d8f2ef2ad06c74395804)
- 直接来源：[`GAGAA-HUE/ASHUO-claude-skills`](https://github.com/GAGAA-HUE/ASHUO-claude-skills)
- 许可证：未声明；详见 [总说明](../SOURCE_AND_LICENSE.md)
