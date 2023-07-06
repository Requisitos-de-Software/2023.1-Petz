# Resultados da Priorização

## 1. Introdução

Este documento possui os resultados obtidos através da elicitação e priorização dos requisitos para o aplicativo móvel Petz[1]. Os requisitos detalhados podem ser encontrados no artefato de [resultado da elicitação](./resultadoElicitacao.md)[2], as técnicas utilizadas para a elicitação e priorização dos requisitos podem ser encontradas nos artefato [técnicas de elicitação](./tecnicas_planejadas.md)[3] e [técnicas de priorização](./tecnicas_priorizacao.md)[4].

## 2. Técnicas de priorização

Abaixo estão descritas de forma resumida as três técnicas de priorização de requisitos utilizadas no projeto.

### 2.1 Escala de três níveis

A escala de três níveis busca priorizar os requisitos através de três níveis de prioridade. para a organização foi utilizada uma matriz de dois eixos(importante e urgente). A partir disso pode-se dividir os requisitos em quatro categorias:

- Alta prioridade: Requisitos necessários e urgentes para os usuários.
- Média prioridade: Requisitos necessários mas não urgentes para os usuários.
- Baixa prioridade: Requisitos que não são necessários nem urgentes para os usuários.
- Não executado: Requisitos desejados por usuários específicos, contudo não interessantes para o sistema.

A priorização detalhada de todos os requisitos pode ser encontrado no artefato de [Priorização por escala de três níveis](./escalaTresNiveis.md).

### 2.2 MoscoW

O método MoscoW busca priorizar os requisitos de acordo com sua importância para o usuário do sistema, permite que a equipe de desenvolvimento defina rapidamente os requisitos críticos e permite a participação do usuário nestaa definição. A técnica MoSCoW prioriza os requisitos em quatro níveis:

- Must Have: Requisitos que o sistema necessita para que possa funcionar adequadamente.
- Should Have: Requisitos que o sistema deve ter para que atenda as necessidades básicas de seus usuários no sistema.
- Could Have: Requisitos desejados pelos usuários, contudo não estritamente necessários.
- Won't Have: Requisitos de baixa importância que podem ser excluídos ou adiados para uma etapa posterior de desenvolvimento.

A priorização detalhada de todos os requisitos pode ser encontrado no artefato de [Priorização por MoSCoW](./moscow.md).

### 2.3 Priorização baseada em valor, custo e risco

O método baseado em valor, custo e risco busca analisar os requisitos de forma analítica, utiliza oito passos para calcular matemáticamente a prioridade de cada requisito nos escopo do projeto. Estes passos são:

1. Benefício relativo: Vai de 1 a 9, em que 1 significa que poucos ou nenhum usuário acharam útil o requisito, e 9 significa que o requisito seria considerado muito valioso. Possui peso 2.

2. Penalidade relativa: Vai de 1 a 9, onde 1 significa que a penalidade por não possuir o requisito é baixa e 9 significa que caso o requisito não seja integrado, a penalidade para o projeto será alta. Possui peso 1.

3. Valor total: É a soma do benefício relativo com a penalidade relativa, considerando seus respectivos pesos.

4. Porcentagem do valor.

5. Custo relativo: Vai de 1 a 9, onde 1 é fácil e rápido de implementar, e 9 é complexo, caro e utiliza-se de bastante tempo. Possui peso 1.
6. Porcentagem do custo.
7. Risco relativo: Vai de 1 a 9, onde 1 significa que é possível implementar na primeira tentativa e 9 significa necessidades de especialidades, estudos anteriores, uso de tecnologias não familiares ou preocupação sobre a complexidade do requisito. Possui peso 1/2.
8. Porcentagem do risco.

A partir destes passos, pode-se calcular a prioridade de cada requisito no projeto, deve-se denotar contudo, que os requisitos de maior prioridade não necessariamente será o primeiro a ser desenvolvido, pois requisitos de menor prioridade podem ser necessários para sua produção.

A priorização detalhada de todos os requisitos pode ser encontrado no artefato de [Priorização baseada em valor, custo e risco](./custoxbeneficio.md).

## 3. Requisitos Funcionais

A tabela 1 apresenta os requisitos funcionais elicitados ordenados por seu ID, a tabela detalha sua descrição, suas priorizações conforme as técnicas utilizadas e as técnicas de elicitação que geraram o mesmo.

| **ID** | **Requisito** | **Priorização por escala de 3 níveis** | **Priorização baseada em valor, custo e risco** | **Priorização por MosCow** | **Técnica(s)** |
|--|--|--|--|--|--|
| RF01 | O usuário deve ser capaz de se cadastrar na aplicação. | Alta prioridade | 0,64 | Must Have | Introspecção[2], Questionário[3] |
| RF02 | O usuário deve ser capaz de entrar em sua conta cadastrada. | Alta prioridade | 0,59 | Must Have | Introspecção[2] |
| RF03 | O usuário deve ser capaz de visualizar catálogo online de produtos para animais de estimação. | Alta prioridade | 0,47 | Must Have | Storytelling[4] |
| RF04 | O usuário deve ser capaz de visualizar itens de produtos e serviços. | Alta prioridade | 0,64 | Must Have | Introspecção[2] |
| RF05 | O usuário deve ser capaz de cadastrar-se para promoções. | Baixa prioridade | 0,13 | Should Have | Introspecção[2], Brainstorming[1], Questionário[3] |
| RF06 | `O usuário deve ser capaz de repetir um pedido anterior.` | Média prioridade | 0,29 | Could Have | Introspecção[2] |
| RF07 | O usuário deve ser capaz de pesquisar produtos. | Alta prioridade | 0,81 | Should Have | Introspecção[2], Brainstorming[1],Questionário[3] |
| RF08 | O usuário deve ser capaz de pesquisar serviços. | Baixa prioridade | 0,69 | Should Have | Introspecção[2], Brainstorming[1] |
| RF09 | O usuário deve ser capaz de selecionar itens. | Alta prioridade | 0,71 | Should Have | Introspecção[2] |
| RF10 | O usuário deve ser capaz de adicionar itens ao sacola de compras. | Alta prioridade | 0,59 | Should Have | Introspecção[2] |
| RF11 | O usuário deve ser capaz de acompanhar a situação do pedido. | Alta prioridade | 0,36 | Should Have | Introspecção[2] |
| RF12 | O usuário deve ser capaz de adicionar uma opção de pagamento. | Alta prioridade | 0,37 | Should Have | Introspecção[2] |
| RF13 | O usuário deve ser capaz de realizar um pedido na loja. | Média prioridade | 0,49 | Must Have | Introspecção[2] |
| RF14 | O usuário deve ser capaz de realizar uma compra na aplicação. | Alta prioridade | 0,49 | Must Have | Introspecção[2], Brainstorming[1], Questionário[3] |
| RF15 | O usuário deve ser capaz de cadastrar um perfil para o Pet. | Alta prioridade | 0,26 | Should Have | Introspecção[2], Brainstorming[1], Storytelling[4] |
| RF16 | O usuário deve ser capaz de remover itens da sacola de compras. | Alta prioridade | 1,24 | Must Have | Introspecção[2], Questionário[3] |
| RF17 | O usuário deve ser capaz de favoritar itens. | Média prioridade | 0,44 | Should Have | Introspecção[2] |
| RF18 | O usuário deve ser capaz de visualizar o preço de itens. | Alta prioridade | 0,71 | Must Have | Introspecção[2], Questionário[3] |
| RF19 | O usuário deve ser capaz de agendar um serviço de banho e tosa. | Alta prioridade | 0,19 | Should Have | Introspecção[2], Brainstorming[1], Storytelling[4], Questionário[3] |
| RF20 | `O usuário deve ser capaz de assinar um serviço.` | Baixa prioridade | 0,39 | Should Have | Introspecção[2], Brainstorming[1] |
| RF21 | O usuário deve ser capaz de recuperar sua conta através do endereço de email cadastrado. | Alta prioridade | 0,61 | Should Have | Introspecção[2] |
| RF22 | O usuário deve ser capaz de cancelar um pedido. | Alta prioridade | 1,36 | Must Have | Introspecção[2] |
| RF23 | O usuário deve ser capaz de escolher como receber um produto. | Alta prioridade | 0,25 | Must Have | Introspecção[2], Storytelling[4] |
| RF24 | `O usuário deve ser capaz de registrar uma lista de compras frequentes.` | Média prioridade | 0,35 | Must Have | Brainstorming[1], Storytelling[4], Questionário[3] |
| RF25 | `O usuário deve ser capaz de acessar a avaliação e recomendações de um produto.` | Alta prioridade | 0,28 | Should Have | Brainstorming[1] |
| RF26 | O usuário deve ser capaz de solicitar a entrega de produtos. | Alta prioridade | 0,66 | Must Have | Brainstorming[1] |
| RF27 | O usuário deve ser capaz de consultar a loja mais próxima. | Média prioridade | 0,44 | Should Have | Brainstorming[1] |
| RF28 | O usuário deve ser capaz de filtrar produtos por categoria. | Alta prioridade | 0,62 | Must Have | Storytelling[4], Questionário[3] |
| RF29 | O usuário deve ser capaz de cadastrar mais de um animal de estimação na aplicação. | Alta prioridade | 0,61 | Should Have | Questionário[3] |
| RF30 | `O usuário deve ser capaz de reportar falhas e erros.` | Baixa prioridade | 1,24 | Should Have | Questionário[3] |
| RF31 | O sistema deve possuir filtros e classificação por categorias para os produtos. | Alta prioridade | 0,35 | Must Have | Brainstorming[1] |
| RF32 | `O sistema deve realizar a sugestão de produtos a partir de um perfil.` | Média prioridade | 0,24 | Should Have | Brainstorming[1] |
| RF33 | `O usuário deve ser capaz de assinar pacotes periódicos de produtos pelo aplicativo.` | Não executado | 0,35 | Should Have | Brainstorming[1] |
| RF34 | `O usuário deve ser capaz de obter informações sobre cuidados de animais.` | Não executado | 0,64 | Must Have | Storytelling[4] |
| RF35 | `O usuário deve ser capaz de alterar local de entrega do produto.` | Alta prioridade | 0,49 | Must Have | Questionário[3] |
| RF36 | `O usuário deve ser capaz de acessar um blog com dicas sobre _pets_.` | Não executado | 0,35 | Should Have | Brainstorming[1] |
| RF37 | `O usuário deve ser capaz de solicitar transporte para o animal até a loja física.` | Média prioridade | 0,39 | Should Have | Brainstorming[1] |
| RF38 | `O usuário deve ser capaz de marcar consultas veterinárias.` | Alta prioridade | 0,32 | Should Have | Brainstorming[1] |
| RF39 | `O usuário deve ser capaz de acessar uma tela com eventos próximos relacionados a _pets_.` | Não executado | 0,54 | Won't Have | Brainstorming[1] |
| RF40 | `O usuário deve ser capaz de acessar uma tela com _posts_ da comunidade.` | Baixa prioridade | 0,54 | Should Have | Brainstorming[1], Storytelling[4] |
| RF41 | `O sistema deve notificar o usuário acerca de pendências médicas dos seus _pets_.` | Média prioridade | 0,49 | Must Have | Brainstorming[1] |
| RF42 | `O usuário deve ser capaz de se cadastrar em um sistema de fidelidade pelo aplicativo.` | Baixa prioridade | 0,13 | Should Have | Brainstorming[1] |
| RF43 | `O sistema deve fornecer ao usuário serviços de hotelaria para animais.` | Não executado | 0,39 | Won't Have | Brainstorming[1] |

<h6 align = "center"> Tabela 1: Requisitos funcionais elicitados e priorizados </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

## 4. Requisitos não funcionais

A tabela 2 apresenta os requisitos não funcionais elicitados ordenados por seu ID, a tabela detalha sua descrição e suas priorizações conforme as técnicas utilizadas.

| **ID** | Requisito | **Priorização por escala de 3 níveis** | **Priorização baseada em valor, custo e risco** | **Priorização por MosCow** |
|--|--|--|--|--|
| RNF01 | O sistema deve ser manter seguro as informações do usuário criptografando dados sensíveis. | Alta prioridade | 0,37 | Must Have |
| RNF02 | O sistema deve estar disponível para os sistemas Android e iOS. | Alta prioridade | 0,59 | Must Have |
| RNF03 | O sistema deve ser responsivo. | Média prioridade | 0,54 | Must Have |
| RNF04 | O sistema deve ter um sistema de busca eficiente. | Alta prioridade | 0,53 | Must Have |
| RNF05 | O sistema deve ser confiável e disponível. | Alta prioridade | 0,41 | Must Have |

<h6 align = "center"> Tabela 2: Requisitos não funcionais elicitados e priorizados </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

## 5. Referências Bibliográficas

> [1] Petz, acesso em: 01 de maio de 2023. Para mais informações acesse: [link]().

> [2] Resultados da elicitação de requisitos, acesso em 01 de maio de 2023. Para mais informações acesse: [link](./resultadoElicitacao.md).

> [3] Técnicas de elicitação planejadas para o projeto, acesso em 01 de maio de 2023. Para mais informações acesse: [link](./tecnicas_planejadas.md).

> [4] Técnicas de priorização planejadas para o projeto, acesso em 01 de maio de 2023. Para mais informações acesse: [link](./tecnicas_priorizacao.md).

## 6. Histórico de versão

| Versão | Data     | Descrição                                     | Autor(es)   | Revisor(es)   |
| ------ | -------- | --------------------------------------------- | ----------- | ------------- |
| `1.0`  | 01/05/23 | Criação da página de resultados da elicitação | Pedro Muniz | Felipe Corrêa |
| `1.1` | 05/07/23 | Atualização resultados MosCow |Vitor Manoel| Felipe Corrêa |
