<!-- l10n-sync: source-file="README.md" -->
# Soc Ops 🎉

> Un juego de social bingo para encuentros presenciales, workshops y días de equipo.
> Encuentra personas que coincidan con las pistas, marca tu tablero y corre para completar 5 en fila.

🎮 **[Jugar ahora](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)** • 📚 **[Empezar la guía del lab](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/)** • 🧭 **[Abrir archivos del workshop](workshop/)**

---

## Por qué existe este proyecto

Soc Ops convierte las presentaciones incómodas en un juego rápido y ligero que ayuda a conectar a las personas.

Está hecho con **Blazor WebAssembly + .NET 10**, corre completamente en el navegador y está estructurado para aprendizaje práctico con GitHub Copilot.

### Destacados

- ⚡ **Empieza en segundos** — un clic y el tablero está listo
- 💾 **Estado persistente** — la partida actual se guarda en local storage
- ✅ **Detección automática de bingo** — las líneas completadas se rastrean mientras juegas
- 🧪 **Arquitectura lista para workshop** — separación clara entre servicios y componentes para ejercicios guiados

---

## Empieza en 60 segundos

### Ejecutar en local

```bash
cd SocOps
dotnet run
```

Luego abre la dirección local que aparece en la terminal (normalmente `http://localhost:5166`).

### Compilar

```bash
cd SocOps
dotnet build
```

---

## Ruta del workshop

| Parte | Enfoque |
|------|--------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Descripción general & Lista rápida |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Configuración & Ingeniería de Contexto |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Frontend Design-First |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Quiz Master Personalizado |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Desarrollo Multi-Agent |

¿Quieres trabajar sin conexión? Usa los materiales locales en [`workshop/`](workshop/).

---

## Mapa del proyecto

- `SocOps/Components` — piezas de UI reutilizables
- `SocOps/Pages` — pantallas enrutadas
- `SocOps/Models` — modelos de datos del juego
- `SocOps/Services` — estado del juego, reglas y persistencia
- `SocOps/Data` — contenido estático de prompts de bingo

---

## Requisitos

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) o superior

El despliegue se publica automáticamente en GitHub Pages al hacer push a `main`.
