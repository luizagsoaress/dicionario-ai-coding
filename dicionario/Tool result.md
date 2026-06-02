---
descrição: O que o harness envia de volta depois de executar a chamada da ferramenta — conteúdos dos arquivos, saída, ou erro. A única janela do agente para o ambiente.
---
O que o [harness](./Harness.md) envia de volta depois de executar a [chamada de ferramenta](./Tool%20call.md) — os conteúdos dos arquivos, o comando de saída, o erro. A única janela do [agente](./agente.md) para o [ambiente](./Environment.md). Viaja de volta para o [modelo](./Model.md) na *próxima* [requisição do provedor de modelos](./Model%20provider%20request.md), onde o modelo decide o que fazer com isso. Chamada de ferramenta e resultado de ferramenta são duas extremidades para a mesma troca, ambos dentro de um [turno](./Turn.md).

*Uso:*

"Ele está raciocinando sobre o arquivo como se ele estivesse vazio."

"O resultado da ferramenta volta como permissão negada, não os conteúdos. O modelo só vê a string de erro — ele não tem outra janela para o arquivo."
