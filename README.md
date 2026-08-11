# Improved IR Mod v0.7.1

## What it does
This mod improves the IR/IRST seeker behavior in Nuclear Option with stronger target acquisition logic, better locking behavior, and more reliable compatibility with newer game updates.

## What changed and updated
- Updated for Nuclear Option v0.34 compatibility.
- Added lock-based acquisition logic for IRST behavior.
- Added LOAL-style guidance support and debug hooks for analysis.
- Improved reflection-based compatibility handling for runtime API changes.
- Rebuilt and repackaged with cleaned metadata for public release.

## How to install
1. Copy `ImprovedIRMod.dll` and `ImprovedIRMod.json` into:
   ```
   Nuclear Option/BepInEx/plugins/IMPROVED IR MOD/
   ```
2. Start Nuclear Option.
3. Launch a mission and use the mod normally.
4. Check BepInEx logs if you need debug output.

## Included files
- `ImprovedIRMod.dll`
- `ImprovedIRMod.json`
- `README.md`
- `source-code.zip`
- `source-code.tar.gz`

## Requirements
- Nuclear Option v0.34+
- BepInEx 5.x

## Release notes
- v0.7.1: final v0.34 compatibility pass and release cleanup