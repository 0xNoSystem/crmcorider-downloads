# CRM Corider downloads

Portable Windows x64 dispatch desk.

**[Download nfd.exe](https://github.com/0xNoSystem/crmcorider-downloads/releases/latest/download/nfd.exe)**

[View all releases and checksums](https://github.com/0xNoSystem/crmcorider-downloads/releases)

## First run

1. Download `nfd.exe` into a permanent folder, then open it.
2. Choose your company and sign in with your own CRM account.
3. To use the map, open **Connection & recovery → Map API keys** and save your own Map ID and API token. This creates the local `.env` file automatically.

Saved profiles, workspaces, notes, and technicians use `%LOCALAPPDATA%\NFD\nfd-live.db` by default. Map configuration is stored in `%LOCALAPPDATA%\NFD\.env`.

## Updating an existing installation

Wait until edits show **Saved**, stop the running app's console, and replace the executable. Keep `%LOCALAPPDATA%\NFD` intact to preserve saved data and settings.

## About this repository

This repository hosts compiled releases and download instructions. Application source is maintained separately. Distributed demo work orders are synthetic; CRM credentials and saved user databases are not included in the download.
