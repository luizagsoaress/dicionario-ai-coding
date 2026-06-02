---
descrição: Uma mensagem do usuário mais tudo que o agente faz em resposta, até que ele ceda de volta ao usuário. Contém uma ou mais requisições do provedor.
---
Uma mensagem do usuário mais tudo que o [agente](./agente.md) faz em resposta, até que ele ceda de volta ao usuário. Contém uma ou mais [requisições do provedor de modelo](./Model%20provider%20request.md) — muitas, se o agente chamar [ferramentas](./Tool.md). Uma pergunta esclarecedora encerra o turno; sua resposta abre o próximo. A hierarquia é [sessão](./Session.md) **> Turno > Requisição do provedor de modelo**.

*Uso:*

"Um turno leva dois minutos?"

"Ele fez quatorze [chamadas de ferramentas](./Tool%20call.md) dentro daquele turno — cada uma é uma requisição separada do provedor de modelo. A latência se acumula antes do agente finalmente ceder de volta para você."
