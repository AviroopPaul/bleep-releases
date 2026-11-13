# bleep

A little droid that floats on your Mac. It watches your Claude Code and Codex sessions, your mail and your calendar. It handles the small asks and tells you what needs you.

Site: https://bleep-omega.vercel.app

This repo holds only the downloads. The source is private.

## Install

1. Download **bleep-mac.dmg** from the [latest release](https://github.com/AviroopPaul/bleep-releases/releases/latest).
2. Open it and drag **bleep** into **Applications**.
3. Open bleep. macOS blocks the first launch because this build is not notarized by Apple yet.
4. Go to **System Settings > Privacy & Security** and click **Open Anyway**.
5. The setup window opens. It checks Claude Code, connects Google, and can install hooks for Claude Code and Codex.

## Needs

- A Mac with Apple silicon, on macOS 15 or later.
- Claude Code, installed. bleep signs in to Claude once during setup.

## Remove

Quit bleep from its menu bar icon. In Settings > Agents, remove the hooks. Then delete bleep from Applications and the `~/.bleep` folder.
