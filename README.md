<div align="center">
  <img width="680" alt="DRH - Asset Pipeline Studio banner" src="docs/media/Logo.png" />
</div>

<br>

<div align="center">

# DRH - Asset Pipeline Studio

### Support · Documentation · Feedback · Development On-Hold

Import, export, auto-fix, validate, and batch-deliver multi-format 3D assets in Blender.

![Status](https://img.shields.io/badge/status-In%20Development%20%5BOn-Hold%5D-7C3AED?style=for-the-badge)
![Version](https://img.shields.io/badge/version-1.0.0-00B7FF?style=for-the-badge)
![Blender](https://img.shields.io/badge/blender-4.2%2B-0B1F4D?style=for-the-badge)
![Platforms](https://img.shields.io/badge/platforms-Windows%20%7C%20macOS%20%7C%20Linux-EAF2FF?style=for-the-badge&labelColor=0B1F4D&color=EAF2FF)

<br>

DRH Blender Tools: support, documentation, and release information.

[![DRH Add-ons Hub](https://img.shields.io/badge/DRH%20Add--ons%20Hub-Visit%20Hub-1E5BFF?style=for-the-badge&labelColor=0B1F4D)](https://github.com/pacosalasv/DRH_Addons_Hub)

</div>

---

<div align="center">

DRH - Asset Pipeline Studio helps Blender users import, export, validate, inspect, report, and batch-process 3D assets across supported file formats and production workflows.

This repository tracks documentation, support, compatibility reports, and development notes while active development is on hold.

</div>

---

## Overview

DRH - Asset Pipeline Studio is a Blender import/export and pipeline utility designed to help users move, validate, inspect, and prepare assets across many production formats.

It is intended for technical artists, asset creators, game artists, environment artists, marketplace creators, CAD/ArchViz users, BlendKit creators, pipeline-focused users, and small teams that need cleaner asset handoff, repeatable export setup, local file scanning, batch-oriented exchange, and format-aware validation.

Instead of manually managing transfers across folders, formats, naming conventions, scene cleanup steps, validation checks, and delivery requirements, DRH - Asset Pipeline Studio centralizes the process inside Blender with dedicated import/export modes, pipeline presets, runtime-aware format handling, and local reporting tools.

## Media preview

<!--
<div align="center">
  <img width="920" alt="DRH - Asset Pipeline Studio feature preview" src="docs/media/Featured_Image.png" />
</div>
-->

### Screenshots

<div align="center">

| Export Formats and Presets | Export Sanity Checker and Reports |
|---|---|
| <img height="420" alt="DRH - Export Formats and Presets" src="docs/media/ScreenShot_01.png" /> | <img height="420" alt="DRH - Export Sanity Checker and Reports" src="docs/media/ScreenShot_02.png" /> |

</div>

<details>

  <summary><strong>More Screenshots...</strong></summary>

<div align="center">

| Import Formats and File Queue | Export QA Report |
|---|---|
| <img height="420" alt="Import Formats and File Queue" src="docs/media/ScreenShot_03.png" /> | <img height="420" alt="Export QA Report" src="docs/media/ScreenShot_04.png" /> |

</div>

</details>

---

## What DRH - Asset Pipeline Studio does

DRH - Asset Pipeline Studio helps you prepare, validate, import, export, inspect, report, and batch-process asset data across supported formats inside Blender.

It is not only a simple import/export shortcut. It is designed as a workflow helper for format-based asset pipelines, asset handoff, file preparation, local organization, validation steps, inspection, previews, and repeatable production-oriented transfer processes.

Use it to:

| Details |
|---|
| Import assets using supported file formats |
| Export assets using supported file formats |
| Prepare assets for cross-format workflows |
| Validate assets before handoff, packaging, or marketplace delivery |
| Inspect scene, object, material, texture, and file-related data |
| Build local sanity checker reports for QA review |
| Batch-export enabled formats from one workflow |
| Scan source directories and build import queues |
| Filter supported files and optionally include subfolders |
| Route imported files into current, scene, per-file, or custom collections |
| Use pipeline presets for common delivery workflows |
| Reduce repetitive manual import/export preparation |
| Support more consistent asset transfer between tools or environments |
| Improve pipeline clarity for asset creators and technical users |

---

## Supported formats

DRH - Asset Pipeline Studio is built around format-based asset pipeline workflows.

Format availability may depend on Blender version, enabled Blender operators, packaged dependencies, Python ABI, operating system, and format-specific runtime requirements.

---

### Export-capable formats

#### Core 3D formats

![FBX](https://img.shields.io/badge/FBX-.fbx-1E5BFF?style=for-the-badge&labelColor=0B1F4D)
![OBJ](https://img.shields.io/badge/OBJ-.obj-1E5BFF?style=for-the-badge&labelColor=0B1F4D)
![glTF / GLB](https://img.shields.io/badge/glTF%20%2F%20GLB-.gltf%20%7C%20.glb-1E5BFF?style=for-the-badge&labelColor=0B1F4D)
![USD / USDZ](https://img.shields.io/badge/USD%20%2F%20USDZ-.usd%20%7C%20.usda%20%7C%20.usdc%20%7C%20.usdz-1E5BFF?style=for-the-badge&labelColor=0B1F4D)
![STL](https://img.shields.io/badge/STL-.stl-1E5BFF?style=for-the-badge&labelColor=0B1F4D)
![PLY](https://img.shields.io/badge/PLY-.ply-1E5BFF?style=for-the-badge&labelColor=0B1F4D)

#### Scene, animation, and exchange formats

![Collada](https://img.shields.io/badge/Collada-.dae-00B7FF?style=for-the-badge&labelColor=0B1F4D)
![Alembic](https://img.shields.io/badge/Alembic-.abc-00B7FF?style=for-the-badge&labelColor=0B1F4D)
![BVH](https://img.shields.io/badge/BVH-.bvh-00B7FF?style=for-the-badge&labelColor=0B1F4D)
![X3D / WRL](https://img.shields.io/badge/X3D%20%2F%20WRL-.x3d%20%7C%20.wrl-00B7FF?style=for-the-badge&labelColor=0B1F4D)

#### CAD, vector, 3D print, and data formats

![AutoCAD DXF](https://img.shields.io/badge/AutoCAD%20DXF-.dxf-7C3AED?style=for-the-badge&labelColor=0B1F4D)
![3MF](https://img.shields.io/badge/3MF-.3mf-7C3AED?style=for-the-badge&labelColor=0B1F4D)
![SVG](https://img.shields.io/badge/SVG-.svg-7C3AED?style=for-the-badge&labelColor=0B1F4D)
![OFF](https://img.shields.io/badge/OFF-.off-7C3AED?style=for-the-badge&labelColor=0B1F4D)
![XYZ](https://img.shields.io/badge/XYZ-.xyz-7C3AED?style=for-the-badge&labelColor=0B1F4D)

---

### Import-capable formats

#### Core 3D and Blender formats

![FBX](https://img.shields.io/badge/FBX-.fbx-2563EB?style=for-the-badge&labelColor=0B1F4D)
![Blender Library](https://img.shields.io/badge/Blender%20Library-.blend-2563EB?style=for-the-badge&labelColor=0B1F4D)
![OBJ](https://img.shields.io/badge/OBJ-.obj-2563EB?style=for-the-badge&labelColor=0B1F4D)
![glTF / GLB](https://img.shields.io/badge/glTF%20%2F%20GLB-.gltf%20%7C%20.glb-2563EB?style=for-the-badge&labelColor=0B1F4D)
![USD / USDZ](https://img.shields.io/badge/USD%20%2F%20USDZ-.usd%20%7C%20.usda%20%7C%20.usdc%20%7C%20.usdz-2563EB?style=for-the-badge&labelColor=0B1F4D)
![STL](https://img.shields.io/badge/STL-.stl-2563EB?style=for-the-badge&labelColor=0B1F4D)
![PLY](https://img.shields.io/badge/PLY-.ply-2563EB?style=for-the-badge&labelColor=0B1F4D)

#### Scene, animation, and exchange formats

![Collada](https://img.shields.io/badge/Collada-.dae-0891B2?style=for-the-badge&labelColor=0B1F4D)
![Alembic](https://img.shields.io/badge/Alembic-.abc-0891B2?style=for-the-badge&labelColor=0B1F4D)
![BVH](https://img.shields.io/badge/BVH-.bvh-0891B2?style=for-the-badge&labelColor=0B1F4D)
![X3D / WRL](https://img.shields.io/badge/X3D%20%2F%20WRL-.x3d%20%7C%20.wrl-0891B2?style=for-the-badge&labelColor=0B1F4D)

#### CAD, architecture, and DCC formats

![Autodesk MAX](https://img.shields.io/badge/Autodesk%20MAX-.max-9333EA?style=for-the-badge&labelColor=0B1F4D)
![Autodesk 3DS](https://img.shields.io/badge/Autodesk%203DS-.3ds-9333EA?style=for-the-badge&labelColor=0B1F4D)
![AutoCAD DXF](https://img.shields.io/badge/AutoCAD%20DXF-.dxf-9333EA?style=for-the-badge&labelColor=0B1F4D)
![SketchUp](https://img.shields.io/badge/SketchUp-.skp-9333EA?style=for-the-badge&labelColor=0B1F4D)
![Rhinoceros 3DM](https://img.shields.io/badge/Rhinoceros%203DM-.3dm-9333EA?style=for-the-badge&labelColor=0B1F4D)
![3DXML](https://img.shields.io/badge/3DXML-.3dxml-9333EA?style=for-the-badge&labelColor=0B1F4D)

#### Game, voxel, volume, vector, and data formats

![Unreal PSK](https://img.shields.io/badge/Unreal%20PSK-.psk%20%7C%20.pskx-14B8A6?style=for-the-badge&labelColor=0B1F4D)
![Unreal PSA](https://img.shields.io/badge/Unreal%20PSA-.psa-14B8A6?style=for-the-badge&labelColor=0B1F4D)
![OpenVDB](https://img.shields.io/badge/OpenVDB-.vdb-14B8A6?style=for-the-badge&labelColor=0B1F4D)
![MagicaVoxel VOX](https://img.shields.io/badge/MagicaVoxel%20VOX-.vox-14B8A6?style=for-the-badge&labelColor=0B1F4D)
![SVG](https://img.shields.io/badge/SVG-.svg-14B8A6?style=for-the-badge&labelColor=0B1F4D)
![3MF](https://img.shields.io/badge/3MF-.3mf-14B8A6?style=for-the-badge&labelColor=0B1F4D)
![OFF](https://img.shields.io/badge/OFF-.off-14B8A6?style=for-the-badge&labelColor=0B1F4D)
![XYZ](https://img.shields.io/badge/XYZ-.xyz-14B8A6?style=for-the-badge&labelColor=0B1F4D)

---

### Format support notes

| Details |
|---|
| Export and import format availability may depend on Blender version, installed or bundled dependencies, operating system, Python ABI, or format-specific requirements |
| Some formats are import-only in the current package |
| Some formats are export-capable and import-capable |
| SketchUp import is packaged for Windows x64 in this release |
| Rhinoceros 3DM import depends on a compatible bundled `rhino3dm` wheel for the active Blender Python build and platform |
| Unsupported runtime paths are designed to fail closed with clear availability messages instead of exposing broken import/export actions |
| Format-specific behavior should be tested with real production files before marketplace release |
| Pipeline presets may enable different format combinations depending on the selected delivery workflow |

---

## Capabilities

| Details |
|---|
| Multi-format 3D import and export from one production panel |
| Export and import modes in Blender’s 3D View sidebar |
| File menu import/export entries for supported formats |
| Pipeline presets for 3D Print, ArchViz, General Delivery, Godot, glTF Web, Marketplace, OBJ General, Unreal Engine, and Unity delivery |
| Batch export workflow for enabled formats |
| Directory-based import workflow with source folder scanning and supported-file filtering |
| Import queue with refresh, toggle, clear, and import-checked actions |
| Optional subfolder scanning for import workflows |
| Collection routing to current collection, scene collection, per-file collections, or custom collection |
| Export sanity checker and local report generation |
| Asset inspection and round-trip-oriented review states |
| Scene, object, material, texture, and delivery-oriented validation checks |
| Runtime-aware format availability handling |
| Local-only workflow with no external service or account requirement for normal operation |

---

<details>
  <summary>Feature reference</summary>

## Feature reference

### Multi-format pipeline
| Details |
|---|
| Unified import and export workflow |
| Format-aware asset pipeline |
| Local file-based processing |
| Format-specific availability handling |
| Runtime messages for unsupported formats or unavailable operators |
| Import/export menu integration |
| 3D View sidebar workflow panel |

### Supported formats
| Content Creation & Exchange | Game Engine & Animation Pipelines | CAD, Design & Fabrication | Specialized Data Formats |
|---|---|---|---|
| - FBX | - Unreal PSK / PSKX | - Autodesk MAX | - OpenVDB |
| - BLEND import | - Unreal PSA | - Autodesk 3DS | - SVG |
| - OBJ | - BVH | - STL | - VOX |
| - glTF / GLB | - Alembic | - USD / USDA / USDC / USDZ | - OFF |
| - DAE / Collada | - X3D / WRL | - DXF | - XYZ |
| - PLY |  | - SKP | - 3DXML |
|  |  | - 3DM | - 3MF |

### Export workflow
| Details |
|---|
| Output directory selection |
| Enabled format selection |
| Active export format switching |
| Batch export for enabled formats |
| Format-specific export option panels |
| Transform and scale controls |
| Selection-based export where supported |
| Animation-aware export options where supported |
| Path and file naming handling |
| Unique path handling for export outputs |
| Cleanup and transform controls for supported formats |

### Import workflow
| Details |
|---|
| Source directory selection |
| Refresh import file list |
| Toggle checked files |
| Clear file list |
| Import checked files |
| Supported-format filtering |
| Include subfolders option |
| Import queue workflow |
| Format-specific import option panels |
| Native import fallback flow where available |
| Collection routing to current collection |
| Collection routing to scene collection |
| Collection routing per file |
| Collection routing to a custom collection |
| Manual import inspector option in preferences |

### Pipeline presets
| Details |
|---|
| 3D Print preset |
| ArchViz Exchange preset |
| General Delivery preset |
| Godot preset |
| glTF Web preset |
| Marketplace preset |
| OBJ General preset |
| Unreal Engine preset |
| Unity preset |
| Auto-apply preset workflow |
| Sync sanity profile |
| Sync enabled formats |
| Sync import workflow |

### Validation and inspection
| Details |
|---|
| Export sanity checker workflow |
| Inspector report summary |
| Scene metrics review |
| Object metrics review |
| Material metrics review |
| Texture metrics review |
| Delivery-oriented sanity profiles |
| Round-trip status states: Pass, Warn, Fail, None |
| Local QA/report output |
| Findings with severity, category, object, message, fixability, fix ID, and details |

### Batch and handoff
| Details |
|---|
| Batch export workflow |
| Repeated handoff preparation |
| Marketplace delivery preparation |
| Asset-library preparation |
| Client delivery cleanup workflow |
| Format-specific delivery preparation |
| Local path and folder-based exchange |

### Package and runtime
| Details |
|---|
| Source-based Blender extension package |
| Blender 4.2+ minimum |
| Windows x64 package declaration |
| Bundled Rhino wheel files for compatible Windows Blender Python builds |
| Bundled SketchUp native components for Windows x64 package support |
| Clear runtime messages when a format is not available in the current build or platform |

</details>

---

## Intended users

DRH - Asset Pipeline Studio is designed for:

| Details |
|---|
| Technical artists |
| Blender asset creators |
| Game artists |
| Environment artists |
| Pipeline-focused users |
| ArchViz and CAD exchange users |
| Marketplace asset creators |
| BlendKit creators |
| Small teams and solo creators |
| Users managing repeated import/export tasks |
| Users preparing asset packs, libraries, or deliverables |
| Users working with format-based asset pipelines |
| Users who need cleaner asset transfer, validation, inspection, and handoff workflows |

---

## Status

| Item | Details |
|---|---|
| Status | 🟣 In Development [On-Hold] |
| Current version | 1.0.0 |
| Add-on name | DRH - Asset Pipeline Studio |
| Extension ID | `drh_asset_pipeline_studio` |
| Minimum Blender version | 4.2.0 |
| Platforms | Windows x64 |
| Type | Blender add-on |
| Category / Tags | Import-Export, Pipeline |
| Maintainer | Paco Salas \| DRH |
| License | GPL-3.0-or-later |
| Release type | In development before public marketplace release |
| Support repository | [DRH Asset Pipeline Studio Support](https://github.com/pacosalasv/DRH_Asset_Pipeline_Studio-Support) |

This add-on is currently in development. Compatibility feedback, usability comments, feature expectations, and workflow suggestions are welcome before public release.

---

## Technical notes

This add-on is source based, with:

- No obfuscation
- No external services required for normal operation
- No account requirements for normal operation
- No external downloads required for normal operation

Local file access may be used for:

| Details |
|---|
| Import workflows |
| Export workflows |
| Format-based asset pipelines |
| Source directory scanning |
| Asset transfer |
| Asset validation |
| Asset inspection |
| Local validation reports |
| Local file handling |
| Path-based workflows |
| Asset package preparation |
| Project or asset folder selection |
| Batch-processing workflows |

The add-on is intended to work locally inside Blender.

Current package notes:

| Details |
|---|
| Minimum Blender version: 4.2.0 |
| Platform currently indicated in package metadata: Windows x64 |
| Sidebar tab: `DRH-Asset Pipeline` |
| Panel label: `DRH - Asset Pipeline Studio` |
| Blender category: Import-Export |
| Extension ID: `drh_asset_pipeline_studio` |
| SketchUp import uses bundled Windows native components and is currently packaged for Windows x64 |
| Rhinoceros 3DM import depends on compatible bundled `rhino3dm` wheels for the current Blender Python ABI and platform |
| Format support may depend on Blender version, available import/export operators, bundled dependencies, Python ABI, and operating system support |

---

## Availability

This add-on may be available through multiple marketplaces and storefronts after release.

This GitHub repository remains the central public location for:

| Details |
|---|
| Support |
| Documentation |
| Issue tracking |
| Compatibility reports |
| Public feedback |
| Release notes |

---

## Documentation

- [User Manual](docs/manual/user-manual.pdf)
- [Changelog](CHANGELOG.md)

---


## Support

Use [GitHub Discussions](https://github.com/pacosalasv/DRH_Asset_Pipeline_Studio-Support/discussions) for setup questions, workflow guidance, and general feedback. Use [GitHub Issues](https://github.com/pacosalasv/DRH_Asset_Pipeline_Studio-Support/issues/new/choose) for reproducible bugs, regressions, compatibility problems, and focused feature requests.

Do not post credentials, payment information, license keys, confidential production files, private client material, or sensitive local paths.

Detailed guidance is available in [SUPPORT.md](SUPPORT.md).

## Support DRH development

Development support is optional. Contributions through [Ko-fi](https://ko-fi.com/pacosalasv) help cover maintenance, Blender compatibility work, documentation, and testing.

## License

This repository is distributed under GPL-3.0-or-later.

---

<div align="center">
