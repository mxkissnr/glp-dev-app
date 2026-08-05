# GLP Dev Channel — not for end users

This repository exists so the GLP maintainer can test unreleased builds on a
real Home Assistant instance **without touching the installation that normal
users run**. It ships no source code: it is a Home Assistant app manifest
that points at a container image built from the `dev` branch of
[gaggiuino-local-profiler](https://github.com/mxkissnr/gaggiuino-local-profiler).

**If you are looking for GLP, you want the stable app instead:**
<https://github.com/mxkissnr/gaggiuino-local-profiler>

## What you get if you install this anyway

Unreleased code. It is expected to be broken at times, may corrupt its own
database, and carries no upgrade path — the stable app will not import
anything from it. There are no release notes and no support for this channel.

## How it coexists with the stable app

The dev app uses a different slug (`gaggiuino_local_profiler_dev`), so Home
Assistant treats it as a completely separate app:

| | Stable | Dev |
|---|---|---|
| Slug | `gaggiuino_local_profiler` | `gaggiuino_local_profiler_dev` |
| Data directory | its own `/data` | its own `/data` |
| Web port | 8099 | 8098 |
| Sidebar | GLP | GLP DEV |

Separate slugs mean separate persistent storage, so the dev app can never
write to the stable app's shot archive or coffee library. Both can run at the
same time. Point them at the same machine only if you accept that both will
sync shots from it.

Dev builds are published for **amd64 only** — the stable app still ships
amd64, armv7 and aarch64.

## Maintainer setup

1. Home Assistant → Settings → Apps → Store → ⋮ → Repositories
2. Add `https://github.com/mxkissnr/glp-dev-app`
3. Install **GLP DEV**

Each push to `dev` in the main repository builds a new image and bumps
`version` in this repository's `config.yaml`, which is what makes Home
Assistant offer the update. See `.github/workflows/build-dev.yaml` in the main
repository.
