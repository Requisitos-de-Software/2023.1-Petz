## 1 - Introdução

Este artefato tem como objetivo verificar a composição do documento de Cenários do Grupo 8 que está analisando a Twitch. Com base nisso o objetivo é buscar possíveis erros conceituais e estruturais que possam ter passado despercebidos durante a etapa de desenvolvimento do documento.

## 2 - Metodologia

Como especificado no [planejamento da verificação](../planejamento.md) o método de verificação utilizado será a inspeção, assim produzindo checklists para analisar o conteúdo e a estrutura do documento. A versão do artefato que está sendo verificada é a `1.2` .

## 3 - Checklist

A seguir são apresentadas as perguntas do checklist e suas respectivas definições nas quais foram embasadas, e suas referências.

* 1 - **Possui os elementos básicos de um cenário (Titulo, Objetivo, Contexto, Recurso, Ator, Episódio, Exceção)?**

Esta notação (texto estruturado) utiliza uma linguagem natural semi-estruturada (ancorada no mundo real), partindo da premissa que a utilização da linguagem da aplicação e não do software facilita o entendimento e a validação dos requisitos por parte dos clientes. A notação para cenários é composta pelos seguintes elementos. Titulo, objetivo, contexto, recurso, episódio (pode conter restrições exceções).

`
Leite, J.C.S.P; Bergmann, Ulf (2003). Evolução de Cenários através de um Mecanismo de Rastreamento Baseado 
em Transformações - 3 Cenários. PUC - Rio.
`
* 2 - **Há conexão com os Léxicos produzidos?**

Um importante complemento para a descrição dos cenários é o Léxico Ampliado da Linguagem (LAL), um metamodelo projetado para ajudar a capturar a linguagem utilizada no domínio. 

`
Leite, J.C.S.P; Bergmann, Ulf (2003). Evolução de Cenários através de um Mecanismo de Rastreamento Baseado 
em Transformações - 3 Cenários. PUC - Rio.
`

* 3 - **Os cenários possuem identificação única?**

Título (title): identifica o cenário.

`
Leite, J.C.S.P; Bergmann, Ulf (2003). Evolução de Cenários através de um Mecanismo de Rastreamento Baseado 
em Transformações - 3 Cenários. PUC - Rio.
`
* 4 - **Os Objetivos estabelecem a finalidade do cenário?**

Objetivo (goal): estabelece a finalidade de um cenário. O cenário deve descrever de que modo este objetivo deve ser alcançado. 

`
Leite, J.C.S.P; Bergmann, Ulf (2003). Evolução de Cenários através de um Mecanismo de Rastreamento Baseado 
em Transformações - 3 Cenários. PUC - Rio.
`

* 5 - **Os contextos descrevem os estados iniciais dos cenários?**

Contexto (context): descreve o estado inicial de um cenário, suas pré-condições, o local (físico) e tempo. Na sua definição podem ser especificadas restrições sobre estes elementos (constraint). 

`
Leite, J.C.S.P; Bergmann, Ulf (2003). Evolução de Cenários através de um Mecanismo de Rastreamento Baseado 
em Transformações - 3 Cenários. PUC - Rio.
`

* 6 - **Os recursos identificam os objetos com os quais os atores lidam?**

Recurso (resource): identifica os objetos passivos com os quais lidam os atores. Na sua definição podem ser especificadas restrições sobre os objetos a serem lidados pelo cenário (constraint).

`
Leite, J.C.S.P; Bergmann, Ulf (2003). Evolução de Cenários através de um Mecanismo de Rastreamento Baseado 
em Transformações - 3 Cenários. PUC - Rio.
`

* 7 - **Os atores representam uma pessoa ou organização?**

Ator (actor): Pessoa ou estrutura organizacional que tem um papel no cenário. 

`
Leite, J.C.S.P; Bergmann, Ulf (2003). Evolução de Cenários através de um Mecanismo de Rastreamento Baseado 
em Transformações - 3 Cenários. PUC - Rio.
`

* 8 - **Os episódios representam as ações realizadas pelo ator com os recursos disponíveis?**

Episódio (episode): Cada episódio representa uma ação realizada por um ator onde participam outros atores utilizando recursos disponíveis. Um episódio também pode se referir a outro cenário.

`
Leite, J.C.S.P; Bergmann, Ulf (2003). Evolução de Cenários através de um Mecanismo de Rastreamento Baseado 
em Transformações - 3 Cenários. PUC - Rio.
`

* 9 - **As restrições ou exceções se referem ao episódio?**

Episódios podem conter restrições (constraint) e exceções (exception). Uma restrição é qualquer imposição que restrinja um episódio de um cenário. Uma exceção é o tratamento para uma situação excepcional ou de erro. 

`
Leite, J.C.S.P; Bergmann, Ulf (2003). Evolução de Cenários através de um Mecanismo de Rastreamento Baseado 
em Transformações - 3 Cenários. PUC - Rio.
`

<center>

|Item | Descrição| Avaliação |
|--|--|--|
| 1 | Possui os elementos básicos de um cenário (Titulo, Objetivo, Contexto, Recurso, Ator, Episódio, Exceção)? | ✅ |
| 2 | Há conexão com os Léxicos produzidos? | ❌ |
| 3 | Os cenários possuem identificação única? | ✅|
| 4 | Os Objetivos estabelecem a finalidade do cenário? |✅ |
| 5 | Os contextos descrevem os estados iniciais dos cenários? |✅ |
| 6 | Os recursos identificam os objetos com os quais os atores lidam?  |✅ |
| 7 | Os atores representam uma pessoa ou organização? |✅ |
| 8 | Os episódios representam as ações realizadas pelo ator com os recursos disponíveis? | ✅|
| 9 | As restrições ou exceções se referem ao episódio? | ✅|

</center>

<h6 align="center">Tabela 1: Checklist do conteúdo</h6>
<h6 align="center">Fonte: Autor, 2023</h6>

<center>

| ID  | Verificação  | Realizado | Possíveis correções |
| :-: | --------------------------------------------------------- | --------- | ------------------- |
|  1  | Possui ortografia correta e formal?                                  |    ✅     | -                   |
|  2  | Possui introdução?                                                   | ✅         | -                   |
|  3  | Possui links necessários?                                            |       ❌   | Adicionar link com os léxicos                   |
|  4  | As tabelas e imagens possuem legenda padronizada e chamada no texto? | ✅         | -                   |
|  5  | As tabelas e imagens estão totalmente em português?                  | ✅         | -                   |
|  6  | Possui bibliografia?                                                 | ✅         | -                   |
|  7  | Possui histórico de versão padronizado?                              | ✅         | -                   |
|  8  | O histórico de versão possui autor(es) e revisor(es)?                | ✅         | -                   |

</center>

<h6 align="center">Tabela 2: checklist para padronização</h6>
<h6 align="center">Fonte: Autor, 2023</h6>

## Conclusões

A verificação conclui que foi feito um trabalho que atende as definições conceituais de um cenário. Porém existem alguns pontos que podem ser ajustados, como por exemplo a ligação entre os léxicos e cenários. Um exemplo é C04: Mandar sussuro, "sussuro" é apresentado dentro dos léxicos como "whisper", sendo assim essa ligação pode ser realizada e também é necessário definir um padrão para utilizar esse léxico, sendo "sussuro" ou "whisper" para evitar conflitos. "Usuário" também poderia estar ligado aos léxicos.

## 5. Referências Bibliográficas

> [1] Leite, J.C.S.P; Bergmann, Ulf (2003). Evolução de Cenários através de um Mecanismo de Rastreamento Baseado em Transformações - 3 Cenários. PUC - Rio.



## Histórico de versão

|  Versão  |   Data   |                      Descrição                      |    Autor(es)   |  Revisor(es)  |
| -------- | -------- | --------------------------------------------------- | -------------- | ------------- |
|  `1.0`   | 10/06/23 | Criação da primeira versão do artefato de verificação de cenários | Vitor Manoel  | Samuel Sato |
