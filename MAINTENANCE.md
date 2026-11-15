# Antigravity maintenance

Upstream: https://github.com/trustybird/AvenCores-open-antigravity-patcher
Baseline commit: b59258fbc2f4c397e3b752c5a9033b5185bd9641

## Verified baseline (2026-11-15)
- Windows x64, Antigravity 2.32.1.
- Manager patch applied; status verified as patched; unchanged file size and five changed bytes.
- User confirmed the application works after restart.
- Original binary remains beside the installed binary as language_server.exe.agybak.

## Maintenance procedure
1. Check installed version and patch status before changing anything.
2. Review upstream changes before applying them; do not execute downloaded updates automatically.
3. Preserve version-specific backups and SHA-256 hashes outside the repository.
4. Close the application only when no user task is running.
5. Reject missing or ambiguous patch signatures. Verify the resulting bytes and file size.
6. Restart and verify login plus a real model response separately.
7. Restore only a backup belonging to the same application build. Otherwise reinstall the matching official build.

Do not upload credentials, tokens, application data, binaries or backup files.
OAuth EOF is a connection error; server-side entitlement and quota errors need separate diagnosis.
Maintenance is on request; no background monitoring or automatic patching has been configured.
