# bleep

A little droid that floats on your Mac. It watches your Claude Code and Codex sessions, your mail and your calendar. It handles the small asks and tells you what needs you.

Site: https://bleep-omega.vercel.app

This repo holds only the downloads. The source is private.

## Install

Pick one, in Terminal:

```sh
brew install --cask AviroopPaul/tap/bleep
```

```sh
curl -fsSL https://bleep-omega.vercel.app/install.sh | sh
```

Both check the download against its SHA-256, put bleep in Applications and let macOS open it. Then press Cmd+Space and type bleep. A short setup checks Claude Code, connects Google, and can install hooks for Claude Code and Codex.

Downloading `bleep-mac.dmg` in a browser also works, but macOS blocks the first launch because the build is not notarized. Use System Settings > Privacy & Security > Open Anyway once.

## Needs

- A Mac with Apple silicon, on macOS 15 or later.
- Claude Code, installed. bleep signs in to Claude once during setup.

## Remove

In bleep Settings > Agents, remove the hooks. Then `brew uninstall --cask --zap bleep`, or quit bleep and delete it from Applications and the `~/.bleep` folder.
