# Antigravity Kit 2 — Template

This is a GitHub template repository for a static frontend project that includes Antigravity Kit 2 assets via a local vendor folder. It's configured for deployment on Vercel and uses the MIT license.

Quick start

1. Clone the repo:

   git clone https://github.com/skyxxxnyc/antigravity-kit2-template.git
   cd antigravity-kit2-template

2. Fetch official Antigravity Kit 2 assets into `vendor/` (one-step):

   npm run setup

   This runs the official kit CLI (`npx @vudovn/ag-kit init`) into a temporary folder and copies the built `web` assets into `vendor/antigravity-kit-2/`.

3. Serve locally (optional):

   npm run start

   or open `index.html` in your browser.

Deploying to Vercel

- Import the repository into Vercel (https://vercel.com/new).
- For a static site, Vercel will detect `index.html`. No build step required. The included `vercel.json` is configured to serve `index.html` for all routes.

Notes

- The repository does not commit the Antigravity Kit 2 distribution files by default — running `npm run setup` pulls the official kit assets into `vendor/antigravity-kit-2/` for you. If you prefer the assets committed, replace the vendor files manually or run the setup and then commit `vendor/` to the repo.
- If the official kit CLI changes, check the kit's README: https://github.com/vudovn/antigravity-kit

License

This project is licensed under the MIT License. See LICENSE for details.