# Coming Soon Website — Fixed Video Loop

This is a static HTML/CSS/JavaScript site for Vercel. The MP4 is deliberately stored beside `index.html` in the repository root so the static path `/coming-soon-portrait-4k.mp4` works with Vercel's **Other** preset.

## Deploy the fix
1. Extract this ZIP.
2. In your existing GitHub repository, replace the old `index.html` and `style.css`, and upload `coming-soon-portrait-4k.mp4` to the same root level as `index.html`.
3. Commit the changes.
4. In Vercel, open your project and redeploy the latest commit (or wait for automatic deployment).

Expected root layout:
- index.html
- style.css
- coming-soon-portrait-4k.mp4

Video playback uses `autoplay muted loop playsinline`. The site also retries playback and shows a play button if the browser blocks autoplay. Muted autoplay is normally required by browser policies.
