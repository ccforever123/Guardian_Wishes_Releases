# Guardian Wishes Releases

Public distribution repository for Guardian Wishes. Application source code is maintained in a separate private repository.

- `web-*` releases contain **AES-256-GCM encrypted** server deployment packages and SHA-256 checksums. A separately provisioned private key is required to deploy.
- `android-*` releases contain signed Android APKs and a version/checksum manifest. APKs are publicly downloadable.
- Release assets are versioned; existing assets are never overwritten.
- Do not upload credentials, databases, signing keys, unencrypted server bundles or source maps here.
