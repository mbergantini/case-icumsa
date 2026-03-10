# ICUMSA Color Case Study Portfolio (Public Summary)

This repository is a **public-facing case-study showcase** for a private machine learning/computer vision project. It is designed for GitHub Pages publication and focuses on project context, methodology, and outcomes appropriate for recruiter and hiring-manager review.

## Repository purpose

- Present a clear, professional summary of an industrial AI case study.
- Share validated narrative and key results without exposing confidential source code or raw data.
- Provide a static, no-build portfolio artifact that can be published immediately.

## Project structure

- `index.html` — one-page case-study website (all sections and portfolio narrative)
- `style.css` — responsive styling, layout, typography, and print baseline
- `.nojekyll` — ensures GitHub Pages serves files directly from root
- `Article.pdf` — source article PDF used as technical reference
- `assets/architecture-diagram.svg` — custom pipeline diagram (CV/ML workflow)
- `assets/favicon.svg` — minimalist icon for browser tab and metadata
- `LICENSE` — repository license
- `README.md` — setup, deployment, and customization instructions

## Deploy on GitHub Pages (no build step)

1. Push this repository to GitHub.
2. Open the repository on GitHub.
3. Go to **Settings**.
4. In the sidebar, open **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select:
   - **Branch:** `main`
   - **Folder:** `/(root)`
7. Save the settings.
8. Wait for GitHub Pages deployment to complete.

Expected published URL pattern:

`https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPOSITORY_NAME/`

## What to customize

Replace these placeholders before publishing:

- `YOUR_GITHUB_USERNAME`
- `YOUR_REPOSITORY_NAME`
- `YOUR_GITHUB_PROFILE_URL`
- `YOUR_LINKEDIN_URL`
- `YOUR_EMAIL`

## Confidentiality note

This repository is intentionally limited to a public summary. Full implementation code, raw datasets, internal model artifacts, and deployment infrastructure remain private due to confidentiality and intellectual property constraints.

## Optional next improvements

- Add approved screenshots (if public-safe assets become available).
- Configure a custom domain for portfolio branding.
- Add additional public case studies using the same static template.
