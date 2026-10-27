# 黄白 × LibTV 课程技能

用于编写、修改和审查黄白 × LibTV 课程，并按指定课节对齐定稿脚本、有效大纲、原生思维导图和音频。

## 使用

将本仓库下载或克隆为 Codex 技能目录中的 `huangbai-libtv` 文件夹，保留 `references`、`assets` 和 `agents`，然后在对话中调用 `$huangbai-libtv`。

```bash
git clone https://github.com/huangbai-AI/huangbai-libtv.git ~/.codex/skills/huangbai-libtv
```

如本机已有同名技能，先备份和比较，避免覆盖未同步的修改。私有仓库需要对应的 GitHub 访问权限。

## 内容

- [技能入口](SKILL.md)：黄白课程表达、完整教学保护、编写与交付规则。
- [表格标准](references/table-standard.md)：三列大纲、七列脚本、真实合并和素材位置。
- [对齐功能](references/alignment.md)：以已确认脚本为准，核对大纲、导图与音频；支持只检查。
- [自然表达复核](references/humanizer-check.md)：去除生硬和空泛表达，保留事实、教学细节和用户原句。
- [素材与试听](references/materials-and-preview.md)、[MiniMax网页流程](references/minimax-web.md)。
- `assets/`：大纲与脚本表格模板；`agents/`：Codex显示与调用说明。

## 同步范围

2026年10月27日首次同步当前本机技能，共14个技能文件，内容原样保留。此仓库独立于旧课程资料仓库。

课程入口见[课程背景](references/course-context.md)，正文和权限以飞书线上最新版为准。本仓库包含技能规则与资料链接，不包含课程正文备份、个人照片、录音、账号凭据或登录状态。实际编辑、生成、配音和外发仍按用户当次授权执行。

Humanizer相关来源与许可保留在[来源说明](references/humanizer-NOTICE.txt)，不据此改变其余技能内容的许可。
