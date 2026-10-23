<div align="center">

<img width="860" alt="DRH Add-on Manager and Audit" src="docs/media/Logo.png" />

# DRH - Add-on Manager & Audit

**Forty add-ons. Three hotkey clashes. Two builds of the same tool. Find them before a render does.**

![Status](https://img.shields.io/badge/Status-Released-22C55E?style=for-the-badge) ![Version](https://img.shields.io/badge/Version-1.0.0-00B7FF?style=for-the-badge) ![Blender](https://img.shields.io/badge/Blender-4.2%2B-0B1F4D?style=for-the-badge)

[![Download](https://img.shields.io/badge/Download-Free%20on%20BlendKit-0B1F4D?style=for-the-badge)](https://www.blendkit.com/asset-gallery-detail/89fe5b10-df59-4940-b66e-8e8114e9fd53/) [![Issues](https://img.shields.io/badge/Support-Issues-1E5BFF?style=for-the-badge)](https://github.com/pacosalasv/DRH_Addons_Audit-Support/issues) [![Hub](https://img.shields.io/badge/DRH-Hub-334155?style=for-the-badge)](https://github.com/pacosalasv/DRH_Addons_Hub)

</div>

## The wall

Something in Blender started behaving oddly. You installed three add-ons last week. One of them may be an old copy sitting next to the new one, and Blender's own add-on list won't tell you which. Debugging by disabling tools one at a time takes an afternoon.

This add-on writes down what's installed, compares it against metadata and manifests, and points at the conflicts.

<img src="docs/media/ScreenShot_01.png" alt="Add-on inventory and audit panel" width="100%" />

## What it looks at

Local add-on and extension inventory scanning, including the folders Blender doesn't show you by default. Manifest and add-on metadata review. Compatibility checks against the Blender version. Duplicate detection. Version conflicts between installs. Shadow states, where a second copy is loaded from a path that shouldn't win but does.

It also lists operator and hotkey review candidates, which is usually where the "why did Ctrl+Shift+S stop working" question gets answered.

## Snapshots, so changes are visible

Save a snapshot before you install something. Compare after. The diff tells you what appeared and what changed, which beats trying to remember whether a panel was always there. Reports export, so you can attach one to a support thread instead of describing your setup in prose.

## Who it's for

Anyone running more than twenty add-ons. People who support other Blender users and need to see their setup. Pipeline leads keeping machines consistent across a team.

## Get it

Free on BlendKit, Blender 4.2 or newer.

[![Download on BlendKit](https://img.shields.io/badge/Get%20Add--on%20Manager-BlendKit-1597E5?style=for-the-badge&logo=blender)](https://www.blendkit.com/asset-gallery-detail/89fe5b10-df59-4940-b66e-8e8114e9fd53/)

Bugs and requests: [open an issue](https://github.com/pacosalasv/DRH_Addons_Audit-Support/issues)

<div align="center">
  <a href="https://ko-fi.com/pacosalasv">
    <img width="560" alt="Support on Ko-fi" src="docs/media/SupportMe.png" />
  </a>
</div>
