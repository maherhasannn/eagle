# Jackie Memorial Site

Source for [jackiememorialsite.com](https://jackiememorialsite.com), a memorial page for **Jackie**, the bald eagle of Big Bear Valley, California, whose nest was watched by hundreds of thousands of people through the Friends of Big Bear Valley live cam. Jackie was found grounded in July 2026 and passed at the Ojai Raptor Center on August 10, 2026.

## What the page covers

- Who she was — the nest cam, her mate Shadow, and the eight seasons they raised eaglets together.
- A timeline of her life in the Jeffrey pine: Mr. B, Stormy and BBB, Simba and Cookie, Spirit, the 2023 blizzard vigil, Misty/Sunny/Gizmo, Luna and Sandy, and her final weeks.
- "In her honor" — a few facts worth remembering, and the memorial in Fawnskin.
- Donation and support links.

## Repo layout

- `index.html` — the entire site as a single self-contained bundle (HTML, CSS, JS, and images are packed into the file and unpacked in the browser on load).
- `images/` — the original photographs used on the page.
- `images/credits.json` — per-photo credits: date, subject, photographer, and license. Eagle photographs are by Trisha Dale Green and Owen Phairis and are used with permission.
- `CNAME` — custom domain for GitHub Pages.

## Editing

Because `index.html` is a generated bundle, edit the source page and re-bundle rather than editing the unpacked markup by hand. When adding a photo, drop it in `images/` and add a matching entry to `credits.json` so attribution stays complete.
