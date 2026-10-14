# ACTING 中文介绍

## 功能

ACTING 是 AI 视频角色表演指导 Skill。它把目标、障碍、赌注、策略、节拍与潜台词转化为镜头可见的身体语言、视线、停顿、微表情、声音和反应时序，强调“压力下的行为”而不是抽象情绪标签。

## 使用方法

加载原文件后，提供角色身份、当前场景、角色想从谁那里得到什么、阻碍与失败代价、台词以及前后状态。先建立稳定的角色主档案，再为具体场景生成表演段落，并将结果嵌入视频生成提示词中的角色行为部分。

## 平台限制

原文件专为 Seedance 2.0 的角色行为提示设计。即梦等平台可能不会严格执行细粒度眨眼率、反应先后、声音身份或连续状态。迁移时优先保留可见动作、姿态、视线、说话节奏和关键反应，减少内部心理解释；复杂表演宜拆成较短片段测试。

## 原文件与来源

- 原文件：[skill.md](./skill.md)
- 上游路径：`acting/skill.md`
- 上游 Blob：`df0b98ab5722f2bbb1f54f90b37dab38029d2f5d`
- 固定版本：[`da8e7876d7b166451473d8f2ef2ad06c74395804`](https://github.com/GAGAA-HUE/ASHUO-claude-skills/commit/da8e7876d7b166451473d8f2ef2ad06c74395804)
- 直接来源：[`GAGAA-HUE/ASHUO-claude-skills`](https://github.com/GAGAA-HUE/ASHUO-claude-skills)
- 许可证：未声明；详见 [总说明](../SOURCE_AND_LICENSE.md)
