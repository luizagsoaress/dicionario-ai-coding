---
descrição: Uma função que o harness expõe para o agente chamar — Ler, Escrever, Bash, Pesquisar. Como um agente percebe e age no ambiente.
---
Uma função que o [harness](./Harness.md) expõe para o [agente](./agente.md) chamar — Ler, Escrever, Bash, Pesquisar. Ferramentas são como o agente percebe e age no [ambiente](./Environment.md): ele não pode ver o ambiente exceto por [resultados da ferramenta](./Tool%20result.md), e não pode mudar isso exceto por [chamadas das ferramentas](./Tool%20call.md). Cada chamada da ferramenta custa uma [requisição do provedor de modelo](./Model%20provider%20request.md) extra, pois o resultado precisa voltar para o modelo antes que ele possa decidir o que fazer em seguida.

*Uso:*

"O agente pode consultar o staging diretamente?"

"Adicione uma ferramenta `psql` ao harness, com escopo de somente leitura no staging. Sem uma ferramenta para isso, o agente fica 'cego' para tudo fora do [sistema de arquivos](./Filesystem.md)."
