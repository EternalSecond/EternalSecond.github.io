# EternalSecond — portfolio

Static portfolio built for GitHub Pages. No build step or API keys required.

## Publish on GitHub Pages

1. Create a public repository named `EternalSecond.github.io` (or use it if it exists).
2. Extract the portfolio ZIP and upload its contents into the repository root: `index.html`, `style.css`, `app.js`, SVG assets, and `.nojekyll`.
3. In **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. After deployment, visit https://eternalsecond.github.io and add that URL to the Website field on your GitHub profile.

For a repository with a different name the URL is `https://eternalsecond.github.io/REPOSITORY/`. All asset paths are relative and support this configuration.

## Edit

- Text, project links, and contact: `index.html`
- Colors, layout, responsive behavior: `style.css`
- Local project launch instructions: `app.js`
- Icons and neural-network illustration: SVG files

The page is in English, consistent with the GitHub profile. Contact links currently point to GitHub; no email was supplied.

Google Fonts are optional; system fonts are used if the service is unavailable. All other presentation assets are local. JavaScript is only needed for the launch-instructions dialogs. Navigation and source links work without JavaScript.

## Content provenance

Content checked against these public READMEs on 2026-11-16:
- https://github.com/EternalSecond/DeepRFModel
- https://github.com/EternalSecond/GeometryDash_RFModel
- https://github.com/EternalSecond/Machine-Learning-Course

The diagrams are original explanatory illustrations, not captured trained-policy behavior. No model performance scores, commercial experience, or pretrained demos are claimed. Training/evaluation outputs describe implemented capabilities, not measured performance. The ML course's Claude assistance is acknowledged as documented in its README.

## Validation

JavaScript syntax, HTML internal links, local assets, SVG parsing, and ZIP integrity checked. Browser rendering and interactions could not be tested in the provided environment because the browser-control tool was unavailable. Responsive layouts and reduced-motion styling are included; review on a phone before public release.
