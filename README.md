# Miasma for Obsidian

A dark, organic Obsidian theme built from the **Miasma** palette by xero, as shipped with [Omarchy](https://github.com/omacom/omarchy). Earthy neutrals, a muted olive accent, and warm gold accents for links and headings — calm enough for long writing sessions, with enough warmth to keep the interface feeling alive.

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

- **Two typefaces:** Reading view uses a literary serif stack; editing view stays in a clean sans so writing feels focused
- **Ornamented headings:** h1 gets a fading olive rule, h2 an underline, h4–h6 small-caps label styling
- **Dashed gold links** that fill in on hover, unresolved links in terracotta
- **Blockquotes** with a soft olive wash, decorative quote mark and serif italics
- **Code blocks** with rounded corners, a soft shadow and a three-dot window header in Reading view
- **Tables** with uppercase serif headers and an olive underline
- **Tag pills**, tinted callouts, an ornamented horizontal rule and custom checkboxes
- **Polished chrome:** active tabs with an accent top line, ribbon items with an accent rail, rounded file-explorer rows, blurred modals and slim olive-tinted scrollbars
- Subtle hover transitions throughout, with a `prefers-reduced-motion` fallback
- Extra styling for Dataview tables and Kanban boards

Full semantic color mapping covers surfaces, text, interactive states, borders and form fields, plus both `--code-*` and legacy `--syntax-*` highlighting, Graph and Canvas colors. Everything is local — no remote fonts, images or network calls.

Only dark mode is supported, matching the original Miasma palette.

## Fonts

Locally available font stacks are used by default, so the theme works fully offline. Override `--miasma-serif`, `--font-text-theme`, `--font-ui-theme` or `--font-monospace-theme` in a snippet to change them.

## Credits

- Miasma palette by [xero](https://github.com/xero), distributed with Omarchy by [omacom](https://github.com/omacom/omarchy)
- Original Omarchy Miasma theme by J. S. Brown / [OldJobobo](https://github.com/OldJobobo/omarchy-miasma-theme)

## License

MIT — see [LICENSE](./LICENSE). The upstream Miasma palette is also MIT licensed.
