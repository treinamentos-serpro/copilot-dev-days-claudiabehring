<!-- l10n-sync: source-file="README.md" -->
# Soc Ops 🎉

> Um jogo de social bingo para encontros presenciais, workshops e dias de time.
> Encontre pessoas que correspondam às pistas, marque o tabuleiro e corra para fechar 5 em linha.

🎮 **[Jogar agora](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)** • 📚 **[Começar o guia do lab](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/)** • 🧭 **[Abrir arquivos do workshop](workshop/)**

---

## Por que este projeto existe

O Soc Ops transforma apresentações constrangedoras em um jogo rápido e leve que ajuda pessoas a se conectarem.

Ele foi feito com **Blazor WebAssembly + .NET 10**, roda totalmente no navegador e foi estruturado para aprendizado prático com GitHub Copilot.

### Destaques

- ⚡ **Comece em segundos** — um clique e o tabuleiro está pronto
- 💾 **Estado persistente** — o jogo atual é salvo no local storage
- ✅ **Detecção automática de bingo** — as linhas concluídas são acompanhadas enquanto você joga
- 🧪 **Arquitetura pronta para workshop** — separação clara entre serviços e componentes para exercícios guiados

---

## Comece em 60 segundos

### Executar localmente

```bash
cd SocOps
dotnet run
```

Depois, abra o endereço local exibido no terminal (normalmente `http://localhost:5166`).

### Compilar

```bash
cd SocOps
dotnet build
```

---

## Trilha do workshop

| Parte | Foco |
|------|--------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Visão Geral & Lista Rápida |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Configuração & Engenharia de Contexto |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Frontend Design-First |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Quiz Master Personalizado |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Desenvolvimento Multi-Agent |

Quer estudar offline? Use os materiais locais em [`workshop/`](workshop/).

---

## Mapa do projeto

- `SocOps/Components` — peças de UI reutilizáveis
- `SocOps/Pages` — telas roteáveis
- `SocOps/Models` — modelos de dados do jogo
- `SocOps/Services` — estado do jogo, regras e persistência
- `SocOps/Data` — conteúdo estático dos prompts de bingo

---

## Requisitos

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) ou superior

O deploy é feito automaticamente no GitHub Pages ao fazer push para `main`.
