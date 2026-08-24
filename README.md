# 智企写作工坊

一个由统一入口调度三个上游 Skill 的中文写作工坊：中文自然化、个人风格 DNA、AI 痕迹扫描。

详见 [SKILL.md](SKILL.md)。上游模块位于 `vendor/`，并保留各自来源与许可证说明：

- `vendor/humanizer-zh`：中文去 AI 味主改写；
- `vendor/nuwa-skill`：个人风格 / 思维表达档案提炼；
- `vendor/qu-ai-wei`：事实、声口和 AI 痕迹扫描。

本仓库的顶层 Skill 只做调度，不替代上游规则，也不需要外部 API。
