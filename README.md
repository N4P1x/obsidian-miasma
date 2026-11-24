# Miasma for Obsidian

A restrained dark theme built on the **Miasma** palette by xero, as shipped with [Omarchy](https://github.com/omacom/omarchy). Muted earth tones, readable contrast, and quiet interface chrome — built for long writing sessions without visual noise.

The layout borrows from a Linux tiling desktop: the dock is a launcher, tabs are framed windows, the note is the active pane, and the status bar is a slim panel. Obsidian's semantic CSS variables drive the palette, while a small set of element rules adds the window borders and functional motion that variables can't express.

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
| Selection | `#464a33` |

The accent follows Obsidian's **Accent color** setting, so you can tweak it from **Settings → Appearance** without losing the rest of the theme.

## Design

- **Readable by default.** Body text is `#c2c2b0` on `#222222`; secondary text is brighter than typical dark themes so icons, file names and status items stay visible.
- **Clear hierarchy.** Gold marks headings, links, the settings gear and active navigation. Olive marks interaction; status hues only appear in callouts and code.
- **Variable-first.** Obsidian's own semantic variables drive nearly every surface, including tabs, properties, tag pills, tables and callouts. Fewer overrides means fewer breakages on app updates.
- **Omarchy window logic.** The center pane has a thin frame, tabs have active-state outlines, the dock has visible icon buttons, and the status bar sits below as a panel — not a pile of floating cards.
- **Functional motion.** Hover lifts, icon nudges, tab reveals, callout entrances and modal pop-ins are short and purposeful. `prefers-reduced-motion` and the **Disable interface motion** option turn them off.
- **Focused writing.** A 740 px default line length, calm active-line tint, underlined links, dotted unresolved links, a quiet H1 rule and an olive H2 marker.
- **Fast and offline.** No remote fonts, images or network requests.

Only dark mode is supported, matching the original Miasma palette.

## Style Settings

Install the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin to configure:

| Option | What it does |
| --- | --- |
| Compact interface | Tighter spacing and smaller UI text for dense workspaces |
| Serif Reading view | Opt-in serif text in Reading view; editing view stays sans |
| Quiet sidebar | Slightly dim inactive side panels |
| Note width | Slider for the maximum line width (520–1100 px, default 740) |
| Framed workspaces | Stronger Hyprland-style borders and active window accents |
| Disable interface motion | Turn off hover, reveal and focus animations |

## Fonts

System font stacks are used by default, so the theme works fully offline. Override `--miasma-serif`, `--font-text-theme`, `--font-ui-theme` or `--font-monospace-theme` in a snippet to change them.

## Credits

- Miasma palette by [xero](https://github.com/xero), distributed with Omarchy by [omacom](https://github.com/omacom/omarchy)
- Original Omarchy Miasma theme by J. S. Brown / [OldJobobo](https://github.com/OldJobobo/omarchy-miasma-theme)

## License

MIT — see [LICENSE](./LICENSE). Palette attribution is in [NOTICE](./NOTICE); the upstream Miasma palette is also MIT licensed.
