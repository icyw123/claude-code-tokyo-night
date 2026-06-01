# Tokyo Night — Claude Code Theme

A [Tokyo Night](https://github.com/enkia/tokyo-night-vscode-theme) color theme for Claude Code, based on the built-in `dark` preset. Requires Claude Code v2.1.118+.

[简体中文](./README.zh-CN.md)

## Install

```bash
mkdir -p ~/.claude/themes
curl -fsSL https://raw.githubusercontent.com/icyw123/claude-code-tokyo-night/main/tokyo-night.json \
  -o ~/.claude/themes/tokyo-night.json
```

Then run `/theme` and pick **Tokyo Night**, or set `"theme": "custom:tokyo-night"` in `~/.claude/settings.json`.

## Colors

| Token | Color | Used for |
| :--- | :--- | :--- |
| `claude` | `#7aa2f7` | spinner, Claude label, brand accent |
| `suggestion` | `#89ddff` | selected row, ❯ pointer, ghost text |
| `text` | `#c0caf5` | primary text |
| `inactive` | `#565f89` | secondary text, timestamps |
| `subtle` | `#414868` | faint borders |
| `success` / `autoAccept` | `#9ece6a` | success, accept-edits |
| `error` | `#f7768e` | errors |
| `warning` / `fastMode` | `#e0af68` | warnings, fast mode |
| `merged` / `remember` / `bashBorder` | `#bb9af7` | merged PR, memory, shell border |
| `permission` / `planMode` | `#7dcfff` | permission/picker, plan mode |
| `ide` / `promptBorder` | `#7aa2f7` | IDE indicator, input border |
| `diffAdded` / `diffRemoved` | `#20303b` / `#37222c` | diff added/removed lines |
| `diffAddedWord` / `diffRemovedWord` | `#2c5a3e` / `#6b2e3a` | diff word-level highlight |

Colors from [Tokyo Night](https://github.com/enkia/tokyo-night-vscode-theme).

## License

MIT
