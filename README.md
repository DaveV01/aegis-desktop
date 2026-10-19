# AEGIS desktop

Windows client for [AEGIS Verdandi](https://aihria.eu), published by Daetis.

This repository contains the downloadable installer only. The application source and the API stay in a private repository.

## Download

[AEGIS 1.1.0 for Windows (64-bit)](https://github.com/DaveV01/aegis-desktop/releases/download/v1.1.0/AEGIS_1.1.0_x64-setup.exe)

| | |
| --- | --- |
| File | `AEGIS_1.1.0_x64-setup.exe` |
| SHA-256 | `d54734ac99493e7c4148f236cd5d80ae9c4cb79ed08c20f6a8dbc10364754c82` |
| Publisher shown in the file properties | Daetis |

Windows will warn that the publisher is unknown until a Daetis Authenticode certificate is attached. The file-property publisher name is Daetis; that label is not a cryptographic signature.

## What this installer is

The app is a desktop window around the AEGIS interface. It connects to `https://aihria.eu`. It does not install PostgreSQL, Node, or the API, and it does not contain model keys.

Create an account in the app, then sign in. Projects and documents are stored on the service under that account.
