# Your Name — Portfolio

A single-page art portfolio: sidebar with name & contact info, a video + audio
section, and a gallery grid below.

## Files
- `index.html` — the page content
- `style.css` — all the styling
- `images/` — put your artwork images here (artwork-01.jpg, artwork-02.jpg, etc.)
- `media/` — put your mp3 file here

## Before you publish — swap in your content
1. Open `index.html` in any text editor.
2. Replace `Your Name`, the email, Instagram handle, and about text in the sidebar.
3. Replace the YouTube embed link in the `<iframe src="...">` with your own
   video's embed link (open your video on YouTube → Share → Embed → copy the URL
   inside `src="..."`).
4. Put your mp3 file in the `media` folder and update
   `<source src="media/your-track.mp3">` to match its filename.
5. Put 9 (or more) images in the `images` folder and update each
   `<img src="images/artwork-01.jpg">` to match your filenames + write real
   captions in the `<figcaption>` tags.
   - Want a 3×4 grid instead of 3×3? Copy one `<figure class="art-item">…</figure>`
     block and paste it right before `</div>` that closes `.grid`, then point it
     at a new image.

## Publishing it on GitHub Pages (free hosting)
1. Go to https://github.com and log in (or create a free account).
2. Click the **+** icon top-right → **New repository**.
3. Name it anything, e.g. `portfolio`. Keep it **Public**. Click **Create repository**.
4. On the new repo's page, click **uploading an existing file** (or the
   "Add file" → "Upload files" button).
5. Drag in `index.html`, `style.css`, the `images` folder, and the `media`
   folder (drag the whole folders in — GitHub keeps the folder structure).
6. Scroll down, click **Commit changes**.
7. Go to the repo's **Settings** tab → **Pages** (left sidebar).
8. Under "Build and deployment" → "Source", choose **Deploy from a branch**.
9. Under "Branch", choose **main** and folder **/ (root)**, then **Save**.
10. Wait about a minute, then refresh that Pages settings page — it'll show
    a link like `https://yourusername.github.io/portfolio/`. That's your live site.

Any time you want to update the site, just upload new files to the same repo
(or edit them directly on GitHub by clicking the pencil icon on a file) — the
live site updates automatically within a minute or two.
