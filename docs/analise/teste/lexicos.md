

## 1. Introdução

Este artefato apresenta a verificação do artefato criado pelo [grupo 8 da disciplina](https://github.com/Requisitos-de-Software/2023.1-Twitch) sobre os [léxicos](https://requisitos-de-software.github.io/2023.1-Twitch/modelagem/lexico/) da aplicação [Twitch](https://www.twitch.tv/)[3]. A versão do artefato verificado é a [1.1](https://requisitos-de-software.github.io/2023.1-Twitch/modelagem/lexico/#historico-de-versao) do dia 4 de junho de 2023.

## 2. Metodologia 

A metodologia segue como base, o artefato de [planejamento](https://requisitos-de-software.github.io/2023.1-Petz/analise/planejamento/) de verificação.

Este artefato apresenta duas _[checklist](../planejamento/glossario.md#Checklist)s_ , que podem ser preenchidas com "Sim", caso tenha sido realizado, ou "Não, caso não tenha sido realizado. Se "Não" for preenchido, serão sugeridas possíveis correções ou motivos para a não realização da atividade apresentada. 

## 3. Checklists

### 3.1 Padronização

Esta  _[checklist](../planejamento/glossario.md#Checklist)_ é responsável por verificar a padronização do artefato [léxicos](https://requisitos-de-software.github.io/2023.1-Twitch/modelagem/lexico/)[2].

<center>

| ID | Verificação | Realizado | Possíveis correções |
|:-:|--|--|--|
| 1 | Possui ortografia correta e formal? | Sim | - |
| 2 | Possui introdução? | Sim | - |
| 3 | Possui links necessários? | Não | A bibliografia poderia ser referenciada diretamente nos textos e possuir rastreabilidade para as fontes. |
| 4 | As tabelas e imagens possuem legenda padronizada e chamada no texto? | Não | As tabelas de léxicos poderiam possuir legenda,entretanto somente o primeiro exemplo possui. |
| 5 | As tabelas e imagens estão totalmente em português? | Não | Não existe razão para estar totalmente em português, devido a necessidade da utilização de palavras que expressam especificidades da aplicação em inglês. |
| 6 | Possui bibliografia? | Sim | - |
| 7 | A bibliografia está em ordem alfabética? | Sim | - |
| 8 | Possui histórico de versão padronizado? | Sim | - |
| 9 | O histórico de versão possui autor(es) e revisor(es)? | Não | Adicionar revisores ao histórico de versão e ao artefato. |

</center>

<h6 align="center">Tabela 1: Checklist para padronização</h6>
<h6 align="center">Fonte: Autor, 2023</h6>

### 3.2 Conteúdo abordado

Esta  _[checklist](../planejamento/glossario.md#Checklist)_ é responsável por verificar o conteúdo abordado baseado na construção de léxicos[1] de aplicações.

<center>

| ID | Verificação | Ocorrências | Acertos | Erros | Possíveis correções |
| :-: | ------- | -------- | -------- | ------ | -------- |
| 1 | Os léxicos estão especificados? | 33 |33 | 0 | - |
| 2 | Existe definição do usuário nos léxicos? | 1 | 1 | 0 | - |
| 3 | É adotada a estrutura de dicionário(verbo,objeto,estado) nos léxicos? | 33  | 33 | 0 | - |
| 4 | Os léxicos possuem ligação entre si? | 1  | 1 | 0 | - |
| 5 | A definição dos léxicos está coerente com a aplicação? | 33  | 33 | 0 | - |
| 6 | Os léxicos possuem nome? | 33  | 33 | 0 | - |
| 7 | Os léxicos possuem Classificação? | 33  | 33 | 0 | - |
| 8 | Os léxicos possuem Impacto? |  33 | 33 | 0 | - |
| 9 | Os léxicos possuem Noção? | 33  | 33 | 0 | - |
| 10 | A Noção de cada léxico permite identificar os símbolos? | 33  | 33 | 0 | - |
| 11 | Os símbolos estão classificados corretamente? |  33 | 33 | 0 | - |
| 12 | Os léxicos possuem sinônimos? | 33  | 32 | 1 | Pode adicionar como [assinatura de benefícios](https://requisitos-de-software.github.io/2023.1-Twitch/modelagem/lexico/#l19-prime-gaming)|
| 13 | Os sinônimos estão compatíveis? | 32  | 30 | 2 | Diferenciar o sinônimo do [L18](https://requisitos-de-software.github.io/2023.1-Twitch/modelagem/lexico/#l18-drops) ao [L20](https://requisitos-de-software.github.io/2023.1-Twitch/modelagem/lexico/#l20-loots), visto que o primeiro é relacionado a "derramar" e o segundo a "coletar". |




</center>

<h6 align="center">Tabela 2: Verificação do artefato sobre Léxicos </h6>
<h6 align="center">Fonte: Autor, 2023</h6>

### 3.3 Resultados

Nas figuras 1 e 2 abaixo, se encontram as representações gráficas referentes ao grau de satisfação e da ocorrência de erros do artefato. Estes dados foram recolhidos a partir da verificação de conteúdo do artefato.

## 4 Justificativas

### 4.1 Léxico

"O léxico representa o conhecimento compartilhado, diminuindo dificuldades de entendimento em relação a termos próprios do domínio da aplicação."[1]

### 4.2 Estrutura de dicionário

Sobre a estrutura de dicionário[1]:

    Sujeitos correspondem a entidades ativas, atores com papel relevante para a
    aplicação; um sujeito pode ser um ator, um componente ou um outro sistema com o
    qual deverá ocorrer interação. Verbos registram ações ou funcionalidades a serem
    desempenhadas pelos sujeitos ou pelo sistema em desenvolvimento, com algum
    impacto ou reflexo no ambiente operacional. Objetos são entidades passivas utilizadas ou necessárias a uma ação ou conjunto de ações, e estados são caracterizados por atributos significativos que registram valores em diferentes momentos da execução do sistema.
    
### 4.3 Classificação ou Símbolos

No projeto foi utilizado o termo Classificação, mas que apresenta as mesmas características de um Símbolo, em que "símbolos característicos do domínio da aplicação, e correspondem a um e quatro tipos: sujeito, objeto, verbo ou estado"[1].
    
### 4.4 Impacto

Impactos estão atrelados a cada símbolo e variam ao desenvolver-se de um. Podem representar ações que o sujeito executa, quais os reflexos das ações de um verbo, pode transmitir ações aplicadas ao objeto e identificar outros estados que podem ocorrer a partir do estado em questão.[1]

### 4.5 Noção 

"A noção de um símbolo é o que o define"[1]. Assim, ela caracteriza o sujeito, verbo, objeto ou estado.


## 5. Referências Bibliográficas

> [1] CONSTRUÇÃO do léxico de aplicações. Proceedings of the International Joint Conference IBERAMIA/SBIA/SBRN 2006 : 4th Workshop in Information and Human Language Technology, Ribeirão Preto, Brazil, 23 out. 2006. CD-ROM. Disponível em: http://www.nilc.icmc.usp.br/til/til2006/0030.pdf. Acesso em: 4 de junho de 2023.

> [2] Repositório Twitch do semestre 2023.1, acesso em: 4 de junho de 2023. Para mais informações acesse: <https://requisitos-de-software.github.io/2023.1-Twitch/modelagem/lexico/>

> [3] Twitch, acesso em: 13 de junho de 2023. Para mais informações acesse: <https://www.twitch.tv/>

## 5. Histórico de versão

| Versão | Data     | Descrição                                        | Autor(es)   | Revisor(es)   |
| ------ | -------- | ------------------------------------------------ | ----------- | ------------- |
| `1.0`  | 13/06/23 | Criação do artefato de verificação sobre léxicos | Magno Luiz | Samuel Sato |