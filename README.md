# Short video brief builder

A single-page tool for picking short-video settings (topic, style, voice, length, music and more), with live voice samples and style previews. Press **Copy brief** and paste the result into the chat.

Everything is in `index.html`: no build step, no dependencies, no server. Voice samples and style previews are embedded in the page, so it works offline too.

## Host it on GitHub Pages

1. Create a new repository on GitHub (for example `video-brief-builder`). Public is simplest.
2. Upload the contents of this folder to the repository root: `index.html`, `.nojekyll` and `README.md`.
   - On the repository page choose **Add file → Upload files**, drag the files in and press **Commit changes**.
   - `.nojekyll` is a hidden file. If your file picker hides it, you can skip it: the site works without it.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, then press **Save**.
5. Wait a minute or two. Your site will be at `https://<your-username>.github.io/<repository-name>/`.

## Updating

Replace `index.html` in the repository and commit. The site refreshes within a minute or two.
