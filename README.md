# MORI Coffee

A standalone, English-language portfolio concept with its own pages, assets, navigation and GitHub repository.

Live: https://nothing1212673-droid.github.io/mori-coffee/

## Pages

- index.html — home
- menu.html — full menu, category filters and taste suggestions
- story.html — editorial brand story
- visit.html — visit information and demo reservation

## Motion

A gently floating stamp, staggered section reveals, image hover details, animated navigation and a reading progress line. Motion respects prefers-reduced-motion; essential content and controls remain usable without animation.

## Source

No packages, build step or server dependency. style.css controls the visual system, common.js handles navigation and motion, and app.js contains site-specific interactions. Page links are relative and do not depend on another portfolio site.

To preview, serve this folder with any static HTTP server. Publish via GitHub Pages: main branch, / (root). Keep .nojekyll.

## Demo limits

The reservation is saved locally and can be downloaded. It does not book a real table or contact a café. This is a fictional brand made for a portfolio. Browser-local storage is used; storage failures fall back to the current page session. Prices remain in UAH.

## Visual assets

Illustrative images from Unsplash: photo-1509042239860-f550ce710b93, photo-1501339847302-ac426a4a7cbb, photo-1514432324607-a09d9b4aefdd, photo-1461023058943-07fcbe16d735, photo-1515823064-d6e0c04616a7, photo-1572442388796-11668a67e53d, photo-1555507036-ab1f4038808a and photo-1533134242443-d4fd215305ad. Photo endpoints: https://images.unsplash.com/<photo-id>?auto=format&fit=crop&w=1400&q=85 . Images are illustrative references, not proof of a real venue, product or commission.
