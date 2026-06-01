# Tokyo Night — Claude Code 主题

[English](./README.md)

[Tokyo Night](https://github.com/enkia/tokyo-night-vscode-theme) 风格的 Claude Code 配色，基于官方 `dark` 主题。需要 Claude Code v2.1.118+。

## 安装

```bash
mkdir -p ~/.claude/themes
curl -fsSL https://raw.githubusercontent.com/icyw123/claude-code-tokyo-night/main/tokyo-night.json \
  -o ~/.claude/themes/tokyo-night.json
```

然后运行 `/theme` 选 **Tokyo Night**，或在 `~/.claude/settings.json` 里设 `"theme": "custom:tokyo-night"`。

## 配色

| Token | 颜色 | 作用 |
| :--- | :--- | :--- |
| `claude` | `#7aa2f7` | spinner、Claude 标签、品牌强调 |
| `suggestion` | `#89ddff` | 选中行、❯ 箭头、ghost text |
| `text` | `#c0caf5` | 主文本 |
| `inactive` | `#565f89` | 次要文本、时间戳 |
| `subtle` | `#414868` | 浅边框 |
| `success` / `autoAccept` | `#9ece6a` | 成功、accept-edits |
| `error` | `#f7768e` | 错误 |
| `warning` / `fastMode` | `#e0af68` | 警告、fast mode |
| `merged` / `remember` / `bashBorder` | `#bb9af7` | PR 合并、记忆、shell 边框 |
| `permission` / `planMode` | `#7dcfff` | 权限/选择器、plan 模式 |
| `ide` / `promptBorder` | `#7aa2f7` | IDE 指示、输入框边框 |
| `diffAdded` / `diffRemoved` | `#20303b` / `#37222c` | diff 增/删行 |
| `diffAddedWord` / `diffRemovedWord` | `#2c5a3e` / `#6b2e3a` | diff 词级高亮 |

配色来自 [Tokyo Night](https://github.com/enkia/tokyo-night-vscode-theme)。

## License

MIT
