# Lemoness release pages

Host these two self-contained static files in the same public directory:

- `privacy.html` — Japanese Privacy Policy, effective October 13, 2026.
- `support.html` — Japanese support and local-data information.

The production support email is `lemoness.support@gmail.com`. Both HTML files
display this address as a clickable `mailto:lemoness.support@gmail.com` link.

Expected URL paths:

- `/privacy.html`
- `/support.html`

Both final URLs must be publicly accessible over HTTPS without authentication.
Keep the files together so their relative links continue to work. Each file can
also be opened locally without a server. There are no scripts, external fonts,
cookies, analytics, tracking, remote resources, or backend forms.

A simple static-file host is sufficient; no build step is needed. Upload only the
two HTML files. This README is preparation guidance and need not be published.
No deployment has been performed.
