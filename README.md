# Rinat Ltd — Website (Updated Design)

This repository contains a small single-page static website for Rinat Ltd (Rinat, electrician). The design has been updated with a friendly "electrician-magician" theme and improved layout.

Files included
- `index.html` — main page (with placeholder contact details)
- `assets/styles.css` — site styles
- `.nojekyll` — prevents Jekyll processing on GitHub Pages
- `README.md` — this file

Placeholders to update
- Phone: +44 7123 456789
- Email: info@rinatltd.example
- Address: 123 Example Street, Your Town, UK

How to publish
1) Using GitHub web UI
- Create the `main` branch if repository is empty.
- Add files via "Add file" → "Create new file" or upload (create `assets/` folder and paste `styles.css`).
- Commit to `main`.
- Go to Settings → Pages and set source to `main` branch, folder `/ (root)`.
- Site will appear at `https://Rinatltd.github.io/rinatltd.co.uk/` or a custom domain if you add one.

2) Using git locally
- git clone https://github.com/Rinatltd/rinatltd.co.uk.git
- cd rinatltd.co.uk
- Create files (index.html, assets/styles.css, .nojekyll, README.md)
- git add .
- git commit -m "Add updated site design for Rinat Ltd"
- git branch -M main
- git push -u origin main
- Enable GitHub Pages in repository settings.

Optional: Custom domain
- Add a `CNAME` file with your domain on a single line and configure DNS as per GitHub Pages instructions.

Notes
- Replace the placeholder phone, email and address in index.html before publishing live.
- If you want a real logo image, add `assets/logo.png` and I can update the markup to use it.