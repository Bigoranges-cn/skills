# CINEDANCE HIGGSFIELD 中文介绍

## 功能

CINEDANCE V4 是面向 Seedance 2.0 与 Higgsfield Seedance 的电影级视频提示词导演系统。它控制空间布局、首帧、角色与道具引用、视线和方位、FOV 光学、摄影机运动、动作时序、物理真实性、灯光、声音与连续性，并在输出前执行内部检查。

## 使用方法

加载原文件后，提供场景、人物与参考图标记、空间关系、对白、时长、画幅和希望的单镜头或多镜头模式。复杂场景先明确首帧与位置图，再逐段定义动作、摄影机、物理、光线和声音。默认输出为英文 Seedance 提示词。

## 平台限制

FOV 度数、`@tag`、HARD CUT、时间块、镜头锁和灯光锁是针对特定模型的控制语言，不保证即梦逐项解析。用于即梦时，可把它们改写为清晰的自然语言镜头描述，并根据即梦支持的时长、参考图和运镜选项简化。多镜头连续性、严格空间方位与秒级动作通常需要分段生成、参考图复用和后期剪辑配合。

## 原文件与来源

- 原文件：[skill.md](./skill.md)
- 上游路径：`cinedance-higgsfield/skill.md`
- 上游 Blob：`b3208f7b20be76cfc0c37198a870ef18cda050e7`
- 固定版本：[`da8e7876d7b166451473d8f2ef2ad06c74395804`](https://github.com/GAGAA-HUE/ASHUO-claude-skills/commit/da8e7876d7b166451473d8f2ef2ad06c74395804)
- 直接来源：[`GAGAA-HUE/ASHUO-claude-skills`](https://github.com/GAGAA-HUE/ASHUO-claude-skills)
- 许可证：未声明；详见 [总说明](../SOURCE_AND_LICENSE.md)
