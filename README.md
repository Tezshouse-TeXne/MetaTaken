<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/metataken-wordmark-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/metataken-wordmark-light.png">
    <img alt="MetaTaken" src="assets/metataken-wordmark-light.png" width="520">
  </picture>
</p>

<p align="center"><strong>We have a particular set of tools. We find it. We remove it.</strong></p>
<p align="center"><strong>Inspect. Clean. Verify.</strong></p>

<p align="center">
  A private, local Windows utility for inspecting, removing and verifying metadata in image files.<br>
  <strong>No uploads. No account. No application telemetry.</strong>
</p>

<p align="center">
  <a href="https://github.com/Tezshouse-TeXne/MetaTaken/releases/tag/v0.3.0-rc2"><strong>View MetaTaken v0.3.0-rc2</strong></a>
  ·
  <a href="https://github.com/Tezshouse-TeXne/MetaTaken/releases/download/v0.3.0-rc2/MetaTaken-v0.3.0-rc2-portable.zip"><strong>Download Windows portable ZIP</strong></a>
  ·
  <a href="https://metataken.com/"><strong>metataken.com</strong></a>
</p>

---

## See what's hiding in your images. Remove it. Verify the result.

Images can carry much more than visible pixels. MetaTaken uses ExifTool and additional format-aware checks to surface metadata in understandable categories, clean what can be safely removed, and automatically inspect the result again.

The default workflow is simple:

**Drop image → Inspect → Clean → Verify**

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/metataken-app-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/metataken-app-light.png">
    <img alt="MetaTaken application" src="assets/metataken-app-light.png" width="900">
  </picture>
</p>

## What MetaTaken looks for

MetaTaken can inspect and, where safely supported, remove metadata such as:

- EXIF and camera/device information
- GPS and location data
- XMP and IPTC metadata
- author, account and software/generator information
- comments and descriptions
- timestamps
- embedded thumbnails and previews
- C2PA / Content Credentials / JUMBF provenance data
- other removable metadata identified by ExifTool and MetaTaken's format-aware checks

Raw technical metadata is also available through the Advanced view.

## Cleaning modes

### Privacy Clean

Targets personal and private metadata such as location, author/device information and timestamps while preserving data required for safe image handling where appropriate.

### Full Metadata Clean

Removes all safely removable metadata MetaTaken can identify, including supported AI provenance metadata such as C2PA / Content Credentials.

MetaTaken creates a cleaned copy by default rather than silently overwriting the original.

## Verification is part of the operation

MetaTaken does not treat a successful cleaning command as proof that the job is finished.

After cleaning, the output is inspected again and MetaTaken reports what was:

- detected
- removed
- retained
- unsupported
- uncertain
- not tested

Where practical, MetaTaken also compares decoded image content before and after cleaning. It reports **Pixel content unchanged** only when that check actually passes.

## Supported image formats

Current inspection and cleaning support:

- JPEG / JPG
- PNG
- WebP
- GIF
- HEIC / HEIF / HIF*

\* HEIC/HEIF/HIF pixel verification depends on compatible Windows HEIF/HEVC codec support.

Additional formats may be added only where they can be supported and verified reliably.

## Privacy by design

MetaTaken is deliberately local-first:

- image processing stays on your computer
- no account is required
- no cloud upload is required
- no application telemetry
- ExifTool is bundled locally

## SynthID

SynthID is pixel-level watermarking rather than conventional metadata.

MetaTaken does **not** attempt to remove SynthID. Unless a sufficiently reliable detector is available and actually used, MetaTaken reports:

**SynthID: Not tested / detection unavailable**

That status is not evidence that SynthID is absent.

## Current release — v0.3.0-rc2

MetaTaken v0.3.0-rc2 is an accepted release candidate for v0.3.0.

RC2 has passed retained regression testing, packaged Windows validation, parallel-processing comparison testing and the full 187-image reference corpus.

The portable build requires no installer: extract the ZIP and run `MetaTaken.exe`.

**Release page:**  
https://github.com/Tezshouse-TeXne/MetaTaken/releases/tag/v0.3.0-rc2

**Direct download:**  
https://github.com/Tezshouse-TeXne/MetaTaken/releases/download/v0.3.0-rc2/MetaTaken-v0.3.0-rc2-portable.zip

The release page is the public authority for current release notes, checksum information and known limitations.

## About this repository

This repository is MetaTaken's public GitHub home. It currently hosts the public website source and official release downloads.

The website is intentionally lightweight: static HTML/CSS, no analytics, no cookies, no external fonts and no third-party JavaScript. Open `index.html` directly to preview it locally.

## Built on trusted tooling

ExifTool is MetaTaken's primary metadata engine. Third-party components and required attribution are documented with the distributed application and project material.

## MetaTaken by Tezshouse TeXne

MetaTaken™ is developed and published by **Tezshouse TeXne**.

**Website:** https://metataken.com/  
**GitHub:** https://github.com/Tezshouse-TeXne/MetaTaken

Copyright © 2026 Tezshouse TeXne. All rights reserved.
