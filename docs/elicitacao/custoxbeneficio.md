# Priorização de requisitos baseada em valor, custo e risco

## 1. Introdução

A técnica de priorização de requisitos baseada em valor, custo e risco é um método analítico que permite a descrição matricial das prioridades de um conjunto de requisitos propostos, juntamente com as expectativas estimadas do grupo. Através da aplicação da priorização de Wiegers[2], que consiste em oito etapas para a definição do valor de prioridade, é possível classificar uma lista de requisitos de acordo com seu nível de prioridade, com base em análises e feedbacks dos usuários iniciais. Essa classificação é realizada de forma decrescente, de modo que os requisitos mais importantes são listados no topo da lista.

## 2. Priorização

Ao utilizar a técnica de priorização de Wiegers, é possível construir uma tabela com oito valores a serem preenchidos para cada requisito listado anteriormente. Esses valores são:

1. Benefício relativo: Vai de 1 a 9, em que 1 significa que poucos ou nenhum usuário acharam útil o requisito, e 9 significa que o requisito seria considerado muito valioso. Possui peso 2.

2. Penalidade relativa: Vai de 1 a 9, onde 1 significa que a penalidade por não possuir o requisito é baixa e 9 significa que caso o requisito não seja integrado, a penalidade para o projeto será alta. Possui peso 1.

3. Valor total: É a soma do benefício relativo com a penalidade relativa, considerando seus respectivos pesos.

4. Porcentagem do valor.

5. Custo relativo: Vai de 1 a 9, onde 1 é fácil e rápido de implementar, e 9 é complexo, caro e utiliza-se de bastante tempo. Possui peso 1.
6. Porcentagem do custo.
7. Risco relativo: Vai de 1 a 9, onde 1 significa que é possível implementar na primeira tentativa e 9 significa necessidades de especialidades, estudos anteriores, uso de tecnologias não familiares ou preocupação sobre a complexidade do requisito. Possui peso 1/2.
8. Porcentagem do risco.

Esses valores são preenchidos para cada requisito, permitindo que sejam comparados e priorizados de acordo com seus benefícios, custos e riscos. A pontuação total de cada requisito é obtida a partir da soma dos valores do benefício relativo, penalidade relativa e custo relativo, multiplicados pelos pesos correspondentes.

A partir da análise desses valores, é possível definir uma lista prioritária de requisitos. Essa lista é definida usando a porcentagem do valor dividida pela soma da porcentagem do custo e do risco.

Os requisitos foram priorizados a partir dos [resultados da elicitação](./resultadoElicitacao.md) e com base nas personas delimitadas em [artefato dedicado](./personas.md). A priorização foi realizada com o auxílio da ferramenta [Google Sheets](https://docs.google.com/spreadsheets/) e está incorporada abaixo para visualização.

<iframe src="https://docs.google.com/spreadsheets/d/1PorEBCcPz9i_tk9XD-WKhJhNfVXJF0ce6ArgmUq40lA/edit?usp=sharing" allowfullscreen width="768" height="432" frameborder="0"></iframe>

<h6 align = "center"> Fonte: Autor, 2023 </h6>



A Tabela 1 apresenta a definição da priorização dos requisitos elicitados por meio de valor, custo e risco:

| Número | Requisitos                                                                                  | Benefício relativo | Penalidade relativa | Valor total | Valor % | Custo relativo 1 | Custo % | Risco relativo  | Risco % | Prioridade |
|--------|-----------------------------------------------------------------------------------------------|---------------------|--------------------|-------------|---------|-----------------|--------|-------------------|--------|----------|
| RF22   | O usuário deve ser capaz de cancelar um pedido.                                               | 7                   | 9                  | 23          | 2,59    | 2               | 0,90   | 2                 | 0,87   | 1,36     |
| RF16   | O usuário deve ser capaz de remover itens da sacola de compras.                               | 6                   | 9                  | 21          | 2,36    | 2               | 0,90   | 2                 | 0,87   | 1,24     |
| RF30   | O usuário deve ser capaz de reportar falhas e erros                                           | 7                   | 7                  | 21          | 2,36    | 2               | 0,90   | 2                 | 0,87   | 1,24     |
| RF07   | O usuário deve ser capaz de pesquisar produtos.                                               | 9                   | 9                  | 27          | 3,04    | 5               | 2,26   | 3                 | 1,31   | 0,81     |
| RF09   | O usuário deve ser capaz de selecionar itens.                                                 | 9                   | 9                  | 27          | 3,04    | 5               | 2,26   | 4                 | 1,75   | 0,71     |
| RF18   | O usuário deve ser capaz de visualizar o preço de itens.                                      | 9                   | 9                  | 27          | 3,04    | 5               | 2,26   | 4                 | 1,75   | 0,71     |
| RF08   | O usuário deve ser capaz de pesquisar serviços.                                               | 7                   | 9                  | 23          | 2,59    | 5               | 2,26   | 3                 | 1,31   | 0,69     |
| RF26   | O usuário deve ser capaz de solicitar a entrega de produtos                                   | 7                   | 9                  | 23          | 2,59    | 2               | 0,90   | 6                 | 2,62   | 0,66     |
| RF34   | O usuário deve ser capaz de obter informações sobre cuidados de animais.                      | 2                   | 4                  | 8           | 0,90    | 2               | 0,90   | 1                 | 0,44   | 0,64     |
| RF01   | O usuário deve ser capaz de se cadastrar na aplicação.                                        | 9                   | 9                  | 27          | 3,04    | 5               | 2,26   | 5                 | 2,18   | 0,64     |
| RF04   | O usuário deve ser capaz de visualizar itens de produtos e serviços.                          | 9                   | 9                  | 27          | 3,04    | 5               | 2,26   | 5                 | 2,18   | 0,64     |
| RF28   | O usuário deve ser capaz de filtrar produtos por categoria                                    | 6                   | 9                  | 21          | 2,36    | 4               | 1,81   | 4                 | 1,75   | 0,62     |
| RF21   | O usuário deve ser capaz de recuperar sua conta através do endereço de email cadastrado.      | 7                   | 9                  | 23          | 2,59    | 6               | 2,71   | 3                 | 1,31   | 0,61     |
| RF29   | O usuário deve ser capaz de cadastrar mais de um animal de estimação na aplicação.            | 4                   | 5                  | 13          | 1,46    | 2               | 0,90   | 3                 | 1,31   | 0,61     |
| RNF02  | O sistema deve estar disponível para os sistemas Android e iOS.                               | 9                   | 9                  | 27          | 3,04    | 8               | 3,62   | 3                 | 1,31   | 0,59     |
| RF02   | O usuário deve ser capaz de entrar em sua conta cadastrada.                                   | 8                   | 9                  | 25          | 2,81    | 5               | 2,26   | 5                 | 2,18   | 0,59     |
| RF10   | O usuário deve ser capaz de adicionar itens ao sacola de compras.                             | 9                   | 9                  | 27          | 3,04    | 7               | 3,17   | 4                 | 1,75   | 0,59     |
| RNF03  | O sistema deve ser responsivo.                                                                | 9                   | 7                  | 25          | 2,81    | 7               | 3,17   | 4                 | 1,75   | 0,54     |
| RF39   | O usuário deve ser capaz de acessar uma tela com eventos próximos relacionados a _pets_.      | 3                   | 1                  | 7           | 0,79    | 1               | 0,45   | 2                 | 0,87   | 0,54     |
| RF40   | O usuário deve ser capaz de acessar uma tela com _posts_ da comunidade.                       | 3                   | 1                  | 7           | 0,79    | 1               | 0,45   | 2                 | 0,87   | 0,54     |
| RNF04  | O sistema deve ter um sistema de busca eficiente.                                             | 9                   | 7                  | 25          | 2,81    | 4               | 1,81   | 7                 | 3,06   | 0,53     |
| RF13   | O usuário deve ser capaz de realizar um pedido na loja.                                       | 9                   | 9                  | 27          | 3,04    | 7               | 3,17   | 6                 | 2,62   | 0,49     |
| RF14   | O usuário deve ser capaz de realizar uma compra na aplicação.                                 | 9                   | 9                  | 27          | 3,04    | 7               | 3,17   | 6                 | 2,62   | 0,49     |
| RF41   | O sistema deve notificar o usuário acerca de pendências médicas dos seus _pets_.              | 7                   | 9                  | 23          | 2,59    | 5               | 2,26   | 6                 | 2,62   | 0,49     |
| RF35   | O usuário deve ser capaz de alterar local de entrega do produto.                              | 6                   | 9                  | 21          | 2,36    | 4               | 1,81   | 6                 | 2,62   | 0,49     |
| RF03   | O usuário deve ser capaz de visualizar catálogo online de produtos para animais de estimação. | 9                   | 6                  | 24          | 2,70    | 6               | 2,71   | 6                 | 2,62   | 0,47     |
| RF17   | O usuário deve ser capaz de favoritar itens.                                                  | 4                   | 5                  | 13          | 1,46    | 4               | 1,81   | 3                 | 1,31   | 0,44     |
| RF27   | O usuário deve ser capaz de consultar a loja mais próxima                                     | 5                   | 5                  | 15          | 1,69    | 3               | 1,36   | 5                 | 2,18   | 0,44     |
| RNF05  | O sistema deve ser confiável e disponível.                                                    | 9                   | 8                  | 26          | 2,92    | 8               | 3,62   | 7                 | 3,06   | 0,41     |
| RF20   | O usuário deve ser capaz de assinar um serviço.                                               | 4                   | 2                  | 10          | 1,12    | 3               | 1,36   | 3                 | 1,31   | 0,39     |
| RF43   | O sistema deve fornecer ao usuário serviços de hotelaria para animais.                        | 5                   | 5                  | 15          | 1,69    | 4               | 1,81   | 5                 | 2,18   | 0,39     |
| RF37   | O usuário deve ser capaz de solicitar transporte para o animal até a loja física.             | 4                   | 7                  | 15          | 1,69    | 3               | 1,36   | 6                 | 2,62   | 0,39     |
| RNF01  | O sistema deve ser manter seguro as informações do usuário criptografando dados sensíveis.    | 9                   | 9                  | 27          | 3,04    | 8               | 3,62   | 9                 | 3,93   | 0,37     |
| RF12   | O usuário deve ser capaz de adicionar uma opção de pagamento.                                 | 8                   | 9                  | 25          | 2,81    | 8               | 3,62   | 8                 | 3,49   | 0,37     |
| RF11   | O usuário deve ser capaz de acompanhar a situação do pedido.                                  | 7                   | 9                  | 23          | 2,59    | 7               | 3,17   | 8                 | 3,49   | 0,36     |
| RF31   | O sistema deve possuir filtros e classificação por categorias para os produtos                | 6                   | 9                  | 21          | 2,36    | 7               | 3,17   | 7                 | 3,06   | 0,35     |
| RF33   | O usuário deve ser capaz de assinar pacotes periódicos de produtos pelo aplicativo.           | 4                   | 1                  | 9           | 1,01    | 3               | 1,36   | 3                 | 1,31   | 0,35     |
| RF36   | O usuário deve ser capaz de acessar um blog com dicas sobre _pets_.                           | 1                   | 1                  | 3           | 0,34    | 1               | 0,45   | 1                 | 0,44   | 0,35     |
| RF24   | O usuário deve ser capaz de registrar uma lista de compras frequentes                         | 3                   | 6                  | 12          | 1,35    | 2               | 0,90   | 6                 | 2,62   | 0,35     |
| RF38   | O usuário deve ser capaz de marcar consultas veterinárias.                                    | 4                   | 3                  | 11          | 1,24    | 3               | 1,36   | 5                 | 2,18   | 0,32     |
| RF06   | O usuário deve ser capaz de repetir um pedido anterior                                        | 3                   | 4                  | 10          | 1,12    | 3               | 1,36   | 5                 | 2,18   | 0,29     |
| RF25   | O usuário deve ser capaz de acessar a avaliação e recomendações de um produto                 | 7                   | 4                  | 18          | 2,02    | 7               | 3,17   | 8                 | 3,49   | 0,28     |
| RF15   | O usuário deve ser capaz de cadastrar um perfil para o Pet.                                   | 4                   | 3                  | 11          | 1,24    | 5               | 2,26   | 5                 | 2,18   | 0,26     |
| RF23   | O usuário deve ser capaz de escolher como receber um produto.                                 | 3                   | 7                  | 13          | 1,46    | 5               | 2,26   | 7                 | 3,06   | 0,25     |
| RF32   | O sistema deve realizar a sugestão de produtos a partir de um perfil.                         | 7                   | 3                  | 17          | 1,91    | 8               | 3,62   | 9                 | 3,93   | 0,24     |
| RF19   | O usuário deve ser capaz de agendar um serviço de banho e tosa.                               | 3                   | 2                  | 8           | 0,90    | 5               | 2,26   | 5                 | 2,18   | 0,19     |
| RF42   | O usuário deve ser capaz de se cadastrar em um sistema de fidelidade pelo aplicativo.         | 2                   | 1                  | 5           | 0,56    | 4               | 1,81   | 5                 | 2,18   | 0,13     |
| RF05   | O usuário deve ser capaz de cadastrar-se para promoções.                                      | 2                   | 2                  | 6           | 0,67    | 6               | 2,71   | 5                 | 2,18   | 0,13     |

<h6 align = "center"> Tabela 1: Índices de priorização </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>


## Referências Bibliográficas

> [1] Rahim, Md Shamsur, AZM Ehtesham Chowdhury, and Shovra Das. "Rize: A proposed requirements prioritization technique for agile development." 2017 IEEE Region 10 Humanitarian Technology Conference (R10-HTC). IEEE, 2017. Acesso em: 30 abr. 2023. 

> [2] WIEGERS, Karl; JOY, Beatty. PART II: Requirements development. In: WIEGERS, Karl; JOY, Beatty. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013. Cap. 16. p. 319-320. Disponível em: https://www.dirzon.com/file/telegram/HiLCoE%20-%20DRB1802/Microsoft%20Press%20Software%20Requirements%203%203rd%20Edition%20Aug%202013.pdf. Acesso em: 30 abr. 2023. 


## Histórico de versão

| Versão | Data     | Descrição                        | Autor(es)     | Revisor(es) |
| ------ | -------- | -------------------------------- | ------------- | ----------- |
| `1.0`  | 01/05/23 | Criação da página de priorização  | Magno Luiz | Felipe Corrêa |


