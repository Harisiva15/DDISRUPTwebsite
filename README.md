# DDisrupt Software — Website

Marketing site for **DDisrupt Software Pvt Ltd**. A single, self-contained static page
(`index.html`) — all CSS and JS are inline, so there is no build step and no dependencies.

## Structure
- `index.html` — the entire site (hero, capabilities, ServiceNow, approach, outcomes, industries, careers, contact, footer)
- `robots.txt` — allows all crawlers
- `.nojekyll` — tells GitHub Pages to serve files as-is (no Jekyll processing)

## Run locally
Open `index.html` in a browser, or serve the folder with any static server.

## Deploy (GitHub Pages)
Pushed to a GitHub repo with Pages enabled on the default branch. Any change to
`index.html` on that branch redeploys automatically within a minute.

## Before / after going live
- Confirm contact emails (`hello@`, `sales@`, `careers@ddisrupt.com`) and the LinkedIn URL
- Wire the contact form and job "Apply" buttons to a real endpoint / ATS (currently `mailto:`)
- Replace placeholder job details and outcome figures with real data
- (Optional) add a social share image and set `og:url` / a canonical link once the domain is final
