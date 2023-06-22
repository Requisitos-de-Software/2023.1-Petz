# Verificação - Priorização baseada em valor, custo e risco.

## 1. Introdução

Este artefato contém os checklists de verificação relacionados ao artefato de [priorização baseada em valor, custo e risco](./../elicitacao/custoxbeneficio.md) que, na data da redação deste documento, estava na versão `1.0` de 01/05/2023.

## 2. Metodologia

As verificações a seguir seguem a metodologia proposta no [planejamento](../planejamento.md)[1], onde serão utilizados _[checklists](../../planejamento/glossario.md#Checklist)_ para a verificação dos conteúdos presentes no artefato, buscando encontrar erros e elementos faltantes no mesmo.

As verificações a respeito desta técnica de priorização basearam-se na bibliografia disponível sobre o assunto.

### 2.1 Verificação 1 - O artefato seleciona os requisitos anteriormente a fim de não inserir o núcleo do funcionamento do sistema na matriz?

É necessária uma separação prévia dos requisitos a fim de não inserir o núcleo do sistema na matriz de prriorização ou requisitos obrigatórios por lei, a fim de evitar redundâncias (se o núcleo do sistema estiver na priorização, certamente terá alta prioridade).

`WIEGERS, Karl; JOY, Beatty. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013.`

### 2.2 Verificação 2 - Há registro dos participantes desta priorização?

Por ser uma técnica de priorização de requisitos, é necessário que esta técnica tenha um registro dos participantes da mesma a fim de espacializar e creditar os participantes.

`Elaboração própria`

### 2.3 Verificação 3 - São usados somente itens em um mesmo nível de abstração? (isto é, somente requisitos funcionais ou somente features ou somente casos de uso)?

É necessário que, para a consistência da matriz seja mantida, somente itens de uma mesma natureza sejam nela inseridas.

`WIEGERS, Karl; JOY, Beatty. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013.`

### 2.4 Verificação 4 - A priorização utiliza a matriz de priorização definida para a técnica? 

É definida, na literatura, uma matriz de priorização específica para o registro dos valores encontrados e para o eventual cálculo da prioridade de cada elemento.

`WIEGERS, Karl; JOY, Beatty. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013.`

### 2.5 Verificação 5 - A fórmula de cálculo de prioridade é explanada no artefato?

Para a obtenção numérica da prioridade, um cálculo deve ser realizado a partir dos valores intermediários obtidos com a matriz. Dessa forma, esta fórmula deve ser exposta.

`Elaboração própria`

### 2.6 Verificação 6 - Os valores intermediários são escondidos para melhor visualização dos requisitos em ordem de prioridade?

Os valores intermediários como "Valor %", "Custo %" "Risco %" são importantes para a execução da priorização mas não são importantes para as partes interessadas após a mesma. Dessa forma, para maior claridade de informação, esses dados devem ser omitidos nos resultados finais.

`WIEGERS, Karl; JOY, Beatty. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013.`

### 2.7 Verificação 7 - Os pesos da fórmula do cálculo de prioridade são explicitados no artefato?

A fórmula do cálculo de prioridade pode ser alterada de acordo com as necessidades das partes interessadas com a adição de pesos ao valor, ao custo ou ao risco que cada item possui. Dessa forma, esses pesos devem estar explícitos no artefato.

`WIEGERS, Karl; JOY, Beatty. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013.`

## 3. Desenvolvimento

### 3.1 Padronização 

Na tabela 1, se encontra o _checklist_ de padronização preenchido após a realização da verificação.

| ID| Verificação | Realizado |
|--|--|--|
| 1 | Possui ortografia correta e formal? | Incompleto |
| 2 | Possui introdução? | Sim |
| 3 | Possui links necessários? | Sim |
| 4 | As tabelas e imagens possuem legenda padronizada e chamada no texto? | Sim |
| 5 | As tabelas e imagens estão totalmente em português? | Sim |
| 6 | Possui bibliografia? | Sim |
| 7 | A bibliografia está em ordem alfabética? | Sim |
| 8 | Possui histórico de versão padronizado? | Sim |
| 9 | O histórico de versão possui autor(es) e revisor(es)? | Sim |

<h6 align = "center"> Tabela 1: Verificações de padronização do artefato</h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

### 3.2 Conteúdo

Na tabela 2, se encontra o _checklist_ de conteúdo preenchido após a realização da verificação.

| ID | Verificação | Ocorrências | Acertos | Erros |
|--|--|--|--|--|
| 1 | O artefato seleciona os requisitos anteriormente a fim de não inserir o núcleo do funcionamento do sistema na matriz? | 1 | 0 | 1 |
| 2 | Há registro dos participantes desta priorização? | 1 | 0 | 1 |
| 3 | São usados somente itens em um mesmo nível de abstração? (isto é, somente requisitos funcionais ou somente features ou somente casos de uso?) | 1 | 0 | 1 |
| 4 | A priorização utiliza a matriz de priorização definida para a técnica? | 1 | 1 | 0 |
| 5 | A fórmula de cálculo de prioridade é explanada no artefato? | 1 | 0 | 1 |
| 6 | Os valores intermediários são escondidos para melhor visualização dos requisitos em ordem de prioridade? | 1 | 0 | 1 |
| 7 | Os pesos da fórmula do cálculo de prioridade são explicitados no artefato? | 1 | 0 | 1 |

<h6 align = "center"> Tabela 2: Verificações de conteúdo do artefato</h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

## 4. Problemas encontrados - Padronização

### 4.1 Verificação - Possui ortografia correta e formal?

Na tabela importada via Google Sheets, notam-se erros de ortografia (ex.: custo 1, onde deveria ser custo %).

## 5. Problemas encontrados - Conteúdo

### 5.1 Verificação 1 - O artefato seleciona os requisitos anteriormente a fim de não inserir o núcleo do funcionamento do sistema na matriz? 

Todos os requisitos são priorizados nesta técnica, o que significa que o núcleo do sistema possui alta prioridade.

### 5.2 Verificação 2 - Há registro dos participantes desta priorização?

Além do histórico de versão, não são registrados os participantes desta priorização no artefato.

### 5.3 Verificação 3 - São usados somente itens em um mesmo nível de abstração? (isto é, somente requisitos funcionais ou somente features ou somente casos de uso?)

Não são separados itens de níveis diferentes de abstração para  a realização da priorização.

### 5.4 Verificação 5 - A fórmula de cálculo de prioridade é explanada no artefato?

A fórmula do cálculo da prioridade não é explicada no artefato.

### 5.5 Verificação 6 -  Os valores intermediários são escondidos para melhor visualização dos requisitos em ordem de prioridade?

Na tabela final do artefato, os valores intermediáris são mostrados.

### 5.6 Verificação 7 - Os pesos da fórmula do cálculo de prioridade são explicitados no artefato?

Em nenhum momento no artefato os pesos da fórmula são explicitados.

## 6. Resultados

Os resultados da verificação do artefato de casos de uso podem ser encontrados na tabela 3 abaixo, por meio das figuras 1 e 2, onde podem ser verificados o grau de satisfação e a ocorrência de erros no artefato verificado. Estes resultados levam em conta apenas a verificação do conteúdo.

<center>

| ![Representação do grau de satisfação no artefato](../assets/analise/prioValorCustoRisco/grafico%20prio.png)               | ![Gráfico de ocorrência de erros no artefato](../assets/analise/prioValorCustoRisco/grafico%20erros%20prio.png)                 |
| ----------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| <h6 align="center">Figura 2: Representação do grau de satisfação no artefato<br>Fonte: Autor, 2023</h6> | <h6 align="center">Figura 3: Gráfico de ocorrência de erros no artefato<br>Fonte: Autor, 2023</h6> |

</center>

<h6 align = "center"> Tabela 3: Representações gráficas dos resultados da verificação</h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

## 7. Acompanhamento

Como não houveram correções de conteúdo, o grau de satisfação e a ocorrência de erros no artefato se mantiveram inalterados.

## 8. Referências Bibliográficas

> [1]  WIEGERS, Karl; JOY, Beatty. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013. Disponível em: https://www.dirzon.com/file/telegram/HiLCoE%20-%20DRB1802/Microsoft%20Press%20Software%20Requirements%203%203rd%20Edition%20Aug%202013.pdf. Acesso em: 20 jun. 2023.

## 9. Histórico de versão 

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|--|--|--|--|--|
| `1.0` | 21/06/23 | Criação do documento e adição do conteúdo | Felipe Corrêa | Pedro Muniz |