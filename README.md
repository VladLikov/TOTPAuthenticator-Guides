# TOTP Authenticator Instructions

This directory is the GitHub-hosted source for server-driven instruction guides.

Expected raw manifest URL:

`https://raw.githubusercontent.com/VladLikov/TOTPAuthenticator-Guides/main/instructions-manifest.json`

The app tries this remote manifest first and falls back to bundled resources when the network, repository, or file is unavailable.

Guide list icons are published at `GuideImages/<imageName>.png`, where `imageName` comes from the manifest. The app caches downloaded icons on disk and falls back to its bundled `ServiceIcons` copy when offline.

Localized markdown is published at `Guides/<locale>/<markdownFile>`. The app loads GitHub first, then its disk cache, then the bundled `Guides` fallback.

Keep guide files localized by country/locale and avoid official-looking logos, copied trademarked visual identity, or affiliation claims.
