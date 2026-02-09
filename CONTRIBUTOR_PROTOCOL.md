# Contributor Protocol: Triple-Blind Sync
**Authorized Environment:** Woodfine-Command-Centre

## 🔄 The Cycle Logic
1.  **Transfer:** Push work from the **Woodfine-Command-Centre** to the personal Sandbox (CLI).
2.  **Verify:** Pull the finalized "Gold Copy" from the **PointSav Organization** back to the local environment (CLI).

## 🔒 Security Restrictions
- No direct write access to `pointsav` or `woodfine` organizations.
- All "Ingest" actions must be authorized by the **system-administrator** via the Vendor Manifest.
- Identity isolation is maintained via specific SSH aliases (`github-jwoodfine` / `github-pwoodfine`).
