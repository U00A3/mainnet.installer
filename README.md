# Redbelly Mainnet Node Installer

[![Mirror](https://img.shields.io/badge/mirror-unofficial-7c3aed?style=plastic)](https://github.com/U00A3/mainnet.installer#about-this-repository) [![Redbelly](https://img.shields.io/badge/Redbelly-mainnet-c41e3a?style=plastic&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA1MDAgNTUwIj48cGF0aCBmaWxsPSIjZmZmIiBkPSJNNDYyLjI1LDE0NS41NiwyNTYuMDcsMjYuNjNhMTIuMTMsMTIuMTMsMCwwLDAtMTIuMTQsMEwzNy43NSwxNDUuNTZhMTIuMTUsMTIuMTUsMCwwLDAtNi4wNywxMC41MVYzOTMuOTRhMTIuMTYsMTIuMTYsMCwwLDAsNi4wNywxMC41MUwyNDMuOTMsNTIzLjM4YTEyLjE4LDEyLjE4LDAsMCwwLDEyLjE0LDBMNDYyLjI1LDQwNC40NWExMi4xNiwxMi4xNiwwLDAsMCw2LjA3LTEwLjUxVjE1Ni4wN0ExMi4xNSwxMi4xNSwwLDAsMCw0NjIuMjUsMTQ1LjU2Wk0yNTAsNTEuMTVsMTkwLjYzLDExMGMtMzEuMDUsMTcuNTItNTcuMjUsMzkuNzctNzkuMzUsNjQuNTctNDMuMTItNTAuODQtMTAzLTEwMS0xODQuMzgtMTMyLjM3Wk00MDQuMzUsMzA4LjkxYTEzLjcsMTMuNywwLDAsMS0xMi41NS04LjIxLDEzLjU4LDEzLjU4LDAsMSwxLDI1LjA5LDBBMTMuNjksMTMuNjksMCwwLDEsNDA0LjM1LDMwOC45MVptMC00MC43M2EyNy4yMywyNy4yMywwLDAsMC05LjU0LDEuOGMtNy43Ny0xMS40Ny0xNi4xOC0yMy4xNC0yNS43LTM0LjkyYTMwMi4zNiwzMDIuMzYsMCwwLDEsNzAuNDctNTkuMjksNjYxLjI5LDY2MS4yOSwwLDAsMC0zNC4yNyw5Mi41MUM0MDUsMjY4LjI3LDQwNC42OCwyNjguMTgsNDA0LjM1LDI2OC4xOFpNMzUzLjI4LDIzNWMtMjEuOSwyNi4zNi0zOS40Nyw1NS4xOS01My41Niw4NC02LjgxLTk4LjczLTgyLjctMTc2LjA2LTEyMy40My0yMTNDMjU0LjM3LDEzNi45NCwzMTEuODQsMTg1LjczLDM1My4yOCwyMzVabS02MiwxMjdhMTMuNywxMy43LDAsMCwxLTEyLjU1LTguMjEsMTMuNDQsMTMuNDQsMCwwLDEtMS01LjEyLDEzLjYyLDEzLjYyLDAsMSwxLDEzLjU3LDEzLjMzWm0tMy43NC00MC4zNWEyNy40NywyNy40NywwLDAsMC02LjgxLDEuNzQsNDgwLjk0LDQ4MC45NCwwLDAsMC0xMDEuNzQtMTAyLjQsMjcsMjcsMCwwLDAsMy43Ni0xMy42MiwyNy4zOCwyNy4zOCwwLDAsMC0yMS4zOS0yNi42OFYxMDguOUMxOTguNzcsMTQyLjA2LDI4MS4zOSwyMjAuOTIsMjg3LjQ5LDMyMS41N1pNMTY3LjgzLDIxMi40MWExMy43LDEzLjcsMCwwLDEtMjUuMSwwLDEzLjM5LDEzLjM5LDAsMCwxLTEtNS4xMSwxMy41NywxMy41NywwLDAsMSwyNy4xNCwwQTEzLjM5LDEzLjM5LDAsMCwxLDE2Ny44MywyMTIuNDFabS0xOC42Ny0xMDMuMXY3MS4zM2EyNy4zMiwyNy4zMiwwLDAsMC0xNiwxMC41NEE0NDMuMjcsNDQzLjI3LDAsMCwwLDYzLDE1OVpNNTYsMTgwLjUzYzE4LjEyLDI2Ljg0LDUzLjczLDg0LjEzLDc1LjMxLDE0OC4yLS4yNC4xNS0uNTEuMjctLjc0LjQzQTQ1Mi42LDQ1Mi42LDAsMCwwLDU2LDI3Ni42OVpNMTU5LjU2LDM1MS43OGExMy40NCwxMy40NCwwLDAsMS0xLDUuMTIsMTMuNTIsMTMuNTIsMCwxLDEsMS01LjEyWm0tMTEsODguNTRMNTYsMzg2LjkzVjI5MC42N2E0MzUuMTMsNDM1LjEzLDAsMCwxLDY2LjI0LDQ3LjcxQTI3LjA5LDI3LjA5LDAsMCwwLDE0NC4zMiwzNzlDMTQ4LjE2LDM5OS42MiwxNTAsNDIwLjI5LDE0OC41Myw0NDAuMzJaTTE2MC4xNiw0NDdjMi40LTIyLjkyLjcxLTQ2LjU2LTMuNTUtNzBhMjcsMjcsMCwwLDAsMy43MS0yLDUxOS41Miw1MTkuNTIsMCwwLDEsODIsMTE5LjQxWm04OC43NywzMy41N2E1MzAuODgsNTMwLjg4LDAsMCwwLTgwLTExMy44OUEyNy4zNSwyNy4zNSwwLDAsMCwxNDYsMzI0LjM4YTI3Ljg4LDI3Ljg4LDAsMCwwLTMuMDUuMzFDMTIwLjczLDI1OC4zNCw4NCwxOTkuODcsNjUuNTQsMTcyLjg0YTQzMi4xLDQzMi4xLDAsMCwxLDYyLjgyLDI5LjQ5LDI3Ljg5LDI3Ljg5LDAsMCwwLS41LDUsMjcuNCwyNy40LDAsMCwwLDQyLjkxLDIyLjU5QTQ2Ny45LDQ2Ny45LDAsMCwxLDI3MC44OCwzMzAuMzlhMjcuMDgsMjcuMDgsMCwwLDAsNi42MSw0MS43OEE2NDAuMTYsNjQwLjE2LDAsMCwwLDI0OC45Myw0ODAuNlptMTAuMjEsMTNhNjI0LjY3LDYyNC42NywwLDAsMSwyOS43OS0xMTcuODNjLjc3LjA3LDEuNTEuMjMsMi4zLjIzYTI3LjA3LDI3LjA3LDAsMCwwLDguNzEtMS41NEE1MjMuNzEsNTIzLjcxLDAsMCwxLDMzNi40MSw0NDlabTg3LjkxLTUwLjcxYTUzNy4yLDUzNy4yLDAsMCwwLTM2Ljc1LTc0LjY1QTI3LjE0LDI3LjE0LDAsMCwwLDMwOSwzMjcuODVjMTMuNjgtMjguNTksMzAuNjgtNTcuMjMsNTIuMTYtODMuNCw4LjY2LDEwLjgyLDE2LjQsMjEuNTQsMjMuNTcsMzIuMDlhMjcuMjMsMjcuMjMsMCwwLDAsNy45LDQzLjY5LDUzOS42NSw1MzkuNjUsMCwwLDAtMTAuODQsMTAyLjYzWk0zOTQsNDE1Ljc5QTUzMC4zNCw1MzAuMzQsMCwwLDEsNDA0LjQ5LDMyM2EyNy4wOCwyNy4wOCwwLDAsMCw3Ljc4LTEuMjgsNTAzLjE1LDUwMy4xNSwwLDAsMSwzMC4zMyw2Ni4wOFptNTAtNTdjLTUuMzgtMTIuMzgtMTIuNTEtMjcuMTEtMjEuMjQtNDMuMUEyNy4xNCwyNy4xNCwwLDAsMCw0MTcsMjcxLjM5LDY1My4zMiw2NTMuMzIsMCwwLDEsNDQ0LDE5NS41NVoiLz48L3N2Zz4%3D&logoWidth=36)](https://redbelly.network/) [![Source](https://img.shields.io/badge/source-Vine%20portal-15803d?style=plastic)](https://vine.redbelly.network/) [![Latest](https://img.shields.io/badge/latest-v1.3.15-0369a1?style=plastic)](https://github.com/U00A3/mainnet.installer#package) [![SHA256](https://img.shields.io/badge/sha256-verified-16a34a?style=plastic)](https://github.com/U00A3/mainnet.installer#integrity-sha-256) [![Linux](https://img.shields.io/badge/Linux-supported-FCC624?style=plastic&logo=linux&logoColor=black)](https://github.com/U00A3/mainnet.installer)

[![Tag @1F592 on Discord](https://img.shields.io/badge/Tag%20%401F592-Discord-5865F2?style=plastic&logo=discord&logoColor=white)](https://discord.com/channels/969088176322908160/1378117350619873311)

Self-extracting installer for running a Redbelly mainnet node.

**Last mirror update:** 2026-07-09 (UTC)

## About this repository

This repository is **not** affiliated with Redbelly. It is an **unofficial** mirror maintained by a node operator who shares the installer with others for convenience. For authoritative documentation and releases, use Redbelly’s official channels.

## Package

| Field | Value |
|--------|--------|
| **File name** | `rbn-installer-mainnet-v1.3.15.run` |
| **Installer version (UI)** | see Vine portal |
| **Binary version** | v1.3.15 |

## How to download (simple)

Pick **one** of the options below. After the file is on your machine, **verify the SHA-256** (see [Integrity (SHA-256)](#integrity-sha-256)) before you run the installer.

### Option A - clone the whole repository

Good if you also want this README and the checksum sidecar file (`.sha256`) on disk.

```bash
git clone https://github.com/U00A3/mainnet.installer.git
cd mainnet.installer
```

The installer file is **`rbn-installer-mainnet-v1.3.15.run`** in that folder.

### Option B - one command: download and verify (`wget`)

It saves **`rbn-installer-mainnet-v1.3.15.run`** in the current folder, then checks the SHA-256 from this README. **Only** the `.run` file is downloaded, not the README or `.sha256` sidecar.

```bash
wget -O 'rbn-installer-mainnet-v1.3.15.run' --show-progress \
  'https://raw.githubusercontent.com/U00A3/mainnet.installer/main/rbn-installer-mainnet-v1.3.15.run' \
  && echo "d0d2d1d234e7fcaa69fe501587e27a1a886827b0703d3fe5bf992f122bf9171c  rbn-installer-mainnet-v1.3.15.run" | sha256sum -c
```

If you see **`rbn-installer-mainnet-v1.3.15.run: OK`**, the file matches the SHA-256.

If verification **fails**, delete the file (`rm -f 'rbn-installer-mainnet-v1.3.15.run'`) before you try again.

## Integrity (SHA-256)

Before you run the installer, the file’s **SHA-256** must match what Redbelly publishes for operators on **official channels**, for example the [Vine developer portal](https://vine.redbelly.network/) (Node Onboarding Resources and related pages) and **Discord** / other operator announcements. The hash below is copied here for convenience; **if it disagrees with an official channel, trust the channel** and treat this README as outdated.

**Expected SHA-256 for `rbn-installer-mainnet-v1.3.15.run`:**

```
d0d2d1d234e7fcaa69fe501587e27a1a886827b0703d3fe5bf992f122bf9171c
```

On **Linux**, compute the hash of the file you have (from the directory where `rbn-installer-mainnet-v1.3.15.run` is):

```bash
sha256sum rbn-installer-mainnet-v1.3.15.run
```

**What you should see** (one line; the first field must match the box above and the official sources):

```
d0d2d1d234e7fcaa69fe501587e27a1a886827b0703d3fe5bf992f122bf9171c  rbn-installer-mainnet-v1.3.15.run
```

To check automatically with GNU `sha256sum`:

```bash
echo "d0d2d1d234e7fcaa69fe501587e27a1a886827b0703d3fe5bf992f122bf9171c  rbn-installer-mainnet-v1.3.15.run" | sha256sum -c
```

**`rbn-installer-mainnet-v1.3.15.run: OK`** means the file matches this README’s hash. If the command reports a failure, **do not run** the installer; remove the file and obtain a fresh copy, then compare again with Vine / Discord / other official operator comms.
