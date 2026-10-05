# RCBIAN BLOOD — Proper Cloudflare Worker

This is the Worker version of the link page using Cloudflare Workers Static Assets.

Files:
- `src/index.js` — Worker entry point
- `public/index.html` — RCBIAN BLOOD page
- `public/meta-verified.svg` — uploaded Meta verification badge asset
- `public/googleda9ab5df763b9733.html` — Google Search Console verification file
- `wrangler.jsonc` — Workers Static Assets configuration

## Dashboard deployment
Workers & Pages → Create → Worker → upload/deploy this project using the
Cloudflare Workers deployment flow.

The Worker is configured to serve `public/` as static assets.

After deployment, attach:
`links.varadcreates.in`

Then verify:
`https://links.varadcreates.in/`
`https://links.varadcreates.in/googleda9ab5df763b9733.html`
