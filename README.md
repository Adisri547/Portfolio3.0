# Aditya Srivastav — Portfolio

A responsive personal portfolio for Data Science, Machine Learning, NLP, and Generative AI projects. It is built with **one HTML file** containing its own CSS and JavaScript—no framework, build step, or package installation required.

## Files

- `index.html` — complete website (HTML, CSS, and JavaScript)
- `README.md` — setup and deployment instructions

## Preview locally

1. Download or clone this repository.
2. Open `index.html` in your browser.

For a local development server, you can use the VS Code **Live Server** extension, but it is optional.

## Personalize before publishing

Open `index.html` and update these placeholders:

1. Search for `data-placeholder-link` and replace the `href="#"` values for GitHub and LinkedIn with your actual profile URLs.
2. Add live demo or GitHub repository links to the project cards if available.
3. Review the project descriptions and reported metrics to ensure they accurately reflect your work.
4. If you want visitors to download your resume, add the PDF to the repository (for example, `resume.pdf`) and add a link to it in the hero section.

Your email is currently set to `adityasrivastav76@gmail.com`.

## Deploy with GitHub Pages

1. Create a new **public** repository on GitHub, such as `aditya-portfolio`.
2. Upload `index.html` and `README.md` to the repository root. Keep the main file named exactly `index.html`.
3. Open the repository on GitHub and go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/(root)` folder, then click **Save**.
6. Wait for GitHub Pages to publish. The URL will usually look like:
   `https://YOUR-USERNAME.github.io/aditya-portfolio/`
7. Visit the URL shown in the Pages settings. Future commits to the selected branch will update the site.

If you name the repository `YOUR-USERNAME.github.io`, GitHub Pages can publish it at the root URL `https://YOUR-USERNAME.github.io/`.

## Alternative: Netlify

You can also deploy without GitHub Pages:
1. Sign in to Netlify.
2. Choose **Add new site / Deploy manually**.
3. Drag in the folder containing `index.html`.
4. Netlify will provide a public URL.

## Tech used

- Semantic HTML5
- CSS (responsive layout, dark theme, animations, reduced-motion support)
- Vanilla JavaScript (mobile navigation, reveal-on-scroll, copy-email button, back-to-top control)

## Notes

- No external JavaScript or CSS libraries are required.
- Social links are placeholders until you replace them with your real profile URLs.
- The page is responsive and uses normal document scrolling; it does not create a nested scroll area.
