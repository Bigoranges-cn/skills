# 电影制作 Skill 原文件快照

这里保存 LIRA、ACTING、CINEDANCE HIGGSFIELD 三套 Skill 的原文件快照，以及中文使用说明。

## 文件与作用

| Skill | 原文件 | 主要用途 |
|---|---|---|
| LIRA | [lira/skill.md](./lira/skill.md) | AI 图像提示词设计、角色/场景/道具参考图规划、图像编辑提示词 |
| ACTING | [acting/skill.md](./acting/skill.md) | 将角色目标、障碍、策略、节拍与潜台词转化为可见表演行为 |
| CINEDANCE HIGGSFIELD | [cinedance-higgsfield/skill.md](./cinedance-higgsfield/skill.md) | Seedance 2.0 / Higgsfield Seedance 的空间调度、镜头、物理、灯光与时序提示词 |

每套目录另有 `README.zh-CN.md`，包含中文介绍、使用方法和平台限制。

## 推荐工作流

1. 用 LIRA 准备角色、场景和关键道具的视觉参考。
2. 用 ACTING 把人物动机与潜台词转成可观察的动作、视线、姿态和反应。
3. 用 CINEDANCE HIGGSFIELD 汇总空间关系、镜头、光学、动作时序、物理与灯光，形成视频提示词。
4. 在目标平台生成前，按平台实际界面删改不支持的参数，并先做短片段测试。

本仓库不包含任何特定项目的剧情、角色或视频内容。

## 即梦与跨平台使用限制

这些原文件明显面向 Higgsfield、Seedance 2.0、Soul、Nano Banana Pro、Seedream 4.5、GPT Image 2 等特定工具。诸如 Soul ID、`@tag`、FOV 角度、精确时间块、镜头锁、参考图标记和平台 UI 参数，不保证被即梦或其他平台识别。

用于即梦时，应保留主体、场景、动作、镜头运动、光线和风格等自然语言信息；把平台专用字段改写成即梦可理解的直接描述。不要假定模型会严格执行秒级时序、多镜头硬切、身份锁定或摄影机参数。平台的时长、画幅、参考图数量、提示词长度和内容规则也可能变化，请以实际界面为准。

## 来源与版本

- 核验来源：[`GAGAA-HUE/ASHUO-claude-skills`](https://github.com/GAGAA-HUE/ASHUO-claude-skills)
- 固定提交：[`da8e7876d7b166451473d8f2ef2ad06c74395804`](https://github.com/GAGAA-HUE/ASHUO-claude-skills/commit/da8e7876d7b166451473d8f2ef2ad06c74395804)
- 提交时间：2026-09-22 06:20:55 UTC
- 上游路径：`lira/skill.md`、`acting/skill.md`、`cinedance-higgsfield/skill.md`
- 文件内容：逐字节复制，未改写；中文说明与原文件分开保存
- 来源核验边界：可确认这些文件来自上述公开仓库及提交，但上游仓库未提供足以证明最初作者身份或授权链的资料

详见 [SOURCE_AND_LICENSE.md](./SOURCE_AND_LICENSE.md)。

## 许可证提醒

本快照的上游仓库与三份原文件均未提供 LICENSE 文件或明确的开源许可证。上游 README 声明“个人使用，技能内容归原作者所有”。因此，本目录不能被视为 MIT、Apache-2.0 或其他开放许可发布；复制、修改、再分发和商业使用的授权范围并不明确。若要公开再发布或商业使用，请先向上游维护者及实际权利人取得许可。
