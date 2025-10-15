# Haunted QR Hunt — Netlify Static Site

A spooky, password-gated QR scavenger hunt. Six clues lead players through your locations. Designed for **drag-and-drop deploy** on Netlify.

## Deploy
1. Unzip the folder.
2. In Netlify, click **Add new site → Deploy manually**.
3. Drag the entire folder into Netlify. Done!

## Make QR Codes
Create QR codes that point to:
- `/index.html` (start) and each clue page `/clue1.html` … `/clue6.html`, plus `/finish.html`
Use your Netlify domain like `https://YOUR-SITE.netlify.app/clue2.html`.

## Customize
- Edit the verse text by opening `clueX.html` files.
- Change the required answer by updating the `gate('/next.html','answer')` call on each page.
- Theme is in `assets/style.css`. Light content edits require no build system.

Happy haunting! 👻