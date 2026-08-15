---
layout: default
title: BBCode Tags for Device Names
---

<div class="rule">

## BBCode Support

Device names in the **Control Panel** support a selection of BBCode formatting tags. These tags allow you to organize and color-code devices for easier navigation.

</div>

<div class="rule">

## Text Formatting Tags

<div class="subsection">

#### Basic Formatting

| Tag | Effect |
|------|--------|
| `[b][/b]` | Bold |
| `[i][/i]` | Italic |
| `[u][/u]` | Underline |
| `[s][/s]` | Strikethrough |
| `[sup][/sup]` | Superscript |
| `[sub][/sub]` | Subscript |

</div>

</div>

<div class="rule">

## Color Tags

<div class="subsection">

#### Base Color

| Tag | Effect |
|------|--------|
| `[c][/c]` | Sets the text base color to white instead of the default light-blue. |

</div>

<div class="subsection">

#### Hex Colors

| Tag | Effect |
|------|--------|
| `[######][-]` | Apply a 6-digit RGB or 8-digit RGBA hex color. |
| `[##]` | Set alpha (transparency) using a 2-digit hex value. |

The closing tag for hex colors is `[-]`.

</div>

</div>

<div class="rule">

## How Color Mixing Works

<div class="subsection">

#### Using `[c]` with Hex Colors

The default device-name color is **light blue**. Hex colors are multiplied against this base color, so they inherit a blue tint unless you reset the base color first.

For pure white, use:

```text
[c][FFFFFF]My Device[-][/c]
```

If you omit `[c]`, the text keeps the default light-blue tint, which can be useful if you want to save a few characters.

</div>

</div>

<div class="rule">

## Example Formatting

<div class="subsection">

#### Common Examples

```text
[b]Main Generator[/b]

[c][FFAA00]Fuel Tank[-][/c]

[c][00FF00][b]Solar Capacitor[-][/b][/c]

[c][FF0000]Warning[-][/c]
```

</div>

</div>

<div class="note">

**Tip:** Combining `[c]` with hex colors gives accurate color reproduction, while skipping `[c]` produces a blue-tinted version that can help save characters in device names.

</div>