# CAIOS Nexus module downloads

Public, module-only release downloads for CAIOS Nexus. Nexus Core, its personal API configuration, development sources and internal notes are kept in a separate private repository.

## Warcraft module

- Current early preview: [Nexus Warcraft 0.1.0-dev.1](https://github.com/Tokenkauph/caios-nexus-modules/releases/tag/warcraft-v0.1.0-dev.1)
- Download: [nexus-warcraft-0.1.0-dev.1.zip](https://github.com/Tokenkauph/caios-nexus-modules/releases/download/warcraft-v0.1.0-dev.1/nexus-warcraft-0.1.0-dev.1.zip)
- Expected SHA-256: `6427377062d13cae17a23c24abfe57b105b2daa883a5c87ed14df3c4ef6e8f72`
- Package files: `module.json` and `NexusCore.Warcraft.dll` only.
- Needs compatible Nexus Core 0.1.0. This is not a standalone application or WoW add-on.
- Reads the existing local Warcraft collector's published status files on demand. It does not install or control a second collector, capture the screen, or write to game history.

## For Nexus Core

Read [catalog.json](catalog.json) for the allowlisted module ID, version, compatibility, release asset URL and SHA-256. Download only when the user chooses Install & Enable, verify the downloaded ZIP, and keep enabled state distinct from installed state. Disabled modules do not do ongoing module work.

## Public release boundary

Anyone can download and inspect the release files. Do not upload Nexus Core executables, personal API keys, collector data, user settings, private notes or build artifacts containing those items. This first module build passed source/package checks; installed Windows/Warcraft acceptance is still pending.
