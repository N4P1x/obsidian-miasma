# Miasma for Obsidian

A restrained dark theme built on the **Miasma** palette by xero, as shipped with [Omarchy](https://github.com/omacom/omarchy). Muted earth tones, readable contrast, and quiet interface chrome — made for long writing sessions without visual noise.

![Miasma theme screenshot](./screenshots/screenshot.png)

## Install

1. Open **Settings → Appearance → Themes** in Obsidian.
2. Click **Manage community themes → Browse**.
3. Search for **Miasma** and select it.

To try it locally before installing, copy `theme.css` into `<your vault>/.obsidian/themes/Miasma/` and select it under **Settings → Appearance**.

## Palette

| Role | Hex |
| --- | --- |
| Background | `#222222` |
| Darker background | `#121212` |
| Lighter background | `#2c2c2c` |
| Foreground | `#c2c2b0` |
| Muted foreground | `#8a8a7e` |
| Accent (olive) | `#78824b` |
| Links / highlight (gold) | `#c9a554` |
| Warm orange | `#b36d43` |
| Green | `#5f875f` |
| Terracotta | `#bb7744` |
| Selection | `#383838` |

The accent follows Obsidian's **Accent color** setting, so you can tweak it from **Settings → Appearance** without losing the rest of the theme.

## Design

- **Readable by default.** Foreground, muted text, links and syntax colors are tuned to stay legible against the Miasma surfaces; no low-contrast decoration.
- **Quiet hierarchy.** Headings use size, weight and color instead of rules and ornaments. Links are underlined and settle on hover; unresolved links are dotted.
- **Focused editor.** Subtle active-line tint, clear selection and caret, readable gutters, tidy fold placeholders and tooltips.
- **Useful chrome.** Accent markers on active tabs and files, hover states across the ribbon and file explorer, clean modals, popovers and slim scrollbars.
- **Consistent surfaces.** Code blocks, tables, callouts, tags, properties and embeds all use the same small set of radii and borders.
- **Plugin-friendly.** Sensible styles for Dataview tables and Kanban boards, plus both `--code-*` and legacy `--syntax-*` highlighting, Graph and Canvas colors.
- **Fast.** No remote fonts, images or network requests. Transitions respect `prefers-reduced-motion`.

Only dark mode is supported, matching the original Miasma palette.

## Style Settings

Install the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin to configure:

| Option | What it does |
| --- | --- |
| Compact interface | Smaller text and tighter spacing across the editor, file explorer and status bar |
| Serif Reading view | Opt-in serif text in Reading view; editing view stays sans |
| Quiet sidebar | Dim inactive side panels |
| Note width | Slider for the maximum line width (520–1100 px, default 740) |

## Fonts

System font stacks are used by default, so the theme works fully offline. Override `--miasma-serif`, `--font-text-theme`, `--font-ui-theme` or `--font-monospace-theme` in a snippet to change them.

## Credits

- Miasma palette by [xero](https://github.com/xero), distributed with Omarchy by [omacom](https://github.com/omacom/omarchy)
- Original Omarchy Miasma theme by J. S. Brown / [OldJobobo](https://github.com/OldJobobo/omarchy-miasma-theme)

## License

MIT — see [LICENSE](./LICENSE). Palette attribution is in [NOTICE](./NOTICE); the upstream Miasma palette is also MIT licensed.
