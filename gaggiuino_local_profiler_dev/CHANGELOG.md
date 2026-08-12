## dev-20260812_1501 — 2026-08-12

- fix(dev-channel): sync options/schema into the dev manifest's config.yaml (#806) (8679840)

## dev-20260811_1919 — 2026-08-11

- Add expose_api_port option to close the token endpoint to the LAN (#804) (51faa32)

## dev-20260811_1841 — 2026-08-11

- fix: match X-Ingress-Path by prefix, not by pinned add-on slug (#802) (395c082)

## dev-20260811_1805 — 2026-08-11

- perf: lazy-load echarts/topojson-client/qrcode behind dynamic import() (#799) (f153ecb)

## dev-20260811_1801 — 2026-08-11

- test: add Playwright E2E smoke test on top of the screenshots harness (#798) (#800) (b5eb8a1)

## dev-20260811_1710 — 2026-08-11

- perf: split vendor libraries into separate chunks (#795) (#796) (8f13a79)
- fix: bundle Figtree locally instead of loading from fonts.bunny.net (#793) (#794) (c315be6)
- fix: resolve bag-scoped consumption with the same rule as remaining stock (#788) (#792) (6a66a9e)

## dev-20260811_1638 — 2026-08-11

- ci: sync apparmor.txt into the dev manifest repo (#790) (c9fa589)

## dev-20260811_1631 — 2026-08-11

- Add AppArmor profile for the add-on (needs complain-mode validation) (#787) (0deca1b)

## dev-20260811_1527 — 2026-08-11

- Hardening: bean-math parity test, apparmor.txt, coverage gate refresh, drop dead root lib/ (#786) (d58b239)

## dev-20260811_1338 — 2026-08-11

- chore: CI/build config hygiene — dependabot grouping, stale comment, dead root manifest (#781) (18e781e)

## dev-20260811_1233 — 2026-08-11

- fix: push LIVE_SNAPSHOT immediately on transport arrival, not just the 1s tick (df553bd)

## dev-20260811_1056 — 2026-08-11

- fix: remove redundant sidebar shot count, reorder flap counter before label (#777) (f3ba5a5)

## dev-20260811_1027 — 2026-08-11

- fix: theme swatch gradient clipping and overlapping sync-progress race (#774) (01d414f)

## dev-20260811_0833 — 2026-08-11

- chore: add local Docker smoke test for standalone install (#771) (3ba35c4)

## dev-20260811_0753 — 2026-08-11

- Bump the dev-dependencies group (#766) (6ae7f80)
- Bump better-sqlite3 from 13.0.2 to 13.0.3 in /gaggiuino-local-profiler (#767) (a7172b7)
- Bump express-rate-limit from 8.6.1 to 8.6.2 in /gaggiuino-local-profiler (#768) (023c0e1)
- Bump ws from 8.21.1 to 8.21.3 in /gaggiuino-local-profiler (#769) (1cd1856)

## dev-20260811_0722 — 2026-08-11

- feat: standalone Docker install support (Unraid, TrueNAS, HA Container) (#765) (6997c1c)
- Merge main into dev: resync after CHANGELOG duplicate-content fix (0d11f94)
- Merge pull request #763 from mxkissnr/fix/changelog-duplicate-content (db9263a)
- fix: remove duplicated full-detail block left over in CHANGELOG.md's v2.32.0 entry (02092f3)
- fix: remove duplicated full-detail block left over in CHANGELOG.md's v2.32.0 entry (0564055)
- Merge main into dev: resync after v2.32.0 release + CHANGELOG condense fix (3f5ad5d)
- Merge pull request #762 from mxkissnr/docs/760-changelog-condense-2.32.0 (4c25de9)
- docs: condense CHANGELOG.md's v2.32.0 entry, adopt short-entry convention (2a7219d)

## dev-20260811_0633 — 2026-08-11

- Merge pull request #761 from mxkissnr/fix/760-codeql-xss-suppression (d82845b)
- chore: add CodeQL in-source suppression comments for verified false positives (#760) (96c0834)

## dev-20260811_0615 — 2026-08-11

- Merge pull request #759 from mxkissnr/release/v2.32.0 (99a0593)
- fix: restore whats-new.js release history lost during dev-cycle squash (d4a1934)
- fix: use hostname parsing instead of substring match in GitHub API fetch stub (75c0453)
- release: v2.32.0 (8e5e12c)

## dev-20260810_2111 — 2026-08-10

- Fix syncInstallId() never actually firing on its first run (#758) (366f9ac)

## dev-20260810_2054 — 2026-08-10

- Merge pull request #756 from mxkissnr/feature/755-raw-db-import (801b4b7)
- Fix CodeQL type-confusion false positive in import-db route (b810356)
- Add raw database import counterpart to the dev-only DB export (6d93df2)

## dev-20260810_2037 — 2026-08-10

- Merge pull request #754 from mxkissnr/feature/753-machine-default-delete (8269a23)
- Allow changing the default machine and deleting any machine (76ede8d)

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

