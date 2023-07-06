# Léxico

## 1. Introdução

O Léxico é uma técnica que procura descrever os símbolos de uma linguagem. O principal objetivo dos engenheiros de requisitos é buscar frases e símbolos do domínio da aplicação. Cada um desse símbolo é descrito com uma noção e um impacto, sendo a noção relacionada com o símbolo e o impacto com a descrição do efeito do símbolo na aplicação ou do efeito de algo na aplicação sobre o símbolo.


## 2. Metodologia

Os símbolos foram identificados a partir do uso do aplicativo Petz e dos requisitos elicitados na etapa anterior. Seguem o padrão da tabela [1], ondem cada símbolo apresenta sinônimo, noção, impacto e classificação. 

| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Frase/Palavra| Sinônimo | Denotação | Descrição do efeito | Verbo/Objeto/Estado |

</center>

<h6 align = "center"> Tabela 1: Modelo das tabelas de léxico</h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

## 3. Tabela de Léxicos

### 3.1 Léxicos já implementados
<div id="L01"></div>

### 3.1.1 L01 - Usuário
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Usuário|cliente, consumidor| Pessoa que utiliza o aplicativo | Pode-se cadastrar novo usuário, Usuário possui pets, pode realizar compras, assinar produtos | Objeto |
<div id="L02"></div>

### 3.1.2 L02 - Pet
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Pet|animal de estimação, animal doméstico| Animal de estimação do usuário | Usuário pode agendar banho ou tosa para o pet e comprar produtos para o pet | Objeto |
<div id="L03"></div>

### 3.1.3 L03 - Perfil
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Perfil|características, informações| Local onde são armazenadas as informações do pet | Usuário pode visualizar e alterar informações do pet| Objeto |
<div id="L04"></div>

### 3.1.4 L04 - Novo Pet
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Novo Pet|Cadastrar Pet|Usuário pode cadastrar dados do animal de estimação no aplicativo|Usuário pode agendar banho e tosa para o animal|Verbo|
<div id="L05"></div>

### 3.1.5 L05 - Ofertas
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Ofertas|Promoções| Produtos que estão com desconto | Usuário pode comprar produtos com desconto | Objeto |
<div id="L06"></div>

### 3.1.6 L06 - Produto
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Produto|Mercadoria|Produto vendido pela Petz |Usuário pode ver informações específicas do produto, Usuário pode adicionar produto ao carrinho|Objeto|
<div id="L07"></div>

### 3.1.7 L07 - Assinatura
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Assinatura| Contrato | Usuário pode realizar assinatura especificando a frequência que deseja receber dos produtos assinados |Descontos em produtos, entregas periódicas dos produtos no endereço cadastrado |Objeto|
<div id="L08"></div>

### 3.1.8 L08 - Adicionar ao Carrinho
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Adicionar ao carrinho| Adicionar produto selecionado ao carrinho |Adicionar produto ao carrinho|Quantidade do produto adicionado ao carrinho, valor do produto é somado ao total da compra |Verbo|
<div id="L09"></div>

### 3.1.9 L09 - Finalizar Compra
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Finalizar compra| Realizar compra | Usuário pode realizar pagamento da compra | Pagamento realizado, Emissão de ordem de entrega ou retirada dos produtos |Verbo|
<div id="L10"></div>

### 3.1.10 L10 - Filtro
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Filtro| Agrupar por caracteristicas |Pode-se selecionar atributos e características dos produtos que serão filtrados|Usuário pode encontrar produto com base no filtro|Objeto|
<div id="L11"></div>

### 3.1.11 L11 - Ordenar
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Ordenar|Organizar|Produtos são exibidos de acordo com ordem estabelecida |Usuários pode visualizar primeiro os produtos de sua preferência|Objeto|
<div id="L12"></div>

### 3.1.12 L12 - Favoritos
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Favoritos|Preferido|Produto pode ser favoritado quando usuário adiciona-o a lista de favoritos|Produto pode ser retirado dos favoritos |Estado|
<div id="L13"></div>

### 3.1.13 L13 - Endereço
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Endereço|Local do imóvel|Local onde o usuário deseja receber os produtos comprados|Pode-se entregar produtos nos endereços cadastrados|Objeto|
<div id="L14"></div>

### 3.1.14 L14 - Lojas
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Lojas|Estabelecimento|Unidades da loja Petz próximas|Usuário pode levar animais de estimação para o atendimento, Usuário pode retirar produtos e fazer compras|Objeto|
<div id="L15"></div>

### 3.1.15 L15 - Sair
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Sair|Ausentar-se|Sair da conta|Usuário pode sair da conta|Verbo|
<div id="L16"></div>

### 3.1.16 L16 - Acompanhar Pedido
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Acompanhar Pedido|Pedidos|Usuário acompanhar pedido de produtos após finalizar compra|Usuário pode cancelar pedido|Verbo|
<div id="L17"></div>

### 3.1.17 L17 - Alertas
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Alertas|Avisos|Informa sobre notificações do pet ou pedido|Usuário pode visualizar estatus do pedido|Objeto|
<div id="L18"></div>

### 3.1.18 L18 - Banho
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Banho| Lavar |Serviço que usuário pode agendar para seus animais de estimação|Usuário pode agendar serviço pelo aplicativo|Objeto|
<div id="L19"></div>

### 3.1.19 L19 - Tosa
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Tosa| Aparar pelo |Serviço que usuário pode agendar para seus animais de estimação|Usuário pode agendar serviço pelo aplicativo|Objeto|
<div id="L20"></div>

### 3.1.20 L20 - Atendimento
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Central de atendimento|Atendimento|Formas de entrar em contato com a Petz|Usuário pode entrar em contato com a Petz pelo chat online|Objeto|

### Léxicos não implementados
<div id="L21"></div>

### 3.1.21 L21 - Pedido Frequente
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Registrar pedido frequente|lista de compras frequente|lista de produtos comprados com recorrência|Usuário pode registrar lista de compras recorrente|Verbo|
<div id="L22"></div>

### 3.1.22 L22 - Reportar erro
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Reportar erro|Informações sobre erros no aplicativo|Informar falha ou erro para a Petz|Usuário pode informar eventuais erros ou bugs a equipe técnica da Petz|Verbo|
<div id="L23"></div>

### L23 - Clicar
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Clicar| Pressionar, apertar | Ação que pode ser realizada pelo Usuário para selecionar |Usuário pode selecionar campos e itens do aplicativo |Verbo|
<div id="L24"></div>

### L24 - Salvar
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Salvar| Gravar, armazenar | Armazenamento de informações | Usuário pode salvar informações |Verbo|
<div id="L25"></div>

### L25 - Agendar serviço
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Agendar serviço |marcar serviço, combinar serviço|Permitir marcar horário para realizar serviço |Usuário pode agendar horários para realização de serviços |Verbo|
<div id="L26"></div>


### L26 - Pedido
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Pedido | Solicitação, requisição |Pedido realizado pelo usuário |Usuário pode efetuar pedidos|Objeto|
<div id="L27"></div>

### L27 - Registrar Pedido
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
| Registrar Pedido |guardar pedido | Registrar pedido realizado pelo usuário | Pedido do usuário será armazenado para futura entrega  |Verbo|
<div id="L28"></div>


### L28 - Blog
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
| Blog | diário online |Informações sobre assuntos variados com relação a petz | Usuário pode ler informações relacionadas a petz |Objeto |
<div id="L29"></div>

### L29 - Categoria
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Categoria|Tipo, conjunto | Divisão de elementos por categoria | Usuário pode acessar itens que possuem finalidade comum dividos em categorias |Verbo|
<div id="L30"></div>

### L30 - Categoria de posts
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Categoria de posts| Tipo de posts |Divisão de elementos por categoria de posts (publicações) | Usuário pode acessar posts, dividos em categorias |Objeto|
<div id="L31"></div>

### L31 - Veterinário
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Veterinário| Médico de animais |Profissonal responsável pelo atendimento do pet | Usuário pode visualizar profissionais disponíveis para atender |Objeto|
<div id="L32"></div>

### L32 - Pet-Táxi
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Pet-Táxi| Transporte de petz |transporte de animais através de veiculo |Usuário pode solicitar transporte do seu pet para um estabelecimento da petz |Objeto|
<div id="L33"></div>

### L33 - Eventos
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Eventos| Festividades |Realização de eventos da Petz|Usuário pode visualizar eventos que estão ocorrendo na Petz|Objeto|
<div id="L34"></div>

### L34 - Hotel 
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Hotel | Hospedaria |Hospedagem de animais na Petz| Usuário pode solicitar hospedagem para seu pet |Objeto|


## 4. Referências Bibliográficas

> [1] SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 10

## 5. Histórico de versão

| Versão | Data     | Descrição                                  | Autor(es)     | Revisor(es)   |
| ------ | -------- | ------------------------------------------ | ------------- | ------------- |
| `1.0`  | 11/05/23 | Criação inicial do léxico | Samuel Sato, Lucas Rodrigues | Pedro Muniz |
| `1.1`  | 16/05/23 | Adição de novos símbolos | Samuel Sato | Pedro Muniz |
| `1.2`  | 21/06/23 | Adição de nomes aos léxicos e sinônimos faltantes | Samuel Sato | Magno Luiz |
| `1.3`  | 04/07/23 | Adição de novos léxicos | Vitor Manoel | Samuel Sato |