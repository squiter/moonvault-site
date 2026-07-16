---
title: "Pausing Linux Builds for Moonvault"
description: "Moonvault is pausing official Linux builds for now so paid GitHub Actions time can stay focused on the macOS and Windows builds most players are using."
---

The vault has a very practical trap room today: build minutes.

Moonvault is pausing official Linux builds for now. macOS and Windows builds will continue as the supported desktop downloads, while the Linux release step is being disabled in the release workflow.

This is not a dramatic door slam. It is a table-management call.

## Why the Linux build is taking a rest

Moonvault now pays for GitHub Actions usage, and every release build has a cost. Linux packaging adds another runner, another dependency setup, another bundle, another upload, and another updater entry to verify before a release can leave the dungeon.

Right now, the best use of that paid build time is to keep the macOS and Windows releases steady. Those are the platforms with the clearest day-to-day demand, and they already need careful testing around installers, app updates, and desktop packaging.

Linux support deserves attention, not a neglected checkbox. If I keep publishing Linux builds, I want them to be builds I can actually stand behind instead of artifacts that merely happened to survive the release ritual.

## What changes now

The public Moonvault download pages will list macOS and Windows only. Future release automation will no longer build or surface Linux packages.

Existing Linux artifacts from older releases are not being turned into smoke. If you already downloaded one, it remains what it was. The change is about new official builds going forward.

## Could Linux builds come back?

Yes.

If you use Moonvault on Linux and want official Linux builds back, please reach out to me. Knowing that someone is actively depending on those builds changes the math in a useful way. A real table, a real workflow, and a real need are much better signals than a lonely CI job eating coins in the dark.

For now, Moonvault keeps marching on macOS and Windows, with the build budget pointed where it helps the most people at the table.

Thanks for understanding, and thanks for caring enough about the vault to read the note pinned to this particular dungeon door.
