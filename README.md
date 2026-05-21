# Velora Website

This directory contains a static website for the public pages that support the app:

- `/`
- `/privacy/`
- `/terms/`
- `/support/`
- `/delete-account/`

## Deploy To Netlify

If you connect this repo directly to Netlify:

- Base directory: leave empty
- Publish directory: `website`
- Build command: leave empty

The repo root also includes a `netlify.toml` that points Netlify to this folder.

## Recommended DNS Targets

After the Netlify site is created and linked to `velorainsights.com`:

- `www.velorainsights.com` should point to Netlify per Netlify's custom domain instructions
- the root domain `velorainsights.com` should also be moved from GoDaddy Website Builder to Netlify

## Editing

This site is plain HTML and CSS on purpose:

- no framework lock-in
- easy to split into its own repo later
- easy for AI agents to edit directly
