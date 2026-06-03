---
descrição: O processo que define os parâmetros do modelo expondo eles a uma vasta quantidade de texto e ajustando para melhorar a previsão do próximo token. 
---
O processo que define os [parâmetros](./Parameters.md) do [modelo](./Model.md),  expondo eles a uma vasta quantidade de texto e ajustando para melhorar a [previsão do próximo token](./Next-token%20prediction.md). Um processo único e caro realizado pelo [provedor de modelo](./Model%20provider.md). Abrange tanto o pré-treinamento (a execução principal) quanto o pós-treinamento (refinamentos posteriores como seguimento de instruções e segurança); a distinção não importa no nível deste glossário.

*Uso:*

"Nós podemos fazer ele conhecer nossa API interna?"

"Não via treinamento — esse é um processo de meses pelo provedor de modelo. Carregue a documentação da API no [contexto](./Context.md), esse é o recurso que você realmente tem."


 