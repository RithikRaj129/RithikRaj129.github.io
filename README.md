# rithikraj129.github.io

Personal website of Rithik Raj Vaishya — single-file, no build step, loads fast on GitHub Pages.

## Go live in 5 minutes

1. On GitHub, create a **new public repo** named exactly `RithikRaj129.github.io`.
2. Unzip the package and upload everything: `index.html`, `resume.pdf`, `README.md` and the whole `assets/` folder (Add file → Upload files → Commit). Keep the name `resume.pdf` — the download buttons point to it.
3. Go to **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
4. Wait ~1 minute. Site is live at **https://rithikraj129.github.io**

## Before launch (recommended)

- **Contact form:** sign up free at formspree.io, create a form, and replace `YOUR_FORM_ID` in `index.html` with your ID. Until then the form opens the visitor's email app addressed to you.
- **Photos:** all photos live in `assets/` (already compressed for fast loading). To add one, drop a JPG in `assets/` and copy any `<figure>` line in the "In the room" section.
- **Phone number:** phone, WhatsApp and email are all shown publicly in the contact section. Delete the `tel:` or `wa.me` line in `index.html` to hide either one.
- **Updating your résumé:** replace `resume.pdf` in the repo with the new file, using the same name.

## Custom domain (optional)

Buy a domain (e.g. `rithikraj.in`), then in **Settings → Pages → Custom domain** enter it and add these DNS records at your registrar:

| Type  | Name | Value                  |
|-------|------|------------------------|
| A     | @    | 185.199.108.153        |
| A     | @    | 185.199.109.153        |
| A     | @    | 185.199.110.153        |
| A     | @    | 185.199.111.153        |
| CNAME | www  | rithikraj129.github.io |

Tick **Enforce HTTPS** once the certificate is issued. Update the `canonical` and `og:url` tags in `index.html` to the new domain.

## Editing

Everything — text, colors, sections — is in `index.html`. Accent color is `--accent` at the top of the `<style>` block.
