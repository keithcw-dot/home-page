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

- [x] Build `<img class="ico">` icon system with `image-rendering: pixelated` for crisp scaling
- [x] Replace icon nav emoji with real Win98 icons (desktop_old=2D, ole=3D, paint=Stage Props, search_web=Cool Links)
- [x] Replace About Me silhouette with `address_book_user.png`
- [x] Replace AIM ad block with 1998 Google logo
- [ ] Replace remaining emoji (logo area, sidebar bottom links, inline) with Win98 icons as sourced
- [ ] Source a Win98-style icon for Stage Props that fits better than paint bucket (optional)
- [ ] Consider placing `multimedia_0.png` next to the site title in the logo area
- [ ] Reconsider / rename "Keith's Home on the Web" site title

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
