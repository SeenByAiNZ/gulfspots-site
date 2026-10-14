# gulfspots.co.nz

The public website for Gulf Spots (Northbeam Limited), served by GitHub Pages on the custom domain in `CNAME`.

- Source of truth: `site/index.html` in the private repo SeenByAiNZ/fishing-app (built section by section as a live artifact). This repo is the published copy; Claude copies it here after each change.
- Pages: `index.html`, `terms.html`, `privacy.html`, each self-contained (styles and script inline; fonts from Google Fonts). The beta form posts to the `beta_signup` function on Supabase with the public key.
- No real spot positions ever appear on the site (the hero reading is a labelled example).
- Deploy: push to `main`; GitHub Pages serves the root of `main`.
