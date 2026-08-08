# p3bot

CLI tools for AI agent workflows — context, project boards, search, and browser automation.

| Project | Description |
| --- | --- |
| [start](https://github.com/p3bot/start) | Context-aware AI agent launcher powered by CUE |
| [library](https://github.com/p3bot/library) | Reusable CUE agents, roles, contexts, and tasks |
| [agentdex](https://github.com/p3bot/agentdex) | Detect and inspect local AI coding agents |
| [tk](https://github.com/p3bot/tk) | Ticket board CLI for plain markdown documents |
| [kagi](https://github.com/p3bot/kagi) | CLI client for the Kagi search API |
| [snag](https://github.com/p3bot/snag) | Browser-backed web content fetcher |
| [webctl](https://github.com/p3bot/webctl) | Browser control for automated web interaction |

## Install

Via [Homebrew](https://github.com/p3bot/homebrew-tap) (Linux/macOS):

```bash
brew tap p3bot/tap
brew trust p3bot/tap

brew install p3bot/tap/start
brew install p3bot/tap/agentdex
brew install p3bot/tap/tk
brew install p3bot/tap/kagi
brew install p3bot/tap/snag
brew install p3bot/tap/webctl
```

`library` is a CUE module, not a Homebrew formula — install from the CUE Central Registry (see [library](https://github.com/p3bot/library)).

Public projects are [MPL-2.0](https://opensource.org/licenses/MPL-2.0).
