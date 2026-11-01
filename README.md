# Süzgeç rule packs

Signed rule packs for the Süzgeç iOS SMS filter. The app downloads them from GitHub Pages and refuses any pack whose Ed25519 signature doesn't match.

- `v1/pack.json`: the current pack, for schema version 1.
- `v1/pack.json.sig`: the base64 signature of those exact bytes.

This repository holds rules only: no message samples, no code and no keys.
