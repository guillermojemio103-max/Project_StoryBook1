K-DRAMA STORYBOOK LIBRARY — SEPARATE HTML PAGES

HOW TO OPEN
1. Extract this ZIP.
2. Open the kdrama_storybook folder in VS Code.
3. Run index.html with Live Server.
4. Click "Read story" on any card to open that story's separate HTML page.

PUBLISH ON GITHUB PAGES
1. Upload the contents of this project while preserving the folders shown below.
2. Do not move the story HTML files or image files beside index.html. The stories/ and images/ folders are required.
3. Keep filenames exactly as shown; GitHub Pages uses case-sensitive paths.
4. In the repository, open Settings > Pages and publish from the branch and folder containing index.html.
5. Open the Pages URL, then use "Read story" to open a story and its cover and scene images.

If GitHub's web uploader limits the number of files in one upload, upload the project in multiple batches without changing the folder structure. GitHub Desktop can also upload the whole project folder.

FOLDER STRUCTURE
- index.html: main story library
- stories/story-1.html through stories/story-30.html: separate pages for each story
- style.css: shared design, responsive layout, and dark theme
- script.js: story library, search, genre filter, favorites
- images/covers/: 30 cover illustrations
- images/scenes/: 30 story scene illustrations

Cover photos k1.jpg through k21.jpg and k23.jpg through k30.jpg are matched to their story titles. The extra k22.jpg is a duplicate Signal poster and is intentionally not used. My Demon uses its matching SVG cover. Story scene illustrations use the numbered SVG files.

The story pages use paths relative to this folder structure, so the same links and images work locally and on GitHub Pages.
