## dev-20260930_2024 — 2026-09-30

- Merge pull request #1265 from mxkissnr/ppops/1200-p2a-remove-the-never-publ-1790798274 (541bbbe)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/1200-p2a-remove-the-never-publ-1790798274 (d2d287b)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/1200-p2a-remove-the-never-publ-1790798274 (00a5c67)
- Part of #1200: drop the CHANGELOG entry for the internal-only change (ca413fc)
- Part of #1200: add CHANGELOG entry for the SSE sync event constant removal (ed61839)
- Part of #1200: remove the never-published SSE sync event constants (Go side) (cad1839)

## dev-20260930_2017 — 2026-09-30

- Merge pull request #1264 from mxkissnr/ppops/1262-upgrade-typescript-to-603-1790798066 (362f2af)
- Part of #1102, for #1262: keep the style.css scan test under its timeout (a5e7fcd)
- Part of #1102, for #1262 (d9caae8)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/1262-upgrade-typescript-to-603-1790798066 (0091dba)
- Part of #1102, for #1262: drop the CHANGELOG entry (dev tooling only) (33f5211)
- Part of #1102, for #1262: add CHANGELOG entry for the TypeScript 6 upgrade (9f7f08e)
- Part of #1102, for #1262: upgrade TypeScript 5.9.3 -> 6.0.3 (0aeebe3)

## dev-20260930_1959 — 2026-09-30

- Merge pull request #1263 from mxkissnr/ppops/c4-remove-the-last-domain-type-1790797467 (dd3ce3a)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/c4-remove-the-last-domain-type-1790797467 (8b6c216)
- changelog: drop the cast-cleanup note to match the plan (Part of #1102) (1922a53)
- changelog: note the last unknown-cast cleanups (Part of #1102) (0ff15c2)
- Merge pull request #1261 from mxkissnr/ppops/d1-update-claudemd-and-docs-fo-1790796520 (3a52cb7)
- views: type bean lookups with the API Bean; drop the timer cast (Part of #1102) (7c4868f)
- shots: drop as-unknown-as casts in the library lookup and annotation save (Part of #1102) (7bae91e)
- state: type machine power state and registry with the API shapes (Part of #1102) (93752f6)
- docs: plan-named whats-new.ts needs no edit; DOCS references already point at it (004418e)
- Merge branch 'dev' into ppops/d1-update-claudemd-and-docs-fo-1790796520 (674de86)
- Part of #1102 (668bc47)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/d1-update-claudemd-and-docs-fo-1790796520 (357ac32)
- docs: point the last five frontend `.js` references at their `.ts` files (237d033)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/d1-update-claudemd-and-docs-fo-1790796520 (88fd143)
- docs: spell out the service-worker path in the frontend bullet (27d3068)
- docs: name the service worker by its real source path in CLAUDE.md (9daeaad)
- docs: align CLAUDE.md and CONTRIBUTING.md with the TypeScript frontend (e0499cb)

## dev-20260930_1943 — 2026-09-30

- Merge pull request #1260 from mxkissnr/ppops/c3-remove-as-unknown-as-casts-1790796004 (7c39e4a)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/c3-remove-as-unknown-as-casts-1790796004 (66567fa)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/c3-remove-as-unknown-as-casts-1790796004 (403c7a0)
- changelog: drop internal cast-cleanup entry (Part of #1102) (683c4b5)
- docs: add CHANGELOG entry for the cast cleanup (Part of #1102) (b1f25c3)
- views: drop redundant calcBrewRatio argument cast in dialin-wizard (Part of #1102) (8509400)
- views: drop remaining as-unknown-as casts in wizard/shot helpers (Part of #1102) (8accb20)
- library: drop as-unknown-as casts from bags/import/milk/recipes (Part of #1102) (09c7adc)

## dev-20260930_1936 — 2026-09-30

- Merge pull request #1259 from mxkissnr/ppops/x1-break-the-machines-settings-1790796012 (22f31dd)
- Merge branch 'dev' into ppops/x1-break-the-machines-settings-1790796012 (eef6de5)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/x1-break-the-machines-settings-1790796012 (514ded4)
- #1102 X1: CHANGELOG entry for the import-cycle fix (Part of #1102) (5d67f09)
- #1102 X1: break machines-settings -> status -> setup-wizard import cycle (Part of #1102) (f6173d1)

## dev-20260930_1931 — 2026-09-30

- Merge pull request #1258 from mxkissnr/ppops/1104-l1-eslint-error-rule-for-1790794057 (ff5363a)
- Merge branch 'dev' into ppops/1104-l1-eslint-error-rule-for-1790794057 (1023064)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/1104-l1-eslint-error-rule-for-1790794057 (186292f)
- #1104 L1: cover the sink shapes the review named in the fixture (69622d6)
- #1104 L1: fix the html-sink test's marker matching and simplify the rule (4a543d1)
- #1104 L1: lint the fixture through the real ESLint config in the rule test (fc3ced3)
- #1104 L1: declare node:module in the test builtins shim (bc6238a)
- #1104 L1: load the test's TS parser without a static dependency edge (4d88ca1)
- #1104 L1: add the typed html-sink lint rule test and fixture (bdaa7f4)
- #1104 L1: type-check the Html brand at innerHTML sinks instead of matching syntax (efe8c04)
- #1104 L1: add CHANGELOG entry for the innerHTML lint rule (4ae4961)
- #1104 L1: reject unescaped innerHTML/outerHTML/insertAdjacentHTML in ESLint (f03d48e)

## dev-20260930_1924 — 2026-09-30

- Merge pull request #1257 from mxkissnr/ppops/1105-n6-fix-the-last-five-src-1790795382 (7d31b59)
- #1105 N6: add the CHANGELOG entry for the indexed-access slice (Part of #1105) (d07206a)
- #1105 N6: enable noUncheckedIndexedAccess in tsconfig (Part of #1105) (2b39772)
- Merge branch 'dev' into ppops/1105-n6-fix-the-last-five-src-1790795382 (5924afb)
- #1105 N6: noUncheckedIndexedAccess in library and shots/annotation (Part of #1105) (1785eb6)
- #1105 N6: noUncheckedIndexedAccess in constants/image-crop/machines-settings (Part of #1105) (1dea030)

## dev-20260930_1913 — 2026-09-30

- Merge pull request #1256 from mxkissnr/ppops/1105-t4-nouncheckedindexedacce-1790793550 (1c162be)
- Merge branch 'dev' into ppops/1105-t4-nouncheckedindexedacce-1790793550 (d2c0ed3)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/1105-t4-nouncheckedindexedacce-1790793550 (1a52689)
- #1105 T4: noUncheckedIndexedAccess in the remaining tiny test files (Part of #1105) (1d095c0)
- #1105 T4: noUncheckedIndexedAccess in tiny test files (Part of #1105) (e4f6aaa)

## dev-20260930_1907 — 2026-09-30

- Merge pull request #1255 from mxkissnr/ppops/1105-t5-nouncheckedindexedacce-1790793612 (6e01e85)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/1105-t5-nouncheckedindexedacce-1790793612 (c6ad603)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/1105-t5-nouncheckedindexedacce-1790793612 (cf653c4)
- #1105 T5: noUncheckedIndexedAccess in the last four test files (Part of #1105) (8a159c8)

## dev-20260930_1902 — 2026-09-30

- Merge pull request #1254 from mxkissnr/ppops/1105-t3-nouncheckedindexedacce-1790793305 (f373320)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/1105-t3-nouncheckedindexedacce-1790793305 (79cf689)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/1105-t3-nouncheckedindexedacce-1790793305 (29a2e87)
- #1105 T3: noUncheckedIndexedAccess in eight small test files (d00635e)

## dev-20260930_1857 — 2026-09-30

- Merge pull request #1253 from mxkissnr/ppops/1105-t2-nouncheckedindexedacce-1790793079 (f3b8013)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/1105-t2-nouncheckedindexedacce-1790793079 (cc259c4)
- Part of #1105: guard indexed access in remaining four mid-size test files (e4bd5a0)
- Part of #1105: guard indexed access in four mid-size test files (31c2892)

## dev-20260930_1850 — 2026-09-30

- Merge pull request #1252 from mxkissnr/ppops/1105-t1-nouncheckedindexedacce-1790792858 (3ee9bbf)
- Merge branch 'dev' into ppops/1105-t1-nouncheckedindexedacce-1790792858 (f1c3f60)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/1105-t1-nouncheckedindexedacce-1790792858 (05d197c)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/1105-t1-nouncheckedindexedacce-1790792858 (32233b3)
- Part of #1105: noUncheckedIndexedAccess in the other four test files (T1) (0db1daf)
- Part of #1105: noUncheckedIndexedAccess in four test files (T1) (b6b9ba0)

## dev-20260930_1843 — 2026-09-30

- #1105 N5: noUncheckedIndexedAccess in the last seven small src files… (#1251) (5dd0cd2)

## dev-20260930_1836 — 2026-09-30

- #1105 N4: noUncheckedIndexedAccess in eight small src files (Part of… (#1250) (85d4d0b)

## dev-20260930_1829 — 2026-09-30

- #1105 N3: noUncheckedIndexedAccess in image-crop, grind, score, shots,… (#1249) (96e6457)

## dev-20260930_1813 — 2026-09-30

- #1104 V6: Html branding in library.ts and annotation.ts, drop… (#1248) (5ffb5d5)

## dev-20260930_1752 — 2026-09-30

- #1103 S5: sync dev, fix type error, open PR (Part of #1103) (#1247) (bf19e9e)
- #1104 V5: Html branding in shots/index, main and i18n (Part of #1104) (#1246) (a87f36c)

## dev-20260930_1744 — 2026-09-30

- #1104 V4: Html branding in the analytics view (#1245) (88699c0)

## dev-20260930_1729 — 2026-09-30

- #1104 V3: Html branding in orders, dial-in wizard and machine settings (#1244) (30db2d2)

## dev-20260930_1605 — 2026-09-30

- Add v3.2.0 What's New entry and test that it tracks the release version (#1243) (3c82054)

## dev-20260930_1554 — 2026-09-30

- #1104 V2: Html branding in the remaining small views (Part of #1104) (#1242) (e8d8078)

## dev-20260930_1523 — 2026-09-30

- #1104 V1: Html branding in library sub-views and profile editors (#1238) (eabd387)

## dev-20260930_1503 — 2026-09-30

- TS cleanup C1: remove avoidable as-unknown-as casts (Part of #1105) (#1237) (44a98c7)

## dev-20260930_0601 — 2026-09-30

- chore(ts): drop avoidable "as unknown as" casts in library/live/shot-defaults (#1235) (bae9b83)

## dev-20260930_0555 — 2026-09-30

- chore: brand innerHTML assignments in components/ with Html (first slice) (#1236) (abbfceb)

## dev-20260930_0542 — 2026-09-30

- Show the selected machine's on/off state in the top bar icon (#1234) (b4df058)
- main.ts TS slice M2: type-checked lint for main.ts, CHANGELOG, open PR… (#1233) (cfa12ff)

## dev-20260930_0528 — 2026-09-30

- OpenAPI route contract test without reflect/unsafe (Part of #1103,… (#1232) (e40f6fe)

## dev-20260929_1648 — 2026-09-29

- TypeScript migration: port the coffee library view (library.js) to TS (#1231) (f5eb784)

## dev-20260929_1559 — 2026-09-29

- Merge pull request #1229 from mxkissnr/feat/exact-optional-props-1105 (592c933)
- Enable exactOptionalPropertyTypes in tsconfig (9d7edf0)

## dev-20260929_1555 — 2026-09-29

- Merge pull request #1228 from mxkissnr/feat/library-tests-ts-1133 (2a4af18)
- test: convert five library Vitest files to TypeScript (24d8be3)

## dev-20260929_1545 — 2026-09-29

- Merge pull request #1204 from mxkissnr/renovate/go-dependencies (7ff4c1a)
- fix(deps): update go-dependencies (b576fe4)

## dev-20260929_1539 — 2026-09-29

- Merge pull request #1227 from mxkissnr/ppops/typescript-migration-port-view-1790694615 (962293b)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/typescript-migration-port-view-1790694615 (8ab14ac)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/typescript-migration-port-view-1790694615 (9925e3a)
- fix: drop unnecessary non-null assertions in the GaggiMate editor handler (1efa866)
- fix: annotate the GaggiMate phase transition fallback for strict tsc (6b2a14a)
- refactor: finish the GaggiMate profile editor TypeScript port; escape machine values (a286217)
- refactor: port the GaggiMate profile editor view to TypeScript (WIP) (22c6927)

## dev-20260929_1533 — 2026-09-29

- Merge pull request #1226 from mxkissnr/ppops/bean-dropdown-uses-server-rema-1790694819 (c6fae44)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/bean-dropdown-uses-server-rema-1790694819 (6c18bed)
- test: cover bean picker classification from server remainingG (#1225) (a53acbc)
- fix: bean dropdown uses the server-computed remaining stock (#1225) (ddbea3c)

## dev-20260929_1527 — 2026-09-29

- Merge pull request #1224 from mxkissnr/ppops/typescript-migration-port-view-1790693843 (2be30e2)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/typescript-migration-port-view-1790693843 (5dd096a)
- docs: note why the plan's reference paths are unchanged by the live port (1f6137d)
- test: drop redundant assertions and async-without-await in the live port (342807c)
- test: type the live chart callbacks and mocks for strict tsc (5b7e9cc)
- test: port the live view and its five tests to TypeScript (dd945c1)

## dev-20260929_1511 — 2026-09-29

- Merge pull request #1223 from mxkissnr/ppops/port-1122-bean-bag-queue (26410a1)
- revert: drop CHANGELOG entry for the internal types regeneration (#1122) (afd4a3f)
- docs: add CHANGELOG entry for the bean bag queue API types fix (#1122) (35704af)
- fix: regenerate schema.gen.ts for ThawPortionInput (#1122) (0a1ad21)
- Merge remote-tracking branch 'origin/dev' into sync/ppops/port-1122-bean-bag-queue (68d2246)
- docs: record the bean bag queue and describe it in the library docs (e579db9)
- refactor: type the bag and reorder API from the generated spec (f595ecf)
- fix: reject unknown bag ids on reorder with 400 and test the queue (90648d1)
- test: pin bean remaining with one shared Go/JS fixture (93ecf55)
- fix: wire the Past bags toggle into the click dispatcher (91092ec)
- fix: address second review round on the bean bag queue port (9e348a9)
- fix: address review on the bean bag queue port (8545a24)
- chore: record the #1122 bean bag queue port and add its CHANGELOG entry (15d3e6b)
- fix: address bean-bag-queue review — remaining consistency, reorder validation, newBag sync (328c1e7)
- fix: use typed API for bag PUT/reorder/toggle-active, fix gofmt and race-condition lint findings (aeeb229)
- fix: validateBagFloatField rejected an explicit JSON null instead of clearing the field (01d6043)
- fix: register missing PUT /api/library/bean/{id}/bag/{bagId} route (0e9dd7f)
- fix: bag edit pencil button did nothing (56de181)
- fix: 'Speichern und Packung hinzufügen' silently did nothing (4a91ecb)
- fix: review findings in bean-bag-queue (updateBag sync, validateBagFloatField, writeEnrichedBean) (8ec1c92)
- fix: remove dead toggleBagHistory references crashing app load (7888f0e)
- fix: add missing bag validation helpers and pending-toggle tracking (41b7b9d)
- feat: add bean bag queue tracking (913ae6c)

## dev-20260929_0529 — 2026-09-29

- test: assert the newer profile body survives a stale ReplaceRemoteID (c46e079)
- fix: persist the profile remote id on create and share the per-machine lock (08b9925)
- fix: type the offline-save response in the profile editor (09e925f)
- fix: serialize concurrent profile pushes per machine, guard against lost updates (e4ddf03)
- fix: remove bean-bag-queue fields accidentally pulled into openapi.yaml (414e2b6)
- fix: bound live profile fetches so the offline cache fallback isn't starved by a hung DNS lookup (055833b)
- feat: save machine profiles locally (44e8a92)
- Fix #1201: machine poll state per machine (#1221) (dcd3ec2)

## dev-20260928_1706 — 2026-09-28

- fix: use a Dutch label for the live setup toggle in nl.ts (e7bc5da)
- docs: document the live shot setup panel and correct its CHANGELOG line (4df271e)
- chore: record the #1120 port provenance and address the process-gap flags (4ef3217)
- fix: limit the live shot setup draft to finished brews (6c1e00b)
- chore: type the ported live-shot-setup grinder helpers for annotation.ts (3cc2735)
- fix: address live-shot-setup review — machine-scoped shot pick, minimal payload, defaults-safe apply (ab477f9)
- fix: use typed annotateShot API, remove undefined apiFetch call (c3e3361)
- fix: add missing grinder select-with-other helpers (8a5c25d)
- feat: add live shot setup panel (1bd6f62)

## dev-20260928_1645 — 2026-09-28

- Fix #1057: write the API token file with mode 0600 (#1219) (782a215)

## dev-20260928_1625 — 2026-09-28

- Concurrency: lost library updates and double order completion (#1218) (54e3807)

## dev-20260928_1605 — 2026-09-28

- Fix #1199 slice 3: library HTTP handlers via repo.Update (#1217) (9f67f92)
- Dev-stats charts: full width, light/dark variants, meaningful colours (#1215) (40a57ad)

## dev-20260928_1543 — 2026-09-28

- Fix #1199 slice 2: Create/Update library functions via repo.Update (#1216) (b35d30b)

## dev-20260928_1529 — 2026-09-28

- Audit fixes: order-shot matching, sync blocklist, firmware cache, backup/restore gaps (#1214) (d64b4e7)

## dev-20260928_1517 — 2026-09-28

- Fix #1199 part 1 slice 1: serialise library read-modify-write via… (#1211) (d9df0a9)
- docs(readme): tidy architecture diagrams, add MCP endpoint (#1213) (75baad1)

## dev-20260928_1507 — 2026-09-28

- Dev-stats charts: full width, light/dark variants, meaningful colours (#1212) (e836083)
- chore(deps): update dev-dependencies (#1203) (cac0ccb)

## dev-20260928_1449 — 2026-09-28

- Fix #1197 part A: order-shot time check, transient 404 on newest shot,… (#1209) (3a53d87)

## dev-20260927_1844 — 2026-09-27

- feat: built-in MCP server for shot history, library and analytics (#1208) (c75558c)

## dev-20260927_1738 — 2026-09-27

- demo: interactive GLP web UI demo on GitHub Pages (#1206) (665ab27)

## dev-20260927_1345 — 2026-09-27

- Server-side shot score ignores the bean target (#1202) (6fdf47c)

## dev-20260927_0828 — 2026-09-27

- fix(dev-stats): stack README charts and drop equal-height padding (#1195) (941335d)
- docs: route the cards through the integration proxy in the README diagram (#1192) (50f2501)

## dev-20260927_0755 — 2026-09-27

- docs: refresh screenshots from a sanitized real backup (#1190) (c6c9470)

## dev-20260927_0750 — 2026-09-27

- screenshots: keep seeded orders/live views in backup mode, report restored photos (#1188) (ae8d471)

## dev-20260926_2215 — 2026-09-26

- docs: readable coloured architecture diagrams, aligned dev-stats, updated AI note (#1186) (853d936)
- docs: slim down go/README.md, move migration history to docs/history (#1187) (f999874)

## dev-20260926_1753 — 2026-09-26

- screenshots: optional backup restore instead of seed data (#1183) (1ac9536)
- docs: present Shot Card and Order Card as part of GLP Integration (#1182) (7eb59b6)
- docs: Mermaid architecture diagrams, DOCS architecture fixes, README polish (#1178) (6a444c1)

## dev-20260926_1424 — 2026-09-26

- Treat ppops-oh as internal in close-dev-issues (#1175) (1747eb3)

## dev-20260926_1416 — 2026-09-26

- Merge pull request #1173 from mxkissnr/ppops/firmware-update-maintenance-lo-1790430104 (721d2d7)
- Add changelog entry and issue reference for firmware update maintenance log (f93682a)
- Record from/to firmware version and shot count in firmware update log (0480d17)

## dev-20260926_1312 — 2026-09-26

- Merge pull request #1171 from mxkissnr/sync/v3.2.0-to-dev (b009d7b)
- Sync main into dev after v3.2.0 release (7e2740d)
- Release v3.2.0 (#1168) (a7f7d23)
- Merge pull request #1099 from mxkissnr/release/v3.1.0 (c1d687b)
- Remove duplicate test after main resync merge (b802758)
- Merge remote-tracking branch 'origin/main' into release/v3.1.0 (653ab03)
- Regenerate screenshots/dev-stats after What's New trim (ffdde8e)
- Trim in-app What's New to MAX_ENTRIES after adding v3.1.0 (027e33a)
- Release v3.1.0: bump version, retitle CHANGELOG, regenerate docs (c05bfde)
- chore(deps): update docker/build-push-action digest to c3c9e26 (#1092) (a8d4713)
- chore(deps): update docker/setup-buildx-action digest to f87e599 (#1093) (1e6f671)
- chore(deps): update docker/setup-qemu-action digest to 9901266 (#1094) (4a3bcfc)
- chore(deps): update dev-dependencies to v5.0.1 (#1095) (85e3393)
- fix(deps): update module modernc.org/sqlite to v1.59.0 (#1096) (d66b986)
- chore(deps): update actions/github-script action to v9 (#1097) (5a727f5)
- fix(ui): name the firmware component in the update progress label (#1088) (0b34d57)
- ci: close issues referenced by PRs merged into dev (#1089) (dd9b5c7)
- fix: record the AppArmor profile's completed complain-mode validation (#1084) (45903c0)
- fix: describe the AppArmor profile as shipped and unvalidated (#1078) (8da0af6)
- chore: ignore .graphify_root symlink (#1082) (162c03b)
- build(frontend): bundle the SPA from Go with esbuild, drop the Node stage (#1080) (01137df)
- fix(deps): update go-dependencies (#1069) (d52e508)
- Migrate off deprecated nhooyr.io/websocket to coder/websocket (#1076) (cd61de7)
- Add per-route rate limits to GET /api/backup and image uploads (#1075) (4887d2c)
- fix: correct false claim in Go builder Dockerfile comment (#1074) (bc238b2)
- fix: guard SSRF-exposed HTTP clients, fix dev-only route gate, pin builder digest (#1072) (820aabd)
- Release v3.0.2 (#1041) (#1073) (69a71e0)
- fix: allow explicitly clearing a stored MQTT broker password (#1071) (4c00850)
- chore(deps): update docker/setup-qemu-action digest to 1f40c72 (#1064) (ef95881)
- chore(deps): update github/codeql-action digest to b96794f (#1065) (4669f33)
- chore(deps): update alpine docker tag to v3.24 (#1066) (9bd77bd)
- chore(deps): update golang docker tag to v1.27 (#1068) (15a1ff9)
- chore(deps): lock file maintenance (#1070) (ac76a9d)
- chore(deps): update dependency vite to v8.3.0 (#1067) (54c2504)
- Escape world-map tooltip names and consolidate HTML-escaping helpers (#1059) (dd66853)
- Move Gaggiuino firmware update status/trigger onto the machines list row (#1047) (b537d5d)
- Add Gaggiuino firmware update UI and release-channel selector (#1045) (e6501ff)
- fix(go): log and fast-retry a silent firmware-release match miss (#1043) (4929e47)
- Release v3.0.2 (#1041) (d63a22f)
- docs: "app" terminology, trimmed armv7 note, README screenshot grid, machine valve fields (#1040) (7fe9efa)
- fix: machine firmware check degrades gracefully when GitHub is unreachable (#1038) (d0b2d59)
- Merge remote-tracking branch 'origin/main' into dev (efe5659)
- Release v3.0.1 (#1036) (fe6fa8b)
- Fix README screenshots, bump to Node 24, dev-stats SVG charts (#1035) (7a784bc)
- Resync dev with main after v3.0.0 release (de04591)
- Merge pull request #1030 from mxkissnr/release/v3.0.0 (4aabcf4)
- Release v3.0.0 (5c34e3e)
- Remove the legacy Node.js backend (Go-only for 3.0.0) (#1029) (ff18bc3)
- Merge pull request #1026 from mxkissnr/cutover/977-go-backend-flip (137ea62)
- Fix 7th round of code review findings on #977 backend cutover (9e07ccf)
- Fix 6th round of code review findings on #977 backend cutover (2243be0)
- Fix 5th round of code review findings on #977 backend cutover (df79ef0)
- Fix code review findings on #977 backend cutover (chown handling, config dedup) (4th review pass) (77efdec)
- Finish 3rd review-pass fixes (previous commit missed the modified files) (3fb6183)
- Atomic marker-based DB backup, cache registry debug check, drop dead go/ files (3rd review pass) (74729d4)
- Multi-arch docker-smoke, needs:go-test, required-checks fix (2nd review pass) (bdaf173)
- Fix code review findings on #977 backend cutover (WAL backup, CI smoke test, dedup) (fb9fdb2)
- Wire debug_logging, delete obsolete Go CI workflows, harden AppArmor notice (#977 follow-up) (4d463fa)
- Cutover production image to the Go backend (#977) (2d1c4a5)
- Merge pull request #1025 from mxkissnr/fix/1024-worldmap-light-theme (e7a79db)
- fix: resolve bean-label text-outline halo from theme too (484185e)
- fix: resolve world map colors from the active theme instead of dark literals (b297e39)
- Merge pull request #1023 from mxkissnr/fix/1021-accent-ink-contrast-audit (4cf4a1a)
- fix: sync DOCS.md wording, trim verbose CHANGELOG entry, drop redundant accent apply call (8dc5787)
- fix: light-theme --accent-ink contrast audit for the 8 THEME_PRESETS (ca7e56b)
- Merge pull request #1022 from mxkissnr/feat/1019-unify-accent-theme-presets (8f1ddb8)
- fix: remove dead unreachable-accent-clear branch in applyActiveMachineAccentTheme (74a1aed)
- feat: unify accent theme picker with the 8 named machine theme presets (fc52b49)
- fix: theme toggle active state + add Auto (system) option (#1020) (d3162a6)
- fix: detect mid-session SSE staleness, not just first-connect failure (#1017) (f1aa5fb)
- Merge pull request #1015 from mxkissnr/chore/go-preview-trigger-dev (3e2b654)
- chore(ci): trigger go-preview-publish from dev instead of go-migration (188f3f3)
- Merge pull request #1014 from mxkissnr/fix/codeql-alerts-94-95-96-98-100 (feebc6f)
- fix: resolve 5 pre-existing CodeQL alerts (#94, #95, #96, #98, #100) (4757b31)
- Merge pull request #1012 from mxkissnr/sync/dev-into-go-migration-0907 (7aae0f0)
- Merge remote-tracking branch 'origin/dev' into sync/dev-into-go-migration-0907 (6ae208b)
- docs: fix outdated 'Install via HACS' wording for bundled cards (#1008) (2b62d07)
- fix: resync package-lock.json to fix npm ci in CI (#1010) (b220306)
- chore(deps): lock file maintenance (#1006) (71cc1da)
- chore(deps): update dev-dependencies to v5 (#1005) (6fd7683)
- chore(deps): update docker/setup-qemu-action digest to 1f40c72 (#1003) (3a1e763)
- chore(deps): update dev-dependencies (#1004) (2bd7a90)
- Feature/gaggimate profile editor (#996) (d05f594)
- docs(go): preserve SQLite driver spike decision doc (#958) (#1002) (d4d51cc)
- Security audit #977 round 3 follow-up: govulncheck gate (#998) + dedicated rate limits (#999) (#1001) (2f813cb)
- fix(go): security audit #977 round 3 — DB guard, toolchain pin, Docker digests (#1000) (3fb92a6)
- fix(go): GaggiMate parser hardening — index.bin cap, sampleSize floor, panic recovery (#994) (64b7285)
- fix(go): SSRF hardening round — reconnect revalidation, DNS-rebinding pin, MQTT guard, registry-facade doc (#990) (f5e8599)
- docs: fix uneven screenshot grid in README (#985) (d193d9a)
- docs: fix uneven screenshot grid in README (bda1c8f)
- feat(go): surface descale operation mode as isDescaling in MachineStatus/SSE (#984) (a2f5346)
- Revert "fix: record sync error on unreachable GaggiMate history + float-tolerant wl parsing" (51343bc)
- fix: record sync error on unreachable GaggiMate history + float-tolerant wl parsing (76afac3)
- style: gofmt four files flagged by CI (553cfaf)
- Merge branch 'mxkissnr:go-migration' into go-migration (9cff22a)
- fix(go): scale card-render pool with GOMAXPROCS instead of fixed size 2 (#982) (01777ab)
- docs(readme): update GaggiMate feature row — water sensor, weight label (e743923)
- fix: stop achievement re-evaluation storm from hanging bulk restore (#979) (7747a8f)
- docs: update GaggiMate capabilities — water sensor, weight label (c0af6dc)
- fix(ui): hide Live-Verbindung settings card for GaggiMate (3748026)
- perf(sidebar): debounce shot search input (#976) (117afd3)
- perf(sidebar): debounce shot search input (#975) (8f98c63)
- ci(go-preview): rebuild image on any non-doc push to go-migration (#974) (973367d)
- perf: lazy-build collapsed month groups + index sidebar search by id (#969) (#970) (#972) (51ab6a3)
- perf(go): throttle sidebar rebuild during background shot-meta walk (#969) (#971) (0792d7a)
- perf: lazy-build collapsed month groups + index sidebar search by id (#969) (#970) (6087de8)
- fix(ui): distinguish real vs estimated weight in shot chart (e33f12d)
- feat(ui): add water sensor setting and idle water level display (e6f17c0)
- fix(go/system): gate GaggiMate wl field on has_water_sensor (e116bbe)
- feat(go/machines): add has_water_sensor flag to machine model (5afc8e7)
- feat(go/machines): add GaggiMate binary shot-history sync (0fd094d)
- fix(go): report shots present in the streamed zip restore preview (#968) (d6c5b08)
- fix: build annotation library <select>s via DOM API, not innerHTML (#966) (801ca0b)
- feat: progress bars for backup/restore and dev-channel DB transfers (#960) (#965) (e3e6a67)
- feat(go): optimize stored entity images — downscale, strip EXIF, thumbnails (#961) (#964) (2ac18ec)
- ci: run the Go gate on pull requests, not just go-migration pushes (7f240f7)
- perf(go): streaming + atomic backup import, transactional structured restore (#959) (#963) (b313997)
- ci: CodeQL Go leg uses autobuild (no build-mode: none for Go) (8883f20)
- ci: add Go to the CodeQL language matrix (1c65cdb)
- perf(go): shrink warm RSS — resvg pool 3->2 + GOMEMLIMIT (#956) (23bee3b)
- feat: keyset-paginated GET /api/shots + lazy curve loading (#957) (#962) (e16c5cc)
- perf(go): gate the achievements full-context scan behind a change fingerprint (#956) (b2bc4bb)
- perf(go): concurrent WAL reader pool for SQLite, stop head-of-line blocking (#956) (e395706)
- fix: dispatch GaggiMate default machine live poll + sync by adapter type (#955) (40570ce)
- fix(go): match null-in-series scoring to the map path + keep resvg slots warm on render error (#951) (cf5c31e)
- feat(go): persistent GaggiMate live client, stop the per-tick WS hammer (#952) (29793ba)
- feat(go): port the automatic shot-sync triggers (#953) (92c1c2e)
- fix(go): coalesce buffered live-snapshot SSE frames on a slow consumer (#901) (6052714)
- test(bench): harden the Node-vs-Go harness against rate limiting + SSE false alarms (#951) (d707d7c)
- perf(go): fold grinder wear in one shot scan for GET /api/library (#951) (240356a)
- perf(go): pool warm resvg contexts for the share card (#951) (58bd8c6)
- perf(go): keep /shots.json datapoints raw + goccy encoder (#951) (54e7a01)
- test(go): add a live Node-vs-Go performance benchmark harness (#951) (ceacab5)
- fix(go): accept URL-safe HA ingress tokens in the path-prefix verdict (#901) (ff23165)
- feat(go): add an HA-ingress self-diagnostic to internal/debug (#901) (5d4c5d6)
- Merge remote-tracking branch 'origin/dev' into go-migration (f06313c)
- docs+ci: add PR guidelines and mandatory AI assistance disclosure (#950) (1a29543)
- refactor(go): extract buildApp + add an HA-ingress smoke test (#901) (af85e68)
- test(go): Node-vs-Go route-parity check, wired into CI (#901) (1f92bdd)
- test(go): extend Phase-2 contract-test coverage (#901) (2b2da64)
- feat(go): port the debug routes (#901) (2cd65b0)
- feat(go): port the share-card PNG renderer (#901) (2392282)
- feat(go): port the MQTT live-data transport (#901) (96d229b)
- feat(go): port the bean-import domain (#901) (f71e0cd)
- feat(go): port the achievements ("stamp card") domain (#901) (4a20791)
- feat(go): port geocodeBean + the trivial system/machine-control routes (#901) (3757898)
- build(go): add frontend build stage to the Docker image and Makefile (#901) (01c5bcf)
- feat(go): serve the Vite SPA from the binary, move templ pages under /ui/ (#901) (721491a)
- feat(go): port BREW_AUTO auto-stop, live idle stats + steam/flush states, milk restock (#901) (d9eb10f)
- Merge remote-tracking branch 'origin/dev' into go-migration (803b1b7)
- chore: hold Node v24 bump, announce armv7 deprecation (#945) (626e021)
- chore(deps): lock file maintenance (#938) (5c5dff5)
- fix(deps): update dependency zod to v4.5.4 (#936) (0440922)
- fix: audit follow-up — secret-safe gitignore, ready-by scope comment, coverage thresholds (#943) (94d75e5)
- Merge pull request #935 from mxkissnr/release/v2.36.1 (f76c652)
- Merge origin/main into release/v2.36.1 (0b53f90)
- release: v2.36.1 — bean/milk stock fixes, exhausted bean picker, dark-theme autofill (b1fcd35)
- fix: keep exhausted beans selectable in the shot annotator (#934) (95d689c)
- fix: correcting bean/milk stock now sets the actual amount, not an overwrite (#932) (dcbf4f4)
- chore(deps): lock file maintenance (#926) (e128003)
- chore(deps): update node.js to 83f487e (#923) (4e28a75)
- chore(deps): update dependency js-yaml to v5.4.1 (#925) (dc689f6)
- chore(deps): update github/codeql-action digest to cdf488f (#927) (ad844c5)
- fix(deps): update dependency axios to v1.20.0 (#928) (7e0926d)
- chore(config): migrate config renovate.json (#929) (ccc5ab6)
- chore(deps): update dependency eslint to v10.9.1 (#924) (ab524e5)
- fix: harden .lib-item-sub against WebView text-overflow ellipsis failures (#920) (6579ba6)
- fix: neutralize browser autofill white background on dark-theme inputs (#922) (0fe8e61)
- fix(go): deterministic tiebreak for comparative grind-advice bucket selection (#901) (3b0a488)
- fix(go): wire orders-update SSE publish onto the REST API's Service instance too (#901) (6d8de01)
- fix(go): reject null in boiler settings numeric fields (#901) (e0c06df)
- docs(go): update README Status/Frontend sections for this round's four packages (#901) (fd9f7d3)
- feat(go): A/B compare mode, ghost-curve overlay, score-delta chip, comparative grind-advice panel on shot detail (#901) (64a9d0e)
- feat(go): port calcComparativeGrindAdvice as internal/shots.ComputeComparativeGrindAdvice (#901) (6dfe07b)
- feat(go): real SSE live-update for the Orders queue, replacing 10s polling (#901) (15fecf2)
- feat(go): make boiler/system Settings editable with real field-level validation (#901) (3a96082)
- feat(go): freshness/firmware/ordered-by badges on the Shots list (#901) (fdacd83)
- feat(go): full Edit UI for Library and Machines pages (#901) (dbaa06f)
- refactor(go): extract library/machine PUT handlers into exported update.go service functions (#901) (54822b9)
- docs: add CHANGELOG entries for napi-rs/canvas and codeql-action bumps (#910, #909) (c946458)
- chore(deps): update github/codeql-action digest to db488dd (#909) (7581a72)
- chore(deps): update dependency @napi-rs/canvas to v1.0.8 (#910) (4722d81)
- Merge pull request #919 from mxkissnr/release/v2.36.0 (aafe7bd)
- Release v2.36.0: idle Live stats, steam/flush live states, docs/screenshots/dev-stats refresh (2be925b)
- Merge pull request #918 from mxkissnr/fix/913-live-catch-unreachable (9a680fb)
- Merge dev into fix/913-live-catch-unreachable (393d8dc)
- Merge pull request #917 from mxkissnr/fix/915-bean-picker-exhausted-stock (163d2f1)
- Merge dev into fix/915-bean-picker-exhausted-stock (3f6c553)
- Merge pull request #916 from mxkissnr/fix/914-mobile-power-button (5a536b5)
- fix: clear stale live data on a network-level fetch failure (d9b6aee)
- fix: hide exhausted beans from the shot-annotation bean picker (2f3d6ca)
- fix: add mobile topbar power toggle (#railPowerBtn) (c097fc7)
- feat: Live tab idle machine stats + steam/flush live states (#908) (07f778b)
- chore(deps): update dev-dependencies (#911) (57766c1)
- fix: end the live brew immediately on BREW_AUTO auto-stop (#907) (a4ed788)
- feat(go): Shots master-detail view with metrics, verdict, and chart (6bc68bb)
- fix(go): correct dangling README cross-reference in layout.templ (9a0bb7a)
- feat(go): fixed left icon sidebar replaces the top-tab menu (e383dd2)
- fix(go): correct README's stale Library/Settings "read-only" claims (#901) (ee08d44)
- feat(go): verdict-first default-machine status on the Machines page (#901) (5b0f644)
- feat(go): verdict-first due/soon/ok summary on the Maintenance page (#901) (f8a0ef9)
- feat(go): stock bars for Beans/Milks on the Library pages (#901) (8b0dd20)
- fix(go): restore styled htmx error fragments with a generic class (38d17bf)
- feat(go): Verdict header for Shots list + read-only tone for Settings (#901) (532a855)
- feat(go): port Instrument design-token system onto templ frontend (#901) (740ae98)
- fix(go): address code-review findings on Settings/Library/Machines forms (#901) (0bd9aad)
- feat(go): Create/Edit forms for Library, Machines, and all 5 Settings categories (#901) (35afcbc)
- fix(go): raise GET /api/token rate limit for genuine Ingress callers (#901) (fda1212)
- fix(go): X-Frame-Options DENY -> SAMEORIGIN, blocked HA sidebar panel embed (02affd9)
- fix(go): make every template href/src/hx-* path Ingress-safe (#901) (290dcfe)
- fix(go): register GET / so HA Ingress's base URL stops 404ing (38d8aaa)
- fix(go): wire GLP_DEV_BUILD through the go-preview image build (#901) (cbe833e)
- Merge pull request #902 from mxkissnr/dev (c116c3b)
- fix: revert Docker base image from node:24-slim to node:22-slim, restoring armv7 support (490ad6b)
- Merge main into dev: resolve release v2.35.0 conflicts (5120716)
- Release v2.35.0: finalize CHANGELOG, bump version, refresh docs/screenshots/dev-stats (118a9aa)
- chore(deps): update docker/setup-buildx-action digest to 37fe631 (#892) (ac2605c)
- chore(deps): update node.js to v24 (#900) (896641b)
- chore(deps): update node.js to d649c27 (#894) (e56db27)
- chore(deps): update github/codeql-action digest to ff2f1c6 (#893) (55cc5f4)
- chore(deps): update dependency node to v24 (#898) (e4d96a4)
- chore(deps): update dependency js-yaml to v5.3.0 (#897) (15f1a9f)
- chore(deps): update dev-dependencies (#896) (b535114)
- chore(deps): update dependency @napi-rs/canvas to v1.0.7 (#895) (8aae389)
- chore: bump version only at release time, not per dev commit (#891) (f443bb8)
- fix: RGB easter egg rotates the icon's own colour, clip topbar icon, floor bean stock display at 0 (#889) (2ec0976)
- fix: correct stale dependency-review-action version comment (#884) (939f036)
- chore: consolidate test.yaml and version-release-check.yaml (#881) (0e37101)
- chore: add job timeout, retry-wrap the Playwright Chromium install step (#883) (e11907a)
- fix: put Renovate config on main with baseBranches: dev (#879) (1a51367)
- chore: switch from Dependabot to Renovate (#876) (f61619e)
- Share card: band-system stats grid and corrected chart phase tint (#874) (abb62ce)
- fix: split Bohne & Mühle into two separate recipe cards (#872) (8ec7a2c)
- fix: replace ice-cube grid icon with a geometric snowflake (#870) (be67055)
- fix: drop basket/puck screen from shot detail bean/grinder line (#868) (5c90d6d)
- fix: move shot score between title and hero photo on mobile (#866) (b99d6f0)
- feat: show the shot hero photo on mobile instead of the tiny thumb (#864) (35b8a56)
- fix: push #main/#sidebar down below the dev-build banner on mobile (#862) (fbc2656)
- fix: wrap Coffee Library action buttons instead of overflowing off-screen on mobile (#860) (1cbcd4e)
- feat: show a visible paused-age badge on frozen coffee portions (#856) (#857) (21c444f)
- chore(deps): Bump js-yaml in /gaggiuino-local-profiler (#854) (296bc46)
- chore(deps): Bump @napi-rs/canvas in /gaggiuino-local-profiler (#853) (fd5ad8d)
- fix: shot hero photo panel renders as a circle again (ba2e14d)
- Add shot detail hero photo panel and split puck screen onto its own line (#852) (ecfd40a)
- fix: clip easter egg panel rainbow to icon, make colour uniform (#849) (2be28e0)
- fix: dedupe topbar machine icon, fix rainbow coverage (#847) (c3b958a)
- Remove redundant verdictSubline duplicating topTitle and beanGrinderVal (#844) (ddba421)
- style: render the steam knob black instead of chrome (#843) (0657e8e)
- fix: constrain topbar machine icon to 44px via ID specificity (#840) (865cf2c)
- Add animated machine icon as an ambient topbar widget + click easter egg (#837) (#838) (e2582f4)
- fix(docs): crop screenshots to view container instead of full viewport (#836) (4cbd9e9)
- chore: second empty commit for clean Gitea Actions guard verification (#834) (77c955e)
- chore: empty commit to verify Gitea Actions guard (#834) (86b3d31)
- fix: skip GitHub-only CI workflows on the local Gitea mirror (a0bc913)
- fix: migrate raw font-size:.85rem literals onto the type scale (#832) (#833) (0b64949)
- Reduce duplicate info on shot detail screen and sidebar (7426508)
- Close out #760: escape the one real gap the CodeQL false-positive audit surfaced (a183c79)
- chore(deps): Bump @napi-rs/canvas in /gaggiuino-local-profiler (#828) (edabe36)
- chore(deps-dev): Bump globals (#827) (2908d82)
- Remove dead shot-count DOM lookups left over from the flap-board flattening (c28af70)
- Show last-used grind setting in the Library bean list (7e7cbc0)
- Merge pull request #826 from mxkissnr/release/v2.34.0 (dfb8342)
- Release v2.34.0: finalize CHANGELOG, bump version, refresh docs/screenshots/dev-stats (590e4f9)
- fix: flatten sidebar shot-count header from split-flap odometer to plain text (#823) (#825) (2754bce)
- Merge pull request #821 from mxkissnr/fix/820-chip-active-fill (b148878)
- Merge pull request #824 from mxkissnr/feat/822-static-machine-icon (4ea0e3d)
- Give static machine icons per-type geometry (Gaggiuino vs GaggiMate) (5a2326b)
- Convert three remaining filled-pill toggles to the bordered chip pattern (d6cc238)
- Merge pull request #819 from mxkissnr/fix/811-share-card-verdict (b0f3cb1)
- Merge pull request #818 from mxkissnr/fix/811-shots-view-boxes (98ae9cb)
- Share Card: score ring becomes typographic verdict, chart loses its box (6ec2f6d)
- Shots view: de-box the verdict line, grind-advice colors, sidebar avatar, topnav pill (581885d)
- Merge pull request #815 from mxkissnr/feat/811-instrument-tokens (8d37538)
- Catch the orders_types_saved sibling the icon sweep missed (550d94c)
- Replace the last text-glyph buttons and status glyphs with drawn icons (7108259)
- Add the missing CHANGELOG entry for the score-colour fix (f266d2d)
- Match the share card's score colour to the app's own rule (2febf53)
- Pull the share card onto the #811 tokens and always show an install code (357021e)
- Stop a comment from breaking the stylesheet, and guard the class (47fd1af)
- Add the stamp card view for the achievement catalogue (6e71ffd)
- Add achievement copy in six languages, and the tests that were missing (d73f9ad)
- Merge the chart theming work into the redesign branch (318ae9a)
- Wire the animated machine icon into the Live view (a851221)
- Add the achievements backend: schema, registry and event evaluation (2bac080)
- Add animated machine icon with live states (#811) (bbb98c3)
- Resolve chart and banner colours from the theme tokens (2e67197)
- Give the fill-styled buttons a themed surface (f091b87)
- Replace the shot view's tile walls and score ring with type (82aec2e)
- Replace the remaining emoji UI glyphs with drawn icons (03e0e3b)
- Regenerate the README screenshots for the new token layer (888d9f3)
- Make text on a semantic fill readable, and audit that direction (ee91032)
- docs: log the stylesheet token-application work in CHANGELOG (bde8f87)
- style: map padding/margin/gap onto the --sp spacing ladder (19bdfab)
- style: replace inline #52525b with the themed --gray-600 token (f9a13f3)
- style: collapse repeated font-family declarations to one inherited rule (fc1e7c3)
- style: border diet -- full borders only around clickable things (218d3a6)
- style: replace hardcoded #fff with themed role tokens (ba8236a)
- style: map font-size literals onto the --fs scale, drop uppercase labels (410c226)
- Move the token layer to cool graphite and fix the contrast failures under it (b5e665b)
- ci(dev-channel): retry the GHCR push once after a rate-limit failure (#810) (73129b9)
- Explain a closed direct port instead of showing a bare HTTP 401 (#808) (d882599)
- fix(dev-channel): sync options/schema into the dev manifest's config.yaml (#806) (8679840)
- Add expose_api_port option to close the token endpoint to the LAN (#804) (51faa32)
- fix: match X-Ingress-Path by prefix, not by pinned add-on slug (#802) (395c082)
- perf: lazy-load echarts/topojson-client/qrcode behind dynamic import() (#799) (f153ecb)
- test: add Playwright E2E smoke test on top of the screenshots harness (#798) (#800) (b5eb8a1)
- perf: split vendor libraries into separate chunks (#795) (#796) (8f13a79)
- fix: bundle Figtree locally instead of loading from fonts.bunny.net (#793) (#794) (c315be6)
- fix: resolve bag-scoped consumption with the same rule as remaining stock (#788) (#792) (6a66a9e)
- ci: sync apparmor.txt into the dev manifest repo (#790) (c9fa589)
- Add AppArmor profile for the add-on (needs complain-mode validation) (#787) (0deca1b)
- Hardening: bean-math parity test, apparmor.txt, coverage gate refresh, drop dead root lib/ (#786) (d58b239)
- chore: CI/build config hygiene — dependabot grouping, stale comment, dead root manifest (#781) (18e781e)
- fix: push LIVE_SNAPSHOT immediately on transport arrival, not just the 1s tick (df553bd)
- fix: remove redundant sidebar shot count, reorder flap counter before label (#777) (f3ba5a5)
- fix: theme swatch gradient clipping and overlapping sync-progress race (#774) (01d414f)
- chore: add local Docker smoke test for standalone install (#771) (3ba35c4)
- Bump the dev-dependencies group (#766) (6ae7f80)
- Bump better-sqlite3 from 13.0.2 to 13.0.3 in /gaggiuino-local-profiler (#767) (a7172b7)
- Bump express-rate-limit from 8.6.1 to 8.6.2 in /gaggiuino-local-profiler (#768) (023c0e1)
- Bump ws from 8.21.1 to 8.21.3 in /gaggiuino-local-profiler (#769) (1cd1856)
- feat: standalone Docker install support (Unraid, TrueNAS, HA Container) (#765) (6997c1c)
- Merge main into dev: resync after CHANGELOG duplicate-content fix (0d11f94)
- Merge pull request #763 from mxkissnr/fix/changelog-duplicate-content (db9263a)
- fix: remove duplicated full-detail block left over in CHANGELOG.md's v2.32.0 entry (02092f3)
- fix: remove duplicated full-detail block left over in CHANGELOG.md's v2.32.0 entry (0564055)
- Merge main into dev: resync after v2.32.0 release + CHANGELOG condense fix (3f5ad5d)
- Merge pull request #762 from mxkissnr/docs/760-changelog-condense-2.32.0 (4c25de9)
- docs: condense CHANGELOG.md's v2.32.0 entry, adopt short-entry convention (2a7219d)
- Merge pull request #761 from mxkissnr/fix/760-codeql-xss-suppression (d82845b)
- chore: add CodeQL in-source suppression comments for verified false positives (#760) (96c0834)
- Merge pull request #759 from mxkissnr/release/v2.32.0 (99a0593)
- fix: restore whats-new.js release history lost during dev-cycle squash (d4a1934)
- fix: use hostname parsing instead of substring match in GitHub API fetch stub (75c0453)
- release: v2.32.0 (8e5e12c)
- Fix syncInstallId() never actually firing on its first run (#758) (366f9ac)
- Merge pull request #756 from mxkissnr/feature/755-raw-db-import (801b4b7)
- Fix CodeQL type-confusion false positive in import-db route (b810356)
- Add raw database import counterpart to the dev-only DB export (6d93df2)
- Merge pull request #754 from mxkissnr/feature/753-machine-default-delete (8269a23)
- Allow changing the default machine and deleting any machine (76ede8d)
- Merge pull request #751 from mxkissnr/fix/750-wizard-install-id-reset (9249d8e)
- Fix setup wizard staying suppressed after an add-on data wipe (53984b8)
- Merge pull request #749 from mxkissnr/fix/748-wizard-test-connection-closes (67aa094)
- Fix setup wizard closing itself on Test connection, duplicate machine (#748) (dc796c0)
- Merge pull request #747 from mxkissnr/fix/746-wizard-trigger-empty-host (afd0656)
- Trim whats-new.js back to MAX_ENTRIES=8 (drop oldest, v2.27.3) (32d9574)
- Fix setup wizard never auto-opening on a real fresh install (#746) (a8c18e4)
- Merge pull request #745 from mxkissnr/feature/744-setup-wizard (e0338c8)
- Merge remote-tracking branch 'origin/dev' into feature/744-setup-wizard (b1c3cbd)
- Add guided first-run setup wizard (274e2de)
- Push Live view telemetry/preheat and shot counter over SSE (#743) (06bda45)
- Document multi-machine state invariant after third recurrence (823cb03)
- Try two SSE hardening techniques against HA Ingress buffering (#741) (0641e85)
- Fix SSE sync-progress still updating in blocks over HA Ingress (#739) (185fb51)
- Push shot-import progress over SSE, with automatic polling fallback (#737) (93c08ba)
- Fix machine settings follow-ups: keep test dialog open, fix stale shot count, catch backgrounded sync toasts (#734) (5e58da7)
- Fix machine setup UX follow-ups: sync only on explicit save, progress-bar layout, completion toast (#732) (8f719d0)
- Simplify machine test button to save-then-test, sync on every save, add import progress (#730) (657500b)
- Stop an out-of-range shot id from wedging default-machine sync forever (#720) (7f37676)
- Add "Save & test" combined action to the machine form (#728) (d4910f3)
- Trigger an immediate sync on reachability recovery and on machine-config save (#726) (a1aa12a)
- Add dev-channel-only raw SQLite DB export endpoint (#724) (adf12db)
- Skip permanently-missing (404) shot ids during backfill instead of aborting sync forever (#723) (2d3b95c)
- Merge main into dev: resync after v2.31.0 release + post-release CHANGELOG cleanup (93589b9)
- Allow an empty machine host, skip cleanly instead of a placeholder fallback (c049e11)
- Log raw /latest response body from the machine (a62b690)
- Log per-shot response time during backfill (e09da76)
- Add registry snapshot + full request tracing to debug logging (0a91814)
- Fix startup log's Machine URL line to read the registry, not raw options.json (7621f39)
- Show dev build tag in the startup log line (507adcf)
- Add periodic connectivity summary log for machine host (f5cdd56)
- Add debug-gated logging for sync 404s and brew-event flapping (db19341)
- Log options.json key set at startup for stale-schema diagnosis (#707) (24de8ea)
- ci: decouple dev manifest publish from armv7/aarch64 builds (6c92680)
- fix: suppress stable-release update banner on dev builds, show build id in dev banner (aaaf183)
- feat: expose each machine's theme in GET /api/status machines[] (954a40f)
- ci: build armv7 and aarch64 images for the dev channel too (81749ce)
- fix: getMachineUrl() always appends /api/shots regardless of input format (91077d0)
- fix: await loadLibrary() before loadData() to fix stale Basket/Puck Screen on first load (34f397c)
- fix: wire live pump-flow reading into the live-shot accumulator (24b1570)
- fix: bump nanoid to patch GHSA-2v37-7h3g-55p8 DoS vulnerability (4980db6)
- feat: deprecate machine_host/switch_entity add-on options (#662) (#697) (5297a84)
- docs: remove personal attribution from CHANGELOG entries (#696) (ae724be)
- docs: remove personal attribution from CHANGELOG entries (#695) (32ebc66)
- chore: firmware-check pagination + grinder-stats dedup (#673, #674) (#694) (d3c993a)
- Release v2.31.0 (41f6217)
- release: v2.31.0 (0ddc38d)
- fix: wire autocomplete onto the shot-defaults Grinder field (#692) (893849f)
- chore(dev): switch dev build version to a UTC timestamp (#690) (6fd52c3)
- fix: dev-banner overlay + wrong changelog path for GLP DEV updates (#688) (07f40c8)
- feat: on-duration status, edge-swipe drawer, dev-build banner, restore reload (#685) (1056bd1)
- refactor: consolidate resolveMachine()/requireSettingsProxySupport() into their canonical files (#680) (45f96f8)
- fix: allow same-origin camera access so the barcode/QR scanner works (#678) (f79ff6a)
- fix: add SIGTERM/SIGINT handler so add-on stop exits cleanly (#676) (0b59de4)
- docs: document dev-first branch workflow in CLAUDE.md (#672) (db0d708)
- Round 08-06: release-check retry, shot defaults, firmware version check, basket/puck-screen analytics (#669) (225da8a)
- Retry release-existence check to tolerate merge-to-publish gap (3d739e4)
- Merge pull request #664 from mxkissnr/release/v2.30.0 (1f51041)
- Use Array.isArray, not just Buffer.isBuffer, as the CodeQL barrier (#665) (788afc1)
- Add explicit type/format barriers for CodeQL false positives (#665) (e201f9c)
- Release v2.30.0 (93fec89)
- Retry the post-power-on sync a few times instead of a single attempt (#663) (8da82c7)
- Reconcile machine host/switch entity after backup restore (#661) (dbafc14)
- Add time to backup filenames, not just the date (8acdb2d)
- Clear backup modal passphrase fields on close, not just its bundle state (6f74993)
- Fix dev-9 regression: attribute-based file input selector broke on the new accept value (48d5c9e)
- Export backup as a real .zip instead of base64-embedding images in JSON (c2a6a9d)
- Fix Enter key in backup passphrase field; log skipped images in export (935c524)
- Back up shot photos too, by scanning the image directory instead of a hand-maintained entity list (1517cae)
- Show the dev-channel build tag next to the app version, on GLP DEV only (3435b47)
- Give the restore dry-run preview its own rate-limit budget (87700f6)
- Mirror the status dot's tooltip on the rail footer dot too (#655 follow-up) (8ab9be0)
- Fix status dot/Live tab never reflecting machine reachability (#655) (5b8bb42)
- Fix the API-token/MQTT-login checkbox not actually being included in an export (f24f571)
- Log what changed with every dev build (9467130)
- Complete the backup: missing tables, trash, photos, selective sections, encrypted secrets, dry-run preview (27ef29c)
- Document the absent-vs-cleared option distinction (fc0ce62)
- Distinguish an absent add-on option from a cleared one (a4b08d3)
- Don't fail the dev manifest job when the version is already current (1b80fac)
- Introduce a machine-config registry facade; end #638/#641/#643/#648's class of bugs (7d3e715)
- Point dev channel at the renamed glp-dev-app repository (52bcd35)
- Add dev channel build for testing on a real HA instance (df3c556)
- Adopt add-on option changes into the machine registry (38b6c89)
- Fix native <datalist> UX and non-scrolling mobile tab bars (e534b4b)
- Fix dead barcode scan (CSP block), German-only log timestamps, and German-default language fallback (c2a43ce)
- Merge pull request #650 from mxkissnr/release/v2.29.0 (1ec4367)
- Release v2.29.0: Baskets & Puck Screens, docs/screenshots/dev-stats refresh (031d8a5)
- Merge dev into release/v2.29.0 (f09cda8)
- test(library): cover Baskets/Puck Screens CRUD, images, and annotation roundtrip (4d3dd02)
- feat(library): add Baskets and Puck Screens frontend + i18n (#635) (229200f)
- feat(library): add Baskets and Puck Screens backend (#635) (8bab324)
- Merge main into dev (v2.28.0 release resync) (c8fb4eb)
- fix: resolve four low-severity audit findings (#648) (#649) (a5f02d2)
- fix(shots): guard loadData() against overlapping/out-of-order responses (#646) (91cc3c4)
- fix(switch-entity): resolve default machine's switch_entity from the registry, not stale options.json (#647) (d1e0c4a)
- fix: guard against unhandled promise rejections in background timers (#645) (5f4655a)
- Chore(deps): Bump better-sqlite3 in /gaggiuino-local-profiler (#630) (fe0f276)
- fix(sync): resolve default machine's host from the registry, not stale options.json (#641) (c973bc5)
- Chore(deps): Bump actions/upload-artifact from 4.6.2 to 7.0.1 (#632) (dd7edac)
- Chore(deps): Bump @napi-rs/canvas in /gaggiuino-local-profiler (#631) (ca7b55f)
- Chore(deps): Bump axios in /gaggiuino-local-profiler (#629) (19d98a6)
- Revert "docs: document standalone Docker install (non-HA-OS environment) (#640)" (c3e7c54)
- Chore(deps): Bump js-yaml in /gaggiuino-local-profiler (#628) (ac457e8)
- Chore(deps-dev): Bump the dev-dependencies group across 1 directory with 2 updates (#627) (83c74c0)
- docs: add AI-generated-project disclaimer to README (#637) (e5e71f8)
- docs: document standalone Docker install (non-HA-OS environment) (#640) (db904fd)
- ci: fail loudly when config.yaml version has no matching GitHub release (#634) (774efd3)
- Downgrade version from 2.29.0 to 2.28.0 (#633) (392f2de)
- feat(dev-stats): real Claude Pro subscription cost + hours-of-development estimate (v2.29.0) (#625) (6032ec2)
- Merge main into dev (v2.28.0 release resync) (9b0ed91)
- Merge pull request #624 from mxkissnr/release/v2.28.0 (c4df24b)
- chore(release): v2.28.0 dev-stats + screenshot refresh (173bf5c)
- feat: in-app "What's New" changelog in Settings (v2.28.0) (#622) (be85faa)
- fix(machines): evict stale live-WS session on machine delete/host-change (#621) (5b36899)
- fix(machine-state): prefer live-transport sensorSnap over REST for temperature/pressure/weight (#619) (64794e8)
- Move preheat-ready/low-stock notify toggles to Settings page (#614) (#618) (33a094b)
- Merge remote-tracking branch 'origin/main' into dev (2e3dafe)
- chore(release): v2.27.1 dev-stats, CHANGELOG security entry, dependency bumps (#617) (77fbdc4)
- Transport logging + architecture diagram fix (#611, #612) (#613) (46b5831)
- Merge main into dev (v2.27.0 release resync) (6d5ee26)
- Regenerate screenshots and dev-stats for v2.27.0 (#609) (0c2ce3a)
- Chore(deps): Bump undici in /gaggiuino-local-profiler (#607) (4c9ea4f)
- MQTT as an alternative live-data transport with Supervisor broker auto-discovery (#608) (2731e65)
- Add per-notification-type toggles in Settings (#603) (#606) (f09d83b)
- Default machine's colour theme drives the whole app UI accent (#604) (#605) (aab0c1c)
- Chore(deps-dev): Bump postcss in /gaggiuino-local-profiler (#602) (1cd6679)
- Merge main into dev (v2.24.0 release resync) (c77f1f0)
- Merge pull request #601 from mxkissnr/release/v2.24.0 (d86ce29)
- release: bump to v2.24.0, regenerate screenshots and dev-stats (9d75372)
- Merge remote-tracking branch 'origin/main' into dev (fccc469)
- Add Gaggiuino settings + control API proxy (#597) (#599) (ef7921f)
- Merge remote-tracking branch 'origin/main' into dev (04eef92)
- Add per-machine colour theme + detailed Gaggia Classic machine icon (#595) (49ba7fd)
- Center logo.svg text block vertically in banner (#593) (0f77cdf)
- Center logo.svg text block vertically in banner (9ed559a)
- Merge pull request #592 from mxkissnr/release/v2.23.1 (e0d5a2c)
- release: regenerate screenshots and dev-stats for v2.23.1 (5902cde)
- Merge pull request #591 from mxkissnr/dev (2e73670)
- fix: fill remaining width in Bibliothek/Einstellungen, fix mobile power icon (a3edb48)
- Merge pull request #588 from mxkissnr/release/v2.23.0 (cf1c55e)
- release: regenerate screenshots and dev-stats for v2.23.0 (f6dc799)
- Merge pull request #587 from mxkissnr/dev (49e31a4)
- Merge origin/main into dev: reconcile v2.23.0 (REST profile-write, #580) with dial-in/settings UI fixes (#584, #585) (8f94902)
- Merge pull request #586 from mxkissnr/feat/580-rest-profile-write (84357c1)
- Profile create tries REST (POST /api/profile) before WebSocket fallback (23ec732)
- fix: persist dial-in shot count, make dial-in/settings grids fill window width (73fd805)
- Merge pull request #582 from mxkissnr/dev (4bd0eee)
- Release prep for v2.22.0: regen dev-stats/screenshots, fix release-notes rule (57c5733)
- Auto-sync descaling/backflush maintenance from machine's native Service Log (2decabc)
- Profile detail read: try REST GET /api/profile/:id, fall back to WebSocket (2736763)
- Fix package.json version drift from the 2.21.1 patch release (5391af1)
- Fix bean stock deduction for retroactively-assigned shots and mobile card overflow (61c1a34)
- Merge pull request #574 from mxkissnr/dev (0f14174)
- Scope write permissions to job level, not workflow top-level (60eab75)
- Merge pull request #572 from mxkissnr/dev (57d1380)
- Pin GitHub Actions and Docker base image by hash, add token permissions (f47211c)
- Pin ossf/scorecard-action to a real release SHA (#569) (#570) (114083a)
- Add dependency-review, npm cache, and OSSF Scorecard CI workflows (#568) (9ff5c65)
- Merge pull request #566 from mxkissnr/release-batch (fd27d7a)
- Release v2.21.0: beanId persistence, ecosystem-audit refactor batch, coverage gate (5f6e4ab)
- Persist beanId on POST /api/orders (#563) (#565) (a5ee1a9)
- Ecosystem-audit refactor batch: #548-#555 (8 issues, no behavior change) (#564) (9ccbc05)
- Update CONTRIBUTING.md code-notes table to the current architecture (#562) (6be07f3)
- Add vitest coverage-v8 provider and enforce coverage gate in CI (#561) (51b7ebd)
- Merge pull request #560 from mxkissnr/release/v2.20.1 (480b53a)
- Release v2.20.1: bump version, changelog, dev-stats (587cb9d)
- Chore(deps-dev): Bump playwright (#544) (e8d33f9)
- Chore(deps): Bump express-rate-limit in /gaggiuino-local-profiler (#545) (9bdd331)
- Order-mine identity check + port-8099-default doc warning (#547, #546) (#559) (82ab8b9)
- Merge pull request #543 from mxkissnr/release/v2.20.0 (3985776)
- Release v2.20.0: bump version, changelog, docs, screenshots, dev-stats (c6ebb84)
- Fix races on shared UI state, mobile sidebar overlap, and ready-by preheat backend (#542) (2630a8f)
- Merge branch 'main' into dev — release-check screenshot precision (#537/#539) (d0104bf)
- release-check: only flag screenshots stale for visually-relevant public-src/ changes (#539) (d3e2c29)
- Merge main into dev (v2.19.3 release resync) (df3a90b)
- chore(release): v2.19.3 (#538) (f8d777b)
- Merge branch 'main' into dev — render-race fix (#526) (8347662)
- fix: re-render library/analytics views once late-loading data arrives (#526) (#535) (2495f20)
- Merge remote-tracking branch 'origin/main' into dev (a4db3ab)
- Release v2.19.2: fix /api/token direct-port regression from v2.19.1 (#536) (0df0526)
- Serve /api/token to any caller that can reach the port (#534) (b0405ed)
- Merge branch 'main' into dev — v2.19.1 release (token-storage fix, dev-stats scope fix, ESLint 10 CI gate) (61cb965)
- docs: fix CHANGELOG.md, ESLint 10 not 9 (v2.19.1 entry) (#532) (879daab)
- Release v2.19.1 (#531) (99333b4)
- Fix historyScope() silently falling back to HEAD (#530) (9b6699b)
- Merge branch 'main' into dev — token-storage fix, screenshots, dev-stats scope (c2878db)
- Make dev-stats independent of the checked-out branch (#528) (c43c73e)
- chore: refresh screenshots and dev-stats for release gate (#525) (b7a18e2)
- Stop persisting the GLP API token to localStorage (#524) (4d43a19)
- Merge branch 'main' into dev — Lint-Gates (ESLint 10 + release:check) nach dev übernehmen (f79766c)
- Add ESLint 9 flat-config CI gate + release-check script (#520) (14677dc)
- Sync dev with main after v2.19.0 release (32bf819)
- Release v2.19.0 (#518) (8e88e82)
- fix: drop in-app add-on self-update, revert hassio_role: manager (#514/#515 unreleased) (#517) (695be2a)
- fix: grant hassio_role: manager so in-app add-on self-update stops 403ing (#515) (2c254eb)
- Sync dev with main after v2.18.2 release (701d633)
- Release v2.18.2 (#513) (b019990)
- fix: mobile shot search no longer force-closes drawer on keyboard open (#512) (96f67be)
- Vendor Chart.js/ECharts/topojson-client/QRCode instead of cdn.jsdelivr.net (#510) (435f128)
- Release v2.18.1 (#508) (15a7cf0)
- fix: resolve npm audit findings (body-parser DoS, js-yaml ReDoS) (2aa8d7d)
- Merge remote-tracking branch 'origin/main' into dev-sync (5e8ea1e)
- Release v2.18.0 (#507) (e1d805d)
- Add optional speciality/normal category field to bean model (#506) (0fcea6f)
- Merge branch 'main' into dev (5b60284)
- Release v2.17.0 (#504) (c90c682)
- Track which frozen portion a shot used, auto-deduct from the library (#503) (fd09a2c)
- Merge remote-tracking branch 'origin/main' into dev (6d3a087)
- Release v2.16.5 (#501) (735cc6d)
- Represent blend components fully and extract bullet-list brew recipes (#500) (49b3b28)
- Sync dev with main after v2.16.4 release (6b6a372)
- Release v2.16.4 (#497) (7a17a73)
- Extract flavor notes from an all-caps slash-separated .additional-info line (#496) (e18c481)
- Sync dev with main after v2.16.3 release (41c4bb6)
- Release v2.16.3 (#494) (4fa71ff)
- Fix the actual root cause: custom-shopify import path never ran HTML enrichment (#493) (80523a4)
- Sync dev with main after v2.16.2 release (950b6e1)
- Release v2.16.2 (#491) (bc40abf)
- Add opt-in ?debug=1 diagnostic field to the import response (#490) (c95eadb)
- Merge remote-tracking branch 'origin/main' into dev (da2abb9)
- Release v2.16.1 (#488) (2d309e2)
- Fix browser caching stale bean-import responses forever (#487) (84e1a83)
- Sync dev with main after v2.16.0 release (1225deb)
- Release v2.16.0 (#485) (9e3ea8a)
- Add a debug-logging add-on option, instrument the import flow with it (#484) (3d97934)
- Merge remote-tracking branch 'origin/main' into dev (7343776)
- Release v2.15.2 (#482) (1c79188)
- Log generic-Shopify HTML-enrichment fetch failures instead of swallowing them (#481) (946d478)
- Sync dev with main after v2.15.1 release (5af1898)
- Release v2.15.1 (#479) (d5a25a6)
- Scope frozen-portion freshness offset to the portion, not the whole bag (#478) (765a937)
- Release v2.15.0 (#476) (335283d)
- Release v2.14.0 (#468) (7583a3e)
- Release v2.13.5 (#465) (f845e8d)
- Release v2.13.2 (#460) (3ed448a)
- Merge pull request #458 from mxkissnr/release/v2.13.1 (6fc9c7c)
- Release prep v2.13.1: README features table + regenerated screenshots (e33174f)
- Correct #456: beanId-first matching must fall back to name for a truly-deleted bean (000a857)
- Show a hint when a shot's score used the bean's own brew target (v2.13.0) (40e9b77)
- Bump to 2.12.2, changelog entry for #456 (3ec1642)
- Backfill beanId on historical annotations, add #456 regression tests (fa170e5)
- Migrate bean<->shot matching from name-string to stable beanId (6b8e48f)
- fix: prefer variant option label over unreliable Shopify weight field (447a040)
- fix: mobile Shots tab opens shot detail, not list; enlarge photo thumb (533263e)
- Merge pull request #453 from mxkissnr/release/v2.12.0 (5871817)
- Regenerate dev-stats for v2.12.0 release (8342e9e)
- Regenerate README screenshots for v2.12.0 (7597399)
- Score shots against bean's own brew recommendation, offer Brew Guide extra recipes for import (v2.12.0) (#452) (d4ca206)
- Fix mobile drawer stale shot list and missing topbar machine name, add shot photo to header (v2.11.0) (#449) (cdb0864)
- merge: bring main's v2.10.0 release commit back into dev (b8b4114)
- Release v2.10.0 (#445) (35a9d87)
- Configurable mobile bottom nav (#443) (#444) (58d7c70)
- merge: reconcile CLAUDE.md versioning clarification with v2.9.0 back-merge (230ab7d)
- Release v2.9.0 (#442) (59bc6a2)
- Regenerate dev-stats for v2.8.0 (236bdf9)
- Release v2.8.0 (#437) (1eb9002)
- Release v2.7.1 (#435) (67d17a0)
- Release v2.7.0 (#427) (a74cd6f)
- chore: regenerate dev-stats for v2.6.1 (#421) (8b5fa4f)

## dev-20260926_1249 — 2026-09-26

- fix(system): bounds-check upTime conversion in rawStatusFrom (#1170) (a1d7476)

## dev-20260925_2133 — 2026-09-25

- Fix #1162: a Gaggiuino default machine with id != 1 stores its shots a (#1167) (889c3e5)

## dev-20260925_2112 — 2026-09-25

- chore(deps): update node.js to 0e0ff40 (#1141) (5ce341e)
- chore(deps): update golang:1.27-alpine docker digest to 8a5910f (#1140) (d719457)
- chore(deps): update alpine:3.24 docker digest to 294b683 (#1138) (77497cf)
- chore(deps): update github/codeql-action digest to 2892aa5 (#1139) (6792411)

## dev-20260925_2104 — 2026-09-25

- Fix #1153: sync right after startup and machine power-on (#1166) (c1e4d38)

## dev-20260925_2051 — 2026-09-25

- Package 4a: fix #1154, #1155 (#1165) (a473b57)

## dev-20260925_2048 — 2026-09-25

- ci: keep externally reported issues open until release (#1156) (#1164) (6e05bc0)

## dev-20260925_2029 — 2026-09-25

- Fix #1146: sync enabled non-default machines again (#1163) (b7d7a4f)

## dev-20260925_2004 — 2026-09-25

- Fix #1147: GaggiMate default machine with id != 1 syncs under its own  (#1161) (9265fa5)

## dev-20260925_1928 — 2026-09-25

- Fix #1159: blocklist shots removed by the 30-day trash purge (#1160) (7d769be)

## dev-20260925_1917 — 2026-09-25

- Fix #1150, #1151 and #1152 (read all three issues on GitHub for detail (#1158) (c717ddf)

## dev-20260925_1855 — 2026-09-25

- Fix #1149 and #1148 (read both issues on GitHub for full details). #11 (#1157) (c7ad187)

## dev-20260925_1810 — 2026-09-25

- Fix shot sync ignoring lastShotId sent as a JSON string (#1142) (#1145) (0a6ea18)
- docs: add CHANGELOG entry for firmware-update maintenance log (#1136) (#1144) (c993ff0)

## dev-20260925_1716 — 2026-09-25

- Implement #1136 slice 2 (frontend): localize firmware_update log title (#1143) (69eb4a6)
- Implement #1136 slice 1 (backend): log machine firmware updates in the (#1137) (90a3c9a)
- docs: link the ordering feature row to the kiosk page (#1132) (6a5f8c8)
- docs: drop the removed Go preview channel section (#1132) (d3d0e60)
- docs: document the kiosk ordering page (#1132) (a10c9c3)
- docs: record kiosk mode, profile duplication, the bottom-nav fix and the TypeScript test migration in the changelog (#1132) (2506e55)

## dev-20260920_2307 — 2026-09-20

- test: keep the fakeRow doc comment attached to its function (#1133, slice-14) (b40f60a)
- test: satisfy require-await on the library-profile-editor json stubs (#1133, slice-14) (0778448)
- test: type the library-profile-editor fake DOM and race fixtures (#1133, slice-14) (5fa2e73)
- test: type the machine-icon, sidebar-month and dialin-wizard fixtures (#1133, slice-14) (410503e)
- test: rename Vitest files to .ts, mechanical step (#1133, slice-14) (f8fe993)
- test: type the bottom-nav and rail-status fake DOMs (#1133, slice-13) (a382171)
- test: type the world-map race, shots race and bean-filter fixtures (#1133, slice-13) (bd5dc66)
- test: rename Vitest files to .ts, mechanical step (#1133, slice-13) (13e3c97)
- test: type the theme and world-map Vitest fixtures (#1133, slice-12) (a1360af)
- test: rename Vitest files to .ts, mechanical step (#1133, slice-12) (2dedd95)
- test: declare the plain-JS sync-dev-config surface for the .ts fixture (#1133, slice-11) (afcd7ec)
- test: type the sync-progress-toast SSE/polling fixtures (#1133, slice-11) (98d02f3)
- test: type the suggest-grind-dose, sync-dev-config and theme-contrast fixtures (#1133, slice-11) (5137386)
- test: rename Vitest files to .ts, mechanical step (#1133, slice-11) (f4c2571)
- test: satisfy the require-await/no-unsafe-return lint rules in the slice-10 fixtures (#1133, slice-10) (045df0d)
- test: type the sidebar swipe/lazy-group and SSE Vitest fixtures (#1133, slice-10) (2cbbff1)
- test: type the shot-defaults and shots pagination Vitest fixtures (#1133, slice-10) (acfd27d)
- test: rename Vitest files to .ts, mechanical step (#1133, slice-10) (b87f93a)
- test: satisfy the typed lint rule on the shot-curves json stubs (#1133, slice-09) (52ad2f7)
- test: type the share-or-download, shot-count-header and shot-curves fixtures (#1133, slice-09) (34b75c0)
- test: type the score, setup-wizard and screenshot-freshness Vitest fixtures (#1133, slice-09) (5f182a0)
- test: rename Vitest files to .ts, mechanical step (#1133, slice-09) (414c9bf)
- test: build frozen-portion roast dates in local time (#856, #1133) (eefe607)
- test: satisfy typed lint in the notify/rail-power-btn fetch mocks (#1133, slice-08) (71360f3)
- test: type the notify/dialin/profile-suggestion/rail-power-btn fixtures (#1133, slice-08) (885a2e6)
- test: rename Vitest files to .ts, mechanical step (#1133, slice-08) (e4121f0)
- test: type the machines-settings, maint-dashboard and milk-deduct Vitest fixtures (#1133, slice-07) (cc44e1e)
- test: satisfy typed lint in the machine-form/on-duration/load mocks (#1133, slice-07) (2303b8c)
- test: type the machine-form, machine-on-duration and machines-load Vitest fixtures (#1133, slice-07) (64602a0)
- test: rename Vitest files to .ts, mechanical step (#1133, slice-07) (9087d37)
- test: type the i18n, legacy-banner and machine-accent Vitest fixtures (#1133, slice-06) (6f3af76)
- test: rename Vitest files to .ts, mechanical step (#1133, slice-06) (7709ac1)
- test: avoid require-await in the frozen-portion fetch mock (#1133, slice-05) (29316fc)
- test: type the grind-baseline Vitest fixture (#1133, slice-05) (dd3638c)
- test: type the flavor-match, freshness and frozen-portion Vitest fixtures (#1133, slice-05) (1ab2833)
- test: rename Vitest files to .ts, mechanical step (#1133, slice-05) (c87ef14)
- test: type the dev-stats history-scope fixture, declare its script types (#1133, slice-04) (bfe1297)
- test: type the dev-banner and firmware-progress-stage Vitest fixtures (#1133, slice-04) (2b6064e)
- test: type the best-grind-combo and day-grouping Vitest fixtures (#1133, slice-04) (8b75718)
- test: rename Vitest files to .ts, mechanical step (#1133, slice-04) (0e45cf0)
- test: register fake XHRs via a helper to satisfy no-this-alias (#1133) (d8cf91c)
- test: type the autocomplete fake-DOM harness (#1133, slice-03) (0b299f4)
- test: type the bean-library Vitest fixtures (#1133, slice-03) (d19065f)
- test: type the backup progress Vitest fixtures (#1133, slice-03) (024ff54)
- test: type the backup markup/wiring/reload Vitest files (#1133, slice-03) (6484c77)
- test: rename Vitest files to .ts, mechanical step (#1133, slice-03) (1c00a62)
- test: migrate annotation and API Vitest files to TypeScript (#1133) (a771855)
- fix: annotate the analytics stub calcShotScore parameter (#1133) (d80f4a0)
- test: migrate achievements and analytics Vitest files to TypeScript (#1133) (eee3df4)
- test: type Node builtins for the migrated Vitest files without @types/node (#1133) (ea7211d)
- test: migrate style-css-parses and glp-qr Vitest files to TypeScript (#1133) (502154a)
- test: migrate version-sync and whats-new Vitest files to TypeScript (#1133) (100bdba)
- test: migrate first batch of Vitest files to TypeScript (#1133) (72489c5)

## dev-20260920_1724 — 2026-09-20

- docs: document custom maintenance tasks in CHANGELOG, DOCS and README (b564449)
- fix: truncate maintenance log notes by rune, not byte (81fbe73)
- fix: address maintenance review — i18n, custom-task existence check, rune-safe truncation (5b36e0c)
- fix: typecheck/lint errors in ported maintenance view (162c2fd)
- fix: escape machineId in custom-maint-task button attribute (CodeQL DOM-XSS) (7931e5c)
- fix: use typed API for custom maintenance tasks, remove undefined apiFetch calls (8063441)
- fix: maintenance log shows raw task keys, log-entry form ignores custom/disabled tasks (e1c07e6)
- feat: improve maintenance tracking (d5bf422)

## dev-20260920_1716 — 2026-09-20

- fix: validate since, define duplicate-since behavior for retroactive zero-point (2e20a95)
- fix: escape grinder id/since in zero-point history delete button (CodeQL DOM-XSS) (5fdf2e4)
- feat: retroactive zero-point — optional since parameter for grinder zero-point history (eb1ced1)
- fix: regenerate schema.gen.ts to include zero-point route/field (21af0d8)
- fix: use typed API for grinder zero-point, remove undefined apiFetch call (96be49c)
- feat: grinder zero-point tracking for grind-setting suggestions (3affdee)

## dev-20260920_1211 — 2026-09-20

- TypeScript migration A6: convert top-level and shared modules to TS (#1128) (19844b4)

## dev-20260920_1202 — 2026-09-20

- TypeScript migration A5: convert views/ to TS (15 of 18 files) (#1127) (a84056b)

## dev-20260920_1150 — 2026-09-20

- feat: kiosk view (#1117) (b96adca)

## dev-20260920_1012 — 2026-09-20

- feat: duplicate machine profile (#1121) (01be407)
- fix: add bottom nav clearance padding to prevent content overlap (#1116) (4a2b5ea)

## dev-20260919_1803 — 2026-09-19

- Migrate components/ (~20 files) from JS to TS/TSX. See https://github. (#1114) (5ddebd0)

## dev-20260919_1222 — 2026-09-19

- TypeScript migration package A3: generated API types + typed client (#1112) (af5bdca)

## dev-20260918_1145 — 2026-09-18

- TypeScript migration package A2: core modules, state split, chart/timer registries (#1109) (5e81a81)

## dev-20260918_0728 — 2026-09-18

- Merge pull request #1107 from mxkissnr/ts-migration (d9cb552)
- Complete package A1: rename main.js to main.ts, wire CI typecheck gate (847620e)
- docs: main.ts in CONTRIBUTING.md's frontend source row (#1106) (47100f9)
- docs: main.ts in CONTRIBUTING.md's frontend source row (#1106) (4e8a0f6)
- test(frontend-build): expect main.ts as the entry point (#1106) (8780049)
- build(frontend): point the esbuild entry at public-src/main.ts (#1106) (fa35ea1)
- chore(lint): add TypeScript-aware ESLint blocks (#1106) (f41ca94)
- chore(frontend): add TS toolchain devDeps and typecheck/types:api scripts (#1106) (1e52794)
- Add tsconfig.json (TypeScript migration package A1, #1106) (4212aee)

## dev-20260917_2245 — 2026-09-17

- Merge pull request #1101 from mxkissnr/fix/1100-ai-model-breakdown (e4cfb70)
- Generalize dev-stats AI model breakdown beyond Claude (fcb6014)

## dev-20260917_1847 — 2026-09-17

- Merge pull request #1099 from mxkissnr/release/v3.1.0 (c1d687b)
- Remove duplicate test after main resync merge (b802758)
- Merge remote-tracking branch 'origin/main' into release/v3.1.0 (653ab03)
- Regenerate screenshots/dev-stats after What's New trim (ffdde8e)
- Trim in-app What's New to MAX_ENTRIES after adding v3.1.0 (027e33a)
- Release v3.1.0: bump version, retitle CHANGELOG, regenerate docs (c05bfde)
- Release v3.0.2 (#1041) (d63a22f)

## dev-20260917_1818 — 2026-09-17

- chore(deps): update docker/build-push-action digest to c3c9e26 (#1092) (a8d4713)
- chore(deps): update docker/setup-buildx-action digest to f87e599 (#1093) (1e6f671)
- chore(deps): update docker/setup-qemu-action digest to 9901266 (#1094) (4a3bcfc)
- chore(deps): update dev-dependencies to v5.0.1 (#1095) (85e3393)
- fix(deps): update module modernc.org/sqlite to v1.59.0 (#1096) (d66b986)
- chore(deps): update actions/github-script action to v9 (#1097) (5a727f5)

## dev-20260917_1436 — 2026-09-17

- fix(ui): name the firmware component in the update progress label (#1088) (0b34d57)

## dev-20260917_1314 — 2026-09-17

- ci: close issues referenced by PRs merged into dev (#1089) (dd9b5c7)

## dev-20260917_1256 — 2026-09-17

- fix: record the AppArmor profile's completed complain-mode validation (#1084) (45903c0)

## dev-20260917_1050 — 2026-09-17

- fix: describe the AppArmor profile as shipped and unvalidated (#1078) (8da0af6)

## dev-20260917_0909 — 2026-09-17

- chore: ignore .graphify_root symlink (#1082) (162c03b)
- build(frontend): bundle the SPA from Go with esbuild, drop the Node stage (#1080) (01137df)

## dev-20260915_1855 — 2026-09-15

- fix(deps): update go-dependencies (#1069) (d52e508)

## dev-20260915_1848 — 2026-09-15

- Migrate off deprecated nhooyr.io/websocket to coder/websocket (#1076) (cd61de7)

## dev-20260915_1842 — 2026-09-15

- Add per-route rate limits to GET /api/backup and image uploads (#1075) (4887d2c)
- fix: correct false claim in Go builder Dockerfile comment (#1074) (bc238b2)

## dev-20260914_1557 — 2026-09-14

- fix: guard SSRF-exposed HTTP clients, fix dev-only route gate, pin builder digest (#1072) (820aabd)

## dev-20260914_1552 — 2026-09-14

- Release v3.0.2 (#1041) (#1073) (69a71e0)
- fix: allow explicitly clearing a stored MQTT broker password (#1071) (4c00850)

## dev-20260914_1514 — 2026-09-14

- chore(deps): update docker/setup-qemu-action digest to 1f40c72 (#1064) (ef95881)
- chore(deps): update github/codeql-action digest to b96794f (#1065) (4669f33)
- chore(deps): update alpine docker tag to v3.24 (#1066) (9bd77bd)
- chore(deps): update golang docker tag to v1.27 (#1068) (15a1ff9)
- chore(deps): lock file maintenance (#1070) (ac76a9d)

## dev-20260914_0841 — 2026-09-14

- chore(deps): update dependency vite to v8.3.0 (#1067) (54c2504)

## dev-20260913_1748 — 2026-09-13

- Escape world-map tooltip names and consolidate HTML-escaping helpers (#1059) (dd66853)

## dev-20260912_0548 — 2026-09-12

- Move Gaggiuino firmware update status/trigger onto the machines list row (#1047) (b537d5d)

## dev-20260911_1942 — 2026-09-11

- Add Gaggiuino firmware update UI and release-channel selector (#1045) (e6501ff)
- fix(go): log and fast-retry a silent firmware-release match miss (#1043) (4929e47)
- docs: "app" terminology, trimmed armv7 note, README screenshot grid, machine valve fields (#1040) (7fe9efa)

## dev-20260910_2022 — 2026-09-10

- fix: machine firmware check degrades gracefully when GitHub is unreachable (#1038) (d0b2d59)

## dev-20260910_1611 — 2026-09-10

- Merge remote-tracking branch 'origin/main' into dev (efe5659)
- Release v3.0.1 (#1036) (fe6fa8b)

## dev-20260910_1557 — 2026-09-10

- Fix README screenshots, bump to Node 24, dev-stats SVG charts (#1035) (7a784bc)

## dev-20260909_2007 — 2026-09-09

- Resync dev with main after v3.0.0 release (de04591)
- Merge pull request #1030 from mxkissnr/release/v3.0.0 (4aabcf4)
- Release v3.0.0 (5c34e3e)

## dev-20260909_1939 — 2026-09-09

- Remove the legacy Node.js backend (Go-only for 3.0.0) (#1029) (ff18bc3)

## dev-20260909_1810 — 2026-09-09

- Merge pull request #1026 from mxkissnr/cutover/977-go-backend-flip (137ea62)
- Fix 7th round of code review findings on #977 backend cutover (9e07ccf)
- Fix 6th round of code review findings on #977 backend cutover (2243be0)
- Fix 5th round of code review findings on #977 backend cutover (df79ef0)
- Fix code review findings on #977 backend cutover (chown handling, config dedup) (4th review pass) (77efdec)
- Finish 3rd review-pass fixes (previous commit missed the modified files) (3fb6183)
- Atomic marker-based DB backup, cache registry debug check, drop dead go/ files (3rd review pass) (74729d4)
- Multi-arch docker-smoke, needs:go-test, required-checks fix (2nd review pass) (bdaf173)
- Fix code review findings on #977 backend cutover (WAL backup, CI smoke test, dedup) (fb9fdb2)
- Wire debug_logging, delete obsolete Go CI workflows, harden AppArmor notice (#977 follow-up) (4d463fa)
- Cutover production image to the Go backend (#977) (2d1c4a5)

## dev-20260907_2040 — 2026-09-07

- Merge pull request #1025 from mxkissnr/fix/1024-worldmap-light-theme (e7a79db)
- fix: resolve bean-label text-outline halo from theme too (484185e)
- fix: resolve world map colors from the active theme instead of dark literals (b297e39)

## dev-20260907_1858 — 2026-09-07

- Merge pull request #1023 from mxkissnr/fix/1021-accent-ink-contrast-audit (4cf4a1a)
- fix: sync DOCS.md wording, trim verbose CHANGELOG entry, drop redundant accent apply call (8dc5787)
- fix: light-theme --accent-ink contrast audit for the 8 THEME_PRESETS (ca7e56b)

## dev-20260907_1818 — 2026-09-07

- Merge pull request #1022 from mxkissnr/feat/1019-unify-accent-theme-presets (8f1ddb8)
- fix: remove dead unreachable-accent-clear branch in applyActiveMachineAccentTheme (74a1aed)
- feat: unify accent theme picker with the 8 named machine theme presets (fc52b49)

## dev-20260907_1503 — 2026-09-07

- fix: theme toggle active state + add Auto (system) option (#1020) (d3162a6)

## dev-20260907_1410 — 2026-09-07

- fix: detect mid-session SSE staleness, not just first-connect failure (#1017) (f1aa5fb)

## dev-20260907_1358 — 2026-09-07

- fix: detect mid-session SSE staleness, not just first-connect failure (#1017) (f1aa5fb)

## dev-20260907_1046 — 2026-09-07

- Merge pull request #1015 from mxkissnr/chore/go-preview-trigger-dev (3e2b654)
- chore(ci): trigger go-preview-publish from dev instead of go-migration (188f3f3)

## dev-20260907_1040 — 2026-09-07

- Merge pull request #1014 from mxkissnr/fix/codeql-alerts-94-95-96-98-100 (feebc6f)
- fix: resolve 5 pre-existing CodeQL alerts (#94, #95, #96, #98, #100) (4757b31)

## dev-20260907_0940 — 2026-09-07

- Merge pull request #1012 from mxkissnr/sync/dev-into-go-migration-0907 (7aae0f0)
- Merge remote-tracking branch 'origin/dev' into sync/dev-into-go-migration-0907 (6ae208b)
- docs: fix outdated 'Install via HACS' wording for bundled cards (#1008) (2b62d07)
- Feature/gaggimate profile editor (#996) (d05f594)
- docs(go): preserve SQLite driver spike decision doc (#958) (#1002) (d4d51cc)
- Security audit #977 round 3 follow-up: govulncheck gate (#998) + dedicated rate limits (#999) (#1001) (2f813cb)
- fix(go): security audit #977 round 3 — DB guard, toolchain pin, Docker digests (#1000) (3fb92a6)
- fix(go): GaggiMate parser hardening — index.bin cap, sampleSize floor, panic recovery (#994) (64b7285)
- fix(go): SSRF hardening round — reconnect revalidation, DNS-rebinding pin, MQTT guard, registry-facade doc (#990) (f5e8599)
- docs: fix uneven screenshot grid in README (bda1c8f)
- feat(go): surface descale operation mode as isDescaling in MachineStatus/SSE (#984) (a2f5346)
- Revert "fix: record sync error on unreachable GaggiMate history + float-tolerant wl parsing" (51343bc)
- fix: record sync error on unreachable GaggiMate history + float-tolerant wl parsing (76afac3)
- style: gofmt four files flagged by CI (553cfaf)
- Merge branch 'mxkissnr:go-migration' into go-migration (9cff22a)
- fix(go): scale card-render pool with GOMAXPROCS instead of fixed size 2 (#982) (01777ab)
- docs(readme): update GaggiMate feature row — water sensor, weight label (e743923)
- docs: update GaggiMate capabilities — water sensor, weight label (c0af6dc)
- fix(ui): hide Live-Verbindung settings card for GaggiMate (3748026)
- perf(sidebar): debounce shot search input (#975) (8f98c63)
- ci(go-preview): rebuild image on any non-doc push to go-migration (#974) (973367d)
- perf: lazy-build collapsed month groups + index sidebar search by id (#969) (#970) (#972) (51ab6a3)
- perf(go): throttle sidebar rebuild during background shot-meta walk (#969) (#971) (0792d7a)
- fix(ui): distinguish real vs estimated weight in shot chart (e33f12d)
- feat(ui): add water sensor setting and idle water level display (e6f17c0)
- fix(go/system): gate GaggiMate wl field on has_water_sensor (e116bbe)
- feat(go/machines): add has_water_sensor flag to machine model (5afc8e7)
- feat(go/machines): add GaggiMate binary shot-history sync (0fd094d)
- fix(go): report shots present in the streamed zip restore preview (#968) (d6c5b08)
- feat: progress bars for backup/restore and dev-channel DB transfers (#960) (#965) (e3e6a67)
- feat(go): optimize stored entity images — downscale, strip EXIF, thumbnails (#961) (#964) (2ac18ec)
- ci: run the Go gate on pull requests, not just go-migration pushes (7f240f7)
- perf(go): streaming + atomic backup import, transactional structured restore (#959) (#963) (b313997)
- ci: CodeQL Go leg uses autobuild (no build-mode: none for Go) (8883f20)
- ci: add Go to the CodeQL language matrix (1c65cdb)
- perf(go): shrink warm RSS — resvg pool 3->2 + GOMEMLIMIT (#956) (23bee3b)
- feat: keyset-paginated GET /api/shots + lazy curve loading (#957) (#962) (e16c5cc)
- perf(go): gate the achievements full-context scan behind a change fingerprint (#956) (b2bc4bb)
- perf(go): concurrent WAL reader pool for SQLite, stop head-of-line blocking (#956) (e395706)
- fix(go): match null-in-series scoring to the map path + keep resvg slots warm on render error (#951) (cf5c31e)
- feat(go): persistent GaggiMate live client, stop the per-tick WS hammer (#952) (29793ba)
- feat(go): port the automatic shot-sync triggers (#953) (92c1c2e)
- fix(go): coalesce buffered live-snapshot SSE frames on a slow consumer (#901) (6052714)
- test(bench): harden the Node-vs-Go harness against rate limiting + SSE false alarms (#951) (d707d7c)
- perf(go): fold grinder wear in one shot scan for GET /api/library (#951) (240356a)
- perf(go): pool warm resvg contexts for the share card (#951) (58bd8c6)
- perf(go): keep /shots.json datapoints raw + goccy encoder (#951) (54e7a01)
- test(go): add a live Node-vs-Go performance benchmark harness (#951) (ceacab5)
- fix(go): accept URL-safe HA ingress tokens in the path-prefix verdict (#901) (ff23165)
- feat(go): add an HA-ingress self-diagnostic to internal/debug (#901) (5d4c5d6)
- Merge remote-tracking branch 'origin/dev' into go-migration (f06313c)
- refactor(go): extract buildApp + add an HA-ingress smoke test (#901) (af85e68)
- test(go): Node-vs-Go route-parity check, wired into CI (#901) (1f92bdd)
- test(go): extend Phase-2 contract-test coverage (#901) (2b2da64)
- feat(go): port the debug routes (#901) (2cd65b0)
- feat(go): port the share-card PNG renderer (#901) (2392282)
- feat(go): port the MQTT live-data transport (#901) (96d229b)
- feat(go): port the bean-import domain (#901) (f71e0cd)
- feat(go): port the achievements ("stamp card") domain (#901) (4a20791)
- feat(go): port geocodeBean + the trivial system/machine-control routes (#901) (3757898)
- build(go): add frontend build stage to the Docker image and Makefile (#901) (01c5bcf)
- feat(go): serve the Vite SPA from the binary, move templ pages under /ui/ (#901) (721491a)
- feat(go): port BREW_AUTO auto-stop, live idle stats + steam/flush states, milk restock (#901) (d9eb10f)
- Merge remote-tracking branch 'origin/dev' into go-migration (803b1b7)
- fix(go): deterministic tiebreak for comparative grind-advice bucket selection (#901) (3b0a488)
- fix(go): wire orders-update SSE publish onto the REST API's Service instance too (#901) (6d8de01)
- fix(go): reject null in boiler settings numeric fields (#901) (e0c06df)
- docs(go): update README Status/Frontend sections for this round's four packages (#901) (fd9f7d3)
- feat(go): A/B compare mode, ghost-curve overlay, score-delta chip, comparative grind-advice panel on shot detail (#901) (64a9d0e)
- feat(go): port calcComparativeGrindAdvice as internal/shots.ComputeComparativeGrindAdvice (#901) (6dfe07b)
- feat(go): real SSE live-update for the Orders queue, replacing 10s polling (#901) (15fecf2)
- feat(go): make boiler/system Settings editable with real field-level validation (#901) (3a96082)
- feat(go): freshness/firmware/ordered-by badges on the Shots list (#901) (fdacd83)
- feat(go): full Edit UI for Library and Machines pages (#901) (dbaa06f)
- refactor(go): extract library/machine PUT handlers into exported update.go service functions (#901) (54822b9)
- feat(go): Shots master-detail view with metrics, verdict, and chart (6bc68bb)
- fix(go): correct dangling README cross-reference in layout.templ (9a0bb7a)
- feat(go): fixed left icon sidebar replaces the top-tab menu (e383dd2)
- fix(go): correct README's stale Library/Settings "read-only" claims (#901) (ee08d44)
- feat(go): verdict-first default-machine status on the Machines page (#901) (5b0f644)
- feat(go): verdict-first due/soon/ok summary on the Maintenance page (#901) (f8a0ef9)
- feat(go): stock bars for Beans/Milks on the Library pages (#901) (8b0dd20)
- fix(go): restore styled htmx error fragments with a generic class (38d17bf)
- feat(go): Verdict header for Shots list + read-only tone for Settings (#901) (532a855)
- feat(go): port Instrument design-token system onto templ frontend (#901) (740ae98)
- fix(go): address code-review findings on Settings/Library/Machines forms (#901) (0bd9aad)
- feat(go): Create/Edit forms for Library, Machines, and all 5 Settings categories (#901) (35afcbc)
- fix(go): raise GET /api/token rate limit for genuine Ingress callers (#901) (fda1212)
- fix(go): X-Frame-Options DENY -> SAMEORIGIN, blocked HA sidebar panel embed (02affd9)
- fix(go): make every template href/src/hx-* path Ingress-safe (#901) (290dcfe)
- fix(go): register GET / so HA Ingress's base URL stops 404ing (38d8aaa)
- fix(go): wire GLP_DEV_BUILD through the go-preview image build (#901) (cbe833e)
- feat(go): publish workflow + AppArmor profile for the Go preview beta channel (#901) (d7f0258)
- fix(go): stream real container logs and avoid per-tick docker cp in smoke-test.sh (31d094f)
- feat(go): Phase 4 multi-arch build-only CI for the Go rewrite (#901) (0cecd42)
- fix(web): parallelize settings page category fetches (#901) (8455530)
- feat(go): Phase 2e Maintenance/Settings/Backup frontend pages (#901) (2fee56a)
- fix(go): move order status HA-notify onto Service, not REST-only Handlers (#901) (5c02f61)
- feat(go): Phase 2d Orders-domain frontend pages (#901) (54271b4)
- feat(go): Phase 2c Machines-domain frontend pages + live shot chart (#901) (5e3f162)
- fix(go): address #901 Phase 2b code-review findings (#901) (ead6bba)
- feat(go): Phase 2b Library-domain frontend pages (#901) (bdcbdf6)
- Fix glp-token.js Ingress path resolution and htmx request race (#901) (a454956)
- Exclude vendored web assets from ESLint (#901) (033bdd3)
- fix(go): wire X-GLP-Token into htmx write requests structurally (#901) (cccdc7b)
- fix(go): address #901 code review findings on web frontend foundation (b86cf6c)
- Go migration Phase 2a: templ+htmx+Alpine frontend foundation + GET /shots (#901) (8b058f4)
- fix(go): address #901 code review findings on GET /api/status (4360aa7)
- Go migration Phase 3b: GET /api/token + GET /api/status, shared decodeJSONBody (#901) (3e89ec3)

## dev-20260907_0630 — 2026-09-07

- fix: resync package-lock.json to fix npm ci in CI (#1010) (b220306)
- chore(deps): lock file maintenance (#1006) (71cc1da)
- chore(deps): update dev-dependencies to v5 (#1005) (6fd7683)

## dev-20260907_0532 — 2026-09-07

- chore(deps): update docker/setup-qemu-action digest to 1f40c72 (#1003) (3a1e763)
- chore(deps): update dev-dependencies (#1004) (2bd7a90)
- docs: fix uneven screenshot grid in README (#985) (d193d9a)

## dev-20260905_0946 — 2026-09-05

- fix: stop achievement re-evaluation storm from hanging bulk restore (#979) (7747a8f)

## dev-20260905_0852 — 2026-09-05

- perf(sidebar): debounce shot search input (#976) (117afd3)

## dev-20260905_0825 — 2026-09-05

- perf: lazy-build collapsed month groups + index sidebar search by id (#969) (#970) (6087de8)

## dev-20260903_1835 — 2026-09-03

- fix: build annotation library <select>s via DOM API, not innerHTML (#966) (801ca0b)

## dev-20260903_0709 — 2026-09-03

- fix: dispatch GaggiMate default machine live poll + sync by adapter type (#955) (40570ce)

## dev-20260902_1208 — 2026-09-02

- docs+ci: add PR guidelines and mandatory AI assistance disclosure (#950) (1a29543)

## dev-20260831_1658 — 2026-08-31

- chore: hold Node v24 bump, announce armv7 deprecation (#945) (626e021)
- chore(deps): lock file maintenance (#938) (5c5dff5)

## dev-20260831_1637 — 2026-08-31

- fix(deps): update dependency zod to v4.5.4 (#936) (0440922)

## dev-20260831_1626 — 2026-08-31

- fix: audit follow-up — secret-safe gitignore, ready-by scope comment, coverage thresholds (#943) (94d75e5)

## dev-20260830_1725 — 2026-08-30

- Merge pull request #935 from mxkissnr/release/v2.36.1 (f76c652)
- Merge origin/main into release/v2.36.1 (0b53f90)
- release: v2.36.1 — bean/milk stock fixes, exhausted bean picker, dark-theme autofill (b1fcd35)
- chore(config): migrate config renovate.json (#929) (ccc5ab6)

## dev-20260830_1637 — 2026-08-30

- fix: keep exhausted beans selectable in the shot annotator (#934) (95d689c)

## dev-20260830_1633 — 2026-08-30

- fix: correcting bean/milk stock now sets the actual amount, not an overwrite (#932) (dcbf4f4)

## dev-20260830_1617 — 2026-08-30

- chore(deps): lock file maintenance (#926) (e128003)
- chore(deps): update node.js to 83f487e (#923) (4e28a75)
- chore(deps): update dependency js-yaml to v5.4.1 (#925) (dc689f6)
- chore(deps): update github/codeql-action digest to cdf488f (#927) (ad844c5)
- fix(deps): update dependency axios to v1.20.0 (#928) (7e0926d)

## dev-20260826_1813 — 2026-08-26

- chore(deps): update dependency eslint to v10.9.1 (#924) (ab524e5)

## dev-20260825_1355 — 2026-08-25

- fix: harden .lib-item-sub against WebView text-overflow ellipsis failures (#920) (6579ba6)

## dev-20260825_1352 — 2026-08-25

- fix: neutralize browser autofill white background on dark-theme inputs (#922) (0fe8e61)
- docs: add CHANGELOG entries for napi-rs/canvas and codeql-action bumps (#910, #909) (c946458)

## dev-20260824_1522 — 2026-08-24

- chore(deps): update github/codeql-action digest to db488dd (#909) (7581a72)
- chore(deps): update dependency @napi-rs/canvas to v1.0.8 (#910) (4722d81)

## dev-20260824_1141 — 2026-08-24

- Merge pull request #919 from mxkissnr/release/v2.36.0 (aafe7bd)
- Release v2.36.0: idle Live stats, steam/flush live states, docs/screenshots/dev-stats refresh (2be925b)

## dev-20260824_1112 — 2026-08-24

- Merge pull request #918 from mxkissnr/fix/913-live-catch-unreachable (9a680fb)
- Merge dev into fix/913-live-catch-unreachable (393d8dc)
- fix: clear stale live data on a network-level fetch failure (d9b6aee)

## dev-20260824_1110 — 2026-08-24

- Merge pull request #917 from mxkissnr/fix/915-bean-picker-exhausted-stock (163d2f1)
- Merge dev into fix/915-bean-picker-exhausted-stock (3f6c553)
- fix: hide exhausted beans from the shot-annotation bean picker (2f3d6ca)

## dev-20260824_1103 — 2026-08-24

- Merge pull request #916 from mxkissnr/fix/914-mobile-power-button (5a536b5)
- fix: add mobile topbar power toggle (#railPowerBtn) (c097fc7)

## dev-20260824_1023 — 2026-08-24

- feat: Live tab idle machine stats + steam/flush live states (#908) (07f778b)
- chore(deps): update dev-dependencies (#911) (57766c1)

## dev-20260824_1017 — 2026-08-24

- fix: end the live brew immediately on BREW_AUTO auto-stop (#907) (a4ed788)
- Merge pull request #902 from mxkissnr/dev (c116c3b)

## dev-20260820_0502 — 2026-08-20

- fix: revert Docker base image from node:24-slim to node:22-slim, restoring armv7 support (490ad6b)

## dev-20260819_2148 — 2026-08-19

- Merge main into dev: resolve release v2.35.0 conflicts (5120716)
- fix: put Renovate config on main with baseBranches: dev (#879) (1a51367)
- chore(deps): Bump js-yaml in /gaggiuino-local-profiler (#854) (296bc46)
- chore(deps): Bump @napi-rs/canvas in /gaggiuino-local-profiler (#853) (fd5ad8d)
- chore(deps): Bump @napi-rs/canvas in /gaggiuino-local-profiler (#828) (edabe36)
- chore(deps-dev): Bump globals (#827) (2908d82)

## dev-20260819_2142 — 2026-08-19

- Release v2.35.0: finalize CHANGELOG, bump version, refresh docs/screenshots/dev-stats (118a9aa)

## dev-20260819_2121 — 2026-08-19

- chore(deps): update docker/setup-buildx-action digest to 37fe631 (#892) (ac2605c)

## dev-20260819_2104 — 2026-08-19

- chore(deps): update node.js to v24 (#900) (896641b)

## dev-20260819_2059 — 2026-08-19

- chore(deps): update node.js to d649c27 (#894) (e56db27)
- chore(deps): update github/codeql-action digest to ff2f1c6 (#893) (55cc5f4)

## dev-20260819_2050 — 2026-08-19

- chore(deps): update dependency node to v24 (#898) (e4d96a4)
- chore(deps): update dependency js-yaml to v5.3.0 (#897) (15f1a9f)
- chore(deps): update dev-dependencies (#896) (b535114)
- chore(deps): update dependency @napi-rs/canvas to v1.0.7 (#895) (8aae389)

## dev-20260819_2015 — 2026-08-19

- chore: bump version only at release time, not per dev commit (#891) (f443bb8)

## dev-20260819_1930 — 2026-08-19

- fix: RGB easter egg rotates the icon's own colour, clip topbar icon, floor bean stock display at 0 (#889) (2ec0976)

## dev-20260819_1749 — 2026-08-19

- fix: correct stale dependency-review-action version comment (#884) (939f036)

## dev-20260819_1738 — 2026-08-19

- chore: consolidate test.yaml and version-release-check.yaml (#881) (0e37101)

## dev-20260819_1735 — 2026-08-19

- chore: add job timeout, retry-wrap the Playwright Chromium install step (#883) (e11907a)

## dev-20260819_1518 — 2026-08-19

- chore: switch from Dependabot to Renovate (#876) (f61619e)

## dev-20260818_2104 — 2026-08-18

- Share card: band-system stats grid and corrected chart phase tint (#874) (abb62ce)

## dev-20260818_2001 — 2026-08-18

- fix: split Bohne & Mühle into two separate recipe cards (#872) (8ec7a2c)

## dev-20260818_1833 — 2026-08-18

- fix: replace ice-cube grid icon with a geometric snowflake (#870) (be67055)

## dev-20260818_1820 — 2026-08-18

- fix: drop basket/puck screen from shot detail bean/grinder line (#868) (5c90d6d)

## dev-20260818_1749 — 2026-08-18

- fix: move shot score between title and hero photo on mobile (#866) (b99d6f0)

## dev-20260818_1721 — 2026-08-18

- feat: show the shot hero photo on mobile instead of the tiny thumb (#864) (35b8a56)

## dev-20260818_1553 — 2026-08-18

- fix: push #main/#sidebar down below the dev-build banner on mobile (#862) (fbc2656)

## dev-20260818_1532 — 2026-08-18

- fix: wrap Coffee Library action buttons instead of overflowing off-screen on mobile (#860) (1cbcd4e)

## dev-20260818_1518 — 2026-08-18

- feat: show a visible paused-age badge on frozen coffee portions (#856) (#857) (21c444f)

## dev-20260818_1444 — 2026-08-18

- fix: shot hero photo panel renders as a circle again (ba2e14d)

## dev-20260817_2119 — 2026-08-17

- Add shot detail hero photo panel and split puck screen onto its own line (#852) (ecfd40a)

## dev-20260817_2052 — 2026-08-17

- fix: clip easter egg panel rainbow to icon, make colour uniform (#849) (2be28e0)

## dev-20260817_2040 — 2026-08-17

- fix: dedupe topbar machine icon, fix rainbow coverage (#847) (c3b958a)

## dev-20260817_1952 — 2026-08-17

- Remove redundant verdictSubline duplicating topTitle and beanGrinderVal (#844) (ddba421)

## dev-20260817_1938 — 2026-08-17

- style: render the steam knob black instead of chrome (#843) (0657e8e)

## dev-20260817_1913 — 2026-08-17

- fix: constrain topbar machine icon to 44px via ID specificity (#840) (865cf2c)

## dev-20260817_1904 — 2026-08-17

- Add animated machine icon as an ambient topbar widget + click easter egg (#837) (#838) (e2582f4)

## dev-20260817_1813 — 2026-08-17

- fix(docs): crop screenshots to view container instead of full viewport (#836) (4cbd9e9)
- chore: second empty commit for clean Gitea Actions guard verification (#834) (77c955e)
- chore: empty commit to verify Gitea Actions guard (#834) (86b3d31)

## dev-20260817_1635 — 2026-08-17

- fix: skip GitHub-only CI workflows on the local Gitea mirror (a0bc913)

## dev-20260816_1705 — 2026-08-16

- fix: migrate raw font-size:.85rem literals onto the type scale (#832) (#833) (0b64949)

## dev-20260816_1205 — 2026-08-16

- Reduce duplicate info on shot detail screen and sidebar (7426508)

## dev-20260816_1142 — 2026-08-16

- Close out #760: escape the one real gap the CodeQL false-positive audit surfaced (a183c79)

## dev-20260816_1128 — 2026-08-16

- Remove dead shot-count DOM lookups left over from the flap-board flattening (c28af70)
- Show last-used grind setting in the Library bean list (7e7cbc0)

## dev-20260816_1112 — 2026-08-16

- Merge pull request #826 from mxkissnr/release/v2.34.0 (dfb8342)
- Release v2.34.0: finalize CHANGELOG, bump version, refresh docs/screenshots/dev-stats (590e4f9)

## dev-20260816_0730 — 2026-08-16

- fix: flatten sidebar shot-count header from split-flap odometer to plain text (#823) (#825) (2754bce)

## dev-20260816_0725 — 2026-08-16

- Merge pull request #821 from mxkissnr/fix/820-chip-active-fill (b148878)
- Merge pull request #824 from mxkissnr/feat/822-static-machine-icon (4ea0e3d)
- Give static machine icons per-type geometry (Gaggiuino vs GaggiMate) (5a2326b)
- Convert three remaining filled-pill toggles to the bordered chip pattern (d6cc238)

## dev-20260816_0701 — 2026-08-16

- Merge pull request #819 from mxkissnr/fix/811-share-card-verdict (b0f3cb1)
- Share Card: score ring becomes typographic verdict, chart loses its box (6ec2f6d)

## dev-20260816_0657 — 2026-08-16

- Merge pull request #818 from mxkissnr/fix/811-shots-view-boxes (98ae9cb)
- Shots view: de-box the verdict line, grind-advice colors, sidebar avatar, topnav pill (581885d)

## dev-20260814_2041 — 2026-08-14

- Merge pull request #815 from mxkissnr/feat/811-instrument-tokens (8d37538)
- Catch the orders_types_saved sibling the icon sweep missed (550d94c)
- Replace the last text-glyph buttons and status glyphs with drawn icons (7108259)
- Add the missing CHANGELOG entry for the score-colour fix (f266d2d)
- Match the share card's score colour to the app's own rule (2febf53)
- Pull the share card onto the #811 tokens and always show an install code (357021e)
- Stop a comment from breaking the stylesheet, and guard the class (47fd1af)
- Add the stamp card view for the achievement catalogue (6e71ffd)
- Add achievement copy in six languages, and the tests that were missing (d73f9ad)
- Merge the chart theming work into the redesign branch (318ae9a)
- Wire the animated machine icon into the Live view (a851221)
- Add the achievements backend: schema, registry and event evaluation (2bac080)
- Add animated machine icon with live states (#811) (bbb98c3)
- Resolve chart and banner colours from the theme tokens (2e67197)
- Give the fill-styled buttons a themed surface (f091b87)
- Replace the shot view's tile walls and score ring with type (82aec2e)
- Replace the remaining emoji UI glyphs with drawn icons (03e0e3b)
- Regenerate the README screenshots for the new token layer (888d9f3)
- Make text on a semantic fill readable, and audit that direction (ee91032)
- docs: log the stylesheet token-application work in CHANGELOG (bde8f87)
- style: map padding/margin/gap onto the --sp spacing ladder (19bdfab)
- style: replace inline #52525b with the themed --gray-600 token (f9a13f3)
- style: collapse repeated font-family declarations to one inherited rule (fc1e7c3)
- style: border diet -- full borders only around clickable things (218d3a6)
- style: replace hardcoded #fff with themed role tokens (ba8236a)
- style: map font-size literals onto the --fs scale, drop uppercase labels (410c226)
- Move the token layer to cool graphite and fix the contrast failures under it (b5e665b)

## dev-20260812_1543 — 2026-08-12

- ci(dev-channel): retry the GHCR push once after a rate-limit failure (#810) (73129b9)

## dev-20260812_1530 — 2026-08-12

- Explain a closed direct port instead of showing a bare HTTP 401 (#808) (d882599)

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

