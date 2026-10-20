# ReditSon Releases

Official public update channel for the ReditSon desktop application.

This repository contains only signed release manifests and compiled release
assets. The application source code, signing private key, license secrets,
and user data are not stored here.

## Update security

- Every `ReditSon.exe` is pinned by exact SHA-256 and file size.
- Every `latest.json` manifest is signed with the ReditSon Ed25519 update key.
- The desktop client accepts downloads only from this repository.
- The license server separately authorizes the exact executable build hash.
