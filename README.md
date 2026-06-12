# Dash0 CLI — Homebrew tap

This is the official [Homebrew](https://brew.sh) tap for the [Dash0 CLI](https://github.com/dash0hq/dash0-cli).

Install:

```sh
brew install dash0hq/dash0-cli/dash0
```

Homebrew strips the `homebrew-` prefix, so the tap shortname is `dash0hq/dash0-cli`.
The qualified install path above auto-discovers and trusts this tap on Homebrew 6.0+ — no separate `brew tap` or `brew trust` step is required.

The formula is generated automatically on each release by [goreleaser](https://goreleaser.com) running in the [main repository](https://github.com/dash0hq/dash0-cli).
Do not edit `Formula/dash0.rb` directly here — open changes against [`.goreleaser.yaml`](https://github.com/dash0hq/dash0-cli/blob/main/.goreleaser.yaml) in the main repo.

For source, issues, and documentation, see the [main repository](https://github.com/dash0hq/dash0-cli).