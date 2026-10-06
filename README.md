# Borozdov Beacon

A theme from the Borozdov collection. Two faces — dark **Onyx**, a midnight cockpit for the
keyboard, and light **Pearl**, the same cockpit in daylight. Near-black surfaces in
barely-there steps, keycap edges instead of shadows and one coral pulse for what you
trigger.

![Borozdov Beacon in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/beacon/main/screenshots/dark.png)

![Borozdov Beacon in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/beacon/main/screenshots/light.png)

## Principles

- **Void, ink, obsidian, graphite.** Four near-black steps do the work of elevation;
  nothing floats and nothing casts a blur.
- **Keycaps, not cards.** Callouts, code, tags, buttons and menus are keys: a hairline
  edge and a highlight along the top, as if pressed into the surface.
- **One coral pulse.** Coral marks links, the caret, a checked task and an enabled
  toggle. The main button is a light key with dark text, never a chromatic fill.
- **Whispered type.** Inter in a 400–600 band; headings at 500 let size do the work,
  and tags are monospace capitals like version strings in a footer.

## Features

- Dark and light modes, following Settings → Appearance → Base color scheme
- Callouts as keycaps with the title in the type's colour: electric sky, green, amber,
  coral, violet
- Code in a well with a hairline; tables with a rounded frame and grid
- Monospace micro-label tags
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces; the coral is deepened for text on the
  light face
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Console**. Install Borozdov Console under Settings → Appearance → Themes → Manage, then
the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and
choose **Beacon** under Style Settings → Borozdov Console → Variant. The variant brings
this theme's palette, type and corners; its own layout, and its embedded font if it has
one, come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/beacon/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Beacon/`, then choose Borozdov Beacon under
Settings → Appearance → Themes.

## Font

Inter (© The Inter Project Authors) is embedded in `theme.css` as base64 WOFF2 under the
SIL Open Font License 1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt). Weights 400–600, Latin
and Cyrillic.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: тёмный «Оникс» — полуночная кабина для
клавиатуры, и светлый «Жемчуг» — та же кабина днём. Почти чёрные поверхности с едва
заметными ступенями, кромки клавиш вместо теней и один коралловый импульс для того, что вы
запускаете. В каталоге тема живёт вариантом Borozdov Console: установите Borozdov Console и плагин Style Settings, затем выберите Beacon в Style Settings → Borozdov Console → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
