# AEGIS desktop

Windows client for [AEGIS Verdandi](https://aihria.eu), published by Daetis.

This repository contains the downloadable installer only. The application source and the API stay in a private repository.

## Download

[AEGIS 1.1.0 for Windows (64-bit)](https://github.com/DaveV01/aegis-desktop/releases/latest/download/AEGIS_1.1.0_x64-setup.exe)

| | |
| --- | --- |
| File | `AEGIS_1.1.0_x64-setup.exe` |
| SHA-256 | `80a492cace87dd8cc88eacca66f782ad68c895134b8d5dbe48c768453cf06c97` |
| Publisher shown in the file properties | Daetis |

Windows will warn that the publisher is unknown until a Daetis Authenticode certificate is attached. The file-property publisher name is Daetis; that label is not a cryptographic signature.

## What this installer is

The app is a desktop window around the AEGIS interface. It connects to `https://aihria.eu`. It does not install PostgreSQL, Node, or the API, and it does not contain model keys.

Create an account in the app, then sign in. Projects and documents are stored on the service under that account.
