# kbamponsem.github.io

Personal site for Kwabena Boateng Amponsem — a single static page, no build step, no JavaScript.

Live at **https://kbamponsem.github.io/**

## Structure

| File | Purpose |
| --- | --- |
| `index.html` | The whole site |
| `styles.css` | Typographic stylesheet, light + dark, plus a print stylesheet |
| `404.html` | GitHub Pages 404 page |
| `favicon.svg` | Favicon |

## Editing

Edit `index.html` directly and commit to `main`; GitHub Pages redeploys automatically.

Content is kept in sync with the LinkedIn profile. Where the CV and LinkedIn disagree,
LinkedIn wins — it is the more current record.

## Local preview

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

Printing the page to PDF via the browser print dialog produces a clean one-to-two page CV
thanks to the print stylesheet in `styles.css`.
