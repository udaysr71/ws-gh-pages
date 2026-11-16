# Worksheet Maker

Printable maths and phonics worksheets for young children, served by GitHub Pages at **https://ws.kadali.uk**.

Everything is static and self-hosted: `index.html` is the app, and `vendor/` holds the PDF library (jsPDF, MIT) and the Andika and Fredoka fonts (SIL Open Font License), so visitors' browsers don't contact any other site.

## Publish
1. Upload the contents of this folder to the root of a new public repo (not your existing Pages repo).
2. Settings → Pages → Deploy from a branch → `main` / `(root)`.
3. Cloudflare DNS: CNAME `ws` → `<your-username>.github.io`, Proxy status **DNS only**.
4. When GitHub shows the certificate is ready, tick **Enforce HTTPS**.

## Update
Replace `index.html` and commit. GitHub Pages updates within about a minute; browsers may keep the old copy for up to 10 minutes.

Child records are stored in each visitor's browser. Use **Back up records** / **Restore from backup** in the app to move them.
