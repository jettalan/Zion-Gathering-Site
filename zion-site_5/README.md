# The Zion Gathering Site

Plain HTML and CSS, ready to deploy to Vercel.

## File structure
- `index.html` — Home
- `upcoming/index.html` — All upcoming gatherings list at /upcoming
- `upcoming/bear-lake/index.html` — Bear Lake retreat detail at /upcoming/bear-lake
- `upcoming/adam-ondi-ahman/index.html` — Adam-ondi-Ahman retreat detail at /upcoming/adam-ondi-ahman
- `about/index.html` — About at /about
- `testimonials/index.html` — Testimonials at /testimonials
- `contact/index.html` — Contact at /contact
- `styles.css` — Shared styles

## Deployment
Drop this folder into a GitHub repo, then import the repo in Vercel. Vercel auto-detects it as a static site. No build step.

## What needs to be filled in
**Photos** — Every image area is a styled placeholder. Search the HTML files for `image-placeholder-label` to find them. Replace with `<img src="...">` tags pointing to real photos.

**Kajabi links** — All Reserve and Reserve Suite buttons have `href="#"` placeholders. Search the retreat pages for `href="#"` and replace with the actual Kajabi checkout URLs.

For Bear Lake (9 links needed):
- Private Suite ($1,599)
- King Bed Men's ($799)
- King Bed Women's ($799)
- Queen Bed Men's ($699)
- Queen Bed Women's ($699)
- Twin Bed Men's ($599)
- Twin Bed Women's ($599)
- Bed Share ($375)
- Saturday Day Pass ($99)

For Adam-ondi-Ahman (3 links needed):
- Family Suite ($2,500)
- Full Experience with lodging ($630/person)
- Day Attendance no lodging ($299/person)

**Body copy** — Every page has `[Placeholder ...]` markers in brackets where real content goes. Find and replace.

**Email** — Default is `hello@theziongathering.com`. Update if different.

**YouTube link** — Footer links to `https://youtube.com/@zionmedia`. Update with actual channel URL if different.

**Testimonials** — All testimonial cards are placeholders. Replace text and attributions on home page and `/testimonials` page.

**Presenter photos** — Bear Lake page has placeholder circles for each presenter. Add `<img>` tags inside each `presenter-photo` div when ready.
