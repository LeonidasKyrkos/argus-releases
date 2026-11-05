# Argus releases

Downloads for [Argus](https://github.com/LeonidasKyrkos/argus), a macOS app for
running coding agents across git worktrees.

## Install

Download the `.dmg` from the [latest release](https://github.com/LeonidasKyrkos/argus-releases/releases/latest),
open it, and drag **Argus** into **Applications**. Argus needs a Mac with
Apple Silicon.

## Updates

Argus checks this repo for a newer release when it launches, every six hours,
and from **Argus → Check for Updates…**. When it finds one, it downloads it in
the background and shows **Restart to update** in the sidebar.

## What's here

Each release carries the `.dmg`, the `.app.tar.gz` the in-app updater installs,
and `latest.json`, the file the updater reads. Releases are published by the
`just release` script in the Argus repo; this repo holds no source code.
