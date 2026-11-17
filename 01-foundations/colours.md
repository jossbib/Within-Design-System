# Colours

The brand colours and how to use them.

> **Status: started.** HEX values and the Magenta CMYK value are taken from the [brand book](https://docs.google.com/presentation/d/10adt0hE1NL03DJu31Li8YJrdnTZbtgfCTYKqPR8RuIU/edit). Colour combinations are agreed. Some usage rules are still to be added.

## Primary colours

| Name | HEX | CMYK | Used for |
|---|---|---|---|
| Magenta | `#FF1493` | C0 M100 Y0 K3 | The accent colour: highlights, the brush stroke, cover backgrounds and main buttons. Use it sparingly. |
| Dark grey | `#2D2D2C` | C80 M75 Y72 K45 * | Secondary text, dark buttons and dark backgrounds, such as the website header. |
| Mid grey | `#DFDCD1` | C11 M8 Y12 K0 * | Thin dividers, chart gridlines and chart background bands. |
| Off white | `#F0F1EC` | C5 M3 Y4 K0 * | The main background for slides and pages. |

## Secondary colours

| Name | HEX | CMYK | Used for |
|---|---|---|---|
| Yellow | `#FFFC5D` | C6 M1 Y58 K0 * | Not used on slides. _Other uses to be added._ |
| Green | `#1AEA7B` | C45 M0 Y48 K0 * | Marking out a group of items, such as names from a different department. Use it sparingly, about once per deck. |
| Blue | `#61B5FF` | C48 M20 Y0 K0 * | Marking out a group of items, such as names from a different department. Use it sparingly, about once per deck. Also used in charts for activity that belongs to the client rather than WITHIN. |
| White | `#FFFFFF` | C0 M0 Y0 K0 | Cards on slides, and text on Magenta and on photos. Not a slide background. |
| Black | `#1B1212` | C68 M74 Y64 K75 * | The main text colour: titles, headings and body copy. |

\* **Placeholder CMYK values.** These were converted from HEX using the standard macOS print profile (Generic CMYK), not chosen by hand. A designer or the printer must check them before anything is printed. Yellow, Green and Blue are brighter than print ink can reproduce, so they will print duller than they look on screen.

## How to use the colours

_To be added: which colours are for backgrounds, text and highlights, and roughly how much of each to use._

## Colour combinations

These are the only text and background pairings to use. If a pairing isn't listed here, don't use it for text. Numbers are WCAG contrast ratios.

### Any text size

These pairings are 4.5:1 or higher, so they work for body copy and small print as well as headings.

| Background | Text colours (contrast) |
|---|---|
| Off white | Black 16.2 |
| White | Dark grey 13.8 |
| Mid grey | Black 13.4 |
| Yellow | Black 16.9 |
| Green | Black 11.5 |
| Blue | Black 8.4 |
| Dark grey | White 13.8 · Off white 12.1 · Mid grey 10.0 |
| Black | White 18.4 · Yellow 16.9 · Off white 16.2 · Mid grey 13.4 · Green 11.5 · Blue 8.4 · Magenta 5.1 |

Yellow, Green and Blue are only ever paired with Black, whichever way round.

### Headings, title pages and button labels only

Use these in Proxima Nova Bold at heading size, or 1.2rem for button labels. Don't use them for body copy or small print.

| Background | Text colours (contrast) |
|---|---|
| Magenta | White 3.6 · Black 5.1 |

### Slides only

These exceptions apply to slides only, not to web. Magenta, Green and Blue text all fail WCAG contrast at small sizes, and Green and Blue fail even at heading size. We accept that because they're only used for short highlights and group labels, never for running text. See [layout-rules.md](../02-presentations/layout-rules.md#using-colour-on-slides).

| Background | Text | Contrast | Use it for |
|---|---|---|---|
| Off white | Magenta | 3.2 | Key terms, step numbers, key labels and photo credits |
| White (cards) | Magenta | 3.6 | Names on people cards and the key line of a quote |
| White (cards) | Blue | 2.2 | Marking out a group of items, such as names from a different department |
| White (cards) | Green | 1.6 | Marking out a group of items, such as names from a different department |
| Off white | Dark grey | 12.1 | Small secondary text: eyebrows, captions, job titles, page numbers and chart legends |

### Inactive text only

| Background | Text | Contrast | Use it for |
|---|---|---|---|
| Off white | Mid grey | 1.2 | Disabled controls, which are exempt from WCAG contrast minimums |

### Not used

These pairings pass on contrast, but we don't use them:

- Black on White
- Dark grey on Off white (except on slides, see above)
- Dark grey on Mid grey
- Dark grey with Yellow, Green or Blue, either way round

## Things to avoid

_To be added._
