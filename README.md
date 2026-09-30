# jsscleveland
Chevra Kadisha of Greater Cleveland website (Jekyll, served by GitHub Pages).

## Maintaining the site

- **Menu:** `_data/navigation.yml` drives the header dropdowns, footer, section
  landing-page cards and breadcrumbs. To add a page, create the `.md` file with
  `layout: page` and `section: <id>`, then add a line to the menu file.
- **Draft pages:** `review: true` in a page's front matter shows a
  "Draft for review" banner. Remove it once the Chevra Kadisha has approved the page.
- **Redirects:** old jsscleveland.com addresses live in `redirects/`, one small
  file each (`permalink` = old address, `redirect_to` = new address). They keep
  `#section` anchors and are left out of `sitemap.xml`.
- **Downloads:** put documents in `assets/docs/` and list them on `resources/index.md`.
