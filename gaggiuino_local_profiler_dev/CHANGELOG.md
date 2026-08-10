## dev-20260810_2021 — 2026-08-10

- Merge pull request #751 from mxkissnr/fix/750-wizard-install-id-reset (9249d8e)
- Fix setup wizard staying suppressed after an add-on data wipe (53984b8)

## dev-20260810_1951 — 2026-08-10

- Merge pull request #749 from mxkissnr/fix/748-wizard-test-connection-closes (67aa094)
- Fix setup wizard closing itself on Test connection, duplicate machine (#748) (dc796c0)

## dev-20260810_1806 — 2026-08-10

- Merge pull request #747 from mxkissnr/fix/746-wizard-trigger-empty-host (afd0656)
- Trim whats-new.js back to MAX_ENTRIES=8 (drop oldest, v2.27.3) (32d9574)
- Fix setup wizard never auto-opening on a real fresh install (#746) (a8c18e4)

## dev-20260810_1750 — 2026-08-10

- Merge pull request #745 from mxkissnr/feature/744-setup-wizard (e0338c8)
- Merge remote-tracking branch 'origin/dev' into feature/744-setup-wizard (b1c3cbd)
- Add guided first-run setup wizard (274e2de)

## dev-20260810_1655 — 2026-08-10

- Push Live view telemetry/preheat and shot counter over SSE (#743) (06bda45)
- Document multi-machine state invariant after third recurrence (823cb03)

## dev-20260810_1554 — 2026-08-10

- Try two SSE hardening techniques against HA Ingress buffering (#741) (0641e85)

## dev-20260810_1515 — 2026-08-10

- Fix SSE sync-progress still updating in blocks over HA Ingress (#739) (185fb51)

## dev-20260810_1503 — 2026-08-10

- Push shot-import progress over SSE, with automatic polling fallback (#737) (93c08ba)

## dev-20260810_1217 — 2026-08-10

- Fix machine settings follow-ups: keep test dialog open, fix stale shot count, catch backgrounded sync toasts (#734) (5e58da7)

## dev-20260810_1141 — 2026-08-10

- Fix machine setup UX follow-ups: sync only on explicit save, progress-bar layout, completion toast (#732) (8f719d0)

## dev-20260810_1116 — 2026-08-10

- Simplify machine test button to save-then-test, sync on every save, add import progress (#730) (657500b)

## dev-20260810_1005 — 2026-08-10

- Stop an out-of-range shot id from wedging default-machine sync forever (#720) (7f37676)

## dev-20260810_1001 — 2026-08-10

- Add "Save & test" combined action to the machine form (#728) (d4910f3)

## dev-20260810_0625 — 2026-08-10

- Trigger an immediate sync on reachability recovery and on machine-config save (#726) (a1aa12a)

## dev-20260810_0559 — 2026-08-10

- Add dev-channel-only raw SQLite DB export endpoint (#724) (adf12db)

## dev-20260810_0550 — 2026-08-10

- Skip permanently-missing (404) shot ids during backfill instead of aborting sync forever (#723) (2d3b95c)

## dev-20260810_0519 — 2026-08-10

- Merge main into dev: resync after v2.31.0 release + post-release CHANGELOG cleanup (93589b9)
- docs: remove personal attribution from CHANGELOG entries (#696) (ae724be)
- Release v2.31.0 (41f6217)
- release: v2.31.0 (0ddc38d)

## dev-20260809_1827 — 2026-08-09

- Allow an empty machine host, skip cleanly instead of a placeholder fallback (c049e11)

## dev-20260809_1808 — 2026-08-09

- Log raw /latest response body from the machine (a62b690)

## dev-20260809_1801 — 2026-08-09

- Log per-shot response time during backfill (e09da76)

## dev-20260809_1728 — 2026-08-09

- Add registry snapshot + full request tracing to debug logging (0a91814)

## dev-20260809_1723 — 2026-08-09

- Fix startup log's Machine URL line to read the registry, not raw options.json (7621f39)

## dev-20260809_1620 — 2026-08-09

- Show dev build tag in the startup log line (507adcf)

## dev-20260809_1534 — 2026-08-09

- Add periodic connectivity summary log for machine host (f5cdd56)

## dev-20260809_1516 — 2026-08-09

- Add debug-gated logging for sync 404s and brew-event flapping (db19341)

## dev-20260809_0923 — 2026-08-09

- Log options.json key set at startup for stale-schema diagnosis (#707) (24de8ea)

## dev-20260809_0836 — 2026-08-09

- ci: decouple dev manifest publish from armv7/aarch64 builds (6c92680)

## dev-20260809_0817 — 2026-08-09

- fix: suppress stable-release update banner on dev builds, show build id in dev banner (aaaf183)
- feat: expose each machine's theme in GET /api/status machines[] (954a40f)
- ci: build armv7 and aarch64 images for the dev channel too (81749ce)

## dev-20260809_0737 — 2026-08-09

- fix: getMachineUrl() always appends /api/shots regardless of input format (91077d0)
- fix: await loadLibrary() before loadData() to fix stale Basket/Puck Screen on first load (34f397c)

## dev-20260808_1545 — 2026-08-08

- fix: wire live pump-flow reading into the live-shot accumulator (24b1570)

## dev-20260808_1540 — 2026-08-08

- fix: bump nanoid to patch GHSA-2v37-7h3g-55p8 DoS vulnerability (4980db6)

## dev-20260808_1533 — 2026-08-08

- feat: deprecate machine_host/switch_entity add-on options (#662) (#697) (5297a84)
- docs: remove personal attribution from CHANGELOG entries (#695) (32ebc66)

## dev-20260807_1040 — 2026-08-07

- chore: firmware-check pagination + grinder-stats dedup (#673, #674) (#694) (d3c993a)

## dev-20260807_1005 — 2026-08-07

- fix: wire autocomplete onto the shot-defaults Grinder field (#692) (893849f)

## dev-20260807_0625 — 2026-08-07

- chore(dev): switch dev build version to a UTC timestamp (#690) (6fd52c3)

## dev-22 — 2026-08-07

- fix: dev-banner overlay + wrong changelog path for GLP DEV updates (#688) (07f40c8)

## dev-21 — 2026-08-07

- feat: on-duration status, edge-swipe drawer, dev-build banner, restore reload (#685) (1056bd1)

## dev-20 — 2026-08-07

- refactor: consolidate resolveMachine()/requireSettingsProxySupport() into their canonical files (#680) (45f96f8)

## dev-19 — 2026-08-07

- fix: allow same-origin camera access so the barcode/QR scanner works (#678) (f79ff6a)

## dev-18 — 2026-08-07

- fix: add SIGTERM/SIGINT handler so add-on stop exits cleanly (#676) (0b59de4)
- docs: document dev-first branch workflow in CLAUDE.md (#672) (db0d708)
- Round 08-06: release-check retry, shot defaults, firmware version check, basket/puck-screen analytics (#669) (225da8a)

## dev-16 — 2026-08-06

- Retry release-existence check to tolerate merge-to-publish gap (3d739e4)

## dev-15 — 2026-08-06

- Merge pull request #664 from mxkissnr/release/v2.30.0 (1f51041)
- Use Array.isArray, not just Buffer.isBuffer, as the CodeQL barrier (#665) (788afc1)
- Add explicit type/format barriers for CodeQL false positives (#665) (e201f9c)
- Release v2.30.0 (93fec89)

## dev-14 — 2026-08-06

- Retry the post-power-on sync a few times instead of a single attempt (#663) (8da82c7)

## dev-13 — 2026-08-06

- Reconcile machine host/switch entity after backup restore (#661) (dbafc14)

## dev-12 — 2026-08-06

- Add time to backup filenames, not just the date (8acdb2d)

## dev-11 — 2026-08-06

- Clear backup modal passphrase fields on close, not just its bundle state (6f74993)

## dev-10 — 2026-08-06

- Fix dev-9 regression: attribute-based file input selector broke on the new accept value (48d5c9e)

## dev-9 — 2026-08-06

- Export backup as a real .zip instead of base64-embedding images in JSON (c2a6a9d)

## dev-8 — 2026-08-06

- Fix Enter key in backup passphrase field; log skipped images in export (935c524)

## dev-7 — 2026-08-05

- Back up shot photos too, by scanning the image directory instead of a hand-maintained entity list (1517cae)
- Show the dev-channel build tag next to the app version, on GLP DEV only (3435b47)

## dev-6 — 2026-08-05

- Give the restore dry-run preview its own rate-limit budget (87700f6)

## dev-5 — 2026-08-05

- Mirror the status dot's tooltip on the rail footer dot too (#655 follow-up) (8ab9be0)
- Fix status dot/Live tab never reflecting machine reachability (#655) (5b8bb42)
- Fix the API-token/MQTT-login checkbox not actually being included in an export (f24f571)

## dev-4 — 2026-08-05

- Log what changed with every dev build (9467130)

