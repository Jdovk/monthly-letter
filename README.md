# Moon & Lune — A Year Written in Starlight

A fantasy-romance visual novel for Moon and Lune, built as a simple static website for GitHub Pages.

## Preview locally
Open `index.html` in a modern browser. Scene photographs load from Unsplash and require an internet connection.

## Publish with GitHub Pages
1. Open this repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and `/(root)`, then save.
4. After GitHub Pages finishes deploying, use the URL shown in that section.

This update is on the `anniversary-12-month-update` branch. Merge its pull request into `main` before publishing.

## Music player
- Local audio upload plays on the visitor's device only; the file is not sent to GitHub.
- Local audio starts at **20% volume** and can be adjusted.
- Paste an `open.spotify.com` playlist, album, track, artist, show, or episode link and press Enter to embed Spotify.
- Spotify's embedded player has its own volume controls; the website slider controls local audio only.
- To use your own background music for all visitors, upload one audio file you have permission to distribute into `assets/music/` and name it exactly `background.mp3`. The website loads `assets/music/background.mp3` automatically and starts at 20% volume. You can still use the Upload song button to test a different local file on your own device. Do not upload copyrighted music without permission.

## Monthly updates
Use `MONTHLY_UPDATE_TEMPLATE.md` as a checklist. Keep the personal letter as the final page after the story, and preserve earlier versions in Git history.
