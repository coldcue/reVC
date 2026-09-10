# reVC for Mac

**Play the original GTA Vice City natively on your Mac.** A native Apple Silicon build that renders through **Metal**, runs sharp at full **Retina** resolution, and turns on macOS **Game Mode** automatically.

This repository hosts the **release only** — there is no source code here.

### ➜ [Download the latest build](https://github.com/coldcue/reVC/releases/tag/revc-metal-macos-arm64)

> ⚠️ **This needs the original Vice City, not the Definitive Edition.** The Definitive Edition is a different, rebuilt game and will not work.

## Install

**You need:** an Apple Silicon Mac (M1 or newer) on macOS 15.7.9 or later, and your own copy of the **original GTA Vice City** — the classic 2002/2003 PC release ([Steam](https://store.steampowered.com/app/12110/) works out of the box — you never have to launch it).

1. Open **Terminal** (`Cmd+Space`, type `Terminal`, press Enter), paste this line and press Enter:

   ```sh
   curl -fsSL https://github.com/coldcue/reVC/releases/download/revc-metal-macos-arm64/quick-install.sh | bash
   ```

   It finds your game files automatically and puts **reVC.app** in your Downloads folder — about a minute, the app is ~1.6 GB with the game inside.

2. When Finder opens, **drag reVC into Applications** — or just double-click it to play right away.

**Using a non-Steam copy?** Add the path to the end of the command — a game folder (the one with `models`, `data`, `audio`, …) or a Vice City `.app` that contains the files (including Wineskin/Wine wrappers) both work:

```sh
curl -fsSL https://github.com/coldcue/reVC/releases/download/revc-metal-macos-arm64/quick-install.sh | bash -s -- ~/Downloads/"Grand Theft Auto - Vice City.app"
```

**Upgrading?** Run the same one-liner again — it reuses the game files from your installed reVC.app.

Prefer a classic disk image? Add `--dmg` to get a drag-to-Applications `reVC.dmg` instead: `... | bash -s -- --dmg`.

## What's in the build

See the [release notes](https://github.com/coldcue/reVC/releases/tag/revc-metal-macos-arm64) for the full list — Metal rendering via ANGLE, HDR output, MetalFX upscaling, mipmapping with anisotropic filtering, extended draw distance, native fullscreen, and Game Mode support.

## Legal

reVC requires the files from your own legally purchased copy of the original Grand Theft Auto: Vice City. No game assets are distributed here.
