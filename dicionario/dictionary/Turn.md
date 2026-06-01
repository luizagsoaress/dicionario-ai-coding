---
descrição: One user message plus everything the agente does in response, up until it yields back to the user. Contains one or more provider requests.
---
One user message plus everything the [agente](./agente.md) does in response, up until it yields back to the user. Contains one or more [model provider requests](./Model%20provider%20request.md) — many, if the agente calls [tools](./Tool.md). A clarifying question closes the turn; your reply opens the next one. The hierarchy is [session](./Session.md) **> Turn > Model provider request**.

*Uso:*

"Um turno leva dois minutos?"

"It made fourteen [tool calls](./Tool%20call.md) inside that turn — each one is a separate model provider request. Latency stacks up before the agente finally yields back to you."
