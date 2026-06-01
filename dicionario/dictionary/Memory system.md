---
descrição: A system that attempts to make an agente stateful across sessions by persisting to the environment and reloading at session start.
---
A system that attempts to make an [agente](./agente.md) [stateful](./Stateful.md) across [sessions](./Session.md). Persists information into the [environment](./Environment.md) during a session and reloads it into the [context window](./Context%20window.md) at the start of future ones, so the agente carries continuity beyond the user [clearing](./Clearing.md) the session.

*Uso:*

"I keep having to re-tell it I'm on Postgres, not MySQL."

"Wire up a memory system — write what it learns to the [filesystem](./Filesystem.md) on the first [turn](./Turn.md), reload it at session start. The [model](./Model.md) itself is [stateless](./Stateless.md); the memory layer fakes continuity."
