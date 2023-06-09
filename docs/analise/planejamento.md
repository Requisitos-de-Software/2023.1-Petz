# Planejamento da verificação

## 1. Introdução

A fase de análise de requisitos é de extrema importância para que um produto de software possua uma boa qualidade, no caso dos requisitos uma boa análise impede que erros cometidos durante a manipulação dos requisistos se alastrem para o desenvolvimento, criando grandes obstáculos nas etapas mais adiante no processo, o que pode gerar retrabalhos custosos. Na engenharia de requisitos, a análise pode ser dividida em duas áreas, verificação e validação. Enquanto a verificação atua para analisar se os documentos de requisitos estão em conformidade com os padrões do projeto, a validação busca analisar se todas as necessidades do cliente foram especificadas na forma de requisitos[2].

Este artefato detalha o planejamento da verificação para este projeto, apresentando a metodologia, estruturas e padrões que serão utilizados para verificar a estrutura do projeto realizado até então. Este documento possui como inspiração o artefato de planejamento da verificação do repositório [Lichess do semestre 2022.2](https://github.com/Requisitos-de-Software/2022.2-Lichess)[3].

## 2. Metodologia

Para a verificação do projeto, será utilizado o método de inspeção. Que consiste na utilização de _[checklist](../planejamento/glossario.md#Checklist)s_ para verificar os padrões especificados, assim como a presença correta de elementos e conceitos nos artefatos analisados. Para a elaboração do _[checklist](../planejamento/glossario.md#Checklist)_, foi utilizada a proposta de Fagan[1], onde o _[checklist](../planejamento/glossario.md#Checklist)_ deve ponderar os erros mais comuns identificados em projetos semelhantes. Por fim, para que a verificação do projeto seja realizada de forma correta, será executado um teste piloto onde será verificada a estrutura e conteúdo do projeto realizado pelo [grupo 8 da disciplina](https://github.com/Requisitos-de-Software/2023.1-Twitch)[4], o qual é responsável pela análise do aplicativo [Twitch]()[5].

Através dos dados coletados pelo método do _[checklist](../planejamento/glossario.md#Checklist)_, pode-se calcular numericamente o grau de satisfação com os padrões propostos, sendo este cálculo descrito pela fórmula presente na figura 1, a representação gráfica do grau de satisfação será realizada atráves de um anel de progresso, como o apresentado na figura 2. Além do grau de satisfação, pode-se calcular a porcentagem de ocorrência de erros, que deve ser representado em cada verificação por um gráfico de pizza, assim como o representado pela figura 3.

<center>

![Equação para cálculo do grau de satisfação](../assets/analise/equacao.jpg)

<h6 align="center">Figura 1: Equação para cálculo do grau de satisfação</h6>
<h6 align="center">Fonte: Autor, 2023</h6>

| ![Modelo de representação do grau de satisfação](../assets/analise/padraoProgresso.gif)               | ![Modelo de gráfico de ocorrência de erros](../assets/analise/padraoGrafico.gif)                 |
| ----------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| <h6 align="center">Figura 2: Modelo de representação do grau de satisfação<br>Fonte: Autor, 2023</h6> | <h6 align="center">Figura 3: Modelo de gráfico de ocorrência de erros<br>Fonte: Autor, 2023</h6> |

</center>

<h6 align="center">Tabela 1: Modelos para representação gráfica</h6>
<h6 align="center">Fonte: Autor, 2023</h6>

## 3. _[Checklist](../planejamento/glossario.md#Checklist)_

Para a verificação de cada artefato, serão utilizados dois _[checklist](../planejamento/glossario.md#Checklist)s_ distintos, onde um será responsável pelos parâmetros de padronização para cada artefato, sendo este idêntico para cada documento. O segundo _[checklist](../planejamento/glossario.md#Checklist)_ será exclusivo para cada artefato, e analisará o documento de acordo com as necessidades previstas no plano de ensino da disciplina[6]. A tabela 2 abaixo, demonstra a estrutura do _[checklist](../planejamento/glossario.md#Checklist)_ de padronização que será utilizado. A tabela 3 detalha os elementos que a _[checklist](../planejamento/glossario.md#Checklist)_ de conteúdo deve conter.

<center>

| ID | Verificação | Realizado |
|:-:|--|--|
| 1 | Possui ortografia correta e formal? | - |
| 2 | Possui introdução? | - |
| 3 | Possui links necessários? | - |
| 4 | As tabelas e imagens possuem legenda padronizada e chamada no texto? | - |
| 5 | As tabelas e imagens estão totalmente em português? | - |
| 6 | Possui bibliografia? | - |
| 7 | A bibliografia está em ordem alfabética? | - |
| 8 | Possui histórico de versão padronizado? | - |
| 9 | O histórico de versão possui autor(es) e revisor(es)? | - |

</center>

<h6 align="center">Tabela 2: Modelo de checklist para padronização</h6>
<h6 align="center">Fonte: Autor, 2023</h6>

<center>

| ID | Verificação | Ocorrências | Acertos | Erros |
| :-: | ------- | -------- | -------- | ------ |
| USX | Descrição | Qtd. de verificações | Qtd. de acertos | Qtd. de erros |

<h6 align="center">Tabela 3: Modelo de checklist para conteúdo</h6>
<h6 align="center">Fonte: Autor, 2023</h6>

</center>

## 4. Estrutura dos documentos
Os documentos referentes à verificação dos artefatos deve seguir uma estrutura pré-definida, tal estrutura pode ser encontrada abaixo:

### 4.1 Introdução
Nesta seção deve ser feita uma pequena introdução acerca do artefato verificado, além de conter informações sobre a versão do artefato e data da verificação.

### 4.2 Metodologia
Nesta seção devem ser detalhadas todas as verificações de conteúdo elaboradas, contendo uma breve descrição e critérios para a escolha da mesma, além de sua fonte.

### 4.3 Desenvolvimento
Nesta seção devem ser apresentadas as duas _checklists_ de verificação do artefato preenchidas com os dados obtidos da verificação.

### 4.4 Resultados
Nesta seção devem ser apresentadas as representações gráficas do grau de satisfação e ocorrência de erros calculados a partir dos dados obtidos da verificação.

### 4.5 Problemas encontrados
Nesta seção devem ser apresentados os erros e problemas encontrados na verificação de forma detalhada. Além de propostas de correções para os problemas apresentados.

### 4.6 Acompanhamento
Nesta seção devem ser apresentadas as correções necessárias, além de informar quais problemas foram corrigidos.

## 5. Padrões do projeto

Para verificar se o projeto segue um padrão consiso em todos os seus artefatos, segue abaixo o padrão adotado para legenda, bibliografia e histórico de versão
´
### 5.1 Legenda

Todas as tabelas e imagens presentes no projeto, além de serem chamadas de forma coesa pelo texto, devem possuir a legnda padronizada. Tal padrão pode ser encontrado abaixo.

Para tabelas:

```html
<h6 align="center">Tabela X: Descrição</h6>
<h6 align="center">Fonte: Autor, 2023</h6>
```

Para imagens:

```html
<h6 align="center">Figura X: Descrição</h6>
<h6 align="center">Fonte: Autor, 2023</h6>
```

### 5.2 Bibliografia

A bibliografia de cada artefato deve estar em ordem alfabética e identificada com numeração crescente. Abaixo se encontra um exemplo de bibliografia

> [1] Referência A

> [2] Referência B

> [3] Referência C

### 5.3 Histórico de versão

Abaixo se encontra o padrão de histórico de versão adotado no projeto.

<center>

| Versão | Data     | Descrição | Autor(es) | Revisor(es) |
| ------ | -------- | --------- | --------- | ----------- |
| `1.0`  | XX/XX/XX | Descrição | Autor(es) | Revisor(es) |

</center>

<h6 align="center">Tabela 4: Padrão para histórico de versão</h6>
<h6 align="center">Fonte: Autor, 2023</h6>

## 6. Teste piloto

Para a verificação seja feita de forma correta, primeiramente será executado um teste piloto, onde serão analisados os artefatos criados pelo [grupo 8](https://github.com/Requisitos-de-Software/2023.1-Twitch)[4], na tabela 4 apresentada abaixo se encontram os artefatos que serão analisados, assim como o responsável por cada verificação.

<center>

| Artefato | Revisor |
|--|--|
| [Planejamento](../analise/teste/planejamento.md) | Magno |
| [Aspectos gerais](../analise/teste/aspectosGerais.md) | Felipe |
| [Rich Picture](../analise/teste/richpicture.md) | Samuel |
| [Perfil de usuário](../analise/teste/perfilDeUsuario.md) | Lucas |
| [Personas](../analise/teste/personas.md) | Vitor |
| [Brainstorm](../analise/teste/brainstorm.md) | Pedro |
| [Observação](../analise/teste/observacao.md) | Felipe |
| [Análise documental](../analise/teste/analiseDocumental.md) | Magno |
| [MosCow](../analise/teste/moscow.md) | Samuel |
| [First things First](../analise/teste/firstThingsFirst.md) | Lucas |
| [Escala de três níveis](../analise/teste/escalaTresNiveis.md) | Pedro |
| [Cenários](../analise/teste/cenarios.md) | Vitor |
| [Léxicos](../analise/teste/lexicos.md) | Magno |
| [Casos de uso](../analise/teste/casosDeUso.md) | Lucas |
| [Especificação suplementar](../analise/teste/especificacaoSuplementar.md) | Samuel |
| [Histórias de usuário](../analise/teste/historiasUsuario.md) | Vitor |
| [Backlog](../analise/teste/backlog.md) | Felipe |
| [NFR Framework](../analise/teste/nfr.md) | Pedro |

</center>

<h6 align="center">Tabela 5: Artefatos a serem verificados</h6>
<h6 align="center">Fonte: Autor, 2023</h6>

## 7. Verificação
Na tabela 6 se encontram os responsáveis pela verificação dos artefatos desenvolvidos pela equipe.

<center>

| Artefato | Revisor |
|------------------------------------------------------------------------------|--------|
| Planejamento                                                                 | Felipe |
| Aspectos gerais                                                              | Magno  |
| Rich picture                                                                 | Pedro  |
| Geral - Elicitação(Técnicas planejadas, resultados elicitação e priorização) | Samuel |
| Perfil de usuário                                                            | Lucas  |
| Personas                                                                     | Vitor  |
| Brainstorm                                                                   | Felipe |
| Instrospecção                                                                | Magno  |
| StoryTelling                                                                 | Pedro  |
| Questionário                                                                 | Samuel |
| Escala de três níveis                                                        | Lucas  |
| MosCow                                                                       | Vitor  |
| Baseada em valor, custo e risco                                              | Felipe |
| Cenários                                                                     | Magno  |
| Casos de uso                                                                 | Pedro  |
| Léxicos                                                                      | Samuel |
| Especificação suplementar                                                    | Lucas  |
| Histórias de usuário                                                         | Vitor  |
| Backlog                                                                      | Vitor  |
| NFR Framework                                                                | Samuel |

</center>

<h6 align="center">Tabela 6: Artefatos a serem verificados</h6>
<h6 align="center">Fonte: Autor, 2023</h6>

## 8. Validação 

Na tabela 7 se encontram os responsáveis pela verificação dos artefatos desenvolvidos pela equipe.

<center>

| Validação | Reponsável (eis) |
|-----------|------------------|
| Informal | Lucas |
| Prototipação | Pedro e Felipe |

<h6 align="center">Tabela 7: Responsáveis pela validação</h6>
<h6 align="center">Fonte: Autor, 2023</h6>


</center>

## 7. Referências Bibliográficas

> [1] Gerência e Qualidade de Software - Aula 06 - Técnica de revisão – UNIVESP

> [2] REINEHR, Sheila. Engenharia de Requisitos. Porto Alegre: Sagah, 2020.

> [3] Repositório Lichess do semestre 2022.2, acesso em: 24 de maio de 2023. Para mais informações acesse: <https://github.com/Requisitos-de-Software/2022.2-Lichess>

> [4] Repositório Twitch do semestre 2023.1, acesso em: 24 de maio de 2023. Para mais informações acesse: <https://github.com/Requisitos-de-Software/2023.1-Twitch>

> [5] Twitch, acesso em: 24 de maio de 2023. Para mais informações acesse: <https://www.twitch.tv/>

## 8. Histórico de versão

| Versão | Data     | Descrição                                        | Autor(es)   | Revisor(es)   |
| ------ | -------- | ------------------------------------------------ | ----------- | ------------- |
| `1.0`  | 24/05/23 | Criação da página de planejamento da verificação | Pedro Muniz | Felipe Corrêa |
| `1.1` | 25/05/23 | Adição da tabela de conteúdo | Pedro Muniz | Felipe Corrêa |
| `1.2` | 18/06/23 | Adição da verificação e validação do projeto | Pedro Muniz | Felipe Corrêa |
