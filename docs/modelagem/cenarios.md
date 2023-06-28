# Cenários

## 1. Introdução
Um cenário é uma narrativa, textual ou pictórica, concreta, rica em detalhes contextuais, de uma situação de uso da aplicação, envolvendo usuários, processos e dados reais ou potenciais[1]. Ou seja, um cenário representa um contexto real de utilização do sistema e descreve narrativamente os compoenentes e ações que pertencem a este contexto. Neste documento, são apresentados os cenários formulados para o projeto.

## 2. Metodologia
Para a modelagem dos requisitos elicitados em cenários, foi utilizado o modelo apresentado por Milene Serrano[2], onde são apresentados 7 elementos para a criação de cenários:

* Título.
* Metas/Objetivos.
* Contexto.
* Ator(es).
* Recursos.
* Restrição.
* Exceção.
* Episódios.

Para a representação destes elementos, cada cenário apresentado seguirá a estrutura da tabela apresentada abaixo.

| Elemento | Informações |
| -------- | ----------- |
| Título   | Nome descritivo do cenário |
| Objetivos | Metas que os participantes do cenário busca alcançar |
| Contexto | - **Local:** Local onde ocorre o cenário<br>- **Tempo:** Tempo de duração do cenário<br> - **Pré-condição:** Condições anteriores ao cenário |
| Ator | Participantes do cenário |
| Recursos | Recursos disponíveis aos participantes |
| Restrição | Condições necessárias para que o cenário ocorra |
| Episódios | Decorrer do cenário |
| Exceção | Condições inesperadas que podem interromper o cenário |
| Rastreabilidade | Requisitos referentes ao cenário |

<h6 align = "center"> Tabela 1: Estrutura para modelagem dos cenários </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

## 3. Cenários já implementados

Abaixo estão descritos os cenário cujas funcionalidades já se encontravam em funcionamento no aplicativo analisado, isso durante o período de desenvolvimento do projeto.

<div id="C01"></div>

### 3.1 C01 - Realizar uma compra no aplicativo

| Elemento | Informações |
|--|--|
| Título | Realizar uma compra no aplicativo |
| Objetivos | Utilizar o aplicativo para comprar um produto para seu animal |
| Contexto | **Local:** Tela inicial do aplicativo<br>**Tempo:** De 5 a 10 minutos<br>**Pré-condições:** Smartphone com acesso à internet e aplicativo instalado |
| Ator | [Usuário]() cadastrado |
| Recursos | Smartphone<br>Acesso à internet |
| Restrição | Aplicativo instalado no smartphone<br> [Usuário]() já cadastrado no aplicativo |
| Episódios | 1. [Usuário]() [clica]() na [categoria]() de [produtos]() desejada.<br>2. [Usuário]() [clica]() no [produto]() desejado.<br>3. [Usuário]() [clica]() em adicionar ao [carrinho]().<br>4. [Usuário]() seleciona os dados de endereço e pagamento.<br>5. [Usuário]() [clica]() em finalizar compra. |
| Exceção | Falha de conexão<br>Produto indisponível<br>Falta de bateria |
| Rastreabilidade | [RF13](../elicitacao/resultadoElicitacao.md#RF13) e [RF14](../elicitacao/resultadoElicitacao.md#RF14) |

<h6 align = "center"> Tabela 2: Cenário C01 </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

<div id="C02"></div>

### 3.2 C02 - Cadastrar um perfil de [pet]()

| Elemento | Informações |
|--|--|
| Título | Cadastrar um perfil de [pet]() |
| Objetivos | Utilizar o aplicativo para cadastrar informações do seu animal |
| Contexto | **Local:** Tela inicial do aplicativo<br>**Tempo:** De 5 a 10 minutos<br>**Pré-condições:** Smartphone com acesso à internet e aplicativo instalado |
| Ator | [Usuário]() cadastrado |
| Recursos | Smartphone<br>Acesso à internet |
| Restrição | Aplicativo instalado no smartphone<br> [Usuário]() já cadastrado no aplicativo |
| Episódios | 1. [Usuário]() [clica]() na opção [Perfil]().<br>2. [Usuário]() [clica]() na opção Meus [pets]().<br>3. [Usuário]() [clica]() na opção Adicionar [pet]().<br>4. [Usuário]() insere as informações do animal.<br>5. [Usuário]() [clica]() em [Salvar](). |
| Exceção | Falha de conexão<br>Falta de bateria |
| Rastreabilidade | [RF15](../elicitacao/resultadoElicitacao.md#RF15) |

<h6 align = "center"> Tabela 3: Cenário C02 </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

<div id="C03"></div>

### 3.3 C03 - Agendar banho e tosa para seu [pet]()

| Elemento | Informações |
|--|--|
| Título | Agendar banho e tosa para seu [pet]() |
| Objetivos | Utilizar o aplicativo para marcar um serviço de banho e tosa para seu animal |
| Contexto | **Local:** Tela inicial do aplicativo<br>**Tempo:** De 5 a 10 minutos<br>**Pré-condições:** Smartphone com acesso à internet e aplicativo instalado |
| Ator | [Usuário]() cadastrado |
| Recursos | Smartphone<br>Acesso à internet |
| Restrição | Aplicativo instalado no smartphone<br> [Usuário]() já cadastrado no aplicativo |
| Episódios | 1. [Usuário]() [clica]() na opção [Banho e tosa]().<br>2. [Usuário]() [clica]() na opção [Agendar Serviço]().<br>3. [Usuário]() [clica]() no [pet]() desejado.<br>4. [Usuário]() seleciona o profissional desejado.<br>5. [Usuário]() seleciona as datas e horários desejados.<br>6. [Usuário]() [clica]() em [Salvar](). |
| Exceção | Falha de conexão<br>Falta de bateria |
| Rastreabilidade | [RF19](../elicitacao/resultadoElicitacao.md#RF19) |

<h6 align = "center"> Tabela 4: Cenário C03 </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

<div id="C04"></div>

### 3.4 C04 - Visualizar preço de [produtos]() disponíveis

| Elemento | Informações |
|--|--|
| Título | Visualizar preço de [produtos]() disponíveis |
| Objetivos | Utilizar o aplicativo para visualizar o valor de itens disponíveis |
| Contexto | **Local:** Tela inicial do aplicativo<br>**Tempo:** De 5 a 10 minutos<br>**Pré-condições:** Smartphone com acesso à internet e aplicativo instalado |
| Ator | [Usuário]() |
| Recursos | Smartphone<br>Acesso à internet |
| Restrição | Aplicativo instalado no smartphone |
| Episódios | 1. [Usuário]() [clica]() na [categoria]() desejada.<br>2. [Usuário]() visualiza o valor dos [produtos]() presentes na [categoria](). |
| Exceção | Falha de conexão<br>Falta de bateria |
| Rastreabilidade | [RF18](../elicitacao/resultadoElicitacao.md#RF18) |

<h6 align = "center"> Tabela 5: Cenário C04 </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

<div id="C05"></div>

### 3.5 C05 - [Cancelar]() um [pedido]()

| Elemento | Informações |
|--|--|
| Título | [Cancelar]() um [pedido]() |
| Objetivos | Utilizar o aplicativo para [cancelar]() um [pedido]() prévio |
| Contexto | **Local:** Tela inicial do aplicativo<br>**Tempo:** De 5 a 10 minutos<br>**Pré-condições:** Smartphone com acesso à internet e aplicativo instalado |
| Ator | [Usuário]() cadastrado |
| Recursos | Smartphone<br>Acesso à internet |
| Restrição | Aplicativo instalado no smartphone<br>[Usuário]() já cadastrado. |
| Episódios | 1. [Usuário]() [clica]() na opção [Perfil]().<br>2. [Usuário]() [clica]() na opção [Pedidos]().<br>3. [Usuário]() [clica]() no [pedido]() desejado.<br>4. [Usuário]() [clica]() na opção [Cancelar](). |
| Exceção | Falha de conexão<br>Falta de bateria |
| Rastreabilidade | [RF22](../elicitacao/resultadoElicitacao.md#RF22) |

<h6 align = "center"> Tabela 6: Cenário C05 </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

<div id="C06"></div>

### 3.6 C06 - Assinar um pacote periódico de [produtos]()

| Elemento | Informações |
|--|--|
| Título | Assinar um pacote periódico de [produtos]() |
| Objetivos | Utilizar o aplicativo para assinar um pacote periódico de <br>[produtos]() |
| Contexto | **Local:** Tela inicial do aplicativo<br>**Tempo:** De 5 a 10 minutos<br>**Pré-condições:** Smartphone com acesso à internet e aplicativo instalado |
| Ator | [Usuário]() cadastrado |
| Recursos | Smartphone<br>Acesso à internet |
| Restrição | Aplicativo instalado no smartphone<br>[Usuário]() já cadastrado |
| Episódios | 1. [Usuário]() adiciona os [produtos]() desejados ao [carrinho]().<br>2. [Usuário]() clica na opção [pedido periódica]().<br>3. [Usuário]() insere as informações de entrega e pagamento.<br>4. [Usuário]() insere a periodicidade do [pedido]().<br>5. [Usuário]() [clica]() na opção [Salvar](). |
| Exceção | Falha de conexão<br>Falta de bateria |
| Rastreabilidade | [RF33](../elicitacao/resultadoElicitacao.md#RF33) |

<h6 align = "center"> Tabela 07: Cenário C06 </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

## 4. Cenários não implementados

Abaixo estão descritos os cenário cujas funcionalidades não se encontravam em funcionamento no aplicativo analisado, isso durante o período de desenvolvimento do projeto.

<div id="C07"></div>

### 4.1 C07 - Repetir um [pedido]()

| Elemento | Informações |
|--|--|
| Título | Repetir um [pedido]() |
| Objetivos | Utilizar o aplicativo para repetir um [pedido]() prévio |
| Contexto | **Local:** Tela inicial do aplicativo<br>**Tempo:** De 5 a 10 minutos<br>**Pré-condições:** Smartphone com acesso à internet e aplicativo instalado |
| Ator | [Usuário]() cadastrado |
| Recursos | Smartphone<br>Acesso à internet |
| Restrição | Aplicativo instalado no smartphone<br>[Usuário]() já cadastrado. |
| Episódios | 1. [Usuário]() [clica]() na opção [Perfil]().<br>2. [Usuário]() [clica]() na opção [Pedidos]().<br>3. [Usuário]() [clica]() no [pedido]() desejado.<br>4. [Usuário]() [clica]() na opção [Repetir pedido]().<br>5. [Usuário]() insere as informações de entrega e pagamento.<br>6. [Usuário]() [clica]() na opção [Salvar](). |
| Exceção | Falha de conexão<br>Falta de bateria |
| Rastreabilidade | [RF06](../elicitacao/resultadoElicitacao.md#RF06) |

<h6 align = "center"> Tabela 8: Cenário C07 </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

<div id="C08"></div>

### 4.2 C08 - Registrar um [pedido]() como frequente

| Elemento | Informações |
|--|--|
| Título | Registrar um [pedido]() como frequente |
| Objetivos | Utilizar o aplicativo para registrar um [pedido]() como frequente |
| Contexto | **Local:** Tela inicial do aplicativo<br>**Tempo:** De 5 a 10 minutos<br>**Pré-condições:** Smartphone com acesso à internet e aplicativo instalado |
| Ator | [Usuário]() cadastrado |
| Recursos | Smartphone<br>Acesso à internet |
| Restrição | Aplicativo instalado no smartphone<br>[Usuário]() já cadastrado. |
| Episódios | 1. [Usuário]() [clica]() na opção [Perfil]().<br>2. [Usuário]() [clica]() na opção [Pedidos]().<br>3. [Usuário]() [clica]() no [pedido]() desejado.<br>4. [Usuário]() [clica]() na opção [Registrar como frequente](). |
| Exceção | Falha de conexão<br>Falta de bateria |
| Rastreabilidade | [RF24](../elicitacao/resultadoElicitacao.md#RF24) |

<h6 align = "center"> Tabela 9: Cenário C08 </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

<div id="C09"></div>

### 4.3 C09 - Reportar um erro

| Elemento | Informações |
|--|--|
| Título | Reportar um erro |
| Objetivos | Utilizar o aplicativo para registrar um erro inesperado |
| Contexto | **Local:** Tela inicial do aplicativo<br>**Tempo:** De 5 a 10 minutos<br>**Pré-condições:** Smartphone com acesso à internet e aplicativo instalado |
| Ator | [Usuário]() |
| Recursos | Smartphone<br>Acesso à internet |
| Restrição | Aplicativo instalado no smartphone<br>[Usuário]() |
| Episódios | 1. [Usuário]() [clica]() na opção [Registrar erro ou falha]().<br>2. [Usuário]() insere as informações do erro.<br>3. [Usuário]() [clica]() na opção [Salvar](). |
| Exceção | Falha de conexão<br>Falta de bateria |
| Rastreabilidade | [RF30](../elicitacao/resultadoElicitacao.md#RF30) |

<h6 align = "center"> Tabela 10: Cenário C09 </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

<div id="C10"></div>

### 4.5 C10 - Visualizar conteúdo adicional sobre [pets]()

| Elemento | Informações |
|--|--|
| Título | Visualizar conteúdo adicional sobre [pets]() |
| Objetivos | Utilizar o aplicativo para visualizar informações interessantes sobre <br>[pets]() |
| Contexto | **Local:** Tela inicial do aplicativo<br>**Tempo:** De 5 a 10 minutos<br>**Pré-condições:** Smartphone com acesso à internet e aplicativo instalado |
| Ator | [Usuário]() |
| Recursos | Smartphone<br>Acesso à internet |
| Restrição | Aplicativo instalado no smartphone |
| Episódios | 1. [Usuário]() [clica]() na opção [Blog]().<br>2. [Usuário]() [clica]() na [categoria de posts]() desejada.<br>3. [Usuário]() visualiza as informações desejadas. |
| Exceção | Falha de conexão<br>Falta de bateria |
| Rastreabilidade | [RF36](../elicitacao/resultadoElicitacao.md#RF36) e [RF40](../elicitacao/resultadoElicitacao.md#RF40) |

<h6 align = "center"> Tabela 11: Cenário C10 </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

<div id="C11"></div>

### 4.6 C11 - Marcar serviço [veterinário]() com [pet-táxi]()

| Elemento | Informações |
|--|--|
| Título | Marcar serviço [veterinário]() com [pet-táxi]() |
| Objetivos | Utilizar o aplicativo para agendar uma consulta [veterinária](). |
| Contexto | **Local:** Tela inicial do aplicativo<br>**Tempo:** De 5 a 10 minutos<br>**Pré-condições:** Smartphone com acesso à internet e aplicativo instalado |
| Ator | [Usuário]() cadastrado |
| Recursos | Smartphone<br>Acesso à internet |
| Restrição | Aplicativo instalado no smartphone<br>[Usuário]() já cadastrado |
| Episódios | 1. [Usuário]() [clica]() na opção [Veterinário]().<br>2. [Usuário]() seleciona o motivo da consulta.<br>3. [Usuário]() seleciona o profissional desejado.<br>4. [Usuário]() [clica]() na opção [Serviço de pet-táxi]().<br>5. [Usuário]() insere as informações de data e horário.<br>6. [Usuário]() [clica]() na opção [Salvar](). |
| Exceção | Falha de conexão<br>Falta de bateria |
| Rastreabilidade | [RF37](../elicitacao/resultadoElicitacao.md#RF37) e [RF38](../elicitacao/resultadoElicitacao.md#RF38) |

<h6 align = "center"> Tabela 12: Cenário C11 </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

<div id="C12"></div>

### 4.7 C12 - Visualizar eventos para [pets]() próximos

| Elemento | Informações |
|--|--|
| Título | Visualizar eventos para [pets]() próximos |
| Objetivos | Utilizar o aplicativo para Visualizar eventos para [pets]() próximos |
| Contexto | **Local:** Tela inicial do aplicativo<br>**Tempo:** De 5 a 10 minutos<br>**Pré-condições:** Smartphone com acesso à internet e aplicativo instalado |
| Ator | [Usuário]() |
| Recursos | Smartphone<br>Acesso à internet |
| Restrição | Aplicativo instalado no smartphone |
| Episódios | 1. [Usuário]() [clica]() na opção [Eventos]().<br>2. [Usuário]() seleciona seu local.<br>3. [Usuário]() visualiza eventos próximos. |
| Exceção | Falha de conexão<br>Falta de bateria |
| Rastreabilidade | [RF38](../elicitacao/resultadoElicitacao.md#RF38) |

<h6 align = "center"> Tabela 13: Cenário C12 </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

<div id="C13"></div>

### 4.8 C13 - Agendar estadia de [pet]() em [hotel]() para animais

| Elemento | Informações |
|--|--|
| Título | Agendar estadia de [pet]() em [hotel]() para animais |
| Objetivos | Utilizar o aplicativo para agendar estadia de [pet]() em [hotel]() para animais |
| Contexto | **Local:** Tela inicial do aplicativo<br>**Tempo:** De 5 a 10 minutos<br>**Pré-condições:** Smartphone com acesso à internet e aplicativo instalado |
| Ator | [Usuário]() |
| Recursos | Smartphone<br>Acesso à internet |
| Restrição | Aplicativo instalado no smartphone |
| Episódios | 1. [Usuário]() [clica]() na opção [Hotelaria]().<br>2. [Usuário]() seleciona o [pet]() desejado.<br>3. [Usuário]() insere as informações da estadia.<br>4. [Usuário]() [clica]() em salvar. |
| Exceção | Falha de conexão<br>Falta de bateria |
| Rastreabilidade | [RF43](../elicitacao/resultadoElicitacao.md#RF43) |

<h6 align = "center"> Tabela 14: Cenário C13 </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

## 5. Referências Bibliográficas

> [1] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021). Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.

## 6. Histórico de versão

|  Versão  |   Data   |                      Descrição                      |    Autor(es)   |  Revisor(es)  |
| -------- | -------- | --------------------------------------------------- | -------------- | ------------- |
|  `1.0`   | 11/05/23 | Criação e organização do artefato | Pedro Muniz e Felipe Corrêa | Samuel Sato |