# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repo is

A Home Assistant app-store manifest, not a source repository. It exists only so the maintainer
can install unreleased builds of `gaggiuino-local-profiler` (the `dev` branch) on a real HA
instance, side-by-side with the stable app, without affecting real users. There is no application
code here — only `gaggiuino_local_profiler_dev/config.yaml`, `icon.svg`/`icon.png`, and
`CHANGELOG.md`.

## Do not hand-edit `version:` in config.yaml

`.github/workflows/build-dev.yaml` in the main `gaggiuino-local-profiler` repo rewrites
`version:` on every push to its `dev` branch — that timestamp string (`dev-YYYYMMDD_HHMM`) is
what makes Home Assistant offer an update, and it is *not* the app's real semantic version (that
lives in the main repo). Manual edits here get overwritten by the next dev push.

## `options`/`schema` drift is a known trap

The auto-bump workflow syncs `version:` and the `options`/`schema` blocks from the main repo's
`config.yaml` (`scripts/sync-dev-config.mts`, #805; trailing comments fixed in #1920). Every
other top-level key — e.g. `backup: cold` (#1849) and `backup_exclude` — is NOT synced: when the
stable app changes one of those, mirror it here by hand or it silently drifts out of sync.

## Coexistence with the stable app

Slug `gaggiuino_local_profiler_dev` (vs. stable's `gaggiuino_local_profiler`) gives it fully
separate HA storage, ingress port (8098 host-side vs. 8099), and sidebar entry — the two can run
at once without either touching the other's data.
