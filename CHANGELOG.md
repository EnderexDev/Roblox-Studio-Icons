# Changelog

All notable changes to the "Icons Roblox Studio" extension are listed here.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) and the project uses
[Semantic Versioning](https://semver.org/). Dates are YYYY-MM-DD.

## [1.2.1] - 2026-01-10

### Changed
- **docs:** README describes the two icon themes and uses the full Roblox service names.

## [1.2.0] - 2026-01-10

### Added
- **themes:** new "Roblox Studio (Argon)" icon theme (`fileicons/argon.json`), for projects synced with Argon.
- **argon:** icons for Argon's default folders `Shared`, `Client` and `Server` (you also deserve some icons <3).
- **themes:** two themes to pick from in VS Code: "Roblox Studio (Rojo & Azul)" and "Roblox Studio (Argon)".

### Changed
- **themes:** the old "Roblox Studio Icon Theme" (`roblox-icon-theme.json`) is now "Roblox Studio (Rojo & Azul)" (`fileicons/rojo-azul.json`). Its mappings are the same apart from the `Players` folder below.
- **package:** new description and keywords in `package.json`.
- **package:** minimum VS Code version raised from 1.50 to 1.60 (`engines.vscode: ^1.60.0`).

### Removed
- **folders:** the `Players` folder no longer gets an icon (no one puts a script in Players).

## [1.1.0] - 2026-01-08

### Changed
- **folders:** `src` (Rojo) and `sync` (Azul) now have their own Rojo and Azul icons instead of reusing the Workspace one.

## [1.0.0] - 2026-01-08

### Added
- Initial release.
- **scripts:** Roblox Studio icons for `.lua` and `.luau` files: Script (`.server.luau`), LocalScript (`.client.luau`) and ModuleScript (`.luau`).
- **folders:** icons for ReplicatedStorage, ReplicatedFirst, ServerScriptService, ServerStorage, Players, StarterGui, StarterPack, StarterPlayerScripts, StarterCharacterScripts, Lighting, SoundService and Workspace, matching the Studio theme.
- **files:** icons for json, toml, md, txt, png, jpg, jpeg, lock, git and yml files, plus README.
