# Histórias de usuário

## 1. Introdução

Histórias de usuário são uma forma de modelagem de requisitos ágil proposta por Kent Beck, surgindo originalmente na metodologia ágil XP. São utilizadas para resumir de forma sucinta as necessidades dos usuários do sistema, sendo uma maneira muito simples e de fácil entendimento para representar os requisitos de um software[2].

## 2. Metodologia

### 2.1 Formação das histórias

Histórias de usuário devem seguir uma estrutura rígida, definindo sempre três elementos básicos: QUEM (Ator que possui uma neceessidade), O QUE (Ação a ser realizada) e PORQUE (Motivo pelo qual a ação deve ser realizada), seguindo a seguinte estrutura:

Eu como **(tipo de usuário)**, gostaria de **(ação a ser realizada)** para **(motivação da história)**.

Além disso, as histórias de usuário devem se basear no método INVEST que diz que boas histórias devem ser independentes, negociáveis, estimáveis, pequenas e testáveis. Para o projeto cada cartão de história de usuário terá a seguinte estrutura:

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | USXX |
| **Título** | Título da história |
| **História** | Estrutura da história |
| **Critérios de aceitação** | Critérios estabelecidos pelo PO |
| **Rastreabilidade** | Requisitos de origem da história |

<h6 align = "center"> Tabela 1: Estrutura para história de usuário </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

### 2.2 Obtenção e validação das histórias

Para obter as histórias de usuário para o projeto, foram utilizados os requisitos elicitados anteriormente, tais requisitos podem ser encontrados no artefato dos [resultados](../../elicitacao/resultadoPriorizacao.md)[1]. Para validar as histórias desenvolvidas e obter os critérios de aceitação das mesmas, foi necessário a participação de um usuário real, o qual representa o PO do aplicativo. As informações e gravação desta participação podem ser encontradas abaixo no artefato.

## 3. _Features_

Para a listagem das histórias de usuário elicitadas para o projeto, consideramos cada uma como sendo uma _feature_ do aplicativo, gerando então 20 features divididas em 5 categorias distintas.

### 3.1 _Features_ de cadastro e autenticação

#### 3.1.1 Cadastro de usuário

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US01 |
| **Título** | Cadastro de novo usuário no aplicativo |
| **História** | Eu como potencial usuário, gostaria de me cadastrar no aplicativo, para que possa usufruir dos serviços oferecidos. |
| **Critérios de aceitação** | - O usuário deve poder cadastrar-se com o email pessoal ou com o celular<br />- O usuário deve receber um SMS com código verificador ou email para confirmar o cadastro<br />- O usuário deve poder cadastrar-se com uma conta de rede social como Instagram ou Facebook |
| **Rastreabilidade** | [RF01](../../elicitacao/resultadoElicitacao.md#RF01) |

<h6 align = "center"> Tabela 2: História de usuário US01 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

#### 3.1.2 Login de usuário

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US02 |
| **Título** | Login de usuário cadastrado no aplicativo |
| **História** | Eu como usuário cadastrado, gostaria de fazer login no aplicativo, para que possa acessar seus serviços. |
| **Critérios de aceitação** | - O aplicativo deve permitir login via informações biométricas<br />- O aplicativo deve permitir o login com contas de redes sociais |
| **Rastreabilidade** | [RF02](../../elicitacao/resultadoElicitacao.md#RF02) |

<h6 align = "center"> Tabela 3: História de usuário US02 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

#### 3.1.3 Cadastro de _pet_

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US03 |
| **Título** | Cadastro de um novo animal no aplicativo |
| **História** | Eu como usuário autenticado, gostaria de cadastrar um novo _pet_ no aplicativo, para que possa solicitar serviços para ele. |
| **Critérios de aceitação** | - O usuário deve poder cadastrar o nome, peso (opcional), o porte, a raça, a idade, uma foto (opcional) e uma atividade preferida (opcional)<br />- O usuário deve poder cadastrar informações médicas do pet<br />-O usuário deve poder cadastrar a carteira de vacinação do pet |
| **Rastreabilidade** | [RF15](../../elicitacao/resultadoElicitacao.md#RF15), [RF29](../../elicitacao/resultadoElicitacao.md#RF29) |

<h6 align = "center"> Tabela 4: História de usuário US03 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

### 3.2 _Features_ de pedidos

#### 3.2.1 Realizar pedido

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US04 |
| **Título** | Realizar um novo pedido de produtos pelo aplicativo |
| **História** | Eu como usuário autenticado, gostaria de realizar uma nova compra de produtos pelo aplicativo, para que possa suprir as necessidades dos meus _pets_. |
| **Critérios de aceitação** | - O pedido deve permitir selecionar opções de pagamento via Pix, cartões de crédito e boleto bancário<br />- O pedido deve permitir selecionar opções de parcelamento<br />-O pedido deve permitir a verificação do custo do frete com o CEP<br />- O endereço deve poder ser preenchido automaticamente com a inclusão do CEP<br />-Outros endereços devem poder ser cadastrados a partir dessa página<br/>-Os endereços devem poder ser nomeados para organização|
| **Rastreabilidade** | [RF13](../../elicitacao/resultadoElicitacao.md#RF13), [RF14](../../elicitacao/resultadoElicitacao.md#RF14) |

<h6 align = "center"> Tabela 5: História de usuário US04 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

#### 3.2.2 Cancelar um pedido

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US05 |
| **Título** | Cancelar um pedido de produtos já realizado |
| **História** | Eu como usuário autenticado, gostaria de cancelar uma compra prévia, para que possa evitar uma devolução futura. |
| **Critérios de aceitação** | - A política de cancelamento deve seguir o Código de defesa do Consumidor<br />-O usuário deve poder cancelar parte de um pedido<br />- O usuário deve ter acesso a uma página de pedidos correntes<br />- O usuário deve receber um email para poder acompanhar um pedido ou cancelá-lo |
| **Rastreabilidade** | [RF22](../../elicitacao/resultadoElicitacao.md#RF22) |

<h6 align = "center"> Tabela 6: História de usuário US05 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>


#### 3.2.3 Repetir um pedido

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US06 |
| **Título** | Repetir um pedido de produtos já realizado anteriormente |
| **História** | Eu como usuário autenticado, gostaria de repetir uma compra prévia, para que possa economizar tempo em compras frequentes. |
| **Critérios de aceitação** | - O usuário deve receber um email para poder acompanhar um pedido ou repeti-lo<br>- O usuário deve ter acesso aos pedidos passados na página de pedidos |
| **Rastreabilidade** | [RF06](../../elicitacao/resultadoElicitacao.md#RF06) |

<h6 align = "center"> Tabela 7: História de usuário US06 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

#### 3.2.4 Realizar um pedido periódico

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US07 |
| **Título** | Realizar de forma automática a compra de produtos periódicamente |
| **História** | Eu como usuário autenticado, gostaria de configurar a compra automática de um pedido periódicamente, para que possa economizar tempo. |
| **Critérios de aceitação** | - O usuário deve poder acessar essa função na página de checkout ou na página de pedidos<br>- O usuário deve ser capaz de definir a periodicidade do pedido<br>- O usupario deve ser capaz de definir pagamento automático para o pedido |
| **Rastreabilidade** | [RF20](../../elicitacao/resultadoElicitacao.md#RF20), [RF24](../../elicitacao/resultadoElicitacao.md#RF24), [RF33](../../elicitacao/resultadoElicitacao.md#RF33), [RF42](../../elicitacao/resultadoElicitacao.md#RF42) |

<h6 align = "center"> Tabela 8: História de usuário US07 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

#### 3.2.5 Acompanhar e alterar pedidos

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US08 |
| **Título** | Acompanhar e gerenciar compras pelo aplicativo |
| **História** | Eu como usuário autenticado, gostaria de acompanhar e alterar compras em andamento, para que possa realizar mudanças de forma simples. |
| **Critérios de aceitação** | - A compra em andamento deve ser guardada em um carrinho de compras<br>- O carrinho deve permitir a mudança de quantidades de um determinado produto<br>- A mostra dos valores deve ser feita de maneira itemizada<br> - O carrinho deve conter o preço final do pedido<br> - A posição do carrinho no aplicativo deve ser configurável |
| **Rastreabilidade** | [RF11](../../elicitacao/resultadoElicitacao.md#RF11), [RF12](../../elicitacao/resultadoElicitacao.md#RF12), [RF23](../../elicitacao/resultadoElicitacao.md#RF23), [RF35](../../elicitacao/resultadoElicitacao.md#RF35) |

<h6 align = "center"> Tabela 2: História de usuário US01 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

### 3.3 _Features_ para serviços

#### 3.3.1 Solicitar serviço de banho e tosa

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US09 |
| **Título** | Solicitar um serviço de banho e tosa pelo aplicativo |
| **História** | Eu como usuário autenticado, gostaria acompnahar e marcar serviços de banho e tosa para meu _pet_, para que possa economizar tempo. |
| **Critérios de aceitação** | - O usuário deve poder selecionar a cidade e a unidade da Petz em que o serviço ocorrerá<br>- O usuário deve poder selecionar a data e o horário do serviço em calendário dedicado<br>- O usuário deve poder agendar o serviço para um pet cadastrado<br>- O usuário deve ser capaz de acompanhar o serviço com imagens |
| **Rastreabilidade** | [RF19](../../elicitacao/resultadoElicitacao.md#RF19) |

<h6 align = "center"> Tabela 10: História de usuário US09 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

#### 3.3.2 Solicitar serviço de veterinária

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US10 |
| **Título** | Solicitar um serviço veterinário pelo aplicativo |
| **História** | Eu como usuário autenticado, gostaria de acompanhar e marcar consultas veterinárias para meu _pet_., para que possa economizar tempo. |
| **Critérios de aceitação** | - O usuário deve poder selecionar a cidade e a unidade da Petz em que o serviço ocorrerá<br>- O usuário deve poder selecionar a data e o horário do serviço em calendário dedicado<br>- O usuário deve poder agendar o serviço para um pet cadastrado<br>- Os serviços veterinários devem estar categorizados |
| **Rastreabilidade** | [RF38](../../elicitacao/resultadoElicitacao.md#RF38), [RF41](../../elicitacao/resultadoElicitacao.md#RF41) |

<h6 align = "center"> Tabela 11: História de usuário US10 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

#### 3.3.3 Solicitar serviço de hotelaria para animais

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US11 |
| **Título** | Solicitar um serviço de hotelaria para animais pelo aplicativo |
| **História** | Eu como usuário autenticado, gostaria de acompanhar e realizar reservas de hospedagem para meu _pet_. para que possa economizar tempo. |
| **Critérios de aceitação** | - O usuário deve ter acesso às informações do hotel e à galeria de fotos<br>- O usuário deve ter acesso Às datas de reserva disponíveis e orçamento da hospedagem<br>- O usuário deve poder visualizar câmeras dos pets em tempo real |
| **Rastreabilidade** | [RF43](../../elicitacao/resultadoElicitacao.md#RF43) |

<h6 align = "center"> Tabela 12: História de usuário US11 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

#### 3.3.4 Solicitar serviço de transporte para animais

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US12 |
| **Título** | Solicitar um serviço de transporte para animais pelo aplicativo |
| **História** | Eu como usuário autenticado, gostaria de acompanhar e solicitar o transporte do meu _pet_ até o estabelecimento físico, para que possa economizar tempo. |
| **Critérios de aceitação** | - A solicitação de transporte dewve ser disponibilizada dentro dos serviços anteriores<br>- O serviço deve ser capaz de ser acompanhado por imagens e localização em tempo real<br>- O cadastro de outros endereços deve ser oferecido neste serviço |
| **Rastreabilidade** | [RF37](../../elicitacao/resultadoElicitacao.md#RF37) |

<h6 align = "center"> Tabela 13: História de usuário US12 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

### 3.4 _Features_ de catálogo de produtos

#### 3.4.1 Visualizar catálogo

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US13 |
| **Título** | Visualizar catálogo de produtos pelo aplicativo |
| **História** | Eu como usuário, gostaria de visualizar o catálogo de produtos oferecidos, para que possa verificar se o produto que desejo é oferecido. |
| **Critérios de aceitação** | - O catálogo deve ser organizado de maneira a mostrar quatro produtos na tela, no máximo<br>- Os produtos no catálogo devem ter, em primeiro plano: imagem, nome, e preço cheio |
| **Rastreabilidade** | [RF03](../../elicitacao/resultadoElicitacao.md#RF03), [RF04](../../elicitacao/resultadoElicitacao.md#RF04) |

<h6 align = "center"> Tabela 14: História de usuário US13 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

#### 3.4.2 Filtrar catálogo

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US14 |
| **Título** | Filtrar o catálogo de produtos pelo aplicativo |
| **História** | Eu como usuário, gostaria de filtrar os produtos oferecidos, para que possa encontrar o produto desejado rapidamente. |
| **Critérios de aceitação** | - O usuário deve poder filtrar o catálogo de produtos por animais, porte, raça, e subcategorias vindas destas<br>- O usuário deve poder filtrar por preço<br> |
| **Rastreabilidade** | [RF17](../../elicitacao/resultadoElicitacao.md#RF17), [RF28](../../elicitacao/resultadoElicitacao.md#RF28), [RF31](../../elicitacao/resultadoElicitacao.md#RF31) |

<h6 align = "center"> Tabela 15: História de usuário US14 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

#### 3.4.3 Pesquisar produto

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US15 |
| **Título** | Pesquisar um produto específico pelo aplicativo |
| **História** | Eu como usuário, gostaria de pesquisar um produto específico, para que possa encontrar o produto desejado rapidamente. |
| **Critérios de aceitação** | - O serviço de _autocomplete_ deve mostrar no máximo cinco sugestões<br>- Produtos similares à pesquisa devem ser mostrados separadamente |
| **Rastreabilidade** | [RF07](../../elicitacao/resultadoElicitacao.md#RF07), [RF08](../../elicitacao/resultadoElicitacao.md#RF08) |

<h6 align = "center"> Tabela 16: História de usuário US15 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

#### 3.4.4 Visualizar produto

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US16 |
| **Título** | Visualizar os detalhes de um produto pelo aplicativo |
| **História** | Eu como usuário, gostaria de visualizar os detalhes de um produto oferecido, para que possa verificar se necessito do mesmo. |
| **Critérios de aceitação** | - O usuário deve ter acesso à uma descrição fiel do produto (conteúdo, peso, quantidade, recomendações de uso, etc.)<br> - O usuário deve poder visualizar o preço e a imagem do produto<br>- O usuário deve poder adicionar a quantidade que desejar de um produto ao carrinho |
| **Rastreabilidade** | [RF04](../../elicitacao/resultadoElicitacao.md#RF04), [RF09](../../elicitacao/resultadoElicitacao.md#RF09), [RF18](../../elicitacao/resultadoElicitacao.md#RF18), [R25] |

<h6 align = "center"> Tabela 17: História de usuário US16 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

#### 3.4.5 Sugestão de produtos

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US17 |
| **Título** | Receber sugestão de produtos pelo aplicativo |
| **História** | Eu como usuário autenticado, gostaria de receber sugestões de produtos, para que possa encontrar produtos desejados rapidamente. |
| **Critérios de aceitação** | - O usuário deve marcar se deseja sugestões personalizadas de produtos no cadastro<br>- As sugestões de produtos devem aparecer na página inicial do aplicativo e nos resultados da pesquisa |
| **Rastreabilidade** | [RF32](../../elicitacao/resultadoElicitacao.md#RF32) |

<h6 align = "center"> Tabela 18: História de usuário US17 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

### 3.5 _Features_ de informação e configuração

#### 3.5.1 Recuperar conta

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US18 |
| **Título** | Recuperar conta cadastrada através do email |
| **História** | Eu como usuário cadastrado, gostaria de recuperar minha conta, para que recupere meu acesso ao aplicativo. |
| **Critérios de aceitação** | - O usuário deve poder recuperar a conta via SMS ou via email<br>- O usuário deve receber um link de redefinição |
| **Rastreabilidade** | [RF21](../../elicitacao/resultadoElicitacao.md#RF21) |

<h6 align = "center"> Tabela 19: História de usuário US18 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

#### 3.5.2 Reportar erros

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US19 |
| **Título** | Reportar erros e falhas pelo aplicativo |
| **História** | Eu como usuário, gostaria de reportar falhas do aplicativo, para que o mesmo possa ser melhorado. |
| **Critérios de aceitação** | - O reporte de erros deve ser automático quando possível<br>- O reporte de erros deve estar disponível próximo à outras funções importantes do aplicativo<br>- A função de reportar erro deve ter campos para o tipo de erro, a descrição do erro e para o código de erro (opcional)<br>- O usuário deve ter acesso, via o reporte de erro, a um SAC |
| **Rastreabilidade** | [RF30](../../elicitacao/resultadoElicitacao.md#RF30) |

<h6 align = "center"> Tabela 20: História de usuário US19 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

#### 3.5.3 Obter informações sobre animais

| Elemento | Conteúdo |
| ------ | ---- |
| **Código** | US20 |
| **Título** | Obter informações sobre _pets_ pelo aplicativo |
| **História** | Eu como usuário, gostaria de receber informações acerca de animais de estimação, para que possa obter maior conhecimento. |
| **Critérios de aceitação** | - O usuário deve poder acessar uma seção de informações a partir do menu principal<br>- O usuário deve poder optar por receber uma newsletter de informações relacionadas a seus pets cadastrados no cadastro de usuário e no cadastro de pets<br>- A seção de informações deve conter informações gerais sobre pets e informações específcias em uma seção de postagens |
| **Rastreabilidade** | [RF34](../../elicitacao/resultadoElicitacao.md#RF34), [RF36](../../elicitacao/resultadoElicitacao.md#RF36), [RF39](../../elicitacao/resultadoElicitacao.md#RF39), [RF40](../../elicitacao/resultadoElicitacao.md#RF40) |

<h6 align = "center"> Tabela 21: História de usuário US20 </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

## 4. Processo de validação

A validação e definição de critérios de aceitação com um _Product Owner_ (abreviado para PO) foi realizada a fim de garantir que as histórias de usuário representavam os requisitos elicitados e para definir critérios de aceitação para cada história que devem ser satisfeitos pelas funções a serem desenvolvidas para o aplicativo.

A PO definida para esta validação foi Luana Bartoco, que possui perfil similar ao definido no artefato de [perfil de usuário](./../../elicitacao/perfil.md). A validação ocorreu no dia 24/05/2023 a partir das 16:00 via [Google Meet](https://meet.google.com/) e foi gravada com o auxílio do [OBS Studio](https://obsproject.com). A participante também assinou termo de consentimento disponível via Google Docs. O termo de consentimento está transcrito abaixo.

<center>

TERMO DE CONSENTIMENTO

Somos o grupo 07 da turma 02 da disciplina de Requisitos de Software do professor André Barros de Sales ministrada no campus do Gama da Universidade de Brasília - UnB. Estamos em uma etapa do desenvolvimento do projeto em que desejamos definir maneiras de validar a execução de requisitos de software.

Para a realização desta pesquisa, solicitamos o seu consentimento para a realização de uma reunião online via Google Meet. Para isso, é necessário que saiba das seguintes informações:

* Os critérios de aceitação extraídos durante a reunião destinam-se estritamente a atividades de análise do aplicativo Petz.
* Nossa equipe tem o compromisso de divulgar os resultados da pesquisa para o professor e os alunos da disciplina de requisitos de software, bem como em página de documentação, disponível em <https://requisitos-de-software.github.io/2023.1-Petz>.
* A reunião será gravada e disponibilizada pelo YouTube como vídeo não listado, que será acessível pelo site supracitado.
* O consentimento para a atividade é uma escolha livre, feita mediante a prestação de todos os esclarecimentos necessários sobre a pesquisa.
* A reunião pode ser interrompida a qualquer momento, segundo a sua disponibilidade e vontade.
* A equipe encontra-se disponível para contato através do e-mail <211029263@aluno.unb.br>.

De posse dessas informações, gostaríamos que você se pronunciasse acerca da reunião:

( ) Dou meu consentimento para a sua realização.
( ) Não consinto com a sua realização.

Gama, Distrito Federal. 28 de abril de 2023.

Assinatura do monitor da reunião

FELIPE MASTROMAURO CORRÊA

Assinatura do participante

(Apagar e substituir esta linha por assinatura de nome completo na fonte Century Schoolbook, em tamanho 12, em negrito, itálico e sublinhado via Google Docs).

</center>

O vídeo 1 diz respeito à gravação da reunião com a PO, disponível no YouTube como vídeo não listado.

<center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/z2V1XWpXB5o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

</center>

<h6 align = "center"> Vídeo 1: Gravação da reunião de validação </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

## 5. Referências Bibliográficas

> [1] Resultados da priorização de requisitos, acesso em 22 de maio de 2023. Para mais informações acesse: [link](../../elicitacao/resultadoPriorizacao.md).

> [2] REINEHR, Sheila. Engenharia de Requisitos. Porto Alegre: Sagah, 2020.

## 6. Histórico de versão

| Versão | Data     | Descrição                                     | Autor(es)   | Revisor(es)   |
| ------ | -------- | --------------------------------------------- | ----------- | ------------- |
| `1.0`  | 22/05/23 | Criação da página de histórias de usuário | Pedro Muniz | Samuel Sato |
| `1.1`  | 24/05/23 | Validação de histórias de usuário | Felipe Corrêa |Lucas Cardoso|