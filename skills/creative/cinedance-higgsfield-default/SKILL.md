---
name: cinedance-higgsfield-default
description: 默认处理 AI 视频生成提示词、电影化镜头设计、分镜、场景调度、角色与道具连续性、运镜、光学、动作时序、物理和灯光控制。面向 Seedance 2.x、Higgsfield Seedance，也可在明确说明平台差异后适配即梦等其他视频生成平台。图像静帧任务不使用本 Skill。
---

# CINEDANCE HIGGSFIELD 默认视频工作流

这是原版 CINEDANCE V4 的 Codex 兼容入口。处理符合描述的 AI 视频任务时，默认使用本 Skill。

开始工作前，完整读取 [references/original-skill.md](references/original-skill.md)，并以其中的 CINEDANCE V4 规则作为主要工作方法。

## 适配边界

- 不把用户某个具体项目的剧情、角色或视频内容固化进 Skill。
- 用户明确指定其他视频 Skill、平台格式或工作流时，以用户当次要求为准。
- 用于即梦或其他非 Higgsfield/Seedance 平台时，保留可观察的画面、空间、动作、运镜、物理和灯光描述；对平台不识别的 `@tag`、FOV、HARD CUT、秒级锁定等语法做显式改写，并说明能力限制。
- LIRA 用于图像资产和图像编辑提示词，ACTING 可补充角色表演；它们不替代本 Skill 的视频镜头统筹职责。

## 来源

原始内容来自 `GAGAA-HUE/ASHUO-claude-skills` 的 `cinedance-higgsfield/skill.md`，固定提交 `da8e7876d7b166451473d8f2ef2ad06c74395804`。原文件未声明开源许可证，使用与再分发范围不明确。
