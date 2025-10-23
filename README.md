
# Perspicuum Power BI Demo (GitHub Pages)

This folder is ready to be published as a static website on **GitHub Pages**.

## Quick publish steps
1. Create a new GitHub repository (public): `perspicuum-powerbi-demo` (or any name).
2. Upload the two files from this folder:
   - `index.html`
   - `README.md`
3. Commit to the **main** branch.
4. Go to **Settings → Pages**:
   - **Source:** *Deploy from a branch*
   - **Branch:** `main` / **Folder:** `/ (root)`
   - Save.
5. Wait ~1–2 minutes, then open:
   - `https://<your-username>.github.io/<your-repo>/`

> If you prefer to keep the existing filename, you can publish `public_demo5.html` directly, but `index.html` loads automatically at the root URL so it is recommended.

## Notes
- The page embeds a public Power BI *Publish to web* URL, so it can load without sign-in.
- Everything is HTTPS; no mixed-content warnings should appear on GitHub Pages.
- If you see a temporary 404 after enabling Pages, wait a minute and hard refresh (Ctrl/Cmd + Shift + R).
