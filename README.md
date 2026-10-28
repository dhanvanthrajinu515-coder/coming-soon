# Coming Soon Website

A single-page, responsive landing page using the supplied MP4 as a full-screen background video. No build tools or dependencies are required.

## Preview locally
Open `index.html` in a browser. For the most accurate test, use a local server such as VS Code Live Server.

## Publish with GitHub + Vercel
1. Extract this ZIP.
2. Create a new GitHub repository and upload all files and the `public` folder.
3. In Vercel, choose **Add New → Project**, import the repository.
4. Framework preset: **Other**. Build command: leave empty. Output directory: `.` (or leave default if detected).
5. Click **Deploy**.

The MP4 is stored in `public/coming-soon-portrait-4k.mp4`. Video autoplay is muted because browsers usually block autoplay with sound. Visitors can enable sound with the button. If the video does not autoplay on a device, visitors can still view the page and the browser may show its own playback controls only if you add `controls` to the video element.
