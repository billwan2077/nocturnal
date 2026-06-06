# Reference Notes

Cached on 2026-06-06 while modernizing this fork.

## Upstream

- Source repository: `https://github.com/joshjon/nocturnal`
- Checked out branch: `origin/master`
- Checked out commit: `fc90a0d` (`update brew install command (#33)`)

## Dependency Checks

- `sindresorhus/LaunchAtLogin`
  - Latest tag checked: `v5.0.2`
  - Its README says apps targeting macOS 13 or later should use `sindresorhus/LaunchAtLogin-Modern` instead.
- `sindresorhus/LaunchAtLogin-Modern`
  - Latest tag checked: `v1.1.0`
  - SwiftPM product: `LaunchAtLogin`
  - Minimum package platform: macOS 13
- `shpakovski/MASShortcut`
  - Latest tag checked: `2.4.0`
  - No `Package.swift` was present at that tag, so it remains a Carthage dependency.

Remove this file when the project no longer needs the cached migration notes.
