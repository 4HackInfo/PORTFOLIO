# Christian Andiason — Portfolio Website

A responsive personal portfolio built with plain HTML, CSS, and JavaScript. No build step or paid service is required.

## Before publishing
1. Open `index.html`.
2. Replace `christian.andiason@example.com` with your real professional email in both the visible text and `mailto:` link.
3. Review the About section and skill ratings so they accurately describe you.
4. Add real project screenshots and working project links when available. The ResQTrack visual is explicitly a concept illustration, not a screenshot of a finished system.
5. Check every link and test the page on desktop and mobile.

## Run locally
- Simplest: double-click `index.html` to open it in a browser.
- Recommended: open this folder in VS Code, install the Microsoft **Live Preview** extension, open `index.html`, and launch the preview.

## Publish on GitHub Pages (recommended for this static site)
1. Sign in at https://github.com and create a **public** repository named `portfolio`.
2. Upload the *contents* of this folder (not the ZIP file and not an extra outer folder). Keep `index.html`, `style.css`, `script.js`, and `assets/` at the repository root.
3. Open repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`, then click **Save**.
6. Wait for publishing, then open the site link shown in Settings → Pages. It usually looks like `https://YOUR-USERNAME.github.io/portfolio/`.
7. Test the public link in an incognito/private window and on a phone.

## Update after publishing
Edit and test the files locally, upload the changed files to the same repository, and commit the changes. Wait for GitHub Pages to finish publishing, then refresh the same live URL.

## Common fixes
- **404:** confirm the repository is public, Pages is enabled, and `index.html` is at the repository root on `main`.
- **Missing CSS:** ensure `style.css` is at the same level as `index.html` and its spelling/capitalization matches.
- **Mobile menu doesn't open:** confirm `script.js` is uploaded and the script tag is present at the bottom of the HTML.
- **Email button opens a sample address:** replace the example email before publishing.
- **Old version still appears:** confirm you committed the changes, wait for deployment, and refresh the page.

## Other hosting choices
- **Vercel:** import the GitHub repository at https://vercel.com. For this plain HTML site, use the repository root and no build command; output directory can be `.` if required.
- **Firebase Hosting:** requires Node.js and Firebase CLI. Install Node.js LTS, run `npm install -g firebase-tools`, then `firebase login`. Create a `public` folder and copy the website files into it. From the project root run `firebase init hosting`, select the existing Firebase project, set public directory to `public`, answer **No** to single-page-app rewrites for this one-page portfolio, preserve your own `index.html`, then run `firebase deploy --only hosting`.

## Project structure
- `index.html` — content and page sections
- `style.css` — colors, layout, responsive styling, animation-safe behavior
- `script.js` — mobile navigation and current year
- `assets/` — add your own images or downloadable public files here

Do not upload passwords, private documents, or API keys. Publish only content you are comfortable making public.


### Add your real profile photo

The homepage currently uses `assets/profile-placeholder.svg` as a visual placeholder. Replace it with your own portrait image named `profile.jpg` inside the `assets` folder, then update the image source in `index.html` to `assets/profile.jpg`. A vertical portrait with good lighting works best.
