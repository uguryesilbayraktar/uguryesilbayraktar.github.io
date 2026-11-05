# Uğur Yeşilbayraktar

Personal academic website at https://uguryesilbayraktar.github.io/.

Plain HTML and CSS. No build step or dependencies.

## Edit the website

- `index.html`: biography and home page.
- `research.html`: papers, coauthors, publication information, links and abstracts.
- `teaching.html`: courses and teaching roles.
- `styles.css`: shared design and responsive layout.

The sidebar and CV link appear on all three pages. Update each page when these change. The postal contact details are on the home page.

## Update the portrait

Replace `portrait.png` with the new photo. The same image is used on all three pages; the circular crop is controlled by `.portrait` in `styles.css`.

## Publish

In repository Settings → Pages, choose **Deploy from a branch**, branch **main**, folder **/ (root)**. Save. GitHub Pages will publish subsequent commits automatically.

## Preview locally

Run `python3 -m http.server 8000` from this folder and open http://localhost:8000.
