# This project is now macVC

**reVC for Mac has been renamed, and downloads have moved to
[gtamac/macVC](https://github.com/gtamac/macVC).**

### ➜ [Get macVC](https://github.com/gtamac/macVC)

The [release here](../../releases/latest) only keeps existing installs working —
it carries the two files an installed `reVC.app` fetches when it checks for
updates, and they point at the new repository. The build itself lives there.

## Install

```sh
curl -fsSL https://raw.githubusercontent.com/gtamac/macVC/main/quick-install.sh | bash
```

Upgrading from the old build carries everything over: the installer takes the
game files out of your existing `reVC.app`, and the first launch copies your
settings and saves into `~/Library/Application Support/macVC`. Nothing is moved
or deleted — the old app and its save folder stay exactly where they are.

## Legal

macVC requires the files from your own legally purchased copy of the original
Grand Theft Auto: Vice City. No game assets are distributed here.
