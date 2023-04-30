# Escala de três níveis

## 1. Introdução

A técnica de escala de três níveis é relativamente comum, pois separa os requisitos naqueles de alta, média e baixa prioridade. No entanto, ela é muito abstrata para os propósitos deste artefato. Dessa forma, para uma priorização mais objetiva destes requisitos foi utilizada uma matriz de dois eixos (urgente e importante). Dessa forma, os requisitos foram analisados de maneira menos subjetiva e a priorização ocorreu dentro da escala de três níveis, já que os requisitos _urgentes_ e _não importantes_ são interessantes para alguma parte interessada mas não ajudam no sucesso de objetivos de negócios [2].
Assim, os outros quadrantes da matriz podem ser descritos como:

- Importantes e urgentes: quando os clientes necessitam do requisito e não podem esperar por ele (**alta prioridade**)[2].
- Importantes e não urgentes: quando os clientes necessitam do requisito mas podem esperar por ele (**média prioridade**)[2].
- Não importantes e não urgentes: quando os clientes não necessitam do requisito e podem esperar por ele (**baixa prioridade**)[2].

## 2. Priorização

Os requisitos foram priorizados a partir dos [resultados da elicitação](./resultadoElicitacao.md) e com base nas personas delimitadas em [artefato dedicado](./personas.md). A priorização foi realizada com o auxílio da ferramenta [Miro](https://miro.com) e está incorporada abaixo para vizualização.

<iframe src="https://miro.com/app/live-embed/uXjVMN20OnQ=/?moveToViewport=-880,-928,1998,1536&embedId=453219108021" scrolling="no" allow="fullscreen; clipboard-read; clipboard-write" allowfullscreen width="768" height="432" frameborder="0"></iframe>

<h6 align = "center"> Fonte: Autor, 2023 </h6>

A partir da priorização realizada, foram construídas as tabelas 1, 2 e 3, onde estão marcados os requisitos de alta, média e baixa prioridade, respectivamente. Os requisitos que possuem o texto destacado não foram implementados pelo aplicativo [1].

### 3.1 Requisitos de alta prioridade 


| ID | Requisito | Justificativa |
|--|--|--|
| RF01 | O usuário deve ser capaz de se cadastrar na aplicação | Este requisito possibilita personalização necessária para as personas |
| RF02 | O usuário deve ser capaz de entrar em sua conta cadastrada. | Este requisito é fundamental para o funcionamento de outras partes do sistema. |
| RF03 | O usuário deve ser capaz de visualizar catálogo online de produtos para animais de estimação. | A visualização de produtos é essencial para atingir objetivos de negócio. |
| RF04 | O usuário deve ser capaz de visualizar itens de produtos e serviços. | Este requisito é essencial para atingir objetivos de negócio. |
| RF07 | O usuário deve ser capaz de pesquisar produtos. | Qualquer usuário deve ser capaz de encontrar produtos específicos rapidamente. |
| RF09 | O usuário deve ser capaz de selecionar itens. | Este requisito é essencial para atingir objetivos de negócio. |
| RF10 | O usuário deve ser capaz de adicionar itens ao sacola de compras. | Este requisito é essencial para atingir objetivos de negócio. |
| RF11 | O usuário deve ser capaz de acompanhar a situação do pedido. | Qualquer usuário dentre as personas teria interesse em acompanhar seu pedido. |
| RF12 | O usuário deve ser capaz de adicionar uma opção de pagamento. | Este requisito é essencial para atingir objetivos de negócio. |
| RF14 | O usuário deve ser capaz de realizar uma compra na aplicação.|Este requisito é essencial para atingir objetivos de negócio.|
| RF15 | O usuário deve ser capaz de cadastrar um perfil para o Pet. | Todas as personas tem necessidades especiais para cada animal de estimação. |
| RF16 | O usuário deve ser capaz de remover itens da sacola de compras. | Este requisito é essencial para atingir objetivos de negócio. |
| RF18 | O usuário deve ser capaz de visualizar o preço de itens. | Este requisito é essencial para atingir objetivos de negócio. |
| RF19 | O usuário deve ser capaz de agendar um serviço de banho e tosa. | Todas as personas (exceto por Gilson) tem interesse neste requisito. |
| RF21 | O usuário deve ser capaz de recuperar sua conta através do endereço de email cadastrado. | Este requisito é essencial para atingir objetivos de negócio. |
| RF22 | O usuário deve ser capaz de cancelar um pedido. | Este requisito é essencial para atingir objetivos de negócio. |
| RF23 | O usuário deve ser capaz de escolher como receber um produto. | Este requisito é essencial para atingir objetivos de negócio. |
| RF25 | O usuário deve ser capaz de acessar a avaliação e recomendações de um produto. | Este requisito é essencial para atingir objetivos de negócio. |
| RF26 | O usuário deve ser capaz de solicitar a entrega de produtos. | Este requisito é essencial para atingir objetivos de negócio. |
| RF28 | O usuário deve ser capaz de filtrar produtos por categoria. | Todo e qualquer usuário deve poder filtrar sua pesquisa para maior facilidade. |
| RF29 | O usuário deve ser capaz de cadastrar mais de um animal de estimação na aplicação. | Personas como Marcos, Anete e Julia podem ter necessidades diferentes para cada animal. |
| RF31 | O sistema deve possuir filtros e classificação por categorias para os produtos. | Todo e qualquer usuário deve poder filtrar sua pesquisa para maior facilidade.|
| RF35 | `O usuário deve ser capaz de alterar local de entrega do produto.` | Este requisito é essencial para atingir objetivos de negócio. |
| RF38 | `O usuário deve ser capaz de marcar consultas veterinárias.` | As personas possuem interesse neste tipo de serviço. |
| RNF01 | O sistema deve ser manter seguro as informações do usuário criptografando dados sensíveis. | Todo usuário tem direito à segurança e inviolabilidade de seus dados. |
| RNF02 | O sistema deve estar disponível para os sistemas Android e iOS. | Quanto mais dispositivos forem compatíveis, maiores as possibilidades de se atingir objetivos de negócio.|
| RNF04 | O sistema deve ter um sistema de busca eficiente.| Todo usuário deve poder procurar por produtos de maneira rápida e fácil. |
| RNF05 | O sistema deve ser confiável e disponível | Todo usuário deve poder utilizar o sistema a qualquer momento de forma eficiente. |

<h6 align = "center"> Tabela 1: Requisitos de alta prioridade </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

### 3.2 Requisitos de média prioridade 

| ID | Requisito | Justificativa |
|--|--|--|
| RF06 | `O usuário deve ser capaz de repetir um pedido anterior.` | Este requisito não é essencial para a obtenção de objetivos de negócios. |
| RF13 | O usuário deve ser capaz de realizar um pedido na loja. | A rapidez da compra e a capacidade de compra em si são mais importantes para as personas do que a localização ou fidelidade. |
| RF17 | O usuário deve ser capaz de favoritar itens. | Este requisito não é essencial para a obtenção de objetivos de negócios. |
| RF24 | `O usuário deve ser capaz de registrar uma lista de compras frequentes.` | Este requisito não é essencial para a obtenção de objetivos de negócios. |
| RF27 | O usuário deve ser capaz de consultar a loja mais próxima. | As personas (exceto Anete) tem facilidade com o uso de dispositivos móveis. |
| RF32 | `O sistema deve realizar a sugestão de produtos a partir de um perfil.` | Nenhuma das personas é indecisa quanto à compra de produtos específicos. |
| RF37 | `O usuário deve ser capaz de solicitar transporte para o animal até a loja física.` | As personas (exceto Anete) não possuem este serviço como prioridade. |
| RF41 | `O sistema deve notificar o usuário acerca de pendências médicas dos seus _pets_.` | As personas (exceto Gilson) poderiam se aproveitar deste requisito, porém este não é primordial para a obtenção de objetivos de negócio.|
| RNF03 | O sistema deve ser responsivo. | A responsividade não é primordial a nenhuma das personas. |

<h6 align = "center"> Tabela 2: Requisitos de média prioridade </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

### 3.3 Requisitos de baixa prioridade 

| ID | Requisito | Justificativa |
|--|--|--|
|RF05|O usuário deve ser capaz de cadastrar-se para promoções.| O cadastro em promoções é desnecessário ou não prioritário para as personas.|
|RF08|O usuário deve ser capaz de pesquisar serviços.| Não há uma quantidade de serviços que justifique a necessidade de uma pesquisa dedidcada. |
|RF20|O usuário deve ser capaz de assinar um serviço.|Este requisito não é importante para a maioria dos usuários. |
|RF30|O usuário deve ser capaz de reportar falhas e erros| As personas não possuem o perfil para utilizar ou ter como prioridade este requisito. |
|RF40|`O usuário deve ser capaz de acessar uma tela com _posts_ da comunidade.`| As personas não possuem o perfil para utilizar ou ter como prioridade este requisito.|
| RF42 | `O usuário deve ser capaz de se cadastrar em um sistema de fidelidade pelo aplicativo.` |As personas não possuem o perfil para utilizar ou ter como prioridade este requisito.|

<h6 align = "center"> Tabela 3: Requisitos de baixa prioridade </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

## 4. Requisitos não executados

Nesta priorização, os requisitos que não serão executados estão descritos na tabela 4 sob a justificativa já detalhada na [introdução](#1-introducao) deste artefato.

### 4.1 Requisitos não executados

|ID|Requisito|
| -- | -- |
|RF33|`O usuário deve ser capaz de assinar produtos pelo aplicativo.`|
|RF34|`O usuário deve ser capaz de obter informações sobre cuidados de animais.`|
|RF36|`O usuário deve ser capaz de acessar um blog com dicas sobre _pets_.`|
|RF39|`O usuário deve ser capaz de acessar uma tela com eventos próximos relacionados a _pets_.`|
|RF43|`O sistema deve fornecer ao usuário serviços de hotelaria para animais.` |

<h6 align = "center"> Tabela 4: Requisitos não executados </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

## Referências Bibliográficas

> [1] Lichess. Priorização de requisitos. Disponível no [link](https://requisitos-de-software.github.io/2022.2-Lichess/elicitacao/priorizacao/). Acesso em: 30 abr. 2023.

> [2] WIEGERS, Karl; JOY, Beatty. PART II: Requirements development. In: WIEGERS, Karl; JOY, Beatty. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013. Cap. 16. p. 319-320. Disponível em: https://www.dirzon.com/file/telegram/HiLCoE%20-%20DRB1802/Microsoft%20Press%20Software%20Requirements%203%203rd%20Edition%20Aug%202013.pdf. Acesso em: 30 abr. 2023. 



## Histórico de versão

| Versão | Data     | Descrição                        | Autor(es)     | Revisor(es) |
| ------ | -------- | -------------------------------- | ------------- | ----------- |
| `1.0`  | 30/04/23 | Criação da página de priorização | Felipe Corrêa | Pedro Muniz |
| `1.1`  | 30/04/23 | Atualização dos requisitos | Felipe Corrêa | Pedro Muniz |
