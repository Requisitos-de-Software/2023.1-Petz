# Priorização de requisitos baseada em valor, custo e risco

## Introdução

A técnica de priorização de requisitos baseada em valor, custo e risco é um método analítico que permite a descrição matricial das prioridades de um conjunto de requisitos propostos, juntamente com as expectativas estimadas do grupo. Através da aplicação da priorização de Wiegers, que consiste em oito etapas para a definição do valor de prioridade, é possível classificar uma lista de requisitos de acordo com seu nível de prioridade, com base em análises e feedbacks dos usuários iniciais. Essa classificação é realizada de forma decrescente, de modo que os requisitos mais importantes são listados no topo da lista.

## Priorização

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





## Referências Bibliográficas

> [1] WIEGERS, Karl; JOY, Beatty. PART II: Requirements development. In: WIEGERS, Karl; JOY, Beatty. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013. Cap. 16. p. 319-320. Disponível em: https://www.dirzon.com/file/telegram/HiLCoE%20-%20DRB1802/Microsoft%20Press%20Software%20Requirements%203%203rd%20Edition%20Aug%202013.pdf. Acesso em: 30 abr. 2023. 

> [2] Rahim, Md Shamsur, AZM Ehtesham Chowdhury, and Shovra Das. "Rize: A proposed requirements prioritization technique for agile development." 2017 IEEE Region 10 Humanitarian Technology Conference (R10-HTC). IEEE, 2017. Acesso em: 30 abr. 2023. 

## Histórico de versão

| Versão | Data     | Descrição                        | Autor(es)     | Revisor(es) |
| ------ | -------- | -------------------------------- | ------------- | ----------- |
| `1.0`  | 01/05/23 | Criação da página de priorização  | Magno Luiz | Felipe Corrêa |


