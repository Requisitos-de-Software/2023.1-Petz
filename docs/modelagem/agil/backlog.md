# Backlog do Produto

## 1. Introdução

O Product Backlog é uma lista contendo todas as funcionalidades desejadas para um produto [1]. Prioriza os requisitos do projeto que possuem valor comercial para o cliente [2]. Os itens podem ser adicionado a qualquer momento no projeto.

Backlog DEEP é uma técnica que auxilia a criação e ordenação do backlog. Deep é um acronimo de: 

    - Detailed (Detalhado): Os itens devem ser detalhados.
    - Estimated (Estimado): OS itens devem ser possuir estimativa pontual associada.
    - Emergent (Emergente): Backlog não deve ser imutável, deve ser priorizado e reordenado para refletir atualizações do projeto.
    - Prioritized (Priorizado): Os itens devem ser priorizados a fim de evidenciar itens com maior valor comercial

## 2. Metodologia

A elaboração do backlog do produto partiu da análise e verificação dos requisitos funcionais elicitados, levando e consideração os resultados das técnicas de priorização adotadas. Serão criados itens de forma detalhada, priorizado e emergente, possibilitam a repriorizar e reordenação, com base no Backlog DEEP.

Os itens foram agrupados em tema e épicos:

- Tema: Conjuntos de Épicos que constituem o escopo geral da aplicação Petz.
- Épicos: Conjunto de Histórias de Usuário que façam parte de um mesmo contexto.

## 3. Backlog

### 3.1 Temas

Os épicos estão divididos em dois temas: 

- Venda
- Configuração e Cadastro


### 3.2 Épicos
<div id="EP01"></div>

### Épico 1 - Cadastro e autenticação 
|Feature|História de usuário | Prioridade | Rastreabilidade |
|-------|--------------------|------------|-----------------|
|Cadastro de usuário|US01 - Eu como potencial usuário, gostaria de me cadastrar no aplicativo, para que possa usufruir dos serviços oferecidos.| Alta |[RF01](../../elicitacao/resultadoElicitacao.md#RF01) |
|Login de usuário|US02 - Eu como usuário cadastrado, gostaria de fazer login no aplicativo, para que possa acessar seus serviços.| Alta | [RF02](../../elicitacao/resultadoElicitacao.md#RF02)|
|Cadastro de pet|  	US03 - 	Eu como usuário autenticado, gostaria de cadastrar um novo pet no aplicativo, para que possa solicitar serviços para ele.| Média | [RF15](../../elicitacao/resultadoElicitacao.md#RF15), [RF29](../../elicitacao/resultadoElicitacao.md#RF29)|

<h6 align = "center"> Tabela 1: Épico 1 - Cadastro e autenticação </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

<div id="EP02"></div>

### Épico 2 - Processo de realização de pedidos

|Feature|História de usuário | Prioridade | Rastreabilidade |
|-------|--------------------|------------|-----------------|
|Realizar pedido|US04 - Eu como usuário autenticado, gostaria de realizar uma nova compra de produtos pelo aplicativo, para que possa suprir as necessidades dos meus pets.| Alta | [RF13](../../elicitacao/resultadoElicitacao.md#RF13), [RF14](../../elicitacao/resultadoElicitacao.md#RF14) |
| Cancelar um pedido|US05 -  Eu como usuário autenticado, gostaria de cancelar uma compra prévia, para que possa evitar uma devolução futura.| Alta | [RF22](../../elicitacao/resultadoElicitacao.md#RF22) |
|Acompanhar e alterar pedidos| US08 - Eu como usuário autenticado, gostaria de acompanhar e alterar compras em andamento, para que possa realizar mudanças de forma simples. | Alta | [RF11](../../elicitacao/resultadoElicitacao.md#RF11), [RF12](../../elicitacao/resultadoElicitacao.md#RF12), [RF23](../../elicitacao/resultadoElicitacao.md#RF23), [RF35](../../elicitacao/resultadoElicitacao.md#RF35) |
|Repetir um pedido|US06 - Eu como usuário autenticado, gostaria de repetir uma compra prévia, para que possa economizar tempo em compras frequentes. | Média | [RF06](../../elicitacao/resultadoElicitacao.md#RF06) |
|Realizar um pedido periódico|US07 - Eu como usuário autenticado, gostaria de configurar a compra automática de um pedido periódicamente, para que possa economizar tempo.| Baixa | [RF20](../../elicitacao/resultadoElicitacao.md#RF20), [RF24](../../elicitacao/resultadoElicitacao.md#RF24), [RF33](../../elicitacao/resultadoElicitacao.md#RF33), [RF42](../../elicitacao/resultadoElicitacao.md#RF42)|

<h6 align = "center"> Tabela 2: Épico 2 - Processo de realização de pedidos </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

<div id="EP03"></div>

### Épico 3 - Serviços para o _pet_

|Feature|História de usuário | Prioridade | Rastreabilidade |
|-------|--------------------|------------|-----------------|
|Solicitar serviço de banho e tosa|US09 - Eu como usuário autenticado, gostaria acompnahar e marcar serviços de banho e tosa para meu _pet_, para que possa economizar tempo. | Alta | [RF19](../../elicitacao/resultadoElicitacao.md#RF19)|
|Solicitar serviço de veterinária | US10 - Eu como usuário autenticado, gostaria de acompanhar e marcar consultas veterinárias para meu _pet_., para que possa economizar tempo. | Média | [RF38](../../elicitacao/resultadoElicitacao.md#RF38), [RF41](../../elicitacao/resultadoElicitacao.md#RF41) |
|Solicitar serviço de hotelaria para animais|US11 - Eu como usuário autenticado, gostaria de acompanhar e realizar reservas de hospedagem para meu _pet_. para que possa economizar tempo. | Baixa |[RF43](../../elicitacao/resultadoElicitacao.md#RF43)|
|Solicitar serviço de transporte para animais |US12 - Eu como usuário autenticado, gostaria de acompanhar e solicitar o transporte do meu _pet_ até o estabelecimento físico, para que possa economizar tempo.  |Baixa|[RF37](../../elicitacao/resultadoElicitacao.md#RF37)|

<h6 align = "center"> Tabela 3: Épico 3 - Serviços para o pet </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

<div id="EP04"></div>

### Épico 4 - Catalogação de produtos
|Feature|História de usuário | Prioridade | Rastreabilidade |
|-------|--------------------|------------|-----------------|
|Visualizar catálogo|US13 - Eu como usuário, gostaria de visualizar o catálogo de produtos oferecidos, para que possa verificar se o produto que desejo é oferecido.| Alta |[RF03](../../elicitacao/resultadoElicitacao.md#RF03), [RF04](../../elicitacao/resultadoElicitacao.md#RF04)|
|Filtrar catálogo |US14 - Eu como usuário, gostaria de filtrar os produtos oferecidos, para que possa encontrar o produto desejado rapidamente.|Alta|[RF17](../../elicitacao/resultadoElicitacao.md#RF17), [RF28](../../elicitacao/resultadoElicitacao.md#RF28), [RF31](../../elicitacao/resultadoElicitacao.md#RF31)|
|Pesquisar produto|US15 - Eu como usuário, gostaria de pesquisar um produto específico, para que possa encontrar o produto desejado rapidamente. |Alta|[RF07](../../elicitacao/resultadoElicitacao.md#RF07), [RF08](../../elicitacao/resultadoElicitacao.md#RF08)|
|Visualizar produto|US16 - Eu como usuário, gostaria de visualizar os detalhes de um produto oferecido, para que possa verificar se necessito do mesmo.|Alta|[RF04](../../elicitacao/resultadoElicitacao.md#RF04), [RF09](../../elicitacao/resultadoElicitacao.md#RF09), [RF18](../../elicitacao/resultadoElicitacao.md#RF18), [R25](../../elicitacao/resultadoElicitacao.md#RF25)|
|Sugestão de produtos|US17 - Eu como usuário autenticado, gostaria de receber sugestões de produtos, para que possa encontrar produtos desejados rapidamente. |Média|[RF32](../../elicitacao/resultadoElicitacao.md#RF32)|

<h6 align = "center"> Tabela 4: Épico 4 - Catalogação de produtos </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

<div id="EP05"></div>

### Épico 5 - Informação e configuração de conta
|Feature|História de usuário | Prioridade | Rastreabilidade |
|-------|--------------------|------------|-----------------|
|Recuperar conta|US18 - Eu como usuário cadastrado, gostaria de recuperar minha conta através do email cadastrado, para que recupere meu acesso ao aplicativo.|Alta|[RF21](../../elicitacao/resultadoElicitacao.md#RF21)|
|Reportar erros|US19 - Eu como usuário, gostaria de reportar falhas do aplicativo, para que o mesmo possa ser melhorado.|Média | [RF30](../../elicitacao/resultadoElicitacao.md#RF30)|
|Obter informações sobre animais|US20 - Eu como usuário, gostaria de receber informações acerca de animais de estimação, para que possa obter maior conhecimento. |Baixa|[RF34](../../elicitacao/resultadoElicitacao.md#RF34), [RF36](../../elicitacao/resultadoElicitacao.md#RF36), [RF39](../../elicitacao/resultadoElicitacao.md#RF39), [RF40](../../elicitacao/resultadoElicitacao.md#RF40)|

<h6 align = "center"> Tabela 5: Épico 5 - Informação e configuração de conta </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

### Backlog do produto priorizado

A tabela 6 apresenta o Backlog do produto completo e priorizado conforme o resultado da priorização.

| Tema | Épico |Feature|História de usuário | Prioridade | Rastreabilidade |
|------|-------|-------|--------------------|------------|-----------------|
| Configuração e Cadastro | Épico 1 - Cadastro e autenticação |Cadastro de usuário|US01 - Eu como potencial usuário, gostaria de me cadastrar no aplicativo, para que possa usufruir dos serviços oferecidos.| Alta |[RF01](../../elicitacao/resultadoElicitacao.md#RF01) |
| Configuração e Cadastro | Épico 1 - Cadastro e autenticação |Login de usuário|US02 - Eu como usuário cadastrado, gostaria de fazer login no aplicativo, para que possa acessar seus serviços.| Alta | [RF02](../../elicitacao/resultadoElicitacao.md#RF02)|
| Configuração e Cadastro | Épico 1 - Cadastro e autenticação |Cadastro de pet|  	US03 - 	Eu como usuário autenticado, gostaria de cadastrar um novo pet no aplicativo, para que possa solicitar serviços para ele.| Média | [RF15](../../elicitacao/resultadoElicitacao.md#RF15), [RF29](../../elicitacao/resultadoElicitacao.md#RF29)|
| Venda | Épico 2 - Processo de realização de pedidos | Realizar pedido|US04 - Eu como usuário autenticado, gostaria de realizar uma nova compra de produtos pelo aplicativo, para que possa suprir as necessidades dos meus pets.| Alta | [RF13](../../elicitacao/resultadoElicitacao.md#RF13), [RF14](../../elicitacao/resultadoElicitacao.md#RF14) |
| Venda | Épico 2 - Processo de realização de pedidos| Cancelar um pedido |US05 -  Eu como usuário autenticado, gostaria de cancelar uma compra prévia, para que possa evitar uma devolução futura.| Alta | [RF22](../../elicitacao/resultadoElicitacao.md#RF22) |
| Venda | Épico 2 - Processo de realização de pedidos | Acompanhar e alterar pedidos| US08 - Eu como usuário autenticado, gostaria de acompanhar e alterar compras em andamento, para que possa realizar mudanças de forma simples. | Alta | [RF11](../../elicitacao/resultadoElicitacao.md#RF11), [RF12](../../elicitacao/resultadoElicitacao.md#RF12), [RF23](../../elicitacao/resultadoElicitacao.md#RF23), [RF35](../../elicitacao/resultadoElicitacao.md#RF35) |
| Venda | Épico 2 - Processo de realização de pedidos | Repetir um pedido|US06 - Eu como usuário autenticado, gostaria de repetir uma compra prévia, para que possa economizar tempo em compras frequentes. | Média | [RF06](../../elicitacao/resultadoElicitacao.md#RF06) |
| Venda | Épico 2 - Processo de realização de pedidos | Realizar um pedido periódico|US07 - Eu como usuário autenticado, gostaria de configurar a compra automática de um pedido periódicamente, para que possa economizar tempo.| Baixa | [RF20](../../elicitacao/resultadoElicitacao.md#RF20), [RF24](../../elicitacao/resultadoElicitacao.md#RF24), [RF33](../../elicitacao/resultadoElicitacao.md#RF33), [RF42](../../elicitacao/resultadoElicitacao.md#RF42)|
| Venda | Épico 3 - Serviços para o _pet_|Solicitar serviço de banho e tosa|US09 - Eu como usuário autenticado, gostaria acompnahar e marcar serviços de banho e tosa para meu _pet_, para que possa economizar tempo. | Alta | [RF19](../../elicitacao/resultadoElicitacao.md#RF19)|
| Venda | Épico 3 - Serviços para o _pet_|Solicitar serviço de veterinária | US10 - Eu como usuário autenticado, gostaria de acompanhar e marcar consultas veterinárias para meu _pet_., para que possa economizar tempo. | Média | [RF38](../../elicitacao/resultadoElicitacao.md#RF38), [RF41](../../elicitacao/resultadoElicitacao.md#RF41) |
| Venda | Épico 3 - Serviços para o _pet_|Solicitar serviço de hotelaria para animais|US11 - Eu como usuário autenticado, gostaria de acompanhar e realizar reservas de hospedagem para meu _pet_. para que possa economizar tempo. | Baixa |[RF43](../../elicitacao/resultadoElicitacao.md#RF43)|
| Venda | Épico 3 - Serviços para o _pet_|Solicitar serviço de transporte para animais |US12 - Eu como usuário autenticado, gostaria de acompanhar e solicitar o transporte do meu _pet_ até o estabelecimento físico, para que possa economizar tempo.  |Baixa|[RF37](../../elicitacao/resultadoElicitacao.md#RF37)|
| Venda | Épico 4 - Catalogação de produtos |Visualizar catálogo|US13 - Eu como usuário, gostaria de visualizar o catálogo de produtos oferecidos, para que possa verificar se o produto que desejo é oferecido.| Alta |[RF03](../../elicitacao/resultadoElicitacao.md#RF03), [RF04](../../elicitacao/resultadoElicitacao.md#RF04)|
| Venda | Épico 4 - Catalogação de produtos |Filtrar catálogo |US14 - Eu como usuário, gostaria de filtrar os produtos oferecidos, para que possa encontrar o produto desejado rapidamente.|Alta|[RF17](../../elicitacao/resultadoElicitacao.md#RF17), [RF28](../../elicitacao/resultadoElicitacao.md#RF28), [RF31](../../elicitacao/resultadoElicitacao.md#RF31)|
| Venda | Épico 4 - Catalogação de produtos |esquisar produto|US15 - Eu como usuário, gostaria de pesquisar um produto específico, para que possa encontrar o produto desejado rapidamente. |Alta|[RF07](../../elicitacao/resultadoElicitacao.md#RF07), [RF08](../../elicitacao/resultadoElicitacao.md#RF08)|
| Venda | Épico 4 - Catalogação de produtos |Visualizar produto|US16 - Eu como usuário, gostaria de visualizar os detalhes de um produto oferecido, para que possa verificar se necessito do mesmo.|Alta|[RF04](../../elicitacao/resultadoElicitacao.md#RF04), [RF09](../../elicitacao/resultadoElicitacao.md#RF09), [RF18](../../elicitacao/resultadoElicitacao.md#RF18), [R25](../../elicitacao/resultadoElicitacao.md#RF25)|
| Venda | Épico 4 - Catalogação de produtos |Sugestão de produtos|US17 - Eu como usuário autenticado, gostaria de receber sugestões de produtos, para que possa encontrar produtos desejados rapidamente. |Média|[RF32](../../elicitacao/resultadoElicitacao.md#RF32)|
|Configuração e Cadastro|Épico 5 - Informação e configuração de conta|Recuperar conta|US18 - Eu como usuário cadastrado, gostaria de recuperar minha conta através do email cadastrado, para que recupere meu acesso ao aplicativo.|Alta|[RF21](../../elicitacao/resultadoElicitacao.md#RF21)|
|Configuração e Cadastro|Épico 5 - Informação e configuração de conta|Reportar erros|US19 - Eu como usuário, gostaria de reportar falhas do aplicativo, para que o mesmo possa ser melhorado.|Média | [RF30](../../elicitacao/resultadoElicitacao.md#RF30)|
|Configuração e Cadastro|Épico 5 - Informação e configuração de conta|Obter informações sobre animais|US20 - Eu como usuário, gostaria de receber informações acerca de animais de estimação, para que possa obter maior conhecimento. |Baixa|[RF34](../../elicitacao/resultadoElicitacao.md#RF34), [RF36](../../elicitacao/resultadoElicitacao.md#RF36), [RF39](../../elicitacao/resultadoElicitacao.md#RF39), [RF40](../../elicitacao/resultadoElicitacao.md#RF40)|


<h6 align = "center"> Tabela 6: Product Becklog </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>



## 4. Referências Bibliográficas

> [1] SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 15.

> [2] MAXIM, Bruce; PRESSMAN, Roger; Engenharia de Software: Uma abordagem profissional.

## 5. Histórico de versão

| Versão | Data     | Descrição                                  | Autor(es)     | Revisor(es)   |
| ------ | -------- | ------------------------------------------ | ------------- | ------------- |
| `1.0`  | 20/05/23 | Criação inicial do Backlog | Samuel Sato | Felipe Corrêa |
| `1.1`  | 24/05/23 | Adição de épicos e construção do backlog | Magno Luiz | Felipe Corrêa |
| `1.2` | 03/07/2023 | Adicionar temas ao Backlog, e tabela geral de backlog| Samuel Sato | Felipe Corrêa |