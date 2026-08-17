# MetaTaken Website

Static public website for MetaTaken, comprising one focused product landing page plus minimal search-discovery support files.

## Preview

Open `index.html` directly in a browser. No build step, external fonts, analytics, cookies or third-party JavaScript are required.

## Current release authority

The landing page is aligned to the accepted MetaTaken v0.3.0-rc1 release-candidate authority dated 17 August 2026.

- Release state: accepted RC1; prerelease observation / maintenance mode
- Canonical public asset name: `MetaTaken-v0.3.0-rc1-portable.zip`
- Canonical SHA-256: `793fd9c6169eb2422f530fb5d36ab8619969e37784bb673065b2cc0546f7693f`
- Packaged regression: 187 / 187 cases completed
- Decoded-pixel verification: 243 cleaning writes checked; 0 changes detected
- Independent-machine check: manual second-Windows-PC portable smoke test passed

The checksum and detailed release evidence belong on GitHub rather than the ordinary landing page.

## SEO and discovery

The site includes a deliberately small technical SEO layer without adding content bloat or third-party services.

- Canonical public URL: `https://metataken.com/`
- descriptive search title and meta description;
- Open Graph and Twitter/X social-preview metadata using the existing application screenshot;
- `WebSite` and conservative `SoftwareApplication` JSON-LD structured data;
- `robots.txt` allowing normal crawling and pointing to the sitemap;
- `sitemap.xml` containing the single canonical landing-page URL;
- square MetaTaken icon retained as the site favicon / touch icon.

The structured data does not invent ratings, reviews or claims that are not present on the public site. Detailed release evidence remains on GitHub.

## Public release links

The website is wired to the published MetaTaken v0.3.0-rc1 GitHub pre-release.

- Release page: `https://github.com/MGE-Apps/MetaTaken/releases/tag/v0.3.0-rc1`
- Direct Windows portable download: `https://github.com/MGE-Apps/MetaTaken/releases/download/v0.3.0-rc1/MetaTaken-v0.3.0-rc1-portable.zip`
- Public asset: `MetaTaken-v0.3.0-rc1-portable.zip`

The GitHub release page remains the public authority for release notes and checksum information.

Do not expose the internal release-admin pack, diagnostic JSON, runtime inventory or hardening evidence as ordinary website downloads.

## Public-site scope

The website stays deliberately small: brand, explain, reassure and download. Detailed privacy, licensing, third-party, source, release and engineering material belongs on GitHub rather than a standalone website legal/documentation section.

The landing page may still state product-relevant privacy facts directly, including local image processing, no account requirement and no application telemetry.

## Brand assets

The three web assets in `/assets` are copied from the current RC1 candidate source asset set:

- `metataken-wordmark-light.png`
- `metataken-wordmark-dark.png`
- `metataken-icon.png`

## Design decisions currently locked into this landing page

- primary brand line: “We have a particular set of tools. We find it. We remove it.”
- supporting hero headline: “See what's hiding in your images. Remove it. Verify the result.”
- no ABN in ordinary website presentation;
- no website licence navigation item;
- technical, licensing and release detail belongs on GitHub;
- public numeric regression counts are intentionally omitted from the landing page; detailed test evidence belongs on GitHub/release material unless a future public claim is backed by a substantially larger verified corpus;
- primary navigation is limited to How it works, GitHub and Download; direct email support is intentionally kept out of the header;
- footer navigation is limited to GitHub and Support;
- no Windows logo; text-only Windows references plus trademark footnote;
- system light/dark mode supported automatically;
- actual light/dark application screenshots in the hero, switched automatically with system theme;
- original images are never cleaned in place or overwritten; cleaning uses separate output copies;
- product-relevant privacy facts stay on the landing page; detailed privacy/legal/licensing material belongs on GitHub.
- image-support messaging is future-facing without naming or promising unapproved formats: more formats are added only when they can be supported reliably.
