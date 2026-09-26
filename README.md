# TpF2 Multiplayer packages

This repository holds the install packages of
[TpF2 Multiplayer](https://github.com/silver2127/tpf2-multiplayer) that its launchers
download. **Players do not need anything from here:** get the Windows or Linux launcher
from the [latest release](https://github.com/silver2127/tpf2-multiplayer/releases/latest),
and it installs and updates the mod.

Each release here has the same tag as the mod release it belongs to (`v0.7.0.6`, ...)
and carries the files the installers use:

| File | Used by |
| --- | --- |
| `TpF2Multiplayer.msi` | the Windows launcher |
| `tpf2mp-linux-<version>-native.tar.gz`, `.run`, `.sha256` | the Linux launcher (the native Linux game) |
| `TpF2Multiplayer-files.zip`, `install_proton.py`, `install_proton.sh` | the Linux launcher and the Proton script (the Windows game under Proton) |
| `SHA256SUMS.txt` | checksums of the Windows and Proton files |

Release notes are on the mod's releases. Releases up to 0.7.0.5 keep their files on the
mod's own releases; this repository starts with 0.7.0.6.

Nothing here is built by hand: the mod's release process uploads it.
