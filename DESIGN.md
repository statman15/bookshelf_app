---
name: Bookshelf
description: Her books as an iPhone photo library, covers edge to edge inside the phone's own grammar.
colors:
  tint: "#177a63"
  on-tint: "#ffffff"
  danger: "#d70015"
  ground: "#ffffff"
  sheet: "#f2f2f7"
  group: "#ffffff"
  label: "#111113"
  label-secondary: "#636366"
  separator: "rgba(60, 60, 67, .2)"
  fill: "rgba(118, 118, 128, .12)"
  fill-strong: "rgba(118, 118, 128, .2)"
  segment-on: "#ffffff"
  glass: "rgba(255, 255, 255, .72)"
  rim: "rgba(0, 0, 0, .08)"
  lift: "rgba(20, 30, 25, .16)"
  tint-dark: "#40cf9f"
  on-tint-dark: "#052a1f"
  danger-dark: "#ff6961"
  ground-dark: "#0c0c0d"
  sheet-dark: "#1c1c1e"
  group-dark: "#2c2c2e"
  label-dark: "#f5f5f7"
  label-secondary-dark: "#a1a1a6"
  separator-dark: "rgba(84, 84, 88, .6)"
  fill-dark: "rgba(118, 118, 128, .24)"
  fill-strong-dark: "rgba(118, 118, 128, .36)"
  segment-on-dark: "#636366"
  glass-dark: "rgba(30, 30, 32, .7)"
  rim-dark: "rgba(255, 255, 255, .1)"
  lift-dark: "rgba(0, 0, 0, .5)"
  mark-material: "rgba(0, 0, 0, .55)"
  cloth-navy: "#2e4a7d"
  cloth-oxblood: "#7a2e3b"
  cloth-ochre: "#8a5a1f"
  cloth-violet: "#4b3f72"
  cloth-walnut: "#6b4e3d"
  cloth-plum: "#8c3b5e"
  cloth-slate: "#35495e"
  cloth-rust: "#9a4a2f"
  cloth-graphite: "#3a3f47"
  cloth-aubergine: "#5c2f55"
typography:
  large-title:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, system-ui, sans-serif"
    fontSize: "34px"
    fontWeight: 700
    lineHeight: "41px"
    letterSpacing: ".01em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, system-ui, sans-serif"
    fontSize: "22px"
    fontWeight: 700
    lineHeight: 1.2
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.3
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 600
    lineHeight: 1.2
  subhead:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    fontFeature: "tnum"
  cover-title:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 700
    lineHeight: 1.15
  segment:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, system-ui, sans-serif"
    fontSize: "14px"
    fontWeight: 500
  mark:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, system-ui, sans-serif"
    fontSize: "12px"
    fontWeight: 600
    fontFeature: "tnum"
  caption:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, system-ui, sans-serif"
    fontSize: "11px"
    fontWeight: 600
rounded:
  none: "0px"
  cover: "4px"
  segment-inner: "8px"
  field: "10px"
  group: "12px"
  menu: "14px"
  sheet: "22px"
  capsule: "999px"
spacing:
  hairline: "2px"
  xxs: "4px"
  xs: "6px"
  sm: "8px"
  md: "12px"
  lg: "16px"
  xl: "20px"
components:
  button-primary:
    backgroundColor: "{colors.tint}"
    textColor: "{colors.on-tint}"
    typography: "{typography.headline}"
    rounded: "{rounded.capsule}"
    padding: "0 20px"
    height: "44px"
  button-add:
    backgroundColor: "{colors.tint}"
    textColor: "{colors.on-tint}"
    rounded: "{rounded.capsule}"
    size: "64px"
  button-text:
    textColor: "{colors.tint}"
    typography: "{typography.headline}"
    padding: "0 4px"
    height: "44px"
  button-close:
    backgroundColor: "{colors.fill}"
    textColor: "{colors.label-secondary}"
    rounded: "{rounded.capsule}"
    size: "32px"
  button-destructive-row:
    backgroundColor: "{colors.group}"
    textColor: "{colors.danger}"
    rounded: "{rounded.group}"
    height: "50px"
  tab-bar:
    backgroundColor: "{colors.glass}"
    rounded: "{rounded.capsule}"
    padding: "4px"
    height: "64px"
  tab-item:
    textColor: "{colors.label}"
    typography: "{typography.caption}"
    rounded: "{rounded.capsule}"
  tab-item-selected:
    backgroundColor: "{colors.fill}"
    textColor: "{colors.tint}"
  segmented-control:
    backgroundColor: "{colors.fill}"
    rounded: "{rounded.field}"
    padding: "2px"
  segment:
    typography: "{typography.segment}"
    rounded: "{rounded.segment-inner}"
    height: "34px"
  segment-selected:
    backgroundColor: "{colors.segment-on}"
  search-field:
    backgroundColor: "{colors.fill}"
    textColor: "{colors.label}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "0 8px"
    height: "38px"
  grouped-inset:
    backgroundColor: "{colors.group}"
    rounded: "{rounded.group}"
  sheet:
    backgroundColor: "{colors.sheet}"
    textColor: "{colors.label}"
    rounded: "{rounded.sheet}"
    padding: "0 16px 16px"
  cover-badge:
    backgroundColor: "{colors.mark-material}"
    textColor: "{colors.on-tint}"
    typography: "{typography.mark}"
    rounded: "{rounded.capsule}"
    padding: "0 7px"
    height: "22px"
---

# Design System: Bookshelf

## Overview

**Creative North Star: "The Photos Library of Her Shelf"**

Bookshelf borrows the iPhone's own material instead of inventing a brand on top of it. Her covers fill the screen in a gapless grid the way photos fill the Photos app; everything else is iOS system chrome kept thin and out of the way: a large title that collapses into a frosted navigation bar, a floating capsule tab bar with a separate round Add button under the thumb, bottom sheets with grabbers, segmented controls and grouped inset rows. Light and dark follow the phone.

The density is photographic: the covers are the interface, and chrome carries only one colour of its own. A single deep green tint marks what can be tapped and what is selected. A book's state (queued, wished, finished) is never a hue; it is a small neutral frosted mark placed on the cover itself. When a cover has no image, it becomes a plain typographic binding in one of ten muted cloth colours, so the grid never shows a hole.

Motion is short and state-bound (150 to 300ms): the tapped cover lifts out of the grid into the book sheet through a view transition, sheets rise and drag down to dismiss, stars pop in sequence. Nothing moves at rest.

**Key Characteristics:**
- One strict gapless cover grid (2px gutters, 2:3 covers), no cards.
- iOS system face at every size, one family, hierarchy by size and weight only.
- One tint for action and selection; state is a neutral mark on the cover.
- Frosted glass for chrome that floats over covers; flat tonal grounds everywhere else.
- Capsules for buttons and bars, nested radii for containers.

## Colors

A neutral iOS system palette carrying one deep green tint, with a dark-mode twin for every role; the covers supply all other colour.

### Primary
- **Evergreen Tint** (light `tint`, dark `tint-dark`): the only chrome colour. Add button, primary capsule buttons, selected tab, text buttons (Done), the More button glyph, star ratings, search caret, focus rings and selection highlight. Dark mode lifts it to a bright mint and swaps its on-colour to near-black green (`on-tint-dark`) to hold contrast.

### Secondary
- **System Red** (`danger`, `danger-dark`): destructive text only, the Remove from Bookshelf row. Never a fill.

### Tertiary
- **Cloth Bindings** (`cloth-navy` through `cloth-aubergine`, ten values): the background of a generated cover when Open Library has no image. Picked by hashing the title, so a book keeps its colour. White title and author sit on them. They appear only inside a cover, never in chrome.

### Neutral
- **System Ground** (`ground` / `ground-dark`): the page behind the grid, and the theme colour of the status bar.
- **Sheet Grey** (`sheet` / `sheet-dark`): the body of bottom sheets, a step off the ground so a sheet reads as a separate layer.
- **Group White** (`group` / `group-dark`): grouped inset rows inside sheets (rating group, Remove row); also the opaque fallback for glass under reduced transparency.
- **Label** (`label` / `label-dark`) and **Secondary Label** (`label-secondary` / `label-secondary-dark`): primary text; counts, authors, placeholders, helper messages and inactive icons.
- **Separator** (`separator` / `separator-dark`): 0.5px hairlines between list rows, menu items, under the scrolled navigation bar and above the scan footer.
- **System Fill** (`fill` / `fill-strong`, with dark twins): translucent grey wells for the search field, segmented track, close button, selected tab, empty cover placeholder and skeletons; `fill-strong` for pressed tabs and the sheet grabber.
- **Glass, Rim and Lift** (`glass`, `rim`, `lift`, with dark twins): the frosted material, its 0.5px inner edge, and the tinted drop shadow colour for floating chrome.
- **Mark Material** (`mark-material`): translucent black with a 12px blur behind ribbons and badges on covers, identical in both schemes because it sits on artwork, not on the ground.

### Named Rules
**The One Tint Rule.** Evergreen is for actions and selection only. It never colours a book's state, a list, or a heading.

**The State Is a Mark Rule.** Up Next is a bookmark ribbon with her queue number at the top right; Finished is a capsule badge with a star and the rating (or a check when unrated) at the bottom left; Wishlist is a capsule badge with a filled heart. All three use the neutral mark material, never a colour.

**The Covers Bring the Colour Rule.** Chrome stays neutral grey and white (or near-black in dark) so real cover art is the only saturated thing on screen.

## Typography

**Display Font:** the iOS system face (`-apple-system`, SF Pro on iPhone; falls back to BlinkMacSystemFont, system-ui)
**Body Font:** the same face
**Label/Mono Font:** the same face, with tabular numerals for counts, queue numbers and ratings

**Character:** One native family at many sizes, so the app reads as part of the phone. Hierarchy comes from size and weight (400 / 500 / 600 / 700), never from a second face, uppercase, or tracking.

### Hierarchy
- **Large Title** (700, 34px, 41px line, +0.01em): the list name at the top of the main view (Library, Up Next, Wishlist, Finished). Collapses into a 17px semibold centred title in the navigation bar on scroll.
- **Title** (700, 22px, 1.2): sheet headings (Add Books), the book title in the book sheet, empty-state heading.
- **Headline** (600, 17px): result row titles, primary and text buttons, the collapsed nav title.
- **Body** (400, 17px, 1.3): base size, search input, menu items, author line in the book sheet.
- **Subhead** (400, 15px, tabular): book count under the large title, row authors, helper messages.
- **Segment** (500, 14px; 600 when selected): segmented control labels.
- **Cover Title** (700, 15px, 1.15, clamped to 5 lines; 13px in the book sheet) with an 11px author at the foot: generated cloth covers only.
- **Mark** (600-700, 12px, tabular): numbers and stars inside ribbons and badges.
- **Caption** (600, 11px): tab bar labels under 25px icons.

### Named Rules
**The One Face Rule.** Every string uses the system stack. Emphasis is weight, not a second family, italics, or uppercase.

## Layout

A single column on the phone: the header (large title, count, 38px search field) sits inside a 16px side margin, then the cover grid runs full bleed edge to edge. The grid is three equal columns with 2px gaps and 2:3 tiles; from 600px wide it becomes auto-fill columns of at least 150px. Top padding clears the safe area plus a 44px navigation bar; bottom padding reserves 92px plus the home-indicator inset so the floating dock never covers the last row.

The dock floats 6px above the home indicator with 12px side insets and a 560px maximum width: a flexible 64px capsule tab bar and a fixed 64px round Add button, 10px apart. Sheets span full width to a 600px maximum, centred, reaching to 10px below the safe-area top. Spacing steps are small and iOS-derived (2, 4, 6, 8, 12, 16, 20px); 16px is the page and sheet margin, 12px separates rows and groups internally. Every tap target is at least 44px.

## Elevation & Depth

A hybrid. The content layer (grid, ground, sheet interiors) is flat and separates by tone: ground, then sheet grey, then group white. Only chrome that floats over covers gets depth, and it gets it in two parts: frosted glass (`blur(24px) saturate(180%)` over the glass tint) plus a soft, low-contrast drop shadow in the lift colour with a 0.5px inner rim. Under `prefers-reduced-transparency` glass becomes the opaque group colour.

### Shadow Vocabulary
- **Dock** (`box-shadow: 0 10px 30px var(--lift), inset 0 0 0 .5px var(--rim)`; Add button uses `0 10px 26px`): the floating tab bar and Add button.
- **Menu** (`box-shadow: 0 16px 40px var(--lift), inset 0 0 0 .5px var(--rim)`): the More popover.
- **Lifted Cover** (`box-shadow: 0 10px 24px var(--lift)`): the cover inside the book sheet, the landing point of the lift transition.
- **Selected Segment** (`box-shadow: 0 2px 6px rgba(0,0,0,.12), inset 0 0 0 .5px var(--rim)`): the thumb of a segmented control.
- **Hairline** (`box-shadow: 0 .5px 0 var(--sep)`): navigation bar once scrolled, row separators, scan footer.
- **Scrim** (`rgba(0,0,0,.35)`): the backdrop behind an open sheet.

### Named Rules
**The Float Earns Glass Rule.** Only surfaces that hover over the covers (navigation bar when scrolled, tab bar, menu) are frosted. Sheets and groups are opaque tone.

**The Soft Lift Rule.** Shadows are blurred and tinted by the lift colour, never hard or offset.

## Shapes

Radius is assigned by role, nesting from sharp to fully round. Covers in the grid are square-cornered so the tiles meet as one surface; the same cover shown small in a row or large in the book sheet takes a 4px radius. Segment thumbs are 8px inside a 10px track; search fields are 10px; grouped inset rows 12px; the menu 14px; sheets 22px on their top corners only. Buttons, tab items, the tab bar, badges and icon wells are full capsules or circles. Borders are not used; edges come from 0.5px inset rims and hairline shadows. The Up Next ribbon is the one cut silhouette: a 24 by 34px rectangle with a notched tail (`clip-path: polygon(0 0, 100% 0, 100% 100%, 50% 78%, 0 100%)`), echoing the Up Next tab icon.

## Components

Icons throughout are Phosphor 2.1.1 SVG symbols in an inline sprite, filled with `currentColor`, 22px by default; tabs switch from the regular to the fill weight when selected.

### Buttons
- **Shape:** full capsule (`rounded.capsule`), 44px minimum height.
- **Primary:** evergreen fill, on-tint text, 600 weight, 20px side padding, optional leading 22px icon at 8px gap. Used for Add a Book in empty states and Scan Barcode (54px tall, full width) in the add sheet footer.
- **Add:** 64px evergreen circle with a 28px plus, sitting beside the tab bar with the dock shadow.
- **Pressed:** scale to .97 (primary) or .92 (Add) with a 150ms ease-out; no hover styling, this is a touch surface.
- **Text:** evergreen 600-weight label, no fill (Done).
- **Icon well:** tint or secondary glyph inside a circular `fill` well: More (26px well in a 44px target), Close (32px, secondary label), per-result Add (30px well; turns into a solid tint circle with a check once added).
- **Destructive row:** full-width 50px group-white row, 12px radius, danger text and trash icon.
- **Focus:** 2px tint outline, 2px offset, on every focusable element.

### Chips
- **Cover badges:** 22px capsules of mark material, white 12px semibold, 12px icons, 6px from the bottom-left cover edge. Not interactive.

### Cards / Containers
- **Corner Style:** no cards in the library; the grid is the container. Inside sheets, grouped inset rows at 12px.
- **Background:** group colour on sheet grey.
- **Shadow Strategy:** flat (see Elevation).
- **Internal Padding:** 8px vertical for the rating group; content supplies its own.

### Inputs / Fields
- **Style:** 38px `fill` well, 10px radius, no border, 18px leading search glyph in secondary label, 17px input text, secondary placeholder, tint caret.
- **Focus:** the field gains a 2px ring of tint at 55% (`box-shadow: 0 0 0 2px color-mix(in srgb, var(--tint) 55%, transparent)`).

### Navigation
- **Tab bar:** a glass capsule, 64px, 4px padding. Four equal items: 25px icon over an 11px semibold label in label colour. Selected item: tint colour, filled icon, capsule `fill` behind it. Pressed: `fill-strong`. 200ms colour transitions.
- **Navigation bar:** transparent over the large title; on scroll it turns to glass with a hairline and fades in a centred 17px semibold title. More button at the trailing edge opens a glass popover menu of 46px rows with hairline dividers and trailing icons.

### Segmented Control
A `fill` track with 2px padding and 2px gaps; equal segments at 34px, 14px medium. The selected segment is a raised thumb in `segment-on` (white, or system grey in dark) with the segment shadow and 600 weight. The book sheet uses one four-way control (Library, Up Next, Wishlist, Finished) with the star rating group appearing beneath when Finished is chosen; the add sheet uses a three-way control for the destination list.

### Bottom Sheet
A modal dialog in sheet grey with 22px top corners, 16px side padding and a safe-area bottom. A sticky 22px grab strip carries a 36 by 5px `fill-strong` grabber; the sheet drags down to dismiss. It rises in 280ms on `cubic-bezier(.2,.9,.25,1)` over a 35% black scrim. The book sheet opens with a 112px lifted cover beside a 22px bold title and secondary author, bottom-aligned; the tall add sheet is a flex column with a scrolling result list and a hairline-topped scan footer.

### Cover Tile (signature)
A 2:3 tile with a `fill` placeholder, a cloth-coloured typographic binding underneath (white bold title top, small author at the foot, 12px padding, title pushed to 42px when a ribbon is present), and the Open Library image fading in over it in 200ms. Pressed: cover scales to .96 and dims to 90% brightness in 150ms. Tapping lifts it into the book sheet via a view transition named `lift` (300ms). State marks sit on top per The State Is a Mark Rule. In result rows the same cover shrinks to 44px with a 4px radius and no text.

### Star Rating
Five 36px Phosphor stars in 50px targets, tint coloured, filled up to the rating. On change they pop from .55 scale with an overshooting 180ms curve, staggered 20ms each.

## Do's and Don'ts

### Do:
- **Do** let covers run edge to edge in the 2px-gap grid; keep chrome to the header, the floating dock and sheets.
- **Do** use the tint (`#177a63` light, `#40cf9f` dark) only for actions, selection, focus and stars.
- **Do** show a book's state as a neutral frosted mark on the cover: ribbon with queue number, star badge, heart badge.
- **Do** give every cover without an image a cloth binding picked by title hash, so the grid has no gaps.
- **Do** define every colour role in both light and dark, and fall back to opaque group colour under reduced transparency.
- **Do** keep motion between 150 and 300ms, tied to state change, and switch it off under reduced motion.
- **Do** keep tap targets at 44px or more and respect the safe-area insets top and bottom.

### Don't:
- **Don't** put a book's state in a colour, a coloured shelf tab or a tinted cover overlay.
- **Don't** wrap covers in cards, borders, list rows or gutters wider than 2px in the library view.
- **Don't** introduce a second typeface, uppercase labels or letter-spaced captions.
- **Don't** frost surfaces that don't float over the covers, or use hard, offset or untinted heavy shadows.
- **Don't** add a second accent colour; red is reserved for destructive text.
