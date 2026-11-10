# Techfest 2026 — Landing Page Concept

A responsive, single-page landing page inspired by the current Techfest, IIT Bombay visual identity and the 30th-edition event information. Built with plain HTML, CSS and JavaScript; no 3D assets or build tooling.

## Run locally

Open `index.html` in a browser, or serve this folder with any static file server. For example, with Python installed:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Page features

- Responsive desktop and mobile layouts with collapsible mobile navigation
- Scroll reveal transitions, ambient gradients and CSS orbital artwork
- Smooth in-page navigation, useful official-site event links, and map link
- Reduced-motion preference support
- Current edition dates: 16–18 December 2026

The design is an independent concept, not an official Techfest page. Event descriptions and details may change; the buttons link to the official Techfest website for current information.

## GitHub publication

1. Create a GitHub repository named `techfest-landing-page` and choose its visibility. Leave README and license initialization unchecked because this folder already contains a README.
2. In a terminal, change directory to this project folder.
3. Run:

   ```bash
   git init
   git add .
   git commit -m "Build Techfest 2026 landing page"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/techfest-landing-page.git
   git push -u origin main
   ```

4. To publish a live preview, open the repository’s **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save. GitHub will show the published URL in the Pages settings.

Replace `YOUR-USERNAME` with your GitHub username. After the push, enable GitHub Pages from **Settings → Pages** if you want a live preview. Public repositories can use Pages to serve the site directly from this folder.

## Demo recording

### Record with OBS Studio

1. Open the project locally in a browser at `http://localhost:8000`.
2. Open OBS Studio. Add a **Window Capture** source for the browser (or **Display Capture** if Window Capture is unavailable).
3. Set the canvas/output to 1920×1080, 30 fps. Keep the browser window at desktop width; start the page at the top.
4. Start recording, scroll through the hero, experience, event list, summit and visit sections, then stop recording. Save as `techfest-landing-page-demo.mp4`.
5. For a quick responsive moment, resize the browser to a narrow phone-like width and open the menu before ending the recording.

### Share through Google Drive

1. Upload the MP4 to Google Drive.
2. Select the recording and choose **Share**.
3. Under **General access**, choose **Anyone with the link** and set the role to **Viewer**.
4. Select **Copy link** and include that link with your GitHub repository URL.

Check that the recording plays and the link opens in a signed-out/private browser window before sharing.
