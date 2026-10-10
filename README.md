# standright-site

Landing page and privacy policy for the StandRight Android app. Served via
GitHub Pages: https://cipshadow.github.io/standright-site/ (privacy policy at
/privacy-policy).

Screenshots in `assets/screens/` are 540×960 WebP copies of the framed Play
store screenshots in the app repo (`docs/store/screenshots/`). Feature copy
mirrors `docs/store/listing.md` there; update both together.

App source lives in a separate, private repository.

Every push to `main` triggers the "pages build and deployment" run under the
Actions tab. If the live site looks older than `main`, check that run first: on
2026-10-05 it was cancelled before it started, and the site kept serving the
previous build until the next push.
