---
version: 1
slug: "index-html"
primary_target: "index.html"
related_targets: []
---

## Scope

`index.html`, the whole Bookshelf app (one screen plus its sheets). Visitor mode: Operate. One user, her iPhone, standalone home-screen web app.

## Job and constraints

Add books fast (barcode photo or search), mark finished with stars, browse her covers. Keep `readBarcode`, `visible`, status values `shelf|next|wish|read`, and the saved book shape. Single static file on GitHub Pages.

## Direction contract

THESIS: Her books as an iPhone photo library, covers edge to edge inside the phone's own grammar. Refuses the tracker default of list rows, status buttons and coloured shelf tabs.

OWN-WORLD: iOS system material. SF system face at every size, one family. Gapless three-across cover grid on a system ground, light and dark from the phone. Floating frosted capsule tab bar with a separate round tinted Add button, bottom sheets with grabbers, segmented controls, grouped inset rows. One tint, deep green, for actions and selection only. State is a mark on the cover in neutral frosted material, never the tint: a bookmark ribbon with her queue number for Up Next (echoing the Up Next tab icon), a small badge with stars for Finished, a heart badge for Wishlist. The book sheet sets its state with one four-way segmented control, stars beneath Finished.

STORY: She opens to her covers, finds or adds a book in seconds, taps a cover to lift it into a sheet, moves it or marks it finished and rates it.

FIRST VIEWPORT: Large title and count top left with a More button right, search field under it, then covers filling the rest in three columns at 2px gutters; the capsule tab bar and Add button float over the grid under her thumb.

FORM: Photos Library, position 7 of 7 on the grounded list, seed key 0c441ec0. Raises kept: state as a mark not a hue; one face at many sizes; one strict grid, no cards. Signature interaction: the tapped cover lifts out of the grid into the book sheet (view transition), and the sheet drags down to dismiss. Motion 150 to 300ms, state only.

FINISH: unreviewed and undocumented is unfinished; this build ends with the finish review, the verdict, DESIGN.md, and every shipping raster carrying its provenance

## Unresolved

List display names changed to Library, Up Next, Wishlist, Finished; confirm with her.
