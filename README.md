# AEGIS desktop

Windows client for [AEGIS Verdandi](https://aihria.eu), published by Daetis.

This repository contains the downloadable installer only. The application source and the API stay in a private repository.

## Download

[AEGIS 1.1.0 for Windows (64-bit)](https://github.com/DaveV01/aegis-desktop/releases/latest/download/AEGIS_1.1.0_x64-setup.exe)

| | |
| --- | --- |
| File | `AEGIS_1.1.0_x64-setup.exe` |
| Latest release tag | `v1.1.0-e5fbd79` |
| Source revision | `e5fbd7914e86d062d0babf596aacdcc0e2ce3d58` |
| SHA-256 | `cdd03bdc57f96065066863eac9877120b8513deddf0d3636b76ae21deeb8f35d` |
| Publisher shown in the file properties | Daetis |
| Authenticode | Valid |
| Authenticode signer | `CN=DAETIS OÜ, O=DAETIS OÜ, L=Tallinn, C=EE` |

The publisher shown in the Windows file properties is Daetis. That name is not the cryptographic signer. Authenticode verification of this installer is Valid, and the signer is CN=DAETIS OÜ, O=DAETIS OÜ, L=Tallinn, C=EE.

## What this installer is

This is the online-only client. It is a desktop window around the AEGIS interface and connects to `https://aihria.eu`. It does not install PostgreSQL, Node, or the API, and it does not contain model keys.

Create an account in the app, then sign in. Projects and documents are stored on the service under that account.
