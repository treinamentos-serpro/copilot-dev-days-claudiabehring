# Soc Ops

> A social bingo game for in-person mixers, workshops, and team days.
> Find people who match the prompts, mark your board, and race to 5 in a row.

🎮 **[Play the game](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)** • 📚 **[Open the lab guide](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/)**

---

## Why Soc Ops?

Soc Ops turns awkward introductions into a fast, low-stakes game. It is built with Blazor WebAssembly and .NET 10, so it runs right in the browser and is easy to explore, extend, and remix.

### What you’ll find

- **Instant gameplay** — start a round and jump straight into the board
- **Persistent state** — the current game saves to local storage
- **Bingo detection** — lines are tracked automatically as you play
- **Workshop-ready structure** — the codebase is organized for guided learning

---

## Quick start

### Run locally

```bash
cd SocOps
dotnet run
```

Then open the app at the local address shown in the terminal.

### Build

```bash
cd SocOps
dotnet build
```

---

## Lab guide

| Part | Title |
|------|-------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Overview & Checklist |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Setup & Context Engineering |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Design-First Frontend |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Custom Quiz Master |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Multi-Agent Development |

> The full workshop content is also available offline in [`workshop/`](workshop/).

---

## Project map

- `SocOps/Components` — reusable UI pieces
- `SocOps/Pages` — routable screens
- `SocOps/Models` — game data models
- `SocOps/Services` — state, rules, and persistence
- `SocOps/Data` — static question content

---

## Requirements

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) or later

Deploys automatically to GitHub Pages on push to `main`.
