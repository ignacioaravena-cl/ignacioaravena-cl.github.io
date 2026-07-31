# ignacioaravena — personal site

Static site (plain HTML + CSS). No build step. GitHub Pages serves it directly.

## Files
- `index.html` — About
- `research.html` — Working papers
- `opeds.html` — Op-eds + interviews/press
- `policy.html` — Published policy documents
- `teaching.html` — Courses
- `contact.html` — Contact
- `style.css` — all styling (edit colors/fonts here)
- `images/profile.jpg` — your photo (replace the placeholder)
- `files/cv.pdf` — your CV (replace the placeholder)

## Before publishing — search for "EDIT:" in the .html files
1. Replace `images/profile.jpg` with your real portrait.
2. Replace `files/cv.pdf` with your real CV.
3. In `research.html`: check paper titles/abstracts and add PDF links.
4. In `opeds.html` / `policy.html`: replace the example entries with your
   real columns, interviews, and policy documents (each has a copy-paste
   PATTERN block in the comments).
5. In `contact.html`: put your real email and social links.
5. Add ESE / Universidad de los Andes when you want it public
   (marked with EDIT comments in `index.html` and `teaching.html`).

## Publish on GitHub Pages
1. Create a repo named `ignacioaravena-cl.github.io` (Public).
2. Upload all these files (drag-and-drop works).
3. Settings → Pages → it goes live at `https://ignacioaravena-cl.github.io`.
4. Settings → Pages → Custom domain → `ignacioaravena.com` → Save.
5. Tick **Enforce HTTPS** once it's available.

## Point the domain (Cloudflare DNS)
Add these records, all with the proxy OFF (grey cloud, "DNS only"):
- A  @  →  185.199.108.153
- A  @  →  185.199.109.153
- A  @  →  185.199.110.153
- A  @  →  185.199.111.153
- CNAME  www  →  ignacioaravena-cl.github.io
