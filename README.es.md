<!-- l10n-sync: source-file="README.md" -->
# Soc Ops

> Un juego de social bingo para encuentros presenciales, workshops y días de equipo.
> Encuentra personas que coincidan con las pistas, marca tu tablero y corre para completar 5 en fila.

🎮 **[Jugar](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)** • 📚 **[Abrir la guía del lab](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/)**

---

## ¿Por qué Soc Ops?

Soc Ops convierte las presentaciones incómodas en un juego rápido y ligero. Está hecho con Blazor WebAssembly y .NET 10, así que corre directo en el navegador y es fácil de explorar, adaptar y remixar.

### Lo que encontrarás

- **Juego inmediato** — inicia una ronda y entra directo al tablero
- **Estado persistente** — la partida actual se guarda en local storage
- **Detección de bingo** — las líneas se rastrean automáticamente mientras juegas
- **Estructura lista para workshops** — el código está organizado para aprendizaje guiado

---

## Inicio rápido

### Ejecutar en local

```bash
cd SocOps
dotnet run
```

Luego abre la dirección local que aparece en la terminal.

### Compilar

```bash
cd SocOps
dotnet build
```

---

## Guía del lab

| Parte | Título |
|------|--------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Descripción general & Lista rápida |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Configuración & Ingeniería de Contexto |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Frontend Design-First |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Quiz Master Personalizado |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Desarrollo Multi-Agent |

> El contenido completo del workshop también está disponible sin conexión en [`workshop/`](workshop/).

---

## Mapa del proyecto

- `SocOps/Components` — piezas de UI reutilizables
- `SocOps/Pages` — pantallas enrutadas
- `SocOps/Models` — modelos de datos del juego
- `SocOps/Services` — estado, reglas y persistencia
- `SocOps/Data` — contenido estático de preguntas

---

## Requisitos

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) o superior

El despliegue se publica automáticamente en GitHub Pages al hacer push a `main`.
