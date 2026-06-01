---
descrição: The user reading the code the agente produced and forming a judgement on it. Reading the diff counts; reading the summary doesn't.
---
The user reading the code the [agente](./agente.md) produced and forming a judgement on it. Reading the diff or the changed files counts; reading the agente's *description* of what it did does not — narration is not the artifact.

*Evite:* "code review" alone — ambiguous between human and [automated](./Automated%20review.md).

*Uso:*

"I human-reviewed the [AFK](./AFK.md) output."

"You read the diff or just the summary?"

"Diff. The summary said it deleted dead code — turned out the function was called from a generated file."
