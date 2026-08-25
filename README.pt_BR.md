<!-- l10n-sync: source-file="README.md" -->
# Soc Ops

> Um jogo de social bingo para encontros presenciais, workshops e dias de time.
> Encontre pessoas que correspondam às pistas, marque o tabuleiro e corra para fechar 5 em linha.

🎮 **[Jogar](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)** • 📚 **[Abrir o guia do lab](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/)**

---

## Por que o Soc Ops?

O Soc Ops transforma apresentações constrangedoras em um jogo rápido e leve. Ele foi feito com Blazor WebAssembly e .NET 10, então roda direto no navegador e é fácil de explorar, adaptar e remixar.

### O que você vai encontrar

- **Jogabilidade imediata** — comece uma rodada e vá direto para o tabuleiro
- **Estado persistente** — o jogo atual é salvo no local storage
- **Detecção de bingo** — as linhas são acompanhadas automaticamente
- **Estrutura pronta para workshops** — o código foi organizado para aprendizado guiado

---

## Início rápido

### Executar localmente

```bash
cd SocOps
dotnet run
```

Depois, abra o endereço local exibido no terminal.

### Compilar

```bash
cd SocOps
dotnet build
```

---

## Guia do lab

| Parte | Título |
|------|--------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Visão Geral & Lista Rápida |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Configuração & Engenharia de Contexto |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Frontend Design-First |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Quiz Master Personalizado |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Desenvolvimento Multi-Agent |

> O conteúdo completo do workshop também está disponível offline em [`workshop/`](workshop/).

---

## Mapa do projeto

- `SocOps/Components` — peças de UI reutilizáveis
- `SocOps/Pages` — telas roteáveis
- `SocOps/Models` — modelos de dados do jogo
- `SocOps/Services` — estado, regras e persistência
- `SocOps/Data` — conteúdo estático das perguntas

---

## Requisitos

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) ou superior

O deploy é feito automaticamente no GitHub Pages ao fazer push para `main`.
