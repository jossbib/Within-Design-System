# Colours

The brand colours and how to use them.

> **Status: complete (first version).** HEX values are taken from the [brand book](https://docs.google.com/presentation/d/10adt0hE1NL03DJu31Li8YJrdnTZbtgfCTYKqPR8RuIU/edit). CMYK values for print are in [print-specs.md](../04-print/print-specs.md#colours-in-print).

## Primary colours

| Name | HEX | Used for |
|---|---|---|
| Magenta | `#FF1493` | The accent colour: highlights, the brush stroke, cover backgrounds and main buttons. Use it sparingly. |
| Dark grey | `#2D2D2C` | Secondary text, dark buttons and dark backgrounds, such as the website header. |
| Mid grey | `#DFDCD1` | Thin dividers, chart gridlines and chart background bands. |
| Off white | `#F0F1EC` | The main background for slides and pages. |

## Secondary colours

| Name | HEX | Used for |
|---|---|---|
| Yellow | `#FFFC5D` | Diagrams and illustrations, as a fill with Black text on it. Not for text or backgrounds. |
| Green | `#1AEA7B` | Marking out a group of items, such as names from a different department. Use it sparingly, about once per deck. |
| Blue | `#61B5FF` | Marking out a group of items, such as names from a different department. Use it sparingly, about once per deck. Also used in charts for activity that belongs to the client rather than WITHIN. |
| White | `#FFFFFF` | Cards on slides, and text on Magenta and on photos. Not a slide background. |
| Black | `#1B1212` | The main text colour: titles, headings and body copy. |


## How to use the colours

A summary. For slides, the detailed rules are in [layout-rules.md](../02-presentations/layout-rules.md#using-colour-on-slides).

- **Backgrounds.** Off white is the default background for slides and pages. White is for cards that sit on Off white. Magenta, Dark grey and Black are for bold moments only, such as covers, the website header and dark buttons.
- **Text.** Black is the main text colour. Dark grey is for secondary text. White goes on Magenta, photos and dark backgrounds. Always check the pairing against [Colour combinations](#colour-combinations).
- **Highlights.** Magenta is the only accent colour. Use it to pick out the one or two things that matter most, never as decoration. Green and Blue mark out groups, about once per deck.
- **Lines and charts.** Mid grey is for dividers, gridlines and chart bands. Blue shows client activity in charts. Yellow is for diagrams and illustrations.
- **Rough balance.** Most of any page or slide should be Off white and White. Black text comes next. Magenta should be a small accent, no more than about a fifth of the text on a slide. Green and Blue should be rare.

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

- Don't use a text and background pairing that isn't in [Colour combinations](#colour-combinations).
- Don't use the slides-only pairings on web. That rules out small Magenta text, and Green or Blue text, on light backgrounds.
- Don't use Magenta, Green or Blue for running text. They're for short highlights and labels only.
- Don't pair Yellow, Green or Blue with Dark grey. Use Black.
- Don't use tints, shades or any colour outside the palette, including other greys.
- Don't use White as a slide background. It's for cards.
- Don't use Magenta as decoration, or for more than about a fifth of the text on a slide.
- Don't recolour the brush stroke. It's always Magenta.
- Don't use Yellow for text or backgrounds. It's for diagrams and illustrations only.
- Don't put a Yellow shape on its own on Off white or White. It almost disappears (about 1:1 contrast). Put Black text on it or a Black element next to it.
- Don't rely on colour alone to show meaning. A group marked in Green or Blue should also have a label or key, so it still makes sense when printed in black and white or read by someone who is colour-blind.
