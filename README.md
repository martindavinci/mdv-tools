# MDV Tools

The published site. GitHub Pages serves this repo from the root of the `main` branch.

## Do not edit anything here

Every page in this repo is generated. The source lives in `mdv-tools67-src`; the build
writes the pages, then they are copied here and committed. Edit a page here and the next
build overwrites it. Fix the source instead.

## What a page is

One tool is one self-contained HTML file. The stylesheet and the script are inlined at
build time, so a page has no external stylesheet, no script tag pointing elsewhere, no
webfont, no CDN, no analytics.

A tool page makes zero network requests once it has loaded. Your input stays in the tab.
Save a page to disk and it still works with the network off.

## Layout

    index.html          the catalogue
    <slug>.html         one tool
    .nojekyll           stops Jekyll from hiding files whose names start with an underscore

## Licence

MIT. See `LICENSE`.
