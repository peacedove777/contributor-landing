# Anangu Tjuta Contributor Landing Page

This repository contains a GitHub Pages-ready landing page for the Anangu Tjuta Contributor Program.

## 🚀 How to Deploy

1. Fork this repository or upload to your own GitHub account.
2. Go to **Settings > Pages**.
3. Under **Source**, select:
   - Branch: `main` (or `master`)
   - Folder: `/ (root)`
4. Click **Save**.
5. Your site will be live at `https://<your-username>.github.io/contributor-landing/`.

## 🌐 Optional: Use Custom Domain

To use `contribute.anangutjuta.org`, add a file named `CNAME` to the root of this repo containing:
```
contribute.anangutjuta.org
```

Then add a **CNAME DNS record** at your registrar:
- **Name (Host):** contribute
- **Points to:** your-username.github.io
- **TTL:** Auto or 3600

## 📫 Want to Collect Messages?

1. Go to https://formspree.io and create a form.
2. Get your `formID`, and in `index.html`, update:
```html
<form action="https://formspree.io/f/yourformid" method="POST">
```

---

Built with ❤️ for the Anangu Tjuta contributor network.
