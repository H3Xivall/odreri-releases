# Odreri releases

Installers for [Odreri](https://github.com/H3Xivall), the writing studio for serial fiction, notes, academic and technical writing.

This repository holds only release assets:

- `Odreri-<version>-x86_64.AppImage` for Linux
- `manifest.json`, the signed update manifest the app checks once a day

Every manifest is signed with the project's Ed25519 key and verified by the app before anything is downloaded; the download is checked against the manifest's size and SHA-256 before it replaces the running copy.

Source code is not published here.
