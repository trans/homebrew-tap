# Homebrew tap for bai

This tap packages [`bai`](https://github.com/trans/bai), a small AI
shell-command helper that proposes commands and leaves execution to you.

## Install

```sh
brew tap trans/tap
brew install bai
```

## Verify

```sh
bai --version
bai --show-config --no-copy
```

## Upgrade

```sh
brew update
brew upgrade bai
```

The formula builds `bai` from the tagged source release. Clipboard copy on macOS
uses the built-in `pbcopy` command.
