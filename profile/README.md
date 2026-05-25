<h1 align="center">start</h1>

<p align="center"><strong>Context-aware AI agent launcher powered by <a href="https://cuelang.org">CUE</a>.</strong></p>

Stop re-explaining yourself to every AI session. `start` composes intelligent
prompts from your project's context files — what the project does, the role the
agent should play, the task at hand — and launches your configured AI agent
every time, consistently, with zero ceremony.

## Projects

| Project | Description |
| --- | --- |
| [start](https://github.com/start-cli/start) | The CLI: a Go application that composes prompts and launches AI agents. |
| [library](https://github.com/start-cli/library) | CUE module of reusable agents, roles, contexts, tasks, and schemas, published to the CUE Central Registry. |
| [homebrew-tap](https://github.com/start-cli/homebrew-tap) | Homebrew tap for installing the `start` binary. |

## Quick start

```bash
brew tap start-cli/tap
brew install start-cli/tap/start

# Auto-setup detects your installed AI agent and writes initial config,
# then launches an AI session with full project context.
start
```

## What you get

- Role-based sessions — define agent expertise once, reuse it across projects.
- Reusable tasks — package common workflows as shareable prompts.
- Automatic context injection — project files, environment info, and docs included without manual setup.
- Multi-agent support — works with Claude, Gemini, aichat, aider, opencode, or any AI CLI tool.
- Type-safe configuration — validated, order-preserving CUE with built-in schema enforcement.
- Registry packages — install curated roles, contexts, and tasks from the CUE Central Registry.

## Licence

The public projects are released under the [MPL-2.0](https://opensource.org/licenses/MPL-2.0) licence.
