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

### L01
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Usuário|cliente, consumidor| Pessoa que utiliza o aplicativo | Pode-se cadastrar novo usuário, Usuário possui pets, pode realizar compras, assinar produtos | Objeto |

### L02
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Pet|animal de estimação, animal doméstico| Animal de estimação do usuário | Usuário pode agendar banho ou tosa para o pet e comprar produtos para o pet | Objeto |

### L03
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Perfil|características, informações| Local onde são armazenadas as informações do pet | Usuário pode visualizar e alterar informações do pet| Objeto |

### L04
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Novo Pet|Cadastrar Pet|Usuário pode cadastrar dados do animal de estimação no aplicativo|Usuário pode agendar banho e tosa para o animal|Verbo|

### L05
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Ofertas|Promoções| Produtos que estão com desconto | Usuário pode comprar produtos com desconto | Objeto |

### L06
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Produto|Mercadoria|Produto vendido pela Petz |Usuário pode ver informações específicas do produto, Usuário pode adicionar produto ao carrinho|Objeto|

### L07
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Assinatura| Contrato | Usuário pode realizar assinatura especificando a frequência que deseja receber dos produtos assinados |Descontos em produtos, entregas periódicas dos produtos no endereço cadastrado |Objeto|

### L08
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Adicionar ao carrinho|-|Adicionar produto ao carrinho|Quantidade do produto adicionado ao carrinho, valor do produto é somado ao total da compra |Verbo|

### L09
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Finalizar compra| Realizar compra | Usuário pode realizar pagamento da compra | Pagamento realizado, Emissão de ordem de entrega ou retirada dos produtos |Verbo|

### L10
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Filtro|-|Pode-se selecionar atributos e características dos produtos que serão filtrados|Usuário pode encontrar produto com base no filtro|Objeto|

### L11
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Ordenar|Organizar|Produtos são exibidos de acordo com ordem estabelecida |Usuários pode visualizar primeiro os produtos de sua preferência|Objeto|

### L12
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Favoritos|Preferido|Produto pode ser favoritado quando usuário adiciona-o a lista de favoritos|Produto pode ser retirado dos favoritos |Estado|

### L13
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Endereço|Local do imóvel|Local onde o usuário deseja receber os produtos comprados|Pode-se entregar produtos nos endereços cadastrados|Objeto|

### L14
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Lojas|Estabelecimento|Unidades da loja Petz próximas|Usuário pode levar animais de estimação para o atendimento, Usuário pode retirar produtos e fazer compras|Objeto|

### L15
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Sair|Ausentar-se|Sair da conta|Usuário pode sair da conta|Verbo|

### L16
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Acompanhar Pedido|Pedidos|Usuário acompanhar pedido de produtos após finalizar compra|Usuário pode cancelar pedido|Verbo|

### L17
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Alertas|Avisos|Informa sobre notificações do pet ou pedido|Usuário pode visualizar estatus do pedido|Objeto|

### L18
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Banho|-|Serviço que usuário pode agendar para seus animais de estimação|Usuário pode agendar serviço pelo aplicativo|Objeto|

### L19
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Tosa|-|Serviço que usuário pode agendar para seus animais de estimação|Usuário pode agendar serviço pelo aplicativo|Objeto|

### L20
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Central de atendimento|Atendimento|Formas de entrar em contato com a Petz|Usuário pode entrar em contato com a Petz pelo chat online|Objeto|

### Léxicos não implementados

### L21
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Registrar pedido frequente|lista de compras frequente|lista de produtos comprados com recorrência|Usuário pode registrar lista de compras recorrente|Verbo|

### L22
| Léxico | Sinônimo | Noção | Impacto | Classificação |
|--------|----------|-------|---------|---------------|
|Reportar erro|Informações sobre erros no aplicativo|Informar falha ou erro para a Petz|Usuário pode informar eventuais erros ou bugs a equipe técnica da Petz|Verbo|

## 4. Referências Bibliográficas

SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 10

## 5. Histórico de versão

| Versão | Data     | Descrição                                  | Autor(es)     | Revisor(es)   |
| ------ | -------- | ------------------------------------------ | ------------- | ------------- |
| `1.0`  | 11/05/23 | Criação inicial do léxico | Samuel Sato, Lucas Rodrigues | Pedro Muniz |
| `1.1`  | 16/05/23 | Adição de novos símbolos | Samuel Sato | Pedro Muniz |