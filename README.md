# Cita themes for Crest

Cita light and dark recipes for the Crest browser.

Crest has no theme files. You set the colors by hand in Crest Studio, one Space at a time. Crest doesn't follow system light or dark mode, so use one Space for Cita Light and another for Cita Dark.

The colors match the etty themes in `marta-themes` and the Herdr themes in `herdr-theme`.

## Color palette

`Cita.clr` is a macOS color palette with all the Cita colors. It works in any app that uses the system color picker.

```sh
mkdir -p ~/Library/Colors
cp Cita.clr ~/Library/Colors/
```

Restart Crest. In the color picker, open the Color Palettes tab and pick Cita.

## Set up a Space

1. Right-click a Space and open its Appearance page.
2. Open Crest Studio and go to the Sidebar step.
3. Pick Gradient.
4. Pick the colors from the Cita palette, or copy the hex values from the tables below.
5. Set the text color on the Space's Appearance page.

To start over, use Reset Appearance in the `…` menu.

## Cita Light

| Part | Color |
| --- | --- |
| Background | `#f3f7fb` |
| Gradient stop 2 | `#e0fcf3` |
| Accent | `#08805a` |
| Pattern | `#c4f5e9` |
| Text | `#043a73` |

Use a soft intensity for the gradient. Skip stop 2 if you want a flat sidebar.

## Cita Dark

| Part | Color |
| --- | --- |
| Background | `#011d3b` |
| Gradient stop 2 | `#011830` |
| Accent | `#63f2c5` |
| Pattern | `#1a535e` |
| Text | `#e6f0fa` |

The gradient is subtle on purpose. For more depth, use `#1a535e` as stop 2.

## Banner crest

Want a banner instead of a gradient? Use these colors.

| Part | Cita Light | Cita Dark |
| --- | --- | --- |
| Field | `#043a73` | `#011d3b` |
| Second field | `#094480` | `#1a535e` |
| Band | `#08805a` | `#63f2c5` |
| Emblem | `#f3f7fb` | `#e6f0fa` |
| Border | `#9bf7da` | `#63f2c5` |
| Edge | `#043a73` | `#011830` |

## App settings

In Settings → Appearance:

- Keep "Follow Space accent" on. The accent then changes with the Space.
- If you turn it off, use `#08805a` for light or `#63f2c5` for dark.
- For address field colors, use the Space's Background and Text colors.

## Palette

| Name | Cita Light | Cita Dark |
| --- | --- | --- |
| Background | `#f3f7fb` | `#011d3b` |
| Foreground | `#043a73` | `#e6f0fa` |
| Accent | `#08805a` | `#63f2c5` |
| Selection | `#c4f5e9` | `#1a535e` |
| Selected | `#9bf7da` | `#0f6652` |
| Chrome | `#e0fcf3` | `#011830` |
