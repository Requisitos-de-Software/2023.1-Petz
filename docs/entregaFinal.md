# Entrega Final

## 1. Introdução
Para a execução deste projeto no semestre 2023.1, o grupo 7 da disciplina de Requisitos de Software decidiu realizar a avaliação do aplicativo da Petz, usando como objeto de estudo para elicitar e priorizar requisitos durante o semestre letivo, utilizando de técnicas variadas visando aprendizado de todos os membros da equipe. Neste presente documento, está documentado os resultados obtidos, bem como o detalhamento das etapas do projeto com indicação dos artefatos produzidos, autores e revisores. 

## 2. Planejamento do projeto

### 2.1 Ferramentas

Nesta seção, a tabela 1 marca as ferramentas utilizadas dentro do projeto, bem como os artefatos em que foram utilizadas quando rastreável.

| Ferramenta | Objetivo | Artefatos |
|--|--|--|
| [](https://www.github.com)[GitHub](https://www.github.com) | Armazenar a documentação e os artefatos do projeto. | Todos |
| [](https://www.mkdocs.org)[MkDocs](https://www.mkdocs.org)| Gerar páginas de documentação do projeto. | Todos |
| [](https://web.telegram.org/)[Telegram](https://web.telegram.org/) | Comunicação assíncrona e remota entre os integrantes. | \- |
| [](https://www.microsoft.com/pt-br/microsoft-365/microsoft-teams/free)[Microsoft Teams](https://www.microsoft.com/pt-br/microsoft-365/microsoft-teams/free) | Reuniões remotas e gravação de apresentações. | Reuniões e apresentações do grupo |
| [](https://workspace.google.com/intl/pt-BR/)[Google Workspace](https://workspace.google.com/intl/pt-BR/) | Gestão e criação de formulários e planilhas de dados. | - |
| [](https://www.fakenamegenerator.com/)[Fake Name Generator](https://www.fakenamegenerator.com/) | Criação de identidades geradas aleatoriamente. | Brainstorming |
| [](https://www.figma.com)[Figma](https://www.figma.com)| Elaboração de protótipos e elementos visuais. | Prototipação |
| [](https://www.youtube.com)[Youtube](https://www.youtube.com) | Hospedagem das gravações das reuniões e apresentações | Apresentações, reuniões |
| [](https://www.canva.com)[Canva](https://www.canva.com) | Criação de elementos visuais e slides. | Verificações, Apresentação 1 |
| [](https://www.trello.com)[Trello](https://www.trello.com) | Gestão de tarefas e datas. | - |
| [](https://this-person-does-not-exist.com/en)[This Person Does Not Exist](https://this-person-does-not-exist.com/en)| Geração de imagens para as personas. | Personas |
| [](https://miro.com)[Miro](https://miro.com) | Criação de elementos visuais colaborativos. | Escala de três níveis |
| [](https://www.lucidchart.com/pages/pt)[Lucidchart](https://www.lucidchart.com/pages/pt) | Criação de diagramas | Rich Pictures, NFR, Casos de uso |
| [](https://obsproject.com)[OBS Studio](https://obsproject.com) | Gravação de reuniões com usuários | Prototipação |


<h6 align = "center"> Tabela 1: Artefatos elaborados na etapa de elicitação e priorização de requisitos</h6>
<h6 align = "center"> Fonte: Felipe Mastromauro, 2023 </h6>

### 2.2 Cronograma planejado x executado

A tabela 2 a seguir representa a comparação entre os cronogramas planejado e realizado ao final do projeto. As células vazias representam elementos que não foram descritos em uma das duas frentes.

| Atividade | Data de entrega planejada | Data de entrega executada | Autor Planejado | Autor Executado | Revisor Planejado | Revisor Executado |
|--|--|--|--|--|--|--|
| Cronograma de atividades | 11/04/2023 | 15/04/2023 | Samuel Sato | Samuel Sato | Vitor Manoel | Pedro Muniz |
| App selecionado | 12/04/2023 | 15/04/2023 | Vitor Manoel | Vitor Manoel | Felipe Corrêa | Felipe Corrêa |
| Metodologias | 13/04/2023 | 13/04/2023 | Felipe Corrêa | Pedro Muniz | Lucas Rodrigues | Felipe Corrêa |
| Ferramentas do projeto | 13/04/2023 | 13/04/2023 | Lucas Rodrigues | Pedro Muniz | Magno Luiz | Felipe Corrêa |
| Rich Picture | 13/04/2023 | 15/04/2023 | Magno Luiz | Magno Luiz | Pedro Muniz | Pedro Muniz |
| GitHub Pages | 14/04/2023 | 08/04/2023 | Pedro Muniz | Pedro Muniz, Felipe Corrêa | Samuel Sato | Pedro Muniz, Felipe Corrêa |
| Gravação da apresentação | 15/04/2023 | 15/04/2023 | Todos os integrantes | Todos os integrantes | Todos os integrantes | Todos os integrantes |
| Perfil dos usuários | 20/04/2023 | 26/04/2023 | Samuel Sato | Pedro Muniz | Samuel Sato | Samuel Sato |
| Técnicas de elicitação planejadas | 18/04/2023 | 26/04/2023 | Vitor Manoel | Felipe Corrêa | Vitor Manoel | Pedro Muniz |
| Personas | 20/04/2023 | 27/04/2023 | Lucas Rodrigues | Pedro Muniz | Lucas Rodrigues | Vitor Manoel |
| Questionário | 22/04/2023 | 29/04/2023 | Magno Luiz | Samuel Sato | Magno Luiz | Magno Luiz |
| Glossário | 21/04/2023 | 26/04/2023 | Samuel Sato | Felipe Corrêa | Samuel Sato | Pedro Muniz |
| Brainstorming | 25/04/2023 | 28/04/2023 | Felipe Corrêa | Felipe Corrêa | Lucas Rodrigues | Pedro Muniz, Magno Luiz |
| Introspecção | 25/04/2023 | 27/04/2023 | Magno Luiz | Magno Luiz | Vitor Manoel, Samuel Sato | Vitor Manoel, Samuel Sato |
| Storytelling | 25/04/2023 | 26/04/2023 | Vitor Manoel | Vitor Manoel | Felipe Corrêa | Felipe Corrêa |
| Questionário | 25/04/2023 | 29/04/2023 | Samuel Sato | Samuel Sato | Magno Luiz | Magno Luiz |
| Resultados da elicitação | 28/04/2023 | 30/04/2023 | Pedro Muniz | Samuel Sato | Felipe Corrêa | Pedro Muniz |
| Técnicas de priorização planejadas | - | 01/05/2023 | - | Felipe Corrêa | - | Pedro Muniz |
| Escala de três níveis | 27/04/2023 | 30/04/2023 | Felipe Corrêa | Felipe Corrêa | Pedro Muniz | Pedro Muniz |
| MoSCoW | 27/04/2023 | 01/05/2023 | Lucas Rodrigues | Lucas Rodrigues | Pedro Muniz | Pedro Muniz |
| Priorização de requisitos baseada em valor, custo e risco | 27/04/2023 | 01/05/2023 | Magno Luiz | Magno Luiz | Felipe Corrêa | Felipe Corrêa |
| Resultados da elicitação | 28/04/2023 | 01/05/2023 | Pedro Muniz | Pedro Muniz | Felipe Corrêa | Felipe Corrêa |
| Gravação da apresentação | 30/04/2023 | 01/05/2023 | Todos os integrantes | Todos os integrantes | Todos os integrantes | Todos os integrantes |
| Casos de uso | 09/05/2023 | 16/05/2023 | Magno Luiz | Magno Luiz | Pedro Muniz | Pedro Muniz |
| Cenários | 09/05/2023 | 11/05/2023 | Pedro Muniz | Pedro Muniz, Felipe Corrêa | Samuel Sato | Samuel Sato |
| Léxico | 07/05/2023 | 16/05/2023 | Samuel Sato | Samuel Sato, Lucas Cardoso | Vitor Manoel | Pedro Muniz |
| Especificação Suplementar | 10/05/2023 | 16/05/2023 | Vitor Manoel | Vitor Manoel | Felipe Corrêa | Lucas Cardoso |
| Gravação da apresentação | 16/05/2023 | 17/05/2023 | Todos os integrantes | Todos os integrantes | Todos os integrantes | Todos os integrantes |
| Histórias de Usuário | 20/05/2023 | 24/05/2023 | Felipe Corrêa | Pedro Muniz, Felipe Corrêa | Lucas Rodrigues | Lucas Cardoso, Samuel Sato |
| Backlog | 20/05/2023 | 24/05/2023 | Lucas Rodrigues | Magno Luiz, Samuel Sato | Magno Luiz | Felipe Corrêa |
| NFR Framework | 20/05/2023 | 24/05/2023 | Magno Luiz | Vitor Manoel, Lucas Cardoso | Pedro Muniz | Samuel Sato, Felipe Corrêa |
| Gravação da apresentação | 23/04/2023 | 24/04/2023 | Todos os integrantes | Todos os integrantes | Todos os integrantes | Todos os integrantes |
| Verificação Analise Documental Grupo 08 | 03/06/2023 | 13/06/23 | - | Magno Luiz | - | Vitor Manoel |
| Verificação Aspectos Gerais Grupo 08 | 03/06/2023 | 14/06/2023 | - | Felipe Corrêa | - | Magno Luiz |
| Verificação Backlog Grupo 08 | 03/06/2023 | 14/06/2023 | - | Felipe Corrêa | - | Magno Luiz |
| Verificação Brainstorm Grupo 08 | 03/06/2023 | 10/06/2023 | - | Pedro Muniz | - | Samuel Sato |
| Verificação Casos de uso Grupo 08 | 03/06/2023 | 14/06/2023 | - | Lucas Cardoso | - | Samuel Sato |
| Verificação Cenários Grupo 08 | 03/06/2023 | 10/06/2023 | - | Vitor Manoel | - | Samuel Sato |
| Verificação Escala de três níveis Grupo 08 | 03/06/2023 | 11/06/2023 | - | Pedro Muniz | - | Samuel Sato |
| Verificação Especificação Suplementar Grupo 08 | 03/06/2023 | 14/06/2023 | - | Samuel Sato | - | Vitor Manoel, Lucas Cardoso |
| Verificação First Things First Grupo 08 | 03/06/2023 | 14/06/2023 | - | Lucas Cardoso | - | Samuel Sato |
| Verificação Histórias de usuário Grupo 08 | 03/06/2023 | 12/06/2023 | - | Vitor Manoel | - | Samuel Sato |
| Verificação Léxicos Grupo 08 | 03/06/2023 | 13/06/2023 | - | Magno Luiz | - | Samuel Sato |
| Verificação MoSCoW Grupo 08 | 03/06/2023 | 14/06/2023 | - | Samuel Sato | - | Vitor Manoel |
| Verificação NFR Grupo 08 | 03/06/2023 | 12/06/2023 | - | Pedro Muniz | - | Samuel Sato |
| Verificação Observação Grupo 08 | 03/06/2023 | 12/06/2023 | - | Felipe Corrêa | - | Magno Luiz |
| Verificação Perfil de usuário Grupo 08 | 03/06/2023 | 28/06/2023 | - | Lucas Cardoso | - | Samuel Sato |
| Verificação Personas Grupo 08 | 03/06/2023 | 09/06/2023 | - | Vitor Manoel | - | Samuel Sato |
| Verificação Planejamento Grupo 08 | 03/06/2023 | 13/06/23 | - | Magno Luiz | - | Pdro Muniz |
| Verificação Rich Picture Grupo 08 | 03/06/2023 | 14/06/23 | - | Samuel Sato | - | Vitor Manoel, Lucas Cardoso |
| Gravação da apresentação | 03/06/2023 | 14/06/2023 | Todos os integrantes | Todos os integrantes | Todos os integrantes | Todos os integrantes |
| Verificação Aspectos Gerais Grupo 07 | 11/06/2023 | 28/06/2023 | - | Magno Luiz | - | Samuel Sato |
| Verificação Backlog Grupo 07 | 11/06/2023 | 14/06/2023 | - | Felipe Corrêa | - | Magno Luiz |
| Verificação Casos de uso Grupo 07 | 11/06/2023 | 19/06/2023 | - | Pedro Muniz | - | Felipe Corrêa |
| Verificação Escala de três níveis Grupo 07 | 11/06/2023 | 22/06/2023 | - | Lucas Cardoso | - | Pedro Muniz |
| Verificação Especificação Suplementar Grupo 07 | 11/06/2023 | 21/06/2023 | - | Lucas Cardoso, Felipe M | - | Samuel Sato, Magno Luiz |
| Verificação Histórias de usuário Grupo 07 | 11/06/2023 | 21/06/2023 | - | Vitor Manoel | - | Samuel Sato |
| Verificação Introspecção Grupo 07 | 11/06/2023 | 21/06/2023 | - | Magno Luiz | - | Vitor Manoel |
| Verificação Léxicos Grupo 07 | 11/06/2023 | 21/06/2023 | - | Samuel Sato | - | Magno Luiz |
| Verificação MoSCoW Grupo 07 | 11/06/2023 | 20/06/2023 | - | Vitor Manoel | - | Samuel Sato |
| Verificação NFR Grupo 07 | 11/06/2023 | 21/06/2023 | - | Samuel Sato | - | Magno Luiz |
| Verificação Perfil de usuário Grupo 07 | 11/06/2023 | 28/06/2023 | - | Lucas Cardoso | - | Felipe M |
| Verificação Personas Grupo 07 | 11/06/2023 | 20/06/2023 | - | Vitor Manoel | - | Samuel Sato |
| Verificação Questionário Grupo 07 | 11/06/2023 | 21/06/2023 | - | Samuel Sato | - | Magno Luiz |
| Verificação Rich Picture Grupo 07 | 11/06/2023 | 20/06/2023 | - | Pedro Muniz | - | Felipe M |
| Verificação Storytelling Grupo 07 | 11/06/2023 | 20/06/23 | - | Pedro Muniz | - | Felipe M |
| Verificação Brainstorm Grupo 07 | 11/06/2023 | 21/06/23 | - | Felipe M | - | Pedro Muniz |
| Verificação Planejamento Grupo 07 | 11/06/2023 | 21/06/23 | - | Felipe M | - | Pedro Muniz |
| Verificação Priorização baseada em valor, custo e risco Grupo 07 | 11/06/2023 | 21/06/23 | - | Felipe M | - | Pedro Muniz |
| Prototipagem | 11/06/2023 | 20/06/23 | - | Pedro Muniz | - | Felipe M |
| Gravação da apresentação | 11/06/2023 | 21/06/2023 | Todos os integrantes | Todos os integrantes | Todos os integrantes | Todos os integrantes |
| Matriz de rastreabilidade | - | 28/06/2023 | - | Pedro Muniz | - | Felipe Corrêa |
| Backward From | 15/06/2023 | 28/06/2023 | Magno Luiz | Pedro Muniz, Felipe M | Pedro Muniz | Felipe M, Pedro Muniz |
| Forward From | 15/06/2023 | 28/06/2023 | Pedro Muniz | Felipe M | Samuel Sato | Pedro Muniz |
| Validação Informal | - | 28/06/2023 | - | Lucas Cardoso | - | Samuel Sato |
| Gravação da apresentação | 18/06/2023 | 28/06/2023 | Todos os integrantes | Todos os integrantes | Todos os integrantes | Todos os integrantes |
| Planejamento de verificação dos artefatos | 28/06/2023 | 05/07/2023 | Samuel Sato | Todos os integrantes | Vitor Manoel | Todos os integrantes |
| Relato da verificação dos artefatos e ajustes | 01/07/2023 | 05/07/2023 | Vitor Manoel | Todos os integrantes | Magno Luiz | Todos os integrantes |
| Artefato final | - | 05/07/2023 | Todos os integrantes | Todos os integrantes | Todos os integrantes | Todos os integrantes |
| Gravação da apresentação | 04/07/2023 | 05/07/2023 | Todos os integrantes | Todos os integrantes | Todos os integrantes | Todos os integrantes |

<h6 align = "center"> Tabela 2: Cronograma planejado vs Executado</h6>
<h6 align = "center"> Fonte: Felipe Mastromauro, 2023 </h6>

## 3. Execução do projeto

### 3.1 Elicitação e priorização

A etapa de elicitação de requisitos se refere às atividades realizadas pela equipe de desenvolvimento para identificar e representar stakeholders do projeto, assim como os requisitos gerados pelos mesmos[1]. Em complemento à elicitação, a priorização é importante na discriminação e categorização dos requisitos elicitados na etapa anterior, onde são utilizadas técnicas para realizar tal tarefa. Para a realização desta etapa, foram utilizadas 4 técnicas de elicitação(brainstorming, introspecção, storytelling e questionários) além de 3 técnicas para a priorização(escala de três níveis, MosCoW e baseada em valor, custo e risco). Para que as técnicas fossem aplicadas da forma correta, utilizando o grupo certo de participantes para representar os usuários, foram elaborados artefatos para o perfil de usuário do sistema, assim como as personas para o projeto. Na tabela 3 a seguir, se encontram os artefatos elaborados durante esta etapa.

<center>

| Artefato | Autor(es) | Revisor(es) |
|--|--|--|
| [Técnicas planejadas - Elicitação](./elicitacao/tecnicas_planejadas.md) | Felipe Corrêa | Pedro Muniz |
| [Perfil de usuário](./elicitacao/perfil.md) | Pedro Muniz | Samuel Sato |
| [Personas](./elicitacao/personas.md) | Pedro Muniz | Vitor Manoel |
| [Brainstorming](./elicitacao/brainstorming.md) | Felipe Corrêa | Pedro Muniz |
| [Introspecção](./elicitacao/introspeccao.md) | Magno Luiz | Vitor Manoel |
| [Storytelling](./elicitacao/Storytelling.md) | Vitor Manoel | Felipe Corrêa |
| [Questionário](./elicitacao/questionario.md) | Samuel Sato | Magno Luiz |
| [Resultados da elicitação](./elicitacao/resultadoElicitacao.md) | Samuel Sato | Pedro Muniz |
| [Técnicas planejadas - Priorização](./elicitacao/tecnicas_priorizacao.md) | Felipe Corrêa | Pedro Muniz |
| [Escala de três níveis](./elicitacao/escalaTresNiveis.md) | Felipe Corrêa | Pedro Muniz |
| [MosCoW](./elicitacao/moscow.md) | Lucas Cardoso | Pedro Muniz |
| [Baseada em valor, custo e risco](./elicitacao/custoxbeneficio.md) | Magno Luiz | Felipe Corrêa |
| [Resultados da priorização](./elicitacao/resultadoPriorizacao.md) | Pedro Muniz | Felipe Corrêa |

</center>

<h6 align = "center"> Tabela 3: Artefatos elaborados na etapa de elicitação e priorização de requisitos</h6>
<h6 align = "center"> Fonte: Pedro Muniz, 2023 </h6>

### 3.2 Modelagem

Durante a etapa de modelagem, os requisitos elicitados e priorizados anteriormente passaram pela fase de análise e especificação, onde foram sumarizados em artefatos que podem ser verificados e validados[1], além disso, foi possível encontrar e resolver conflitos e duplicidades entre os requisitos encontrados. Para a modelagem clássica foram utilizadas 4 técnicas(cenários, casos de uso, léxicos e especificação suplementar), enquanto para a modelagem ágil foram utilizadas 3 técnicas(histórias de usuário, backlog e NFR Framework). Na tabela 4 a seguir, se encontram os artefatos elaborados durante esta etapa.

<center>

| Artefato | Autor(es) | Revisor(es) |
|--|--|--|
| [Cenários](./modelagem/cenarios.md) | Pedro Muniz e Felipe Corrêa | Samuel Sato |
| [Casos de uso](./modelagem/casos_de_uso.md) | Magno Luiz | Pedro Muniz |
| [Léxicos](./modelagem/lexico.md) | Samuel Sato | Pedro Muniz |
| [Especificação Suplementar](./modelagem/EspecificacaoSup.md) | Vitor Manoel | Lucas Cardoso |
| [Histórias de usuário](./modelagem/agil/userStories.md) | Pedro Muniz e Felipe Corrêa | Samuel Sato |
| [Backlog](./modelagem/agil/backlog.md) | Samuel Sato e Magno Luiz | Felipe Corrêa |
| [NFR Framework](./modelagem/NFRframework.md) | Vitor Manoel e Lucas Cardoso | Felipe Corrêa |

</center>

<h6 align = "center"> Tabela 4: Artefatos elaborados na etapa de modelagem de requisitos</h6>
<h6 align = "center"> Fonte: Pedro Muniz, 2023 </h6>

### 3.3 Rastreabilidade

A rastreabilidade de um projeto de requisitos é de extrema importância para que nada seja perdido durante a execução do mesmo[3]. A rastreabilidade de requisitos pode ser dividida em duas formas: a pré-rastreabilidade, onde os requisitos elicitados são conectados com suas origens e a pós-rastreabilidade, onde os requisitos elicitados são conectados com seus impactos no sistema final. Durante a execução do projeto, diversos requisitos foram coletados de diferentes fontes e após sua priorização foram modelados de várias maneiras, para que todo este processo fosse documentado, foram criados artefatos para ambas as rastreabilidades, assim como uma matriz geral para o projeto. Na tabela 5 a seguir, se encontram os artefatos elaborados durante esta etapa.

<center>

| Artefato | Autor(es) | Revisor(es) |
|--|--|--|
| [Backward from](./rastreabilidade/pre.md) | Pedro Muniz | Felipe Corrêa |
| [Forward from](./rastreabilidade/pos.md) | Felipe Corrêa | Pedro Muniz |
| [Matriz de rastreabilidade](./rastreabilidade/matriz.md) | Pedro Muniz e Felipe Corrêa | Magno Luiz |

</center>

<h6 align = "center"> Tabela 5: Artefatos elaborados na etapa de rastreabilidade de requisitos</h6>
<h6 align = "center"> Fonte: Pedro Muniz, 2023 </h6>

## 4. Técnicas utilizadas

Durante a execução do projeto, forma utilizadas diversas técnicas afim de elaborar os artefatos que pertencem ao mesmo, tais artefatos e técnicas se encontram sumarizados na tabela 6 a seguir.

| Etapa | Artefato | Técnica utilizada | Autor(es) | Revisor(es) |
|-------|----------|-------------------|-----------|-------------|
| Etapa 1 | [Ferramentas](https://requisitos-de-software.github.io/2023.1-Petz/planejamento/ferramentas/)|-|Pedro Muniz|Felipe Corrêa|
| Etapa 1 | [Metodologia](https://requisitos-de-software.github.io/2023.1-Petz/planejamento/metodologia/)|-|Pedro Muniz|Samuel Sato|
| Etapa 1 | [Atas e gravações](https://requisitos-de-software.github.io/2023.1-Petz/atas/reuniao12042023/)|-|Samuel Sato|Pedro Muniz|
| Etapa 1 | [Rich picture](https://requisitos-de-software.github.io/2023.1-Petz/pre-rastreabilidade/richpicture/)| Rich Picture |Magno Luiz e Pedro Muniz| Felipe Corrêa  |
| Etapa 1 | [Geral - Elicitação(Técnicas planejadas, resultados elicitação e priorização)](https://requisitos-de-software.github.io/2023.1-Petz/elicitacao/tecnicas_planejadas/)|-|Pedro Muniz| Samuel Sato |
| Etapa 2 | [Perfil de usuário](https://requisitos-de-software.github.io/2023.1-Petz/elicitacao/perfil/)| Questionário |Pedro Muniz| Samuel Sato |
| Etapa 2 | [Personas](https://requisitos-de-software.github.io/2023.1-Petz/elicitacao/personas/)| Questionário |Pedro Muniz| Vitor Manoel|
| Etapa 2 | [Brainstorm](https://requisitos-de-software.github.io/2023.1-Petz/elicitacao/brainstorming/)|Brainstorm|Felipe Corrêa| Pedro Muniz|
| Etapa 2 | [Instrospecção](https://requisitos-de-software.github.io/2023.1-Petz/elicitacao/introspeccao/)|Instrospecção|Magno Luiz| Vitor Manoel e Samuel Sato  |
| Etapa 2 | [StoryTelling](https://requisitos-de-software.github.io/2023.1-Petz/elicitacao/Storytelling/)|StoryTelling|Vitor Manoel| Felipe Corrêa |
| Etapa 2 | [Questionário](https://requisitos-de-software.github.io/2023.1-Petz/elicitacao/questionario/)|Questionário|Samuel Sato| Magno Luiz|
| Etapa 2 | [Escala de três níveis](https://requisitos-de-software.github.io/2023.1-Petz/elicitacao/escalaTresNiveis/)|Escala de três níveis|Felipe Corrêa| Pedro Muniz |
| Etapa 2 | [MosCow](https://requisitos-de-software.github.io/2023.1-Petz/elicitacao/moscow/)|MosCow|Lucas Cardoso| Pedro Muniz |
| Etapa 2 | [Baseada em valor, custo e risco](https://requisitos-de-software.github.io/2023.1-Petz/elicitacao/custoxbeneficio/)|Priorização baseada em valor, custo e risco|Magno Luiz| Felipe Corrêa |
| Etapa 3 | [Cenários](https://requisitos-de-software.github.io/2023.1-Petz/modelagem/cenarios/)|Cenários|Pedro Muniz e Felipe Corrêa| Samuel Sato e Magno Luiz|
| Etapa 3 | [Casos de uso](https://requisitos-de-software.github.io/2023.1-Petz/modelagem/casos_de_uso/)|Casos de uso|Magno Luiz| Pedro Muniz|
| Etapa 3 | [Léxicos](https://requisitos-de-software.github.io/2023.1-Petz/modelagem/lexico/)|Léxicos|Samuel Sato e Lucas Rodrigues| Felipe Corrêa e Vitor Manoel|
| Etapa 3 | [Especificação suplementar](https://requisitos-de-software.github.io/2023.1-Petz/modelagem/EspecificacaoSup/)|Especificação suplementar|Vitor Manoel| Lucas Cardoso |
| Etapa 4 | [Histórias de usuário](https://requisitos-de-software.github.io/2023.1-Petz/modelagem/agil/userStories/)|Histórias de usuário|Pedro Muniz| Samuel Sato |
| Etapa 4 | [Backlog](https://requisitos-de-software.github.io/2023.1-Petz/modelagem/agil/backlog/)|Backlog|Samuel Sato e Magno Luiz| Felipe Corrêa |
| Etapa 4 | [NFR Framework](https://requisitos-de-software.github.io/2023.1-Petz/modelagem/NFRframework/)|NFR Framework|Vitor Manoel e Lucas Rodrigues| Samuel Sato |
| Etapa 5.1 | [Verificação](https://requisitos-de-software.github.io/2023.1-Petz/analise/planejamento/)|Inspeção por Fagan|Todos| Todos |
| Etapa 5.2 | [Verificação](https://requisitos-de-software.github.io/2023.1-Petz/analise/planejamento/)|Inspeção por Fagan|Todos| Todos |
| Etapa 5.2 | [Validação por prototipação](https://requisitos-de-software.github.io/2023.1-Petz/analise/validacao/prototipagem/)| Prototipação |Pedro Muniz e Felipe Corrêa| Magno Luiz |
| Etapa 5.2 | [Validação informal](https://requisitos-de-software.github.io/2023.1-Petz/analise/validacao/prototipagem/)| Validação informal |Lucas Cardoso| Pedro Muniz |
| Etapa 6 | [Pré-Rastreabilidade](https://requisitos-de-software.github.io/2023.1-Petz/rastreabilidade/pre/)| Metamodelo de Toranzo | Pedro Muniz | Felipe Corrêa |
| Etapa 6 | [Pós-Rastreabilidade](./rastreabilidade/pos.md) | - | Felipe Corrêa | Pedro Muniz |
| Etapa 6 | [Matriz de Rastreabilidade](./rastreabilidade/matriz.md) | - | Pedro Muniz e Felipe Corrêa | Magno Luiz | 

<h6 align = "center"> Tabela 6: Artefatos elaborados no decorrer do projeto</h6>
<h6 align = "center"> Fonte: Samuel Sato, 2023 </h6>


## 5. Verificação e validação
A etapa de verificação e validação é responsável pela análise dos documentos elaborados durante o projeto, buscando erros e possíveis correções presentes no mesmo. A validação possui o objetivo de confirmar o entendimento por parte do engenheiro de requisitos das necessidades dos *stakeholders* assim como seus desejos para o sistema, enquanto a verificação busca confirmar se os artefatos gerados pelo projeto estão corretos, quanto ao seu conteúdo e padrão da organização para a qual o sistema é desenvolvido.[2]
Durante o projeto, para a validação foram utilizadas as técnicas de prototipação, onde protótipos referentes a requisitos não implementados foram prototipados e validados com um usuário, e a validação informal, onde o projeto foi validado junto à equipe técnica do aplicativo Petz. Para a verificação, foi utilizada a técnica de inspeção com base na proposta de Fagan[1], onde são verificados os erros mais comuns presentes em cada artefato, assim como suas possíveis correções. Antes de realizar a verificação e validação do projeto, foi feito uma verificação inicial no projeto do grupo 08 o qual analisou o aplicativo Twitch. Para ambas as verificações, foi estabelecido um padrão a ser seguido, buscando manter uma conformidade entre os artefatos gerados, o qual pode ser encontrado em uma artefato próprio. Na tabela 7 a seguir, se encontram os artefatos verificados no projeto do grupo 08.

<center>

| Artefato | Autor(es) | Revisor(es) |
|--|--|--|
| [Planejamento](./analise/teste/planejamento.md) | Magno Luiz | Pedro Muniz |
| [Aspectos gerais](./analise/teste/aspectosGerais.md) | Felipe Corrêa | Magno Luiz |
| [Rich Picture](./analise/teste/richpicture.md) | Samuel Sato | Vitor Manoel |
| [Perfil de usuário](./analise/teste/perfilDeUsuario.md) | Lucas Cardoso | Samuel Sato |
| [Personas](./analise/teste/personas.md) | Vitor Manoel | Samuel Sato |
| [Brainstorm](./analise/teste/brainstorm.md) | Pedro Muniz | Samuel Sato |
| [Observação](./analise/teste/observacao.md) | Felipe Corrêa | Magno Luiz |
| [Análise documental](./analise/teste/analiseDocumental.md) | Magno Luiz | Vitor Manoel |
| [MosCow](./analise/teste/moscow.md) | Samuel Sato | Vitor Manoel |
| [First things First](./analise/teste/firstThingsFirst.md) | Lucas Cardoso | Samuel Sato |
| [Escala de três níveis](./analise/teste/escalaTresNiveis.md) | Pedro Muniz | Samuel Sato |
| [Cenários](./analise/teste/cenarios.md) | Vitor Manoel | Samuel Sato |
| [Léxicos](./analise/teste/lexicos.md) | Magno Luiz | Samuel Sato |
| [Casos de uso](./analise/teste/casosDeUso.md) | Lucas Cardoso | Samuel Sato |
| [Especificação suplementar](./analise/teste/especificacaoSuplementar.md) | Samuel Sato | Vitor Manoel |
| [Histórias de usuário](./analise/teste/historiasUsuario.md) | Vitor Manoel | Samuel Sato |
| [Backlog](./analise/teste/backlog.md) | Felipe Corrêa | Magno Luiz |
| [NFR Framework](./analise/teste/nfr.md) | Pedro Muniz | Samuel Sato |

</center>

<h6 align = "center"> Tabela 7: Artefatos de verificação para o projeto do grupo 08</h6>
<h6 align = "center"> Fonte: Pedro Muniz, 2023 </h6>

Na tabela 8 a seguir, se encontram os artefatos verificados no projeto.

<center>

| Artefato | Autor(es) | Revisor(es) |
|--|--|--|
| [Planejamento da verificação](./analise/planejamento.md) | Pedro Muniz | Felipe Corrêa |
| [Planejamento](./analise/verif_planejamento.md) | Felipe Corrêa | Pedro Muniz |
| [Aspectos gerais](./analise/aspectosgerais.md) | Magno Luiz | Samuel Sato |
| [Rich picture](./analise/richpicture.md) | Pedro Muniz | Felipe Corrêa |
| [Perfil de usuário](./analise/perfildeusuario.md) | Lucas Cardoso | Pedro Muniz |
| [Personas](./analise/Personas.md) | Vitor Manoel | Samuel Sato |
| [Brainstorm](./analise/verif_brainstorming.md) | Felipe Corrêa | Pedro Muniz |
| [Instrospecção](./analise/introspeccao.md) | Magno Luiz | Vitor Manoel |
| [Storytelling](./analise/storytelling.md) | Pedro Muniz | Felipe Corrêa |
| [Questionário](./analise/questionario.md) | Samuel Sato | Magno Luiz |
| [Escala de três níveis](./analise/escalatresniveis.md) | Lucas Cardoso | Pedro Muniz |
| [MosCow](./analise/mosCow.md) | Vitor Manoel | Samuel Sato |
| [Baseada em valor, custo e risco](./analise/verif_prioValorCustoRisco.md) | Felipe Corrêa | Pedro Muniz |
| [Cenários](./analise/cenarios.md) | Magno Luiz | Pedro Muniz |
| [Casos de uso](./analise/casoDeUso.md) | Pedro Muniz | Felipe Corrêa |
| [Léxicos](./analise/lexicos.md) | Samuel Sato | Magno Luiz |
| [Especificação suplementar](./analise/especificacaosuplementar.md) | Lucas Cardoso | Pedro Muniz |
| [Histórias de usuário](./analise/historiasDeUsuario.md) | Vitor Manoel | Samuel Sato |
| [Backlog](./analise/Backlog.md) | Vitor Manoel | Samuel Sato |
| [NFR Framework](./analise/NFR.md) | Samuel Sato | Magno Luiz |

</center>

<h6 align = "center"> Tabela 8: Artefatos de verificação para o projeto</h6>
<h6 align = "center"> Fonte: Pedro Muniz, 2023 </h6>

Na tabela 9 a seguir, se encontram as validações realizadas no projeto.

<center>

| Artefato | Autor(es) | Revisor(es) |
|--|--|--|
| [Prototipação](./analise/validacao/prototipagem.md) | Pedro Muniz e Felipe Corrêa | Magno Luiz |
| [Validação informal](./analise/validacao/validacaoInformal.md) | Lucas Cardoso | Samuel Sato |

</center>

<h6 align = "center"> Tabela 9: Artefatos de validação para o projeto</h6>
<h6 align = "center"> Fonte: Pedro Muniz, 2023 </h6>

## 6. Resultados alcançados

Os resultados alcançados pelo Grupo 7 da disciplina de Requisitos de Software, ministrada no semestre 2023.1 da Universidade de Brasília, em relação a composição do projeto de Engenharia de Requisitos do aplicativo Petz, estão divididos em relatos dos resultados em relação ao objetivo do projeto, a listagem dos principais resultados, a descrição destes e a identificação aprendizados, facilidades e dificuldades ao executar o projeto.
 
O desenvolvimento deste projeto tem como objetivo aplicar os conhecimentos relacionados aos conceitos da Engenharia de Requisitos, em que os alunos que estão integrados no projeto serão capazes de utilizar técnicas, ferramentas e os recursos necessários na produção deste ou outro projeto referente a Engenharia de Requisitos.
 Ao considerar que o projeto é o reflexo da compreensão dos participantes que confeccionaram os diversos artefatos que categorizam-se em etapas dos processos básicos da Engenharia de Requisitos, é possível analisar e avaliar conhecimentos enquanto coexistem a teoria e a prática.
Ao utilizar-se de uma aplicação abrangente em relação ao público e com fácil acesso ao sistema, seria possível abstrair as informações necessárias para a elaboração de cada artefato presente no projeto.

Desta forma, o Grupo 7,  teve como propósito o desenvolvimento de mais de 80 artefatos, que destacam-se:

- 3 artefatos gerais que contém o planejamento e a organização do projeto;
- 5 técnicas de elicitação de requisitos, planejadas e executadas;
- 3 técnicas de priorização de requisitos, que priorizam e agrupam os requisitos;
- 7 técnicas de modelagem de requisitos, sendo que 3 são baseadas na metodologia ágil;
- 43 requisitos funcionais elicitados, categorizados e priorizados;
- 5 requisitos não funcionais, sendo 4 destes com alta prioridade;
- 3 artefatos que exemplificam o processo de rastreabilidade do projeto;

Analisando os resultados disponibilizados, a equipe desenvolveu baseando-se na metodologia apresentada para a realização do projeto completo, em que foi possível desenvolver habilidades de diagramação, observação, comunicação, organização, planejamento, acompanhamento e apresentação, além de incluir em conjunto os conhecimentos específicos da área de Engenharia de Requisitos, principalmente voltados à elicitação, priorização e modelagem de requisitos. A realização de métodos que constroem a delineação do grupo de estudo a ser pesquisado e os possíveis usuários da aplicação escolhida, mesmo que tenha ocorrido dificuldades para validar etapas do projeto com este grupo de usuários, a organização e rastreabilidade do projeto também foram resultados propostos no desenvolvimento do projeto.

### 6.2 Facilidades

Entre as facilidades encontradas pela equipe, destaca-se a ampla gama de bibliografia disponível acerca da área de requisitos de software o que possibilitou uma pesquisa facilitada dos conceitos a serem trablhados, além disso deve-se citar a atenção e disponibilidade do monitor responsável pelo grupo e do professor para sanar dúvidas e apontar correções necessárias. Por fim, a disponibilidade de repositórios de grupos anteriores facilitou na procuira de bases para o trabalho no projeto.

### 6.3 Dificuldades
Entre as dificuldades, pode-se citar principalmente o curto período para a entrega de cada etapa, o qual acabou por muitas vezes não sendo suficiente para uma elaboração totalmente satisfatória dos artefatos, outro problema encontrado foi a necessidade de validação de diversos artefatos com pessoas de fora do círculo de convívio dos integrantes do grupo. Por fim, cita-se a dificuldade de conciliação do projeto com outras atividades realizadas pelos integrantes da equipe.


## 7. Apresentações

Durante o projeto, houveram entregas parciais do mesmo, onde foram apresentados os artefatos produzidos até então, a tabela 10 a seguir sumariza as apresentações realizadas assim como seus participantes.

| Etapa | Página de apresentação | Participantes |
|-|-|-|
| 1 | [Apresentação etapa 1](./apresentacoes/apresentacao1.md) | Pedro, Felipe, Magno, Vitor, Samuel, Lucas |
| 2 | [Apresentação etapa 2](./apresentacoes/apresentacao2.md) | Pedro, Felipe, Magno, Vitor, Samuel, Lucas |
| 3 | [Apresentação etapa 3](./apresentacoes/apresentacao3.md) | Pedro, Felipe, Magno, Vitor, Samuel, Lucas |
| 4 | [Apresentação etapa 4](./apresentacoes/apresentacao4.md) | Pedro, Felipe, Magno, Vitor, Samuel, Lucas |
| 5.1 | [Apresentação etapa 5.1](./apresentacoes/apresentacao5.md) | Pedro, Felipe, Magno, Vitor, Samuel, Lucas |
| 5.2 | [Apresentação etapa 5.2](./apresentacoes/apresentacao6.md) | Pedro, Felipe, Magno, Vitor, Samuel |
| 6 | [Apresentação etapa 6](./apresentacoes/apresentacao7.md) | Pedro, Felipe, Magno, Vitor, Samuel, Lucas |

<h6 align = "center"> Tabela 10: Apresentações realizadas durante o projeto</h6>
<h6 align = "center"> Fonte: Pedro Muniz, 2023 </h6>


## 8. Agradecimentos
- Ao professor André Barros, pelas aulas, feedbacks e materiais disponibilizados.
- Ao monitor Bernardo Chaves, pelos feedbacks e sugestões de correção.
- Aos participantes do grupo 06 pelas verificações e erros apontados.
- Aos participantes do grupo 07 pela dedicação ao projeto.

## 9. Bibliografia

> [1] Gerência e Qualidade de Software - Aula 06 - Técnica de revisão – UNIVESP

> [2] REINEHR, Sheila. Engenharia de Requisitos. Porto Alegre: Sagah, 2020.

> [3] SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado. Rastreabilidade de Requisitos. 2005. 26 f. Tese (Doutorado) - Curso de Ciência da Computação, Pontifícia Universidade Católica do Rio de Janeiro, Rio de Janeiro, 2005. Cap. 2.

## 10. Histórico de versão

| Versão | Data     | Descrição | Autor(es) | Revisor(es) |
| ------ | -------- | --------- | --------- | ----------- |
| `1.0`  | 04/07/2023 | Adição da execução do projeto e tabela de verificações | Pedro Muniz | Felipe Corrêa |
| `1.1` | 05/07/2023  | Adição da introdução do documento | Vitor Manoel | Pedro Muniz |
| `1.2` | 05/07/2023  | Adição da tabela de técnicas utilizadas | Samuel Sato | Pedro Muniz |
| `1.3` | 05/07/2023 | Adição dos resultados obtidos | Magno Luiz | Felipe Corrêa |
| `1.4` | 05/07/2023 | Adição das ferramentas e cronogramas | Felipe Corrêa | Samuel Sato |
| `1.5` | 05/07/2023 | Adição das facilidades, dificuldades e apresentações | Pedro Muniz | Lucas Cardoso |


