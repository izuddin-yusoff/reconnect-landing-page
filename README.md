# reconnect-landing-page

The landing page at https://reconnect.simoliy.com/ (the link in @spotseason's Instagram bio).

- `public/` holds the site: `index.html`, the Disclosure, Privacy and Terms pages, and `images/`.
- `wrangler.jsonc` tells Cloudflare to serve `public/` from the Worker **damp-band-fcdf**.
- Cloudflare builds and deploys automatically on every push to `main` (Workers Builds).
- The buttons use ClickBank hoplinks tagged `traffic_source=instagram`. Check them against the live page before changing anything.
