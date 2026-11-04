# 个人 Skills 备份

此仓库保存个人使用的 Codex 技能与提示词。所有技能位于 `skill/`，每个技能包含自己的 `SKILL.md`，以及所需的模板、参考资料和界面配置；提示词位于 `提示词/`。

## 技能目录

| 技能 | 用途 |
| --- | --- |
| [deepwhite-image-prompt-builder](skill/deepwhite-image-prompt-builder/SKILL.md) | 生成、改进中英文静态图片提示词 |
| [deepwhite-screenwriting-v1](skill/deepwhite-screenwriting-v1/SKILL.md) | 中文影视编剧、剧本诊断和修改 |
| [deepwhite-shotlist-builder-zh-user](skill/deepwhite-shotlist-builder-zh-user/SKILL.md) | 中文分镜、视频提示词与制作网页 |
| [domain-modeling](skill/domain-modeling/SKILL.md) | 整理项目术语、领域模型和设计决策 |
| [grilling](skill/grilling/SKILL.md) | 通过逐轮追问梳理想法和计划 |
| [grill-with-docs](skill/grill-with-docs/SKILL.md) | 结合追问与领域建模，记录设计文档 |

`grill-with-docs` 依赖 `grilling` 和 `domain-modeling`，使用时应一起安装。

## 提示词目录

| 分类 | 提示词 |
| --- | --- |
| 绘图提示词 | [蜡笔颗粒日系涂鸦](提示词/绘图提示词/蜡笔颗粒日系涂鸦.md) |

## 使用

可以让 Codex 从本仓库安装指定技能，或将对应技能文件夹完整复制到本机的个人 skills 目录。请保留技能内部的目录结构，以便找到其参考资料和模板。

技能的实际名称、适用条件和使用说明以各自的 `SKILL.md` 为准。

## 备份说明

- 本次备份包含 6 个技能、35 个技能文件，保留原始内容。
- 不包含 Codex 系统技能、插件缓存、账号配置或聊天记录。
- `SKILLS_MANIFEST.json` 记录技能文件的大小和 SHA-256，便于检查备份是否完整。
- 本仓库不另行授予统一许可证；如技能或其资料有原作者的许可要求，应继续遵循原有要求。

