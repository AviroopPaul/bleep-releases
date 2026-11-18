# bleep downloads

**bleep is a free, open source AI assistant that lives on your Mac.** It watches your Claude Code and Codex sessions, your Gmail and your Google Calendar. It clears the small asks, and taps you only when something needs you.

- **Source code (MIT):** https://github.com/AviroopPaul/bleep
- **Website:** https://bleep-omega.vercel.app

This repo holds only the signed release builds. Please open issues and pull requests in the [source repo](https://github.com/AviroopPaul/bleep).

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
- One of: Claude Code (bleep signs in once during setup), an API key from Anthropic, OpenAI, Gemini, OpenRouter or Groq, or a local model in Ollama or LM Studio.

## Remove

In bleep Settings > Agents, remove the hooks. Then `brew uninstall --cask --zap bleep`, or quit bleep and delete it from Applications and the `~/.bleep` folder.
