# AEGIS desktop

Windows client for [AEGIS Verdandi](https://aihria.eu), published by Daetis.

This repository contains the downloadable installer only. The application source and the API stay in a private repository.

## Download

[AEGIS 1.1.0 for Windows (64-bit)](https://github.com/DaveV01/aegis-desktop/releases/latest/download/AEGIS_1.1.0_x64-setup.exe)

| | |
| --- | --- |
| File | `AEGIS_1.1.0_x64-setup.exe` |
| Latest release tag | `v1.1.0-d534275` |
| Source revision | `d534275d8256c2ca896a55f6a5c6dd0780a77d99` |
| SHA-256 | `e9f5527c3c31aecad48951a774c148f0919c4aa2e4bc993985ad618f6664ac76` |
| Publisher shown in the file properties | Daetis |
| Authenticode | Valid |
| Authenticode signer | `CN=DAETIS OÜ, O=DAETIS OÜ, L=Tallinn, C=EE` |

The publisher shown in the Windows file properties is Daetis. That name is not the cryptographic signer. Authenticode verification of this installer is Valid, and the signer is CN=DAETIS OÜ, O=DAETIS OÜ, L=Tallinn, C=EE.

## What this installer is

This is the online-only client. It is a desktop window around the AEGIS interface and connects to `https://aihria.eu`. It does not install PostgreSQL, Node, or the API, and it does not contain model keys.

Create an account in the app, then sign in. Projects and documents are stored on the service under that account.
