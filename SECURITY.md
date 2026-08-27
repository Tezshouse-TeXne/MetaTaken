# Security Policy

MetaTaken is a local-first Windows utility that inspects, cleans and verifies image metadata. Security and privacy reports are taken seriously, especially where a flaw could affect user data, file integrity, code execution, dependency safety or the accuracy of a security-relevant verification result.

## Reporting a vulnerability

**Please do not open a public GitHub issue for a suspected security vulnerability.**

Email **support@metataken.com** with the subject:

`MetaTaken security report`

Please include, where practical:

- the MetaTaken version you tested;
- your Windows version;
- a concise description of the issue and its potential impact;
- reproducible steps;
- relevant diagnostic output or error text; and
- a minimal test file only if it is safe and necessary to share.

MetaTaken is a privacy-focused utility, so please do **not** send private or sensitive images unless they are genuinely required to reproduce the issue and you are comfortable sharing them. A synthetic or redacted reproducer is preferred.

We will review the report, confirm whether it affects MetaTaken, and coordinate a fix and disclosure where appropriate.

## Supported versions

| Version | Security support |
| --- | --- |
| Current public MetaTaken release | Supported |
| Superseded prerelease or development builds | Not actively supported |

For the current public build, see the [MetaTaken releases page](https://github.com/Tezshouse-TeXne/MetaTaken/releases).

## What belongs in a security report

Examples include:

- arbitrary code execution or command injection;
- unsafe handling of crafted image files;
- unintended access to, modification of, or deletion of user files;
- packaging or bundled-dependency issues that create a security exposure in MetaTaken;
- a vulnerability that could cause MetaTaken to make a materially false security/privacy claim; or
- other behaviour that could compromise confidentiality, integrity or availability.

Ordinary bugs, metadata-cleaning limitations, unsupported formats and feature requests can be reported through the public issue tracker unless they create a security impact.

## Third-party components

MetaTaken uses third-party components, including ExifTool. If a vulnerability exists entirely in an upstream project, reporting it to that project may also be appropriate. If the issue affects the way MetaTaken bundles, invokes or exposes that component, please report it to us as well.

## Responsible disclosure

Please allow reasonable time for investigation and remediation before publishing technical details that could put users at risk.

Thank you for helping keep MetaTaken safe.
