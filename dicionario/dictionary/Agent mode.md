---
descrição: Uma predefinição que agrupa um modo de permissão com instruções comportamentais injetadas no prompt do sistema. Pode mudar durante a sessão.
aliases:
  - plan mode (modo plan)
  - accept-edits (aceita edições)
  - bypass permissions (permissão bypass)
  - YOLO mode
---
Uma predefinição que molda como o [agente](./agente.md) opera em tempo de execução — agrupa um [modo de permissão](./Permission%20mode.md) com instruções de comportamento injetadas no [sistema de prompt](./System%20prompt.md). Exemplos: um padrão que solicita confirmação em chamadas arriscadas, um **plan mode** que bloqueia edições e direciona o agente para pesquisa, um modo **accept-edits** que auto-aprova edições, um modo **bypass permissions** (coloquialmente **YOLO mode**) que auto-aprova tudo. Pode mudar [durante a sessão](./Session.md).

*Vendor terms:* Claude Code chama de "modos de permissão", Codex chama de "modos de aprovação" — ambos anteriores ao agrupamento comportamental.

*Uso:*

"Ele continua editando arquivos quando eu só quero um plano."

"Mude para o modo plan — isso vai bloquear escritas e se manter em pesquisa."

"E para a execução [AFK](./AFK.md) depois?"

"Modo de bypass, mas apenas dentro de [sandbox](./Sandbox.md)."
