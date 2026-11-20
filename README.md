# Boot Heel Brief — static site

The public web home for the Boot Heel Brief newsletter, served by GitHub Pages.

- `index.html` — homepage (latest issue + subscribe link)
- `issue-no-N/index.html` — one folder per issue, so the URL is clean:
  `bootheelbrief.com/issue-no-11/`
- `style.css` — the BHB theme (cream #FFF8E7, deep teal #0E4A4A, tan #E8DDC0)

Images are NOT stored here. They live on Cloudflare R2 and are served by the
BHB Worker (https://bootheelbrief.dealershiptoolbox.workers.dev/img/...),
so they don't count against GitHub Pages bandwidth.

Email delivery is via Kit (https://boot-heel-brief.kit.com/). This site is the
themed web version of each issue.
