# A celebration for Pranesh

A single-page celebration site built as a static `index.html`. Three.js, Tailwind CSS, and canvas-confetti are loaded from public CDNs; no build step or server-side code is required. The supplied video and photos live in `assets/` and are served directly as static files.

## Preview locally

Open `index.html` in a modern browser with an internet connection.

## Publish with GitHub Pages

1. In the repository, open **Settings > Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and the `/ (root)` folder, then save.
4. Open the Pages URL shown on that settings page once deployment finishes.

The flow is welcome, watch the three college goals get checked off, open the letter to reveal the video, continue to the cake, move the cursor along the glowing guide to cut, serve the separated slice, and click the slice for three bites. The photo frame rotates through the supplied photos every three seconds.

The optional reaction recorder asks for explicit screen, camera, and microphone permissions. It displays a camera picture-in-picture and saves the combined screen recording locally as a WebM or MP4 file. It does not upload recordings. Screen recording requires a secure context and browser support for screen capture and MediaRecorder.

The site is responsive and honors the device's reduced-motion preference. The 3D scene and confetti require JavaScript and an internet connection to load the CDN libraries. The Three.js canvas is transparent so the room styling shows through it.
