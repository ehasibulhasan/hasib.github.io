# Hasibul Hasan — Academic Website

A responsive, minimal academic portfolio built with plain HTML, CSS, and JavaScript for GitHub Pages. No build tools or dependencies are required.

## 1. Personalize before publishing

Open `index.html` and replace the following placeholders:

- `YOUR_EMAIL@colorado.edu` — replace both the visible email address and the `mailto:` address with your preferred public email.
- Google Scholar, GitHub, and LinkedIn URLs — replace the generic profile links with your own profile URLs (or remove any that you do not use).
- Add your current courses, semester information, working papers, and other research details as appropriate.

The biography and research-interest descriptions are starter copy. Please review them for accuracy and update them as your work evolves.

## 2. Add your CV

Place your PDF in the `assets` directory and name it exactly:

`Hasibul_Hasan_CV.pdf`

The CV button already links to this path. If you use a different filename, update the link in `index.html`.

## 3. Publish with GitHub Pages

1. Sign in to GitHub and create a **public** repository named exactly `YOUR-GITHUB-USERNAME.github.io`.
2. Upload the contents of this folder to the root of that repository. The `index.html` file must be at the repository root, not inside another nested folder.
3. Commit the files to the `main` branch.
4. In the repository, open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. Wait for the deployment to finish. Your site will be available at `https://YOUR-GITHUB-USERNAME.github.io/`.

GitHub Pages may take a few minutes to publish the first time. You can monitor progress in the repository's **Actions** tab.

## Files

- `index.html` — page content and structure
- `styles.css` — layout, typography, colors, and responsive styling
- `script.js` — mobile navigation and current footer year
- `assets/` — place your CV PDF and optional profile image here

## Notes

- The site uses Google Fonts for DM Sans and Libre Baskerville. If external font loading is unavailable, local system fallback fonts are used.
- No analytics, trackers, forms, or external JavaScript libraries are included.
- You can preview the site locally by opening `index.html` in a browser.
