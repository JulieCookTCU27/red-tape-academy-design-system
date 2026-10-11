# Red Tape Academy — Design System

Part of the Cook Consulting Services, LLC brand family. Files: `tokens.json` (source of truth), `tokens.css` (CSS variables + font faces), the font files, logos, icons and images (all in the top level).

Red Tape Academy is Julie Cook's education DBA: plain-language teaching about government, policy and the systems people navigate every day. It keeps the CCS feel — linen page, black ink, peacock blue, square and editorial — drops the florals, and adds **civic red** so the palette reads red, white and blue. Brand words carry over: **inclusive, modern, sophisticated**; add **clear**.

Tagline: **government, made clear.**

## Content fundamentals

- The promise is in the name: cut through the red tape. Explain, don't lecture. Define every term the first time it appears.
- Voice: a knowledgeable, encouraging teacher. "Here's how it works", "you'll see this on…", "try it".
- Nonpartisan and evidence-based: cite primary sources in `small`, present multiple perspectives fairly, avoid loaded language.
- Headings in sentence case, Libre Baskerville (`display`, `h1`, `h2`): "How a bill becomes a law". Sub-heads lowercase League Spartan (`h3`): "key terms".
- Labels UPPERCASE tracked in `label`: MODULE 3 · CIVICS, LESSON 2, KEY TERM.
- Tagline: "government, made clear." — lowercase, with the period, set in Libre Baskerville Italic in `peacock-blue` (or `linen` on black). Use it on covers, the website header, social bios and course title slides; drop it below about 200px logo width.
- No emoji, no flags or eagles as decoration, no partisan imagery.

## Visual foundations

### Color

- Red, white and blue, the family way: `linen`/`white` grounds, `peacock-blue` as the lead color (`accent`), `civic-red` as the punch (`highlight`), `black` ink.
- Mix: ~70% linen/white, 15% peacock, 10% black, 5% red. Red is the exclamation point — one red element per view.
- Peacock and civic red have nearly the same lightness (1.1:1 between them). Never place red text on blue or blue on red, and never use the two alone to mean different things in charts — add labels or patterns.
- Dark theme: `black` ground, `linen` ink, `sky-blue` accent, `civic-red-light` highlight.

### Type

- Headings: Libre Baskerville (Bold for `display`/`h1`, Regular for `h2`, Italic for `quote`) — the civic, primary-source voice.
- Family threads: Quicksand for all running text (`body`, `small`), League Spartan for sub-heads (`h3`) and labels (`label`).
- Wordmark sub-line: `tracked`, lowercase, as in the logo's "a c a d e m y".

### Layout

- Square corners (`radius-none`), 1px `rule` frames, `space-6` margins — the same grid as CCS.
- The **tape bar** is the brand's graphic device: a 12px `civic-red` bar with one diagonal cut, used under a title or to mark a key idea. One per page.
- Stripes are allowed as a background band (alternating `civic-red` and `white` at `space-5` pitch) on covers only.
- Worksheets and handouts: `surface-raised` (white) cards on linen, `hairline` borders, generous write-in space.

### Imagery

- No florals. Use real documents, buildings, civic spaces and people in everyday government moments (voting, a council meeting, a permit counter), in the same calm daylight grade as CCS photography.
- Diagrams over decoration: flowcharts and timelines in `peacock-blue` with `civic-red` for the one step that matters.

## Logos

- **Civic-cap mark** (`rta-mark.svg`): a mortarboard over a row of columns standing on the snipped red tape bar — education on top of government. Peacock blue with a civic-red tassel and base. `rta-mark-reversed.svg` is linen and light red on a peacock square for avatars and favicons.
- **Horizontal lockups** — the default for headers, slides and letterhead: mark, a thin divider, then the wordmark.
  - `rta-logo-horizontal-tagline.svg` — with "government, made clear." (first choice where there is room).
  - `rta-logo-horizontal.svg` — without the tagline.
  - `rta-logo-horizontal-reversed.svg` — on black, with tagline.
- **Stacked wordmark** — "red" in `civic-red`, "tape" in `peacock-blue`, League Spartan ExtraBold lowercase (the family's wordmark style), the snipped red tape bar, and "academy" tracked in Quicksand.
  - `rta-logo-tagline.svg` / `rta-logo-tagline-reversed.svg` — with the tagline in Libre Baskerville Italic.
  - `rta-logo-primary.svg` (transparent), `rta-logo-primary-linen.svg` (linen field), `rta-logo-reversed.svg` (black field).
- **Monograms**: `rta-monogram-peacock.svg` / `rta-monogram-linen.svg` — the square "rta" mark for social tiles.
- Clear space = the height of the tape bar × 3. Never separate the bar from the wordmark, recolor "red" anything but red, or set the wordmark in another font.
- These are new marks drafted for the brand; trademark clearance has not been done.

## Iconography

Red Tape Academy has its own line icon set (Icons group), drawn on a 24px grid with a 2px stroke, square caps and mitred corners, single ink `peacock-blue` #016795:

| Icon | Use it for |
| --- | --- |
| `icon-capitol.svg` | Legislatures, Congress, the Texas Capitol, lawmaking |
| `icon-courthouse.svg` | Courts, agencies, "government" in general |
| `icon-graduation-cap.svg` | Courses, learning outcomes, certificates |
| `icon-open-book.svg` | Readings, lessons, study guides |
| `icon-constitution.svg` | Primary sources, laws, documents, policies |
| `icon-ballot-box.svg` | Voting, elections, civic participation |
| `icon-gavel.svg` | Rulings, rules, enforcement |
| `icon-forms-checklist.svg` | Forms, permits, step-by-step processes |
| `icon-cut-the-tape.svg` | The brand promise — simplifying a process, "the short version" |
| `icon-town-hall-discussion.svg` | Discussion questions, public comment, community meetings |

- Show icons at 24, 32 or 48px. Pair each with a text label; never use an icon alone to carry meaning.
- One icon per card or list item, aligned to the first line of text with `space-2` between.
- Never stars, flags or eagles as ornament.

## The family

Cook Consulting Services, LLC is the house; each business below is its own brand with its own system, cut from the same cloth.

| Brand | Role | What it keeps from CCS | What it changes |
| --- | --- | --- | --- |
| CCS | Parent consultancy | — | — |
| The Collective Space | Community and gathering brand | Palette, League Spartan, Quicksand, florals | Leads on black; script word in the logo |
| Impact Advisory Group | Advisory practice | Palette, League Spartan, Quicksand, florals | Quietest of the set: ink and linen, one accent |
| Red Tape Academy | Education DBA | Linen, peacock blue, sky blue, black, Quicksand, League Spartan labels | Adds civic red; Libre Baskerville headings; no florals |
| Jules Studio | Handmade Etsy shop | Linen, black, Quicksand, League Spartan, line florals | Plum, rose and blush from the floral work |

Threads every brand keeps, so the family reads as one: the linen ground (`linen` #F1EFE7), black ink (`black` #101010), Quicksand for body copy, League Spartan somewhere in the hierarchy, wide-tracked lowercase or uppercase sub-lines (as in "a d v i s o r y   g r o u p"), square corners, and 1px hairline rules framing the page.

## Canva brand kit

Set up a Canva Brand Kit for this brand so designs stay consistent.

**Colors**

| Name | Hex | Role |
| --- | --- | --- |
| linen | `#F1EFE7` | Page background (shared family color) |
| white | `#FFFFFF` | Cards and worksheets |
| peacock-blue | `#016795` | Lead accent: headings, links, buttons |
| sky-blue | `#4D9EC0` | Fills and graphics; accents on black |
| civic-red | `#B31942` | Highlight: key terms, tape bar, calls to action |
| civic-red-light | `#E0566E` | Red on black backgrounds |
| black | `#101010` | Text (shared family color) |

**Fonts** — all are Google Fonts; pick them from Canva's font menu. If one is missing, download it from fonts.google.com and upload the TTF to the Brand Kit (Canva Pro).

| Use | Font |
| --- | --- |
| Headings | Libre Baskerville |
| Body text | Quicksand |
| Labels / sub-heads | League Spartan |

**Logos** to upload:
- `rta-logo-horizontal-tagline.svg`
- `rta-logo-horizontal.svg`
- `rta-logo-primary.svg`
- `rta-logo-reversed.svg`
- `rta-mark.svg`
- `rta-mark-reversed.svg`

## Licenses

- Fonts: SIL Open Font License 1.1 — see `FONTS.md` and the `OFL-*.txt` files.
- Logos, icons and brand guidelines: © Cook Consulting Services, LLC. All rights reserved. Not licensed for reuse.
