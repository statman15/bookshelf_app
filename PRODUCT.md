# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

One person: the owner of a personal home library, using Bookshelf on her own iPhone as a home-screen web app (standalone mode, no Safari chrome). Her main jobs, in order of what she asked for:

1. Adding books fast, often standing at a shelf or in a bookstore.
2. Logging a book as finished and giving it stars.
3. Browsing her collection: enjoying the covers, finding a book she owns, checking the wishlist.

Deciding what to read next exists as a list but was not named as a primary job.

## Product Purpose

A private catalogue of the books she owns, wants, has queued, and has finished. Success is that adding a book takes seconds and her shelf feels like hers to browse.

## Positioning

No account, no social feed, no tracking: one file on her phone that knows her books, with a barcode photo as the fastest way in. Unlike Goodreads-style apps there is nobody else in it.

## Operating Context

- One-handed use on an iPhone, often in a store or beside a physical shelf.
- Opened from the home screen icon; runs full-screen with the iPhone safe areas (status bar, home indicator).
- Books are added by typing a title, author or ISBN, or by photographing the barcode on the back cover.

## Capabilities and Constraints

- Lists: Shelf (everything except wishlist), Read next, Wishlist, Read. List names may change; the four states must stay.
- Marking a book read reveals a 1-5 star rating.
- Long-pressing a cover opens quick actions (move between lists, remove) without opening the book.
- Opening a book shows its first-published year, page count and Open Library description, fetched once and saved with the book.
- Search filters her own books by title or author.
- Book data and covers come from Open Library (free, no key), with Google Books as a fallback for editions Open Library lacks. Google Books is used without an API key, so it shares a global allowance and often returns nothing; treat it as a bonus, never a guarantee.
- When no service has the book, she can add it by hand with title and author.
- Book details (year, page count, genre, publisher, description) are fetched on first open and saved with the book.
- Barcode reading uses ZXing on a photo (EAN-13 ISBN).
- Data lives in localStorage on the phone; JSON backup and restore through the share sheet protects against loss.
- Stack: a single static `index.html` (vanilla HTML/CSS/JS, no build step), deployed to GitHub Pages at https://statman15.github.io/bookshelf_app/ from `main`. `check.html` is the self-check for the barcode reader and list filter; exported function names `readBarcode` and `visible` must keep working.
- Existing saved data shape (`id, title, author, cover, status, rating`) must stay compatible.

## Brand Commitments

- Real book covers stay the heart of the main view.
- Nothing else visual from earlier versions is binding.

## Evidence on Hand

Her real books live only on her phone. Open Library covers are the only imagery. No testimonials, logos or claims exist and none should be invented.

## Product Principles

1. Adding a book beats everything else for speed and reach of the thumb.
2. The covers are the interface; chrome stays out of their way.
3. Private and local: no accounts, no sharing surfaces, no data leaving the phone except her own backup.
4. Nothing she has saved may be lost by a redesign.
