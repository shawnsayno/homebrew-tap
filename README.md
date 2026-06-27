# shawnsayno/homebrew-tap

Homebrew Cask tap for [NeatWhisky](https://github.com/shawnsayno/NeatWhisky) —
one-click Steam on macOS (a maintained fork of Whisky/Wine, fully open-source
graphics stack).

## Install

```bash
brew install --cask shawnsayno/tap/neatwhisky
```

The cask strips macOS quarantine on install, so NeatWhisky launches on first
open with no extra steps.

## What's here

- `Casks/neatwhisky.rb` — the cask definition. `version` and `sha256` are
  updated automatically by the NeatWhisky release workflow on each release.
```
