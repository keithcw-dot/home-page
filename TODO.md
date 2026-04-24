# TODO

## Content

- [x] Replace "Keith" placeholder name/bio with real about me text
- [x] Fill in real project sections (2D, 3D, Stage Props)
- [x] Fill in real links with real URLs
- [ ] Add real social links (GitHub, etc.) to sidebar or footer
- [ ] Add actual project entries under each medium once images are ready
- [ ] Add a real headshot or photo to `images/` and wire it up in the sidebar

## Sidebar

- [ ] Decide what to do with the "Site Sponsor" block — real content, a joke, or remove it
- [ ] Replace the "try AIM FREE" block with an actual vintage ad image
  - Classic sidebar ad size: **120×240px** (IAB "Vertical Banner", most authentic for ~1998–2001)
  - Also consider 125×125 (Square Button) if shorter looks better
  - Good candidates: archived Google or Yahoo banner ads from that era
  - Drop the image in `images/ads/` and swap out the placeholder markup
- [ ] Make the poll actually function
  - Option A: pure JS (store vote in localStorage, show result counts)
  - Option B: lightweight backend (Netlify function, Supabase, etc.)
  - Option C: embed a third-party poll widget styled to match

## Icons

- [ ] Replace all emoji with Windows 98 / early-web style icons throughout
  - Icon nav (2D, 3D, Stage Props, Cool Links)
  - Sidebar (About Me avatar, links at bottom)
  - Logo icon
  - Any other emoji used inline
- [ ] Build `<img>`-based icon system so swapping emoji → real images is a one-liner per icon
  - Suggested: `<img class="ico" src="images/icons/foo.png" alt="foo">` everywhere an emoji `ico` span exists now
  - Icons folder: `images/icons/`
- [ ] Source or recreate Windows 98-era icon set (16×16 or 32×32 .png)

## Structure

- [ ] Pull the `<style>` block out into `css/style.css`
- [ ] Create `about.html` for a full bio page
- [ ] Create `projects.html` for a full projects listing
- [ ] Create `links.html` for the cool links / bookmarks page
- [ ] Decide what to do with the guestbook link in the nav (remove or wire up, e.g. Giscus)

## Images

- [ ] Add headshot → `images/headshot.jpg`
- [ ] Add project images → `images/projects/`
- [ ] Add vintage ad → `images/ads/`
- [ ] Add icons → `images/icons/`

## Infrastructure

- [ ] Enable GitHub Pages on `main` branch so the site is publicly accessible
- [ ] Point a custom domain at GitHub Pages (optional)
- [ ] Set up a real visitor counter or remove the fake one
- [ ] Add a favicon — ideally a tiny Windows 98-style icon (`favicon.ico`)

## Nice to have

- [ ] Add basic `<meta>` tags for SEO / social sharing (og:title, og:image, description)
- [ ] Add a `sitemap.xml`
