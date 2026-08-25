# Soc Ops Agent Instructions

## Project

- Soc Ops is a Blazor WebAssembly social bingo game targeting .NET 10.
- Keep UI components in `SocOps/Components`, routable pages in `SocOps/Pages`, domain models in `SocOps/Models`, game state and rules in `SocOps/Services`, and static question data in `SocOps/Data`.
- `Home.razor` composes the start and game screens; `BingoGameService` owns state, persistence, and state-change notifications; `BingoLogicService` owns board generation and bingo calculations.

## Development Loop

- From the repository root, build with `dotnet build SocOps/SocOps.csproj`.
- Run locally with `dotnet run --project SocOps/SocOps.csproj`; the launch profile normally serves `http://localhost:5166`.
- No test project currently exists. When adding tests, keep them focused on `BingoLogicService` and state transitions.
- Validate user-facing changes in a browser when possible: open `/`, start a game, exercise square selection, and verify reset/bingo behavior.
- Do not commit generated `SocOps/bin` or `SocOps/obj` output.

## Conventions

- Preserve the existing Blazor component and event-callback patterns. Put game rules in services rather than components.
- Use the custom Tailwind-like utilities already defined in `SocOps/wwwroot/css/app.css`; add a utility there only when an existing class cannot express the needed style.
- Follow `.github/instructions/css-utilities.instructions.md` for utility styling and `.github/instructions/frontend-design.instructions.md` for new or substantially redesigned UI.
- Keep the game inclusive and low-stakes. Follow the question-safety and variety guidance in `.github/agents/quiz-master.agent.md` when changing bingo prompts.
- Keep documentation changes aligned with the English, Portuguese, and Spanish workshop guides under `workshop/`.

## Useful References

- Setup and contribution commands: [README.md](../README.md)
- Workshop overview: [workshop/GUIDE.md](../workshop/GUIDE.md)
- Portuguese workshop: [workshop/pt_BR/GUIDE.md](../workshop/pt_BR/GUIDE.md)