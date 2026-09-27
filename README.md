# Orris Data/AI — Free Static Website

## Files
- `index.html` — complete responsive website.
- `demo-video.mp4` — add your own demo video with this exact filename.
- `README.md` — deployment instructions.

## Before publishing
Open `index.html` and change:
`const CONTACT_EMAIL = "YOUR_EMAIL@example.com";`

Replace it with the email address that should receive inquiries.

## Free deployment with GitHub Pages
1. Create a GitHub account.
2. Create a public repository, e.g. `orris-data-ai`.
3. Upload `index.html`.
4. Upload your `demo-video.mp4` when ready.
5. Repository → Settings → Pages.
6. Under Build and deployment, select "Deploy from a branch".
7. Select `main` and `/root`.
8. Save.
9. GitHub will publish the site at `https://YOUR-USERNAME.github.io/orris-data-ai/`.

## Cloudflare Pages
1. Create a Cloudflare account.
2. Create a Pages project and connect the GitHub repository.
3. For this static HTML site, no framework is required.
4. Deploy.
5. Cloudflare will provide a `*.pages.dev` address.
6. You can connect a custom domain later.

## Images
The initial design uses Unsplash image URLs for visual placeholders. For production, replace them with your own licensed images, screenshots of your Databricks demo, or company-specific visuals.

## Contact form
The current form uses `mailto:` so it works without a backend, but it depends on the visitor having an email application configured.

For a production lead-generation form, connect the form to a form provider or a small serverless endpoint. Do not put private API keys in browser JavaScript.

## Positioning
The site intentionally focuses on:
- automated reporting
- data integration
- executive dashboards
- operational analytics
- Databricks Apps
- Genie / natural-language analytics
- practical AI/automation
- construction/project analytics as a flagship use case

The copy avoids claiming guaranteed ROI or guaranteed AI accuracy.
