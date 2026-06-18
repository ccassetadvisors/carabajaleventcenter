# Carabajal Event Center — website

Static site. No build step.

## Deploy on GitHub Pages
1. Create a repo and upload the contents of this folder (index.html, the other .html pages, the `images/` folder, `.nojekyll`).
2. Repo **Settings → Pages → Build and deployment → Deploy from a branch**, pick `main` / root.
3. Your site goes live at `https://<user>.github.io/<repo>/`.

## Contact form (FormSubmit)
The form on Contact.html posts to FormSubmit at **jana@poka.com**.
- Replace that address in `Contact.html` (`action="https://formsubmit.co/..."`) with the real inbox if different.
- The **first** real submission triggers a one-time activation email from FormSubmit — click it once and the form is live.

## Notes
- Fonts load from Google Fonts. Photos are in `images/`.
- The gallery shows every venue photo from the export. Drop more JPGs in `images/` and add `<a class="gitem" ...>` entries to grow it.
