# quantizor/homebrew-tap

Homebrew tap for [devctl](https://github.com/quantizor/devctl), an agent-friendly coordinator for many devservers and their unique configurations.

## Install

```sh
brew install --cask quantizor/tap/devctl
```

The fully qualified `quantizor/tap/devctl` trusts only this cask. `brew upgrade` keeps it current; the devctl menu bar app also offers a one-click upgrade when a new version ships.

## Uninstall

```sh
devctl uninstall                                  # agent, hooks, and CLI (keeps your data)
brew uninstall --cask --zap quantizor/tap/devctl  # everything, including data
```

## About this repo

`Casks/devctl.rb` is generated from the canonical template in the devctl repo (`packaging/homebrew/devctl.rb`). On each release, devctl's `Bump Homebrew cask` workflow injects the published version and checksum and pushes here, so the tap is a downstream artifact: open cask issues and pull requests against [quantizor/devctl](https://github.com/quantizor/devctl).
