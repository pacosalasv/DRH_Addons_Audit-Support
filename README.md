<div align="center">
  <img width="680" alt="DRH - Add-ons Audit banner" src="https://github.com/user-attachments/assets/f8303114-2a98-44df-bef1-b32736459f28" />
</div>

<br>

<div align="center">

# DRH - Add-ons Audit

### Public Support Hub · Documentation · Feedback · Pre-release Validation

**A Blender utility for inspecting, documenting, comparing, and troubleshooting add-on setups.**

![Status](https://img.shields.io/badge/status-production%20ready%2C%20pending%20approval-F59E0B?style=for-the-badge)
![Version](https://img.shields.io/badge/version-1.0.0-00B7FF?style=for-the-badge)
![Blender](https://img.shields.io/badge/blender-4.2%2B-0B1F4D?style=for-the-badge)
![Platforms](https://img.shields.io/badge/platforms-Windows%20%7C%20macOS%20%7C%20Linux-EAF2FF?style=for-the-badge&labelColor=0B1F4D&color=EAF2FF)

<br>

**Part of the DRH Add-ons ecosystem — Blender tools, updates, and releases.**

[![DRH Add-ons Hub](https://img.shields.io/badge/DRH%20Add--ons%20Hub-Visit%20Hub-1E5BFF?style=for-the-badge&labelColor=0B1F4D)](https://github.com/pacosalasv/DRH_Addons_Hub)

</div>

<!--
<div align="center">

[![Superhive](https://img.shields.io/badge/Superhive-Coming%20Soon-1E5BFF?style=for-the-badge)](#)
[![Gumroad](https://img.shields.io/badge/Gumroad-Coming%20Soon-00B7FF?style=for-the-badge)](#)
[![BlenderKit](https://img.shields.io/badge/BlenderKit-Coming%20Soon-0B1F4D?style=for-the-badge)](#)

</div>
-->

---

<div align="center">

**DRH - Add-ons Audit** helps Blender users understand what is installed, what changed, and how to document their add-on environment more clearly.

This repository is the central public hub for support, documentation, issue tracking, compatibility feedback, and community validation before marketplace release.

</div>

---

<details>
  <summary><strong>📚 Table of Contents</strong></summary>

## Menu

- [Overview](#overview)
- [Media preview](#media-preview)
- [What DRH - Add-ons Audit does](#what-add-ons-audit-does)
- [Key features](#key-features)
- [Full feature list](#full-feature-list)
- [Who is it for?](#who-is-it-for)
- [Current status](#current-status)
- [Feedback wanted before release](#feedback-wanted-before-release)
- [Quick links](#quick-links)
- [Before you post](#before-you-post)
- [Where to post](#where-to-post)
- [Support policy](#support-policy)
- [Technical notes](#technical-notes)
- [Availability](#availability)
- [Documentation](#documentation)
- [License](#license)

</details>

---

## Overview

**DRH - Add-ons Audit** is a Blender workflow utility designed to help users inspect, compare, document, and troubleshoot their Blender add-on installations.

It is intended for users who work with multiple add-ons, maintain different Blender setups, test compatibility, migrate environments, or need clearer reports when diagnosing issues.

Instead of relying on memory or manual notes, DRH - Add-ons Audit helps turn your Blender add-on setup into structured, readable information.

## Media preview

<!--

---


### Demo video

Replace `YOUTUBE_VIDEO_ID` with your real YouTube video ID.

Example:
https://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID

<div align="center">
  <a href="https://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID" target="_blank">
    <img width="720" alt="DRH - Add-ons Audit demo video" src="https://img.youtube.com/vi/YOUTUBE_VIDEO_ID/maxresdefault.jpg" />
  </a>
  <br>
  <sub>Click the image to watch the demo on YouTube.</sub>
</div>
-->

<!--
### Quick demo GIF

Recommended size: 1280x720 or 960x540.

<div align="center">
  <img width="720" alt="DRH - Add-ons Audit quick demo" src="docs/media/addons-audit-demo.gif" />
</div>
-->

### Screenshots

<div align="center">

| Report Preview | Add-ons Snapshot |
|---|---|
| <img width="420" alt="DRH - Report Preview" src="docs/media/ScreenShot_01.png" /> | <img width="420" alt="DRH - Add-ons Snapshot" src="docs/media/ScreenShot_02.png" /> |

</div>

<!--
### Visual preview

Use this section if you want one large image instead of a gallery.

<div align="center">
  <img width="760" alt="DRH - Add-ons Audit preview" src="docs/media/addons-audit-preview.png" />
</div>
-->

<!--
Temporary placeholder while media is not available.

<div align="center">

Media preview coming soon.

</div>
-->

---

## What DRH - Add-ons Audit does

DRH - Add-ons Audit scans your Blender add-on environment and helps you create structured reports, snapshots, comparisons, and setup references.

It is not only an add-on list viewer. It is designed as a diagnostic and documentation tool for Blender add-on setups.

Use it to:

- Review installed add-ons
- Compare setup snapshots
- Detect changes between configurations
- Export readable reports
- Document your Blender add-on environment
- Prepare setup profiles
- Troubleshoot compatibility or installation issues
- Share clearer setup information when asking for support

---

## Key features

- Scan Blender add-on installations
- Read available add-on manifests and metadata
- Create setup snapshots
- Compare snapshots between different moments or configurations
- Export reports for documentation or support
- Import and export setup profiles
- Identify setup changes, missing entries, or configuration differences
- Provide a clearer view of complex Blender add-on environments

---

<details>
  <summary><strong>🧩 Full feature list</strong></summary>

## Full feature list

### Add-on scanning

- Scan Blender add-on installation folders
- Detect available add-ons
- Read add-on metadata when available
- Identify add-on names, versions, and related information
- Review the current add-on environment from inside Blender

### Manifest and metadata reading

- Read available manifest files
- Extract structured add-on information
- Help document add-on identity, version, and setup data
- Support cleaner troubleshooting by exposing relevant add-on details

### Snapshot system

- Create snapshots of the current add-on setup
- Save setup states for later review
- Use snapshots as references before or after changes
- Keep records of different Blender environments or configurations

### Snapshot comparison

- Compare two setup snapshots
- Identify changes between add-on configurations
- Detect added, removed, or modified add-on entries
- Use comparisons to troubleshoot unexpected setup differences

### Report export

- Export readable reports
- Create support-friendly documentation
- Share setup information when reporting issues
- Keep external records of installed add-ons and configuration states

### Setup profiles

- Export setup profiles
- Import setup profiles
- Prepare reusable add-on environment references
- Help organize different workflows or Blender configurations

### Troubleshooting support

- Help users explain their Blender add-on environment more clearly
- Provide structured information for bug reports
- Reduce guesswork when diagnosing compatibility problems
- Support reproducible reports by documenting setup details

### File and package utilities

- Create installable packages when applicable
- Export setup-related files
- Import setup-related data
- Help organize add-on environment information into portable files

### Transparency

- Source-based add-on
- No obfuscation
- No binary-only content
- No external services required
- Local file access only for add-on scanning, reports, snapshots, profiles, and package-related operations

</details>

---

## Who is it for?

DRH - Add-ons Audit is designed for:

- Blender users with many installed add-ons
- Artists who work across multiple Blender setups
- Technical artists
- Pipeline and workflow-focused users
- Add-on developers
- Support teams and testers
- Users who frequently migrate or reinstall Blender
- Users who need clearer reports when troubleshooting problems

---

## Current status

| Item | Details |
|---|---|
| **Status** | 🟠 Production Ready, Pending Approval |
| **Current version** | 1.0.0 |
| **Minimum Blender version** | 4.2.0 |
| **Platforms** | Windows, macOS, Linux |
| **Release type** | Preparing for public marketplace release |
| **Support repository** | [DRH - Add-ons Audit Support](https://github.com/pacosalasv/DRH_Addons_Audit-Support) |

This add-on is production ready and currently pending marketplace approval. Compatibility feedback, usability comments, and workflow suggestions are welcome before public release.

---

## Feedback wanted before release

This repository is open for public feedback before marketplace release.

Feedback is especially welcome on:

- Feature usefulness
- Missing workflow options
- Compatibility concerns
- Report/export formats
- Snapshot comparison behavior
- Installation experience
- Documentation clarity
- Expected pricing
- Marketplace expectations

Useful feedback examples:

> “I would use this to compare two Blender installs.”

> “I need CSV export in addition to HTML/JSON.”

> “This should detect disabled add-ons separately.”

> “The report should include Blender version and OS.”

> “This would be useful, but only if it supports portable Blender installs.”

---

## Quick links

- [Support repository](https://github.com/pacosalasv/DRH_Addons_Audit-Support)
- [Ask a question in Discussions](https://github.com/pacosalasv/DRH_Addons_Audit-Support/discussions)
- [Open a new issue](https://github.com/pacosalasv/DRH_Addons_Audit-Support/issues/new/choose)
- [Report a bug](https://github.com/pacosalasv/DRH_Addons_Audit-Support/issues/new?template=bug_report.yml)
- [Request a feature](https://github.com/pacosalasv/DRH_Addons_Audit-Support/issues/new?template=feature_request.yml)
- [Report a compatibility issue](https://github.com/pacosalasv/DRH_Addons_Audit-Support/issues/new?template=compatibility_issue.yml)

---

## Before you post

Please include as much of the following information as possible:

- Add-on version
- Blender version
- Operating system
- Installation method
- Clear steps to reproduce
- Expected result
- Actual result
- Error message, screenshot, or console output when available

For compatibility issues, please also include:

- Blender build type, if known
- Portable or installed Blender version
- Add-on installation location
- Whether the issue happens with a clean Blender configuration

---

## Use Discussions for

- Questions
- How-to topics
- Installation help
- Compatibility checks
- FAQ
- Suggestions
- Pre-release feedback
- Pricing feedback
- Workflow ideas

---

## Use Issues for

- Confirmed bugs
- Reproducible compatibility problems
- Feature requests
- Regressions
- Marketplace or listing-related problems
- Documentation errors

---

## Where to post

Open a **Discussion** for:

- General questions
- Setup help
- Workflow advice
- Suggestions
- Early feedback

Open an **Issue** for:

- Confirmed bugs
- Reproducible compatibility problems
- Regressions
- Feature requests
- Documentation problems

---

## Support policy

This repository is a public support hub.

Do not post:

- Private account details
- License keys
- Payment information
- Confidential production files
- Private client files
- Sensitive system information

If a private file is required to reproduce an issue, please describe the problem first and wait for further instructions.

---

## Technical notes

This add-on is source based, with:

- No obfuscation
- No binary-only content
- No external services

File access is used to:

- Scan installations
- Read manifests
- Compare snapshots
- Export reports
- Create installable packages
- Import or export setup profiles

The add-on is intended to work locally inside Blender.

---

## Availability

This add-on may be available through multiple marketplaces and storefronts after release.

This GitHub repository remains the central public location for:

- Support
- Documentation
- Issue tracking
- Compatibility reports
- Public feedback
- Release notes

---

## Documentation

- [User Manual](docs/manual/user-manual.pdf)
- [Changelog](CHANGELOG.md)

---

## License

This repository is distributed under **GPL-3.0-or-later**.

---

<div align="center">

### DRH Add-ons

**Blender tools, updates, and releases.**

Built for clean workflows, practical utilities, and production-friendly Blender setups.

[![DRH Add-ons Hub](https://img.shields.io/badge/DRH%20Add--ons%20Hub-Visit%20Hub-1E5BFF?style=for-the-badge&labelColor=0B1F4D)](https://github.com/pacosalasv/DRH_Addons_Hub)

</div>
