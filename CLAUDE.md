# CLAUDE.md

## Keymap visualizations

Each keymap file under `config/` (e.g. `config/splitkb_aurora_sweep.keymap`)
contains a `VISUAL LAYOUT` comment block at the bottom that renders every layer
with actual key symbols.

**Whenever you change a keymap's `bindings`, update its visualization to match in
the same change.** The two must never drift apart.

When updating the visualization, keep the existing conventions:

- Keys separated by `|`; the two hands separated by `||`.
- Home-row mods show the tap symbol plus a modifier glyph (`⌃` Ctrl, `⌥` Alt,
  `⌘` Cmd/Gui, `⇧` Shift) — e.g. `S⌃` = tap `S`, hold `Ctrl`.
- `·` = `none` (disabled), `▽` = `trans` (transparent).
- Layer switches shown as `L1`/`L2` etc.; `→L0` = `&to 0`.
