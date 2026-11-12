# botwork-cloud-server-dist

Public distribution repository for prebuilt `botwork-cloud-server` binaries.

This repo contains **only GitHub Releases** (binary assets + sha256). Source code lives in the private `lai-tan/botwork-cloud-server` repo and is not open-sourced.

## Assets

Each release (tagged `cloud-server-vX.Y.Z`) ships:

- `botwork-cloud-server-aarch64-unknown-linux-gnu.tar.gz` + `.sha256`
- `botwork-cloud-server-x86_64-unknown-linux-gnu.tar.gz` + `.sha256`

The device-side installer (`install-cloud-server.sh`) downloads from here anonymously and verifies sha256 before extracting.