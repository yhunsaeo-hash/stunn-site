# stunn.app

Public pages for Stunn, a vintage camera app for iPhone.

Deliberately a separate repository from the app itself. The app repo is private and
stays private; it holds the rendering code and the measured camera profiles, which
are the actual product.

- `index.html` and `support.html` are the same page. Apple wants a Support URL and
  people typing the bare domain want something useful, and that is the same thing.
- `privacy.html` is the Privacy Policy URL on the App Store listing.
- `terms.html` is linked from the app's own Settings screen.

No build step, no dependencies, no external requests. Plain HTML with inline CSS.

House rule: **no em dashes.** They read as machine written.
