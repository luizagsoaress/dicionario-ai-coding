---
descrição: Uma capacidade ensinável agrupada como unidade — mantida fora da janela de contexto até que o ponteiro de contexto a puxe para a tarefa em questão.
---
Uma capacidade ensinável agrupada como unidade — instruções e recursos para concluir uma tarefa bem, mantida no [ambiente](./Environment.md) até que o [ponteiro de contexto](./Context%20pointer.md) a puxe para dentro da [janela de contexto](./Context%20window.md) para a tarefa em questão. A unidade de [divulgação progressiva](./Progressive%20disclosure.md) em uma [harness](./Harness.md).

_Evite:_ "[ferramenta](./Tool.md)" — ferramenta é o que o [agente](./agente.md) _chama_; skill são instruções que ele _lê_.

_Uso:_

"Onde eu devo pôr o 'runbook de deploy'?"

"Como uma skill — o agente a carrega apenas quando a tarefa envolve deploys. Em [AGENTES.md](./AGENTS.md.md) ele vai queimar [tokens](./Token.md) em todo [turno](./Turn.md) para algo que nós usamos semanalmente."
