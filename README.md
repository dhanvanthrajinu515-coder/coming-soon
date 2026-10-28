# EasyBill Coming Soon (Frontend Only)

This is a small static Vercel site that displays the teaser video in a centered 9:16 portrait frame.

## Files
- `index.html` — the coming-soon page
- `public/coming-soon.mp4` — teaser video
- `vercel.json` — static hosting headers

## Deploy to Vercel
1. Extract this ZIP.
2. Create a new GitHub repository, for example `easybill-coming-soon`.
3. Upload the contents of this folder to the repository root. Do not upload the outer ZIP itself.
4. In Vercel, choose **Add New → Project**, import that repository, and deploy.
5. Framework Preset: **Other**. Build Command: leave empty. Output Directory: leave empty (or `.` if Vercel requires a value).
6. No environment variables are needed.

The video autoplays muted because mobile browsers generally block autoplay with sound. Visitors can tap **Sound off** to enable sound. The video is framed vertically using `object-fit: cover`; the original video is not re-encoded, so the sides/top may be cropped to fill the 9:16 portrait frame.
