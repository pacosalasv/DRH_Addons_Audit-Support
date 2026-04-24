<div align="center">
  <img width="680" alt="Add-ons Audit banner" src="https://github.com/user-attachments/assets/f8303114-2a98-44df-bef1-b32736459f28" />
</div>

<div align="center">

# Add-ons Audit | Support Hub

Public support, documentation, feedback, and pre-release validation hub for **Add-ons Audit**.

<table>
  <tr>
    <td align="center"><strong>Status</strong><br>🟣 <strong>In Development</strong></td>
    <td align="center"><strong>Version</strong><br><code>1.0.0</code></td>
    <td align="center"><strong>Blender</strong><br><code>4.2+</code></td>
    <td align="center"><strong>Platforms</strong><br>Windows, macOS, Linux</td>
  </tr>
</table>

</div>

---

<div align="center">

**Add-ons Audit** is a Blender utility designed to help users inspect, compare, document, and troubleshoot their Blender add-on installations.

This repository is used as the central public hub for support, documentation, issue tracking, compatibility feedback, and community validation before marketplace release.

</div>

---

## Quick links

- [Ask a question in Discussions](https://github.com/pacosalasv/DRH_Addons_Audit-Support/discussions)
- [Open a new issue](https://github.com/pacosalasv/DRH_Addons_Audit-Support/issues/new/choose)
- [Report a bug](https://github.com/pacosalasv/DRH_Addons_Audit-Support/issues/new?template=bug_report.yml)
- [Request a feature](https://github.com/pacosalasv/DRH_Addons_Audit-Support/issues/new?template=feature_request.yml)
- [Report a compatibility issue](https://github.com/pacosalasv/DRH_Addons_Audit-Support/issues/new?template=compatibility_issue.yml)

---

<details>
  <summary><strong>📚 Table of Contents</strong></summary>

## Menu

- [Overview](#overview)
- [What Add-ons Audit does](#what-add-ons-audit-does)
- [Key features](#key-features)
- [Full feature list](#full-feature-list)
- [Who is it for?](#who-is-it-for)
- [Current status](#current-status)
- [Feedback wanted before release](#feedback-wanted-before-release)
- [Supported scope](#supported-scope)
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

**Add-ons Audit** helps Blender users review and document their add-on environment.

It is intended for users who work with many add-ons, need to compare Blender setups, troubleshoot compatibility issues, keep records of installed tools, or prepare clean add-on profiles for different workflows.

The goal is to make add-on management more transparent, organized, and easier to communicate when reporting issues or migrating setups.

---

## What Add-ons Audit does

Add-ons Audit scans your Blender add-on environment and helps you create structured reports, snapshots, comparisons, and setup references.

It is not only an add-on list viewer. It is designed as a diagnostic and documentation tool for Blender add-on setups.

Use it to:

- Review installed add-ons
- Compare setup snapshots
- Detect changes between configurations
- Export readable reports
- Document your Blender add-on environment
- Prepare setup profiles
- Troubleshoot compatibility or installation issues

---

## Key features

- Scan Blender add-on installations
- Read available add-on manifests and metadata
- Create setup snapshots
- Compare snapshots between different moments or configurations
- Export reports for documentation or support
- Import and export setup profiles
- Help identify add-on changes, missing entries, or setup differences
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

Add-ons Audit is designed for:

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

**Status:** In Development  
**Current version:** 1.0.0  
**Minimum Blender version:** 4.2.0  
**Platforms:** Windows, macOS, Linux

This add-on is preparing for public release. Compatibility feedback, usability comments, and workflow suggestions are welcome.

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

You can help by opening a Discussion or Issue with your comments.

Useful feedback examples:

- “I would use this to compare two Blender installs.”
- “I need CSV export in addition to HTML/JSON.”
- “This should detect disabled add-ons separately.”
- “The report should include Blender version and OS.”
- “This would be useful, but only if it supports portable Blender installs.”

---

## Supported scope

- **Add-on:** Add-ons Audit
- **Status:** In Development
- **Current version:** 1.0.0
- **Minimum Blender version:** 4.2.0
- **Platforms:** Windows, macOS, Linux

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
