# Pushpendra Raj — Portfolio Website

A responsive, static personal portfolio built with HTML, CSS and vanilla JavaScript. It is designed for GitHub Pages and requires no build tools or backend.

## Preview locally

1. Extract the ZIP file.
2. Open the `pushpendra-raj-portfolio` folder.
3. Double-click `index.html`, or use VS Code's Live Server extension.

## Before publishing — important personalisation

Search `index.html` and replace these placeholders:

- `YOUR_EMAIL@example.com` with your professional email address.
- `https://github.com/` project links with the actual repository URLs.
- Generic LinkedIn and GitHub profile links with your profile URLs.
- Add your résumé PDF to `assets/Pushpendra_Raj_Resume.pdf`, then change the Resume link in the Contact section to `assets/Pushpendra_Raj_Resume.pdf` and add the `download` attribute.
- Verify the employment dates/status and IIT Patna degree status. The current page flags these for verification rather than assuming completion.
- Add measurable achievements, accurate responsibilities and project screenshots where available.

The current project descriptions are based on the projects discussed during portfolio planning. Do not publish claims or technologies that you cannot demonstrate.

## Publish using GitHub Pages

### Option A — personal site (recommended)

1. Sign in to GitHub and create a new **public** repository named exactly:
   `pushpendraraj05.github.io`
2. Extract this ZIP.
3. Upload the **contents** of the `pushpendra-raj-portfolio` folder (the `index.html`, `style.css`, `script.js` and `assets` folder) to the root of that repository.
4. Commit the files to the `main` branch.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch **main** and folder **/(root)**, then click **Save**.
8. Wait for the GitHub Pages deployment to finish. Your site will be available at:
   `https://pushpendraraj05.github.io/`

### Option B — project site

1. Create a public repository, for example `my-portfolio`.
2. Upload the website files to the repository root.
3. Open **Settings → Pages** and select **Deploy from a branch → main → /(root)**.
4. Save. Your site URL will be:
   `https://pushpendraraj05.github.io/my-portfolio/`

## File structure

```text
pushpendra-raj-portfolio/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    └── favicon.svg
```

## Notes

- No API keys, server, database or build step are needed.
- Google Fonts are loaded from Google Fonts; if unavailable, the page uses fallback fonts.
- The contact button uses `mailto:`. It opens the visitor's configured email application.
- Replace placeholder repository/profile URLs before sharing the website publicly.
