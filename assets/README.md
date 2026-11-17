# Assets

The source files that go with the written rules.

> **Status: complete (first version).** Logos, brush strokes, icons and photos are in.

The files here are web-ready copies. The full-size masters are kept in the [brand assets folder on Google Drive](https://drive.google.com/drive/folders/18U7Elyr0tq11N-YQ8gu9d1bOpRqSHczg) (access needed).

## What's here

| Folder | Files | Notes |
|---|---|---|
| [logos/](logos/) | `within-logo-colour.svg`, `-black.svg`, `-magenta.svg`, `-white.svg` | Use the SVG wherever you can. It works at any size. |
| [logos/png/](logos/png/) | The same four logos as PNG, 2235 × 1080 px, transparent background | For tools that can't use SVG, such as Google Slides. |
| [graphics/](graphics/) | `brush-stroke-magenta-01.png`, `brush-stroke-magenta-02.png` | The two Magenta brush strokes, transparent background. See the [brush stroke rules](../02-presentations/layout-rules.md). |
| [photography/slide-backgrounds/](photography/slide-backgrounds/) | `cover-dark.jpg`, `cover-light.jpg`, `cover-magenta.jpg`, `closing.jpg` | Full-bleed photos for cover and closing slides, 1920 × 1080 px (16:9). |
| [photography/people/](photography/people/) | `within-founders.jpg`, `within-workshop-square.jpg`, `within-workshop-wide.jpg` | Photos of the founders and workshops, 1920 px on the long side. Also published on the WITHIN website. |
| [icons/lucide/](icons/lucide/) | All 2,401 [Lucide](https://lucide.dev) icons as SVG, one file per icon | Already set to the brand style: Black (`#1B1212`), stroke width 1.5. See [Icons](#icons) below. |

## Logo colours

| File | Colours |
|---|---|
| `within-logo-colour` | Black (`#1B1212`) letters, Magenta (`#FF1493`) frame |
| `within-logo-black` | All Black (`#1B1212`) |
| `within-logo-magenta` | All Magenta (`#FF1493`) |
| `within-logo-white` | All White. Use on dark or Magenta backgrounds. |

## Icons

The full [Lucide](https://lucide.dev) set, version 1.74.0, the same icon set the WITHIN website uses. Each file is named after the icon on lucide.dev, for example `calendar.svg` or `users.svg`.

- **Finding an icon:** search [lucide.dev/icons](https://lucide.dev/icons), or look up a keyword in [tags.json](icons/lucide/tags.json), which lists the search terms for every icon.
- **Style:** every file is already Black (`#1B1212`) with a 1.5 stroke, the brand style. On a dark or Magenta background, change `stroke="#1B1212"` to `stroke="#FFFFFF"`. Keep the stroke width at 1.5.
- **Google Slides:** Slides can't import SVG files. Download a PNG from lucide.dev instead, as set out in the [layout rules](../02-presentations/layout-rules.md).
- **Licence:** Lucide is free to use under the ISC licence. Keep the [LICENSE](icons/lucide/LICENSE) file with the icons.

## File formats

| Use | Format |
|---|---|
| Logos on screen (web, apps, generated pages) | SVG |
| Icons | SVG (PNG for Google Slides) |
| Logos in Google Slides, Docs or email | PNG from `logos/png/` |
| Photos | JPG |
| Graphics that need a transparent background | PNG |
| Print | Ask for the masters on Google Drive |

## Naming

- All lowercase, words joined with hyphens.
- Pixel sizes are not part of the name. Folders separate sizes instead.
- The same name is used in this repo and on Google Drive, so a file can be traced back to its master.

## Large files and what's kept off GitHub

This repo is public, so these stay on Google Drive only:

- **Full-size masters.** Slide backgrounds at about 3800 px wide, people photos at 2500 px, and the logos at 9311 × 4500 px.
- **Client logos.** These belong to other companies and are for internal use only.

Keep each file here under 1 MB. For anything larger, put it on Google Drive and link to it.
