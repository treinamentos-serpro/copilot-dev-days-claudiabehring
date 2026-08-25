# Soc Ops 🎉

> A social bingo game for in-person mixers, workshops, and team days.
> Find people who match the prompts, mark your board, and race to 5 in a row.

🎮 **[Play now](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)** • 📚 **[Start the lab guide](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/)** • 🧭 **[Open workshop files](workshop/)**

---

## Why this project exists

Soc Ops turns awkward introductions into a fast, low-stakes game that helps people connect.

It is built with **Blazor WebAssembly + .NET 10**, runs fully in the browser, and is intentionally structured for hands-on learning with GitHub Copilot.

### Highlights

- ⚡ **Start in seconds** — one click and the board is ready
- 💾 **Persistent state** — your current game is saved in local storage
- ✅ **Automatic bingo detection** — completed lines are tracked as you play
- 🧪 **Workshop-ready architecture** — clear service/component separation for guided exercises

---

## Get started in 60 seconds

### Run locally

```bash
cd SocOps
dotnet run
```

Open the local URL shown in the terminal (typically `http://localhost:5166`).

### Build

```bash
cd SocOps
dotnet build
```

---

## Workshop path

| Part | Focus |
|------|-------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Overview & Checklist |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Setup & Context Engineering |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Design-First Frontend |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Custom Quiz Master |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Multi-Agent Development |

Want to work offline? Use the local materials in [`workshop/`](workshop/).

---

## Project map

- `SocOps/Components` — reusable UI pieces
- `SocOps/Pages` — routable screens
- `SocOps/Models` — game data models
- `SocOps/Services` — game state, rules, and persistence
- `SocOps/Data` — static bingo prompt content

---

## Requirements

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) or later

Deploys automatically to GitHub Pages on push to `main`.
