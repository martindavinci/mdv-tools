# MDV Tools

One file, one job, no network. Small tools that run in your browser, on your own device, and say
how they work.

**Use them at [martindavinci.github.io/mdv-tools](https://martindavinci.github.io/mdv-tools)**

## What you get

- **Nothing leaves your device.** Once a page has loaded it makes no network requests: no uploads,
  no analytics, no fonts or scripts from anywhere else. The footer of every page counts the requests
  it has made, live, so you can check for yourself.
- **Nothing is kept.** What you type or drop into a tool is gone when you close the tab. Pages
  follow your device's light or dark setting; the one thing a page remembers is the mode you pick
  with the Dark button.
- **No account and no ads.**
- **It works offline.** Every tool is a single HTML file with its styles and code inside it.
- **Every tool explains itself.** "How this works", at the bottom of each page, says what the tool
  does, what it rounds or approximates, and what it refuses to do.

## The tools

There are <!-- mdv-count -->32<!-- /mdv-count --> so far, and more on the way.

<!-- mdv-tools -->

**Text**

- [Case converter](https://martindavinci.github.io/mdv-tools/case-converter.html) — Upper, lower, title, sentence, camel, snake, kebab, constant. Unicode-aware.
- [Remove duplicate lines](https://martindavinci.github.io/mdv-tools/remove-duplicate-lines.html) — Each line once, first or last occurrence, in original order or sorted.
- [Slugify](https://martindavinci.github.io/mdv-tools/slugify.html) — Fold accents to ASCII, pick a separator, cap the length at a word boundary.
- [Sort lines](https://martindavinci.github.io/mdv-tools/sort-lines.html) — A–Z, Z–A, natural, by length, shuffle or reverse, with trim, case-fold, blank and duplicate removal.
- [Text diff](https://martindavinci.github.io/mdv-tools/text-diff.html) — Line-by-line comparison of two blocks of text.
- [Unicode inspector](https://martindavinci.github.io/mdv-tools/unicode-inspector.html) — Every code point with its bytes, category, script and hidden-character flags, plus the four normalisation forms.
- [Word counter](https://martindavinci.github.io/mdv-tools/word-counter.html) — Words, graphemes, bytes, sentences, paragraphs and reading time, live as you type.

**Encoding and crypto**

- [Base64 Encoder & Decoder](https://martindavinci.github.io/mdv-tools/base64-encode-decode.html) — Text to Base64 and back, both fields live, with the URL-safe alphabet and 76-column wrapping.
- [Checksum](https://martindavinci.github.io/mdv-tools/file-checksum.html) — SHA-256, SHA-1 and size for any file, computed locally.
- [Hash generator](https://martindavinci.github.io/mdv-tools/hash-generator.html) — CRC-32, MD5, SHA-1, MySQL PASSWORD(), SHA-256, SHA-384 and SHA-512 of one string at once, with the broken ones marked as broken.
- [JWT decoder](https://martindavinci.github.io/mdv-tools/jwt-decoder.html) — Header, payload and claims with expiry as a date. Decodes only, never verifies.
- [Password generator](https://martindavinci.github.io/mdv-tools/password-generator.html) — Random passwords from the browser crypto API, with length, character sets, and the entropy in bits.
- [QR code generator](https://martindavinci.github.io/mdv-tools/qr-code-generator.html) — Turn a link or any text into a QR code with no redirect inside, then download PNG or SVG or copy the image.
- [URL Encoder & Decoder](https://martindavinci.github.io/mdv-tools/url-encode-decode.html) — Percent-encode or decode text as you type, for a query value, a whole URL or form data, with broken escapes named by position.
- [UUID generator](https://martindavinci.github.io/mdv-tools/uuid-generator.html) — Version 4 random or version 7 time-ordered, up to 1,000 at a time, from WebCrypto.
- [Wi-Fi QR code](https://martindavinci.github.io/mdv-tools/wifi-qr-code.html) — Make a QR code that joins your Wi-Fi when scanned, for WPA, WEP or open networks, ready to print.

**Converters**

- [Base converter](https://martindavinci.github.io/mdv-tools/base-converter.html) — Binary, octal, decimal, hex, any base to 36, exact at any size.
- [JSON and CSV converter](https://martindavinci.github.io/mdv-tools/json-to-csv.html) — Turn a JSON array into CSV or TSV with nested objects as dotted columns, or CSV and TSV back into JSON.
- [JSON and YAML converter](https://martindavinci.github.io/mdv-tools/json-to-yaml.html) — Convert JSON to YAML or YAML to JSON as you type, with anchors, merge keys and several documents read.

**Developer**

- [Cron expression](https://martindavinci.github.io/mdv-tools/cron-generator.html) — Read a crontab line in plain English, field by field, with the next runs on this device's clock.
- [JSON formatter](https://martindavinci.github.io/mdv-tools/json-formatter.html) — Indent, sort keys, or minify. Reports the exact parse error position.
- [Regex tester](https://martindavinci.github.io/mdv-tools/regex-tester.html) — Matches highlighted, groups in a table, replace preview and a plain-English reading of the pattern.

**CSS and design**

- [Clamp calculator](https://martindavinci.github.io/mdv-tools/clamp-calculator.html) — clamp() for fluid type and spacing, in rem or px, with slope, intercept and a preview at six widths.

**Images and media**

- [Image compressor](https://martindavinci.github.io/mdv-tools/image-compressor.html) — Compress up to 50 images to WebP or JPEG with a quality slider and a size cap, and compare before and after.
- [Image resize](https://martindavinci.github.io/mdv-tools/image-resizer.html) — Scale to a width or height and re-encode as PNG, JPEG or WebP.

**Numbers and units**

- [Aspect ratio](https://martindavinci.github.io/mdv-tools/aspect-ratio-calculator.html) — Lock a ratio and solve the missing dimension.
- [Percentage calculator](https://martindavinci.github.io/mdv-tools/percentage-calculator.html) — Five percentage questions answered as you type: percent of, what percent, change, increase or decrease, and the value before, in exact decimals.

**Time and date**

- [Age calculator](https://martindavinci.github.io/mdv-tools/age-calculator.html) — Give a date of birth and read the exact age in years, months and days, with the weekday of the birth and the next birthday.
- [Date difference](https://martindavinci.github.io/mdv-tools/date-difference.html) — The time between two dates in years, months and days, in weeks, total days and weekdays, with the end date and clock times optional.
- [Discord timestamp](https://martindavinci.github.io/mdv-tools/discord-timestamp.html) — Pick a date, time and zone and copy every Discord timestamp code, or paste a code to read the moment inside it.
- [Time zone converter](https://martindavinci.github.io/mdv-tools/timezone-converter.html) — Type a time the way people write it, like 10am PT or 15:00 CET, and read it in every common zone with summer time counted.
- [Timestamp converter](https://martindavinci.github.io/mdv-tools/timestamp-converter.html) — Unix seconds or milliseconds to ISO 8601, local time, ISO week and relative time.

<!-- /mdv-tools -->

## Use them offline

- **One tool:** open it and save the page (Ctrl+S, or ⌘S on a Mac). "Webpage, HTML only" is enough,
  because everything the tool needs is already inside the file.
- **All of them:** download this repository as a ZIP (Code → Download ZIP), unzip it and open
  `index.html`. The pages work straight from the folder; no server is needed.

## Host your own copy

The site is plain static files: no build step, no database, no server code. Any static host will
serve it as it is.

- **Docker**, from inside the unzipped folder, then open <http://localhost:8080>:

  ```sh
  docker run -d --name mdv-tools -p 8080:80 -v "${PWD}:/usr/share/nginx/html:ro" nginx:alpine
  ```

- **Python:** `python3 -m http.server 8080` (on Windows, `python -m http.server 8080`)
- **Node:** `npx serve .`
- **GitHub Pages:** fork this repository, then Settings → Pages → Deploy from a branch → `main`,
  `/ (root)`.
- **Anywhere else** that serves files — Netlify, Cloudflare Pages, nginx, Caddy, an S3 bucket —
  works the same way.

Serve your copy over **HTTPS**, or open it as `localhost`. Browsers keep two things for secure pages
only: the clipboard, which most Copy buttons use, and the SHA functions behind the hash generator and
the file checksum. From a plain `http://` address on another machine, those Copy buttons and SHA
digests stop working. Files opened straight from disk count as secure.

## Browsers

Current versions of Chrome, Edge, Firefox and Safari. An older browser can lack something a tool
relies on, such as the full list of time zones.

## Feedback

A wrong result, a confusing message, or a tool you would like to see: open an issue at
[github.com/martindavinci/mdv-tools/issues](https://github.com/martindavinci/mdv-tools/issues).

## Licence

MIT. Use it, copy it, host it and change it; see [`LICENSE`](LICENSE).
