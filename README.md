# A Little Universe Called Us ♡

A dreamy, mobile-friendly romantic website made for Mansi. Built with plain HTML, CSS, and JavaScript, so it can be published on GitHub Pages for free.

## Files
- `index.html` — the whole website
- `assets/soft-romantic.mp3` — optional music file (you add this yourself)

## Publish on GitHub Pages (no coding tools needed)

1. Sign in at https://github.com
2. Click the **+** button (top-right) → **New repository**.
3. Name it `for-mansi` (or any name you like).
4. Choose **Public** if you're using GitHub Free, add a README if you want, and click **Create repository**.
5. Open the new repository. Click **Add file** → **Upload files**.
6. Upload `index.html`. If you want to include music, create/upload the `assets` folder and your MP3 as described below.
7. Click **Commit changes**.
8. Open **Settings** → **Pages**.
9. Under **Build and deployment**, choose **Deploy from a branch**.
10. Choose branch **main** and folder **/(root)**, then click **Save**.
11. Wait a few minutes, then revisit Settings → Pages. Click **Visit site** when the URL appears.

Your site will usually be at:
`https://YOUR-GITHUB-USERNAME.github.io/for-mansi/`

GitHub Pages sites are public on the internet. Do not upload anything private that you would not want others to see.

## Add your own photos
The gallery currently uses sample romantic photos. To make it personal:
1. In `index.html`, find `class="gallery"`.
2. Replace each sample `src="https://images.unsplash.com/..."` with a photo URL you control, or upload your own images into `assets/` and use paths like `assets/our-photo-1.jpg`.
3. If uploading photos, use **Add file → Upload files** in GitHub. For a folder, create/upload the folder contents; GitHub does not store empty folders.
4. Change the captions in the nearby `<span>` elements to your own memories.

Tip: use compressed images and avoid uploading photos that either of you want to keep private. A public Pages site can be shared by anyone who has the link.

## Add soft romantic music
Music is optional. Browsers generally block autoplay, so the visitor must tap the music button.
1. Choose an MP3 you have the right to use.
2. Rename it exactly `soft-romantic.mp3`.
3. Upload it inside an `assets` folder in the repository.
4. The music button will then play/pause it.

If you don't want music, you can leave out the MP3; the rest of the site still works. A romantic song commercially released by an artist may be copyrighted, so use a track you own or are licensed to use.

## Personalize the date or message
- Wedding countdown: in `index.html`, find `const weddingDate = new Date("2026-12-11T20:00:00+05:30");`.
- Love message: find `const loveLetter =` in the script and edit the text between the backticks.
- Recipient heading: search for `Mansi.` in the hero heading.

## If the site does not appear
- Confirm `index.html` is in the repository root (not inside an extra folder).
- Check **Settings → Pages** and confirm `main` + `/(root)`.
- Open the **Actions** tab to see whether the Pages deployment succeeded.
- Wait a few minutes after committing a change, then refresh the site.
