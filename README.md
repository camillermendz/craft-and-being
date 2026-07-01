# Craft & Being

This folder is the clean static website package for GitHub and Vercel.

## Files

- `index.html` is the homepage.
- `about/index.html` publishes at `/about/`.
- `services/index.html` publishes at `/services/`.
- `gatherings/index.html` publishes at `/gatherings/`.
- `assets/` contains local images, logos, and supporting files.

The old `.html` URLs are redirected to the clean versions through `vercel.json`.

## Publish With Vercel

1. Upload this repository to GitHub.
2. In Vercel, import the GitHub repository.
3. Choose `Other` as the framework preset.
4. Leave the build command blank.
5. Leave the output directory blank.
6. Deploy.

## Domain

After Vercel deploys, add these domains in Vercel:

- `craftandbeing.com`
- `www.craftandbeing.com`

Then update DNS in Squarespace using the records Vercel provides. Keep any email-related records such as MX, TXT, SPF, DKIM, or DMARC.
