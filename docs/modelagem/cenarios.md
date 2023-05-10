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
| Título   | - |
| Objetivos | - |
| Contexto | - **Local:**<br>- **Tempo:**<br> - **Pré-condição:** |
| Ator | - |
| Recursos | - |
| Restrição | - |
| Episódios | - |
| Exceção | - |
| Rastreabilidade | - |

## 3. Cenários

### 3.1 Realizar uma compra no aplicativo

| Elemento | Informações |
|--|--|
| Título | Realizar uma compra no aplicativo |
| Objetivos | Utilizar o aplicativo para comprar um produto para seu animal |
| Contexto | **Local:** Tela inicial do aplicativo<br>**Tempo:** De 5 a 10 minutos<br>**Pré-condições:** Smartphone com acesso à internet e aplicativo instalado |
| Ator | [Usuário]() cadastrado |
| Recursos | Smartphone<br>Acesso à internet |
| Restrição | Aplicativo instalado no smartphone<br>[Usuário] já cadastrado no aplicativo |
| Episódios | 1. [Usuário]() [clica]() na [categoria]() de [produtos]() desejada.<br>2. [Usuário]() [clica]() no [produto]() desejado.<br>3. [Usuário]() [clica]() em adicionar ao [carrinho]().<br>4. [Usuário]() seleciona os dados de endereço e pagamento.<br>5. [Usuário]() [clica]() em finalizar compra. |
| Exceção | Falha de conexão<br>Produto indisponível<br>Falta de bateria |
| Rastreabilidade | [RF13]() e [RF14]() |

### 3.2 Cadastrar um perfil de [pet]()

| Elemento | Informações |
|--|--|
| Título | Cadastrar um perfil de [pet]() |
| Objetivos | Utilizar o aplicativo para cadastrar informações do seu animal |
| Contexto | **Local:** Tela inicial do aplicativo<br>**Tempo:** De 5 a 10 minutos<br>**Pré-condições:** Smartphone com acesso à internet e aplicativo instalado |
| Ator | [Usuário]() cadastrado |
| Recursos | Smartphone<br>Acesso à internet |
| Restrição | Aplicativo instalado no smartphone<br>[Usuário] já cadastrado no aplicativo |
| Episódios | 1. [Usuário]() [clica]() na opção [Perfil]().<br>2. [Usuário]() [clica]() na opção Meus [pets]().<br>3. [Usuário]() [clica]() na opção Adicionar [pet]().<br>4. [Usuário]() insere as informações do animal.<br>5. [Usuário]() [clica]() em [Salvar](). |
| Exceção | Falha de conexão<br>Falta de bateria |
| Rastreabilidade | [RF15]() |