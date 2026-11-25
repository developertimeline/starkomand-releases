# Starkomand

Starkomand is an agentic development environment (ADE) for Mac and Windows. It runs Claude Code, Codex, Cursor, Gemini CLI and other coding agent CLIs in parallel, each in its own real terminal window on one infinite canvas, so you can watch, steer and hand off work between several AI coding agents at once.

[Website](https://starkomand.com) · [Download for Mac](https://github.com/developertimeline/starkomand-releases/releases/latest) · [Windows (Microsoft Store)](https://apps.microsoft.com/detail/9P3BKXSV3CX1) · [Compare with other tools](https://starkomand.com/compare/) · [FAQ](https://starkomand.com/#faq)

![Claude Code and Codex agents working side by side in Starkomand, with an issue note on one agent and a diagram an agent drew beside its terminal](https://starkomand.com/assets/landing/handoff-wires-poster.jpg)

This repository holds the installers and release notes. The source code is not public.

## What it does

- **Run several coding agents side by side.** Each agent is the real CLI in a real terminal, signed in with your own provider account. Open as many sessions of the same provider as you like.
- **Hand work from one agent to another.** A handoff carries a focused brief, the task's acceptance criteria and its history. Model routing on Auto picks a model and effort for each step, and one model can review what another built.
- **Drop a GitHub issue on an agent.** Issues and local tickets are sticky notes on the canvas; dropping one on an agent window hands it the task.
- **Let agents draw.** An agent can draw an editable architecture diagram beside its terminal, or open a browser preview of the app it is building.
- **See where every agent stands.** Each window header shows what its agent is doing and turns amber while it waits on you. Tap Space to flip every window and read the conversation's title, the agent's last message, the files it changed, the dev servers it left running and the pull requests it opened.
- **Keep agents out of each other's way.** Starkomand shows which files each agent changed, and Claude (and Codex, once its hooks are trusted) is stopped before editing a file another agent is changing.
- **Run agents on your own server.** Claude, Codex or a shell can run on a host you own over SSH, with the same canvas features (Mac).
- **Talk to it.** Optional voice control speaks to an agent by name, opens agents and tidies windows. Local dictation runs on the device.

Also included: a Ports widget for every dev server on the Mac, a Flight board for your pull requests across GitHub accounts, separate workspaces per project, and keeping a MacBook awake with the lid closed while agents work.

## Supported agents

Claude Code (`claude`), Codex (`codex`), Cursor (`cursor-agent`), Gemini CLI (`gemini`), Grok CLI (`grok`), GitHub Copilot CLI (`copilot`), OpenCode (`opencode`), Amp (`amp`), Pi (`pi`), Aider (`aider`) and Goose (`goose`), plus any other CLI agent you add yourself.

Starkomand does not resell tokens or ask for API keys. Agent subscriptions and usage are billed by their providers.

## Requirements

- macOS on Apple silicon: download the `-installer.dmg` from the [latest release](https://github.com/developertimeline/starkomand-releases/releases/latest).
- Windows 10 or 11, x64 or Arm64: install from the [Microsoft Store](https://apps.microsoft.com/detail/9P3BKXSV3CX1). Agents on SSH hosts are not available on Windows yet.

There are no Linux or Intel Mac builds.

## Trial and pricing

The 3-day trial includes every feature. Continuing after it requires Starkomand Pro, a one-time purchase that includes a year of updates; you keep using the version you bought after that year. See [current pricing](https://starkomand.com/#pricing).

## Privacy

There is no Starkomand account. Workspace data, local dictation and hand tracking stay on the device. Agents talk to their own providers with your sign-ins. Details are in the [privacy policy](https://starkomand.com/privacy/).

## Updates

The Mac app checks this repository for a newer release and offers to install it (Help → Check for Updates); the Windows app updates through the Microsoft Store. Each release lists what changed.

## How it compares

Starkomand keeps each agent's real CLI in a real terminal and adds the canvas around it, runs locally with no account, and is sold as a one-time license. The [comparison page](https://starkomand.com/compare/) sets it beside Conductor, Superset, Emdash, Maestri, AgentGrid, CNVS, 49Agents and Zeron, with price, platform, supported agents and where the code runs. [Run multiple Claude Code agents in parallel](https://starkomand.com/compare/run-multiple-claude-code-agents/) shows the git worktree setup by hand before comparing the apps.

Starkomand is made by [Developer Timeline](https://developertimeline.io).
