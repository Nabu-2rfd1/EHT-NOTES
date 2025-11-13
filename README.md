# GitHub Pages — Video Embed Starter

This repo is a one‑file website you can deploy on GitHub Pages. It embeds a video from YouTube/Vimeo or an MP4 you host in the repo.

## Quick start
1. Replace `VIDEO_ID` in `index.html` with your YouTube video ID (or swap the iframe src to a full Vimeo embed URL).
2. (Optional) If self‑hosting an MP4, uncomment the `<video>` block and put your file at `assets/video.mp4` (create the `assets/` folder).
3. Commit and push to `main`.
4. In GitHub → **Settings → Pages** → **Build and deployment**:
   - **Source:** Deploy from a branch
   - **Branch:** `main` / `/ (root)`
5. Your site will be available at `https://<username>.github.io/<repo>/`.

## Notes
- You can name the repo anything. If you want a root profile site, name it `<username>.github.io`.
- If the `<video>` tag doesn’t play smoothly, prefer YouTube/Vimeo embeds which use CDNs optimized for streaming.
- If you use self‑hosted MP4s larger than ~100 MB, use **GitHub Releases** to host the file and link it.
- To disable Jekyll processing, this repo includes a `.nojekyll` file.
