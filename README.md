# Clavis Encrypt — downloads and updates

**Clavis Encrypt** ("Clavis" for short) is a free file-encryption app for Windows 10, Windows 11 and Linux.
It locks your files on your own PC with AES-256-GCM, turning your password into a
key with Argon2id. No account, no cloud, nothing uploaded.

**Download:** https://clavisenc.com/download.html
**Website:** https://clavisenc.com/

This repository hosts the release files (installer, portable ZIP, Linux .deb) and
the signed files the app's automatic updater reads. Every update is signed with
Ed25519 and verified by the app before it installs.

| File | What it is |
|---|---|
| `Clavis-Setup.exe` | Windows installer (per-user, no administrator rights) |
| `Clavis-windows.zip` | Portable version for Windows |
| `Clavis-linux.deb` | Ubuntu / Debian package, includes the `clavis-cli` command |

Checksums for each release are on the [download page](https://clavisenc.com/download.html).

> Clavis Encrypt (clavisenc.com) is made by Kapil Palanivel. It is not
> related to other apps named Clavis, such as the Clavis password manager on the
> Microsoft Store.
