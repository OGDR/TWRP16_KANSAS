# TWRP16_KANSAS — OGDR Edition

An independently maintained TWRP 16.0 source tree for the Motorola Moto G 5G 2025 (Kansas).

**Device:** Motorola Moto G 5G 2025  
**Codename:** Kansas  
**Model:** XT2513-1  
**Platform:** MediaTek MT6835  
**Android Base:** Android 16  
**Maintained by:** OGDR

---

## About This Project

TWRP16_KANSAS is an independently maintained TWRP 16.0 source project focused on bringing a stable, reliable custom recovery to the Motorola Moto G 5G 2025.

This project uses its own maintained source environment, with direct control over source revisions, recovery modifications, build configuration, and device-specific development.

The goal is to keep development focused, understand every modification, test changes carefully, and maintain a recovery built specifically for Kansas.

## Why This Project Exists

TWRP16_KANSAS was started as an independent project to take full control of development, avoid questionable source changes, unnecessary build modifications, poorly implemented features, and questionable bullshit code introduced by others.

Development is maintained under OGDR, with an emphasis on stability, reliability, and transparency.

## Source Development

- Independently maintained TWRP 16.0 source tree.
- Dedicated Kansas device-tree integration.
- Controlled source revisions and repository updates.
- Device-specific recovery modifications.
- Independent build and testing environment.

## Device Support

| Component | Details |
|---|---|
| Device | Motorola Moto G 5G 2025 |
| Codename | Kansas |
| Model | XT2513-1 |
| SoC | MediaTek MT6835 |
| Architecture | ARM64 |
| Android Base | Android 16 |

## Development Goals

- Reliable TWRP boot.
- Full touchscreen support.
- Display compatibility.
- ADB support.
- Internal storage access.
- FBE encrypted `/data` decryption.
- Correct partition detection and mounting.
- Accurate backup size calculations.
- Working backup and restore operations.
- Fastbootd support.

## Build Configuration

The initial recovery development baseline uses an `eng` build configuration.

Build instructions, required dependencies, device-tree integration, and additional configuration details will be documented as development progresses.

## Version Branching

This repository is intended to support multiple TWRP generations through separate Git branches.

- `16` — TWRP 16 development.
- `17` — Future TWRP 17 development.
- `18` — Future TWRP 18 development.

Future versions will be maintained in their own branches rather than requiring a separate repository for every major version.

## Project Status

**Development in progress.**

The source environment is being established and synchronized. Device integration, compilation, boot testing, and recovery functionality will be verified before release.

## Credits

- Team Win Recovery Project (TWRP)
- TWRP and Android open-source contributors
- Motorola device research and hardware investigation
- OGDR development and maintenance

## OGDR

Let me use my phone.\
"Because squinting at your phone shouldn't be a full-time job!" 😂\
**Keep it OG.**
