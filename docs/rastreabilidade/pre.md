# Backward from

## 1. Introdução
Este documento tem como objetivo a sumarização das origens dos requisitos elicitados pela equipe durante o desenvolvimento do projeto. Fazendo assim com que um leitor possa se orientar na navegação pelo projeto, possuindo para isso hiperlinks para os artefatos e requisitos referenciados.

## 2. Metodologia
Além das origens dos requisitos listados, para a representação das rastreabilidades será utilizado o meta modelo proposto por Toranzo, o qual divide os elos de rastreabilidade em 4 categorias[1], sendo estas:

- **Ambiental:** Informações relacionadas ao contexto ambiental onde a organização está inserida e como este afeta o sistema.
- **Organizacional:** Informaçõs acerca da organização que possam afetar os requisitos do sistema.
- **Gerencial:** Informações que associam requisitos elicitados à tarefas de sistema.
- **Desenvolvimento:** Informações relacionadas aos artefatos gerados durante o desenvolvimento do projeto.

Além das categorias, Toranzo também define os elos em 6 tipos:

- **Satisfação:** A classe de origem tem dependência de satisfação com a classe de destino.
- **Recurso:** A classe de origem tem dependência de recurso com a classe de destino.
- **Responsabilidade:** Registra a participação, responsabilidade e ação de pessoas sobre artefatos.
- **Representação:** Captura a representação ou modelagem dos requisitos em outras linguagens.
- **Alocado:** Classe de origem está relacionada à classe de destino, que representa um subsistema.
- **Agregação:** Indica uma composição de elementos.

## 3. Poś Rastreabilidade

Para melhor visualização da tabela de listagem de requisitos, serão utilizadas abreviações para os diversos elementos presentes na tabela, na tabela 1 a seguir, estão listadas tais abreviações e seus significados.

| Elemento                | Representação |
|-------------------------|---------------|
| Épico                   | EPXX          |
| Requisito funcional     | RFXX          |
| Requisito não funcional | RNFXX         |
| Richpicture             | RPXX          |
| Richpicture final       | RPF           |
| Introspecção            | INT           |
| Questionário            | QST           |
| Brainstorming           | BSM           |
| Storytelling            | STL           |
| Cenário                 | CXX           |
| Léxico                  | LXX           |
| Caso de uso             | UCXX          |
| História de usuário     | USXX          |
| NFR Framework           | NFRXX         |
| Elo funcional           | EFXX          |
| Elo não funcional       | ENFXX         |

<h6 align = "center"> Tabela 1: Legenda de abreviações para a tabela de rastreabilidade. </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

Na tabela 2 a seguir, estão listados os requisitos elicitados, assim como seus elementos de rastreabilidade.

| Épico | ID | Descrição | Richpicture | Técnicas de elicitação | Cenários | Léxicos | Casos de uso | Histórias de usuário | NFR | Elo |
|--|--|--|--|--|--|--|--|--|--|--|
| [EP01](../modelagem/agil/backlog.md#EP01) | [RF01](../elicitacao/resultadoElicitacao.md#RF01) | O usuário deve ser capaz de se cadastrar na aplicação. | [RP01](../pre-rastreabilidade/richpicture.md#RP01) | [INT](../elicitacao/introspeccao.md), [QST](../elicitacao/questionario.md) | - | [L01](../modelagem/lexico.md#L01) | [UC01](../modelagem/casos_de_uso.md#UC01) | [US01](../modelagem/agil/userStories.md#US01) | - | [EF01](#EF01) |
| [EP01](../modelagem/agil/backlog.md#EP01) | [RF02](../elicitacao/resultadoElicitacao.md#RF02) | O usuário deve ser capaz de entrar em sua conta cadastrada. | [RP01](../pre-rastreabilidade/richpicture.md#RP01) | [INT](../elicitacao/introspeccao.md) | - | [L01](../modelagem/lexico.md#L01) | [UC02](../modelagem/casos_de_uso.md#UC02) | [US02](../modelagem/agil/userStories.md#US02) | - | [EF02](#EF02) |
| [EP01](../modelagem/agil/backlog.md#EP01) | [RF15](../elicitacao/resultadoElicitacao.md#RF15) | O usuário deve ser capaz de cadastrar um perfil para o Pet. | - | [INT](../elicitacao/introspeccao.md), [QST](../elicitacao/questionario.md), [BSM](../elicitacao/brainstorming.md) | [C02](../modelagem/cenarios.md#C02) | [L01](../modelagem/lexico.md#L01), [L02](../modelagem/lexico.md#L02), [L03](../modelagem/lexico.md#L03) | - | [US03](../modelagem/agil/userStories.md#US03) | - | [EF03](#EF03) |
| [EP01](../modelagem/agil/backlog.md#EP01) | [RF29](../elicitacao/resultadoElicitacao.md#RF29) | O usuário deve ser capaz de cadastrar mais de um animal de estimação na aplicação. | - | [QST](../elicitacao/questionario.md) | - | [L01](../modelagem/lexico.md#L01), [L02](../modelagem/lexico.md#L02) | - | [US03](../modelagem/agil/userStories.md#US03) | - | [EF04](#EF04) |
| [EP02](../modelagem/agil/backlog.md#EP02) | [RF13](../elicitacao/resultadoElicitacao.md#RF13) | O usuário deve ser capaz de realizar um pedido na loja. | [RP01](../pre-rastreabilidade/richpicture.md#RP01), [RP02](../pre-rastreabilidade/richpicture.md#RP02), [RPF](../pre-rastreabilidade/richpicture.md#RPF) | [INT](../elicitacao/introspeccao.md) | [C01](../modelagem/cenarios.md#C01) | [L01](../modelagem/lexico.md#L01), [L14](../modelagem/lexico.md#L14) | [UC03](../modelagem/casos_de_uso.md#UC03) | [US04](../modelagem/agil/userStories.md#US04) | - | [EF05](#EF05) |
| [EP02](../modelagem/agil/backlog.md#EP02) | [RF14](../elicitacao/resultadoElicitacao.md#RF14) | O usuário deve ser capaz de realizar uma compra na aplicação. | [RP01](../pre-rastreabilidade/richpicture.md#RP01), [RP02](../pre-rastreabilidade/richpicture.md#RP02), [RPF](../pre-rastreabilidade/richpicture.md#RPF) | [INT](../elicitacao/introspeccao.md), [QST](../elicitacao/questionario.md), [BSM](../elicitacao/brainstorming.md) | [C01](../modelagem/cenarios.md#C01) | [L01](../modelagem/lexico.md#L01) | [UC03](../modelagem/casos_de_uso.md#UC03) | [US04](../modelagem/agil/userStories.md#US04) | - | [EF06](#EF06) |
| [EP02](../modelagem/agil/backlog.md#EP02) | [RF22](../elicitacao/resultadoElicitacao.md#RF22) | O usuário deve ser capaz de cancelar um pedido. | [RP02](../pre-rastreabilidade/richpicture.md#RP02) | [INT](../elicitacao/introspeccao.md) | [C05](../modelagem/cenarios.md#C05) | [L01](../modelagem/lexico.md#L01) | - | [US05](../modelagem/agil/userStories.md#US05) | - | [EF07](#EF07) |
| [EP02](../modelagem/agil/backlog.md#EP02) | [RF11](../elicitacao/resultadoElicitacao.md#RF11) | O usuário deve ser capaz de acompanhar a situação do pedido. | - | [INT](../elicitacao/introspeccao.md) | - | [L01](../modelagem/lexico.md#L01), [L16](../modelagem/lexico.md#L16) | [UC05](../modelagem/casos_de_uso.md#UC05) | [US08](../modelagem/agil/userStories.md#US08) | - | [EF08](#EF08) |
| [EP02](../modelagem/agil/backlog.md#EP02) | [RF12](../elicitacao/resultadoElicitacao.md#RF12) | O usuário deve ser capaz de adicionar uma opção de pagamento. | [RPF](../pre-rastreabilidade/richpicture.md#RPF) | [INT](../elicitacao/introspeccao.md) | - | [L01](../modelagem/lexico.md#L01) | [UC04](../modelagem/casos_de_uso.md#UC04) | [US08](../modelagem/agil/userStories.md#US08) | - | [EF09](#EF09) |
| [EP02](../modelagem/agil/backlog.md#EP02) | [RF23](../elicitacao/resultadoElicitacao.md#RF23) | O usuário deve ser capaz de escolher como receber um produto. | - | [INT](../elicitacao/introspeccao.md), [STL](../elicitacao/Storytelling.md) | - | [L01](../modelagem/lexico.md#L01), [L06](../modelagem/lexico.md#L06) | [UC03](../modelagem/casos_de_uso.md#UC03), [UC04](../modelagem/casos_de_uso.md#UC04) | [US08](../modelagem/agil/userStories.md#US08) | - | [EF10](#EF10) |
| [EP02](../modelagem/agil/backlog.md#EP02) | [RF35](../elicitacao/resultadoElicitacao.md#RF35) | O usuário deve ser capaz de alterar local de entrega do produto. | - | [QST](../elicitacao/questionario.md) | - | [L01](../modelagem/lexico.md#L01), [L13](../modelagem/lexico.md#L13) | - | [US08](../modelagem/agil/userStories.md#US08) | - | [EF11](#EF11) |
| [EP02](../modelagem/agil/backlog.md#EP02) | [RF06](../elicitacao/resultadoElicitacao.md#RF06) | O usuário deve ser capaz de repetir um pedido anterior. | - | [INT](../elicitacao/introspeccao.md) | [C07](../modelagem/cenarios.md#C07) | [L01](../modelagem/lexico.md#L01), [L21](../modelagem/lexico.md#L21) | - | [US06](../modelagem/agil/userStories.md#US06) | - | [EF12](#EF12) |
| [EP02](../modelagem/agil/backlog.md#EP02) | [RF20](../elicitacao/resultadoElicitacao.md#RF20) | O usuário deve ser capaz de assinar um serviço. | - | [INT](../elicitacao/introspeccao.md), [BSM](../elicitacao/brainstorming.md) | - | [L01](../modelagem/lexico.md#L01), [L07](../modelagem/lexico.md#L07) | - | [US07](../modelagem/agil/userStories.md#US07) | - | [EF13](#EF13) |
| [EP02](../modelagem/agil/backlog.md#EP02) | [RF24](../elicitacao/resultadoElicitacao.md#RF24) | O usuário deve ser capaz de registrar uma lista de compras frequentes. | - | [BSM](../elicitacao/brainstorming.md), [STL](../elicitacao/Storytelling.md), [QST](../elicitacao/questionario.md) | [C07](../modelagem/cenarios.md#C07) | [L01](../modelagem/lexico.md#L01), [L22](../modelagem/lexico.md#L22) | - | [US07](../modelagem/agil/userStories.md#US07) | - | [EF14](#EF14) |
| [EP02](../modelagem/agil/backlog.md#EP02) | [RF33](../elicitacao/resultadoElicitacao.md#RF33) | O usuário deve ser capaz de assinar pacotes periódicos de produtos pelo aplicativo. | - | [BSM](../elicitacao/brainstorming.md) | - | [L01](../modelagem/lexico.md#L01), [L06](../modelagem/lexico.md#L06), [L07](../modelagem/lexico.md#L07), [L22](../modelagem/lexico.md#L22) | - | [US07](../modelagem/agil/userStories.md#US07) | - | [EF15](#EF15) |
| [EP02](../modelagem/agil/backlog.md#EP02) | [RF42](../elicitacao/resultadoElicitacao.md#RF42) | O usuário deve ser capaz de se cadastrar em um sistema de fidelidade pelo aplicativo. | - | [BSM](../elicitacao/brainstorming.md) | - | [L01](../modelagem/lexico.md#L01), [L07](../modelagem/lexico.md#L07) | - | [US07](../modelagem/agil/userStories.md#US07) | - | [EF16](#EF16) |
| [EP03](../modelagem/agil/backlog.md#EP03) | [RF19](../elicitacao/resultadoElicitacao.md#RF19) | O usuário deve ser capaz de agendar um serviço de banho e tosa. | [RP02](../pre-rastreabilidade/richpicture.md#RP02), [RPF](../pre-rastreabilidade/richpicture.md#RPF) | [INT](../elicitacao/introspeccao.md), [QST](../elicitacao/questionario.md), [BSM](../elicitacao/brainstorming.md), [STL](../elicitacao/Storytelling.md) | [C03](../modelagem/cenarios.md#C03) | [L01](../modelagem/lexico.md#L01), [L18](../modelagem/lexico.md#L18), [L19](../modelagem/lexico.md#L19) | - | [US09](../modelagem/agil/userStories.md#US09) | - | [EF17](#EF17) |
| [EP03](../modelagem/agil/backlog.md#EP03) | [RF38](../elicitacao/resultadoElicitacao.md#RF38) | O usuário deve ser capaz de marcar consultas veterinárias. | - | [BSM](../elicitacao/brainstorming.md) | [C11](../modelagem/cenarios.md#C11), [C12](../modelagem/cenarios.md#C11) | [L01](../modelagem/lexico.md#L01) | - | [US10](../modelagem/agil/userStories.md#US10) | - | [EF18](#EF18) |
| [EP03](../modelagem/agil/backlog.md#EP03) | [RF41](../elicitacao/resultadoElicitacao.md#RF41) | O sistema deve notificar o usuário acerca de pendências médicas dos seus pets. | - | [BSM](../elicitacao/brainstorming.md) | - |  [L17](../modelagem/lexico.md#L17)  | - | [US10](../modelagem/agil/userStories.md#US10) | - | [EF19](#EF19) |
| [EP03](../modelagem/agil/backlog.md#EP03) | [RF43](../elicitacao/resultadoElicitacao.md#RF43) | O sistema deve fornecer ao usuário serviços de hotelaria para animais. | - | [BSM](../elicitacao/brainstorming.md) | [C13](../modelagem/cenarios.md#C13) | - | - | [US11](../modelagem/agil/userStories.md#US11) | - | [EF20](#EF20) |
| [EP03](../modelagem/agil/backlog.md#EP03) | [RF37](../elicitacao/resultadoElicitacao.md#RF37) | O usuário deve ser capaz de solicitar transporte para o animal até a loja física. | - | [BSM](../elicitacao/brainstorming.md) | [C11](../modelagem/cenarios.md#C11) | - | - | [US12](../modelagem/agil/userStories.md#US12) | - | [EF21](#EF21) |
| [EP04](../modelagem/agil/backlog.md#EP04) | [RF03](../elicitacao/resultadoElicitacao.md#RF03) | O usuário deve ser capaz de visualizar catálogo online de produtos para animais de estimação. | [RP02](../pre-rastreabilidade/richpicture.md#RP02), [RPF](../pre-rastreabilidade/richpicture.md#RPF) | [STL](../elicitacao/Storytelling.md) | - | [L01](../modelagem/lexico.md#L01), [L06](../modelagem/lexico.md#L06) | - | [US13](../modelagem/agil/userStories.md#US13) | - | [EF22](#EF22) |
| [EP04](../modelagem/agil/backlog.md#EP04) | [RF04](../elicitacao/resultadoElicitacao.md#RF04) | O usuário deve ser capaz de visualizar itens de produtos e serviços. | [RP02](../pre-rastreabilidade/richpicture.md#RP02), [RPF](../pre-rastreabilidade/richpicture.md#RPF) | [INT](../elicitacao/introspeccao.md) | - | [L01](../modelagem/lexico.md#L01), [L06](../modelagem/lexico.md#L06) | [UC03](../modelagem/casos_de_uso.md#UC03) | [US13](../modelagem/agil/userStories.md#US13) | - | [EF23](#EF23) |
| [EP04](../modelagem/agil/backlog.md#EP04) | [RF17](../elicitacao/resultadoElicitacao.md#RF17) | O usuário deve ser capaz de favoritar itens. | - | [INT](../elicitacao/introspeccao.md) | - | [L01](../modelagem/lexico.md#L01) | - | [US14](../modelagem/agil/userStories.md#US14) | - | [EF24](#EF24) |
| [EP04](../modelagem/agil/backlog.md#EP04) | [RF28](../elicitacao/resultadoElicitacao.md#RF28) | O usuário deve ser capaz de filtrar produtos por categoria. | - | [QST](../elicitacao/questionario.md), [STL](../elicitacao/Storytelling.md) | - | [L01](../modelagem/lexico.md#L01), [L06](../modelagem/lexico.md#L06), [L10](../modelagem/lexico.md#L10) | - | [US14](../modelagem/agil/userStories.md#US14) | - | [EF25](#EF25) |
| [EP04](../modelagem/agil/backlog.md#EP04) | [RF31](../elicitacao/resultadoElicitacao.md#RF31) | O sistema deve possuir filtros e classificação por categorias para os produtos. | - | [BSM](../elicitacao/brainstorming.md) | - | [L06](../modelagem/lexico.md#L06), [L10](../modelagem/lexico.md#L10) | - | [US14](../modelagem/agil/userStories.md#US14) | - | [EF26](#EF26) |
| [EP04](../modelagem/agil/backlog.md#EP04) | [RF07](../elicitacao/resultadoElicitacao.md#RF07) | O usuário deve ser capaz de pesquisar produtos. | [RP02](../pre-rastreabilidade/richpicture.md#RP02), [RPF](../pre-rastreabilidade/richpicture.md#RPF) | [INT](../elicitacao/introspeccao.md), [QST](../elicitacao/questionario.md), [BSM](../elicitacao/brainstorming.md) | - | [L01](../modelagem/lexico.md#L01), [L06](../modelagem/lexico.md#L06) | - | [US15](../modelagem/agil/userStories.md#US15) | - | [EF27](#EF27) |
| [EP04](../modelagem/agil/backlog.md#EP04) | [RF08](../elicitacao/resultadoElicitacao.md#RF08) | O usuário deve ser capaz de pesquisar serviços. | [RP02](../pre-rastreabilidade/richpicture.md#RP02), [RPF](../pre-rastreabilidade/richpicture.md#RPF) | [INT](../elicitacao/introspeccao.md), [BSM](../elicitacao/brainstorming.md) | - | [L01](../modelagem/lexico.md#L01) | - | [US15](../modelagem/agil/userStories.md#US15) | - | [EF28](#EF28) |
| [EP04](../modelagem/agil/backlog.md#EP04) | [RF04](../elicitacao/resultadoElicitacao.md#RF04) | O usuário deve ser capaz de visualizar itens de produtos e serviços. | [RP02](../pre-rastreabilidade/richpicture.md#RP02), [RPF](../pre-rastreabilidade/richpicture.md#RPF) | [INT](../elicitacao/introspeccao.md) | - | [L01](../modelagem/lexico.md#L01), [L06](../modelagem/lexico.md#L06) | [UC03](../modelagem/casos_de_uso.md#UC03) | [US16](../modelagem/agil/userStories.md#US16) | - | [EF29](#EF29) |
| [EP04](../modelagem/agil/backlog.md#EP04) | [RF09](../elicitacao/resultadoElicitacao.md#RF09) | O usuário deve ser capaz de selecionar itens. | [RP02](../pre-rastreabilidade/richpicture.md#RP02), [RPF](../pre-rastreabilidade/richpicture.md#RPF) | [INT](../elicitacao/introspeccao.md) | - | [L01](../modelagem/lexico.md#L01) | [UC03](../modelagem/casos_de_uso.md#UC03) | [US16](../modelagem/agil/userStories.md#US16) | - | [EF30](#EF30) |
| [EP04](../modelagem/agil/backlog.md#EP04) | [RF18](../elicitacao/resultadoElicitacao.md#RF18) | O usuário deve ser capaz de visualizar o preço de itens. | [RP02](../pre-rastreabilidade/richpicture.md#RP02), [RPF](../pre-rastreabilidade/richpicture.md#RPF) | [INT](../elicitacao/introspeccao.md), [QST](../elicitacao/questionario.md) | [C04](../modelagem/cenarios.md#C04) | [L01](../modelagem/lexico.md#L01), [L06](../modelagem/lexico.md#L06) | [UC03](../modelagem/casos_de_uso.md#UC03) | [US16](../modelagem/agil/userStories.md#US16) | - | [EF31](#EF31) |
| [EP04](../modelagem/agil/backlog.md#EP04) | [RF25](../elicitacao/resultadoElicitacao.md#RF25) | O usuário deve ser capaz de acessar a avaliação e recomendações de um produto. | - | [BSM](../elicitacao/brainstorming.md) | - | [L01](../modelagem/lexico.md#L01), [L06](../modelagem/lexico.md#L06) | - | [US16](../modelagem/agil/userStories.md#US16) | - | [EF32](#EF32) |
| [EP04](../modelagem/agil/backlog.md#EP04) | [RF32](../elicitacao/resultadoElicitacao.md#RF32) | O sistema deve realizar a sugestão de produtos a partir de um perfil. | - | [BSM](../elicitacao/brainstorming.md) | - | [L06](../modelagem/lexico.md#L06), [L03](../modelagem/lexico.md#L03) | - | [US17](../modelagem/agil/userStories.md#US17) | - | [EF33](#EF33) |
| [EP05](../modelagem/agil/backlog.md#EP05) | [RF21](../elicitacao/resultadoElicitacao.md#RF21) | O usuário deve ser capaz de recuperar sua conta através do endereço de email cadastrado. | - | [INT](../elicitacao/introspeccao.md) | - | [L01](../modelagem/lexico.md#L01) | - | [US18](../modelagem/agil/userStories.md#US18) | - | [EF34](#EF34) |
| [EP05](../modelagem/agil/backlog.md#EP05) | [RF30](../elicitacao/resultadoElicitacao.md#RF30) | O usuário deve ser capaz de reportar falhas e erros. | - | [QST](../elicitacao/questionario.md) | [C09](../modelagem/cenarios.md#C09) | [L01](../modelagem/lexico.md#L01), [L22](../modelagem/lexico.md#L22) | - | [US19](../modelagem/agil/userStories.md#US19) | - | [EF35](#EF35) |
| [EP05](../modelagem/agil/backlog.md#EP05) | [RF34](../elicitacao/resultadoElicitacao.md#RF34) | O usuário deve ser capaz de obter informações sobre cuidados de animais. | - | [STL](../elicitacao/Storytelling.md) | - | [L01](../modelagem/lexico.md#L01) | - | [US20](../modelagem/agil/userStories.md#US20) | - | [EF36](#EF36) |
| [EP05](../modelagem/agil/backlog.md#EP05) | [RF36](../elicitacao/resultadoElicitacao.md#RF36) | O usuário deve ser capaz de acessar um blog com dicas sobre pets. | - | [BSM](../elicitacao/brainstorming.md) | [C10](../modelagem/cenarios.md#C10) | [L01](../modelagem/lexico.md#L01) | - | [US20](../modelagem/agil/userStories.md#US20) | - | [EF37](#EF37) |
| [EP05](../modelagem/agil/backlog.md#EP05) | [RF39](../elicitacao/resultadoElicitacao.md#RF39) | O usuário deve ser capaz de acessar uma tela com eventos próximos relacionados a pets. | - | [BSM](../elicitacao/brainstorming.md) | - | [L01](../modelagem/lexico.md#L01) | - | [US20](../modelagem/agil/userStories.md#US20) | - | [EF38](#EF38) |
| [EP05](../modelagem/agil/backlog.md#EP05) | [RF40](../elicitacao/resultadoElicitacao.md#RF40) | O usuário deve ser capaz de acessar uma tela com posts da comunidade. | - | [BSM](../elicitacao/brainstorming.md), [STL](../elicitacao/Storytelling.md) | [C10](../modelagem/cenarios.md#C10) | [L01](../modelagem/lexico.md#L01) | - | [US20](../modelagem/agil/userStories.md#US20) | - | [EF39](#EF39) |
| - | [RNF01](../elicitacao/resultadoElicitacao.md#RNF01) | O sistema deve ser manter seguro as informações do usuário criptografando dados sensíveis. | - | [INT](../elicitacao/introspeccao.md), [STL](../elicitacao/Storytelling.md) | - | - | - | - | [NFR02](../modelagem/NFRframework.md#NFR02) | [ENF01](#ENF01) |
| - | [RNF02](../elicitacao/resultadoElicitacao.md#RNF02) | O sistema deve estar disponível para os sistemas Android e iOS. | - | [INT](../elicitacao/introspeccao.md), [STL](../elicitacao/Storytelling.md) | - | - | - | - | [NFR04](../modelagem/NFRframework.md#NFR04) | [ENF02](#ENF02) |
| - | [RNF03](../elicitacao/resultadoElicitacao.md#RNF03) | O sistema deve ser responsivo. | - | [INT](../elicitacao/introspeccao.md), [STL](../elicitacao/Storytelling.md) | - | - | - | - | [NFR01](../modelagem/NFRframework.md#NFR01) | [ENF03](#ENF03) |
| - | [RNF04](../elicitacao/resultadoElicitacao.md#RNF04) | O sistema deve ter um sistema de busca [efic](#efic)iente. | - | [INT](../elicitacao/introspeccao.md), [STL](../elicitacao/Storytelling.md) | - | - | - | - | [NFR03](../modelagem/NFRframework.md#NFR03) | [ENF04](#ENF04) |
| - | [RNF05](../elicitacao/resultadoElicitacao.md#RNF05) | O sistema deve ser confiável e disponível. | - | [INT](../elicitacao/introspeccao.md), [STL](../elicitacao/Storytelling.md) | - | - | - | - | [NFR02](../modelagem/NFRframework.md#NFR02) | [ENF05](#ENF05) |

<h6 align = "center"> Tabela 2: Rastreabilidade dos requisitos elicitados </h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

## 4. Elos

Abaixo estão listados os elos originados dos requisitos, assim como suas características.


### 4.1 Elos funcionais

<div id="EF01"></div>

#### 4.1.1 EF01

**Categoria**: Desenvolvimento

**Requisito**: [RF01](../elicitacao/resultadoElicitacao.md#RF01)

**Elementos Rastreáveis**: 

* [RP01](../pre-rastreabilidade/richpicture.md#RP01)
* [L01](../modelagem/lexico.md#L01)
* [INT](../elicitacao/introspeccao.md) 
* [QST](../elicitacao/questionario.md)
* [UC01](../modelagem/casos_de_uso.md#UC01)
* [US01](../modelagem/agil/userStories.md#US01)

**Elos**:

* Representação: [UC01](../modelagem/casos_de_uso.md#UC01) representa [US01](../modelagem/agil/userStories.md#US01)
* Recurso: [UC01](../modelagem/casos_de_uso.md#UC01) depende de recursos de [INT](../elicitacao/introspeccao.md) e [QST](../elicitacao/questionario.md)
* Agregação: [UC01] agrega [RP01](../pre-rastreabilidade/richpicture.md#RP01) e [L01](../modelagem/lexico.md#L01)


<div id="EF02"></div>

#### 4.1.2 EF02

**Categoria**: Desenvolvimento

**Requisito**: [RF02](../elicitacao/resultadoElicitacao.md#RF02)

**Elementos Rastreáveis**: 

* [RP01](../pre-rastreabilidade/richpicture.md#RP01)
* [L01](../modelagem/lexico.md#L01)
* [INT](../elicitacao/introspeccao.md) 
* [UC02](../modelagem/casos_de_uso.md#UC02)
* [US02](../modelagem/agil/userStories.md#US02)

**Elos**: 

* Representação: [UC02](../modelagem/casos_de_uso.md#UC02) representa [US02](../modelagem/agil/userStories.md#US02) e [L01](../modelagem/lexico.md#L01)
* Recurso: [UC02](../modelagem/casos_de_uso.md#UC02) depende de recursos de [INT](../elicitacao/introspeccao.md) 
* Agregação: [UC02](../modelagem/casos_de_uso.md#UC02) agrega [L01](../modelagem/lexico.md#L01)
* Recurso: [US02](../modelagem/agil/userStories.md#US02) depende de recursos de [INT](../elicitacao/introspeccao.md) 

<div id="EF03"></div>

#### 4.1.3 EF03

**Categoria**: Desenvolvimento

**Requisito**: [RF15](../elicitacao/resultadoElicitacao.md#RF15)

**Elementos Rastreáveis**: 

* [INT](../elicitacao/introspeccao.md)
* [QST](../elicitacao/questionario.md)
* [BSM](../elicitacao/brainstorming.md) 
* [C02](../modelagem/cenarios.md#C02)
* [L01](../modelagem/lexico.md#L01)
* [L02](../modelagem/lexico.md#L02)
* [L03](../modelagem/lexico.md#L03)
* [US03](../modelagem/agil/userStories.md#US03)

**Elos**:

* Agregação: [C02](../modelagem/cenarios.md#C02) agrega [L01](../modelagem/lexico.md#L01), [L02](../modelagem/lexico.md#L02) e [L03](../modelagem/lexico.md#L03)
* Agregação: [US03](../modelagem/agil/userStories.md#US03) agrega [L01](../modelagem/lexico.md#L01), [L02](../modelagem/lexico.md#L02) e [L03](../modelagem/lexico.md#L03)
* Representação: [US03](../modelagem/agil/userStories.md#US03) representa [INT](../elicitacao/introspeccao.md), [QST](../elicitacao/questionario.md) e [BSM](../elicitacao/brainstorming.md) 
* Representação: [C02](../modelagem/cenarios.md#C02) representa [INT](../elicitacao/introspeccao.md), [QST](../elicitacao/questionario.md) e [BSM](../elicitacao/brainstorming.md)
* Recursos: [US03](../modelagem/agil/userStories.md#US03) depende de recursos de [INT](../elicitacao/introspeccao.md), [QST](../elicitacao/questionario.md) e [BSM](../elicitacao/brainstorming.md)

<div id="EF04"></div>

#### 4.1.4 EF04

**Categoria**: Desenvolvimento

**Requisito**: [RF29](../elicitacao/resultadoElicitacao.md#RF29)

**Elementos Rastreáveis**:

* [QST](../elicitacao/questionario.md)
* [L01](../modelagem/lexico.md#L01)
* [L02](../modelagem/lexico.md#L02)
* [US03](../modelagem/agil/userStories.md#US03)

**Elos**: 

* Agregação: [US03](../modelagem/agil/userStories.md#US03) agrega [L01](../modelagem/lexico.md#L01), [L02](../modelagem/lexico.md#L02) e [L03](../modelagem/lexico.md#L03)
* Recursos: [US03](../modelagem/agil/userStories.md#US03) depende de recursos de [QST](../elicitacao/questionario.md)

<div id="EF05"></div>

#### 4.1.5 EF05

**Categoria**: Desenvolvimento

**Requisito**: [RF13](../elicitacao/resultadoElicitacao.md#RF13)

**Elementos Rastreáveis**:

* [RP01](../pre-rastreabilidade/richpicture.md#RP01)
* [RP02](../pre-rastreabilidade/richpicture.md#RP02)
* [RPF](../pre-rastreabilidade/richpicture.md#RPF)
* [INT](../elicitacao/introspeccao.md)
* [C01](../modelagem/cenarios.md#C01)
* [L01](../modelagem/lexico.md#L01)
* [L14](../modelagem/lexico.md#L14)
* [UC03](../modelagem/casos_de_uso.md#UC03)
* [US04](../modelagem/agil/userStories.md#US04)

**Elos**:

* Representação: [UC03](../modelagem/casos_de_uso.md#UC03) representa [US04](../modelagem/agil/userStories.md#US04), [L01](../modelagem/lexico.md#L01) e [L14](../modelagem/lexico.md#L14)
* Agregação: [RPF](../pre-rastreabilidade/richpicture.md#RPF) agrega [RP01](../pre-rastreabilidade/richpicture.md#RP01) e [RP02](../pre-rastreabilidade/richpicture.md#RP02)
* Representação: [US04](../modelagem/agil/userStories.md#US04) representa [INT](../elicitacao/introspeccao.md)
* Representação: [C01](../modelagem/cenarios.md#C01) representa [INT](../elicitacao/introspeccao.md)
* Recurso: [US04](../modelagem/agil/userStories.md#US04) depende de recursos de [INT](../elicitacao/introspeccao.md)
* Agregação: [US04](../modelagem/agil/userStories.md#US08) agrega [L01](../modelagem/lexico.md#L01) e [L14](../modelagem/lexico.md#L14)

<div id="EF06"></div>

#### 4.1.6 EF06

**Categoria**: Desenvolvimento

**Requisito**: [RF14](../elicitacao/resultadoElicitacao.md#RF14)

**Elementos Rastreáveis**:

* [RP01](../pre-rastreabilidade/richpicture.md#RP01)
* [RP02](../pre-rastreabilidade/richpicture.md#RP02)
* [RPF](../pre-rastreabilidade/richpicture.md#RPF)
* [INT](../elicitacao/introspeccao.md)
* [QST](../elicitacao/questionario.md)
* [BSM](../elicitacao/brainstorming.md)
* [C01](../modelagem/cenarios.md#C01)
* [L01](../modelagem/lexico.md#L01)
* [UC03](../modelagem/casos_de_uso.md#UC03)
* [US04](../modelagem/agil/userStories.md#US04)

**Elos**:

* Representação: [UC03](../modelagem/casos_de_uso.md#UC03) representa [US04](../modelagem/agil/userStories.md#US04) e [L01](../modelagem/lexico.md#L01)
* Agregação: [RPF](../pre-rastreabilidade/richpicture.md#RPF) agrega [RP01](../pre-rastreabilidade/richpicture.md#RP01) e [RP02](../pre-rastreabilidade/richpicture.md#RP02)
* Representação: [US04](../modelagem/agil/userStories.md#US04) representa [INT](../elicitacao/introspeccao.md), [QST](../elicitacao/questionario.md) e [BSM](../elicitacao/brainstorming.md)
* Representação: [C01](../modelagem/cenarios.md#C01) representa [INT](../elicitacao/introspeccao.md), [QST](../elicitacao/questionario.md) e [BSM](../elicitacao/brainstorming.md)
* Recursos: [US04](../modelagem/agil/userStories.md#US04) depende de recursos de [INT](../elicitacao/introspeccao.md), [QST](../elicitacao/questionario.md) e [BSM](../elicitacao/brainstorming.md)
* Agregação: [C01](../modelagem/cenarios.md#C01) agrega [L01](../modelagem/lexico.md#L01)
* Agregação: [US04](../modelagem/agil/userStories.md#US04) agrega [L01](../modelagem/lexico.md#L01)

<div id="EF07"></div>

#### 4.1.7 EF07

**Categoria**: Desenvolvimento

**Requisito**: [RF22](../elicitacao/resultadoElicitacao.md#RF22)

**Elementos Rastreáveis**:

* [RP02](../pre-rastreabilidade/richpicture.md#RP02)
* [INT](../elicitacao/introspeccao.md)
* [C05](../modelagem/cenarios.md#C05)
* [L01](../modelagem/lexico.md#L01)
* [US05](../modelagem/agil/userStories.md#US05)

**Elos**:

* Representação: [US05](../modelagem/agil/userStories.md#US05) representa [INT](../elicitacao/introspeccao.md)
* Recursos: [US05](../modelagem/agil/userStories.md#US05) depende de recursos de [INT](../elicitacao/introspeccao.md)
* Representação: [C05](../modelagem/cenarios.md#C05) representa [INT](../elicitacao/introspeccao.md)
* Agregação: [US05](../modelagem/agil/userStories.md#US05) agrega [C05](../modelagem/cenarios.md#C05),[L01](../modelagem/lexico.md#L01)  e [RP02](../pre-rastreabilidade/richpicture.md#RP02)

<div id="EF08"></div>

#### 4.1.8 EF08

**Categoria**: Desenvolvimento

**Requisito**: [RF11](../elicitacao/resultadoElicitacao.md#RF11)

**Elementos Rastreáveis**:

* [INT](../elicitacao/introspeccao.md)
* [L01](../modelagem/lexico.md#L01)
* [L16](../modelagem/lexico.md#L16)
* [UC05](../modelagem/casos_de_uso.md#UC05)
* [US08](../modelagem/agil/userStories.md#US08)

**Elos**:

* Representação: [US08](../modelagem/agil/userStories.md#US08) representa [INT](../elicitacao/introspeccao.md)
* Recursos: [US08](../modelagem/agil/userStories.md#US08) depende de recursos de [INT](../elicitacao/introspeccao.md)
* Representação: [UC05](../modelagem/casos_de_uso.md#UC05) representa [US08](../modelagem/agil/userStories.md#US08), [L01](../modelagem/lexico.md#L01) e [L16](../modelagem/lexico.md#L16)
* Agregação: [US08](../modelagem/agil/userStories.md#US08) agrega [L01](../modelagem/lexico.md#L01) e [L16](../modelagem/lexico.md#L16)

<div id="EF09"></div>

#### 4.1.9 EF09

**Categoria**: Desenvolvimento

**Requisito**: [RF12](../elicitacao/resultadoElicitacao.md#RF11)

**Elementos Rastreáveis**:

* [RPF](../pre-rastreabilidade/richpicture.md#RPF)
* [INT](../elicitacao/introspeccao.md)
* [L01](../modelagem/lexico.md#L01)
* [UC04](../modelagem/casos_de_uso.md#UC04)
* [US08](../modelagem/agil/userStories.md#US08)

**Elos**:

* Representação: [US08](../modelagem/agil/userStories.md#US08) representa [INT](../elicitacao/introspeccao.md)
* Recursos: [US08](../modelagem/agil/userStories.md#US08) depende de recursos de [INT](../elicitacao/introspeccao.md)
* Representação: [UC04](../modelagem/casos_de_uso.md#UC04) representa [US08](../modelagem/agil/userStories.md#US08), [L01](../modelagem/lexico.md#L01) e [L16](../modelagem/lexico.md#L16)
* Agregação: [US08](../modelagem/agil/userStories.md#US08) agrega [L01](../modelagem/lexico.md#L01) e [L16](../modelagem/lexico.md#L16)

<div id="EF10"></div>

#### 4.1.10 EF10

**Categoria**: Desenvolvimento

**Requisito**: [RF23](../elicitacao/resultadoElicitacao.md#RF23)

**Elementos Rastreáveis**:

* [INT](../elicitacao/introspeccao.md)
* [STL](../elicitacao/Storytelling.md)
* [L01](../modelagem/lexico.md#L01)
* [L06](../modelagem/lexico.md#L06)
* [UC03](../modelagem/casos_de_uso.md#UC03)
* [UC04](../modelagem/casos_de_uso.md#UC04)
* [US08](../modelagem/agil/userStories.md#US08)

**Elos**:

* Representação: [US08](../modelagem/agil/userStories.md#US08) representa [INT](../elicitacao/introspeccao.md) e [STL](../elicitacao/Storytelling.md)
* Recursos: Recursos: [US08](../modelagem/agil/userStories.md#US08) depende de recursos de [INT](../elicitacao/introspeccao.md) e [STL](../elicitacao/Storytelling.md)
* Representação: [UC03](../modelagem/casos_de_uso.md#UC03) e [UC04](../modelagem/casos_de_uso.md#UC04) representa [US08](../modelagem/agil/userStories.md#US08), [L01](../modelagem/lexico.md#L01) e [L06](../modelagem/lexico.md#L06)
* Agregação: [US08](../modelagem/agil/userStories.md#US08) agrega [L01](../modelagem/lexico.md#L01) e [L06](../modelagem/lexico.md#L06)


<div id="EF11"></div>

#### 4.1.11 EF11

**Categoria**: Desenvolvimento

**Requisito**: [RF35](../elicitacao/resultadoElicitacao.md#RF35)

**Elementos Rastreáveis**:

* [QST](../elicitacao/questionario.md)
* [L01](../modelagem/lexico.md#L01)
* [L13](../modelagem/lexico.md#L13)
* [US08](../modelagem/agil/userStories.md#US08)

**Elos**:

* Recursos: [US08](../modelagem/agil/userStories.md#US08) depende de recursos de [QST](../elicitacao/questionario.md)
* Agregação: [US08](../modelagem/agil/userStories.md#US08) agrega [L01](../modelagem/lexico.md#L01) e [L13](../modelagem/lexico.md#L13)

<div id="EF12"></div>

#### 4.1.12 EF12

**Categoria**: Desenvolvimento

**Requisito**: [RF06](../elicitacao/resultadoElicitacao.md#RF06)

**Elementos Rastreáveis**: 

* [INT](../elicitacao/introspeccao.md) 
* [C07](../modelagem/cenarios.md#C07)
* [L01](../modelagem/lexico.md#L01)
* [L21](../modelagem/lexico.md#L21)
* [US06](../modelagem/agil/userStories.md#US06)

**Elos**:

- Agregação: [US06](../modelagem/agil/userStories.md#US06) agrega [INT](../elicitacao/introspeccao.md), [C07](../modelagem/cenarios.md#C07), [L01](../modelagem/lexico.md#L01) e [L21](../modelagem/lexico.md#L21)
- Representação: [C07](../modelagem/cenarios.md#C07) representa [INT](../elicitacao/introspeccao.md)
- Recursos: [US06](../modelagem/agil/userStories.md#US06) depende de recursos de [INT](../elicitacao/introspeccao.md) 

<div id="EF13"></div>

#### 4.1.13 EF13

**Categoria**: Desenvolvimento

**Requisito**: [RF20](../elicitacao/resultadoElicitacao.md#RF20)

**Elementos Rastreáveis**:

* [INT](../elicitacao/introspeccao.md)
* [BSM](../elicitacao/brainstorming.md)
* [L01](../modelagem/lexico.md#L01)
* [L07](../modelagem/lexico.md#L07)
* [US07](../modelagem/agil/userStories.md#US07) 

**Elos**:

* Agregação: [US07](../modelagem/agil/userStories.md#US07) agrega [INT](../elicitacao/introspeccao.md), [BSM](../elicitacao/brainstorming.md), [L01](../modelagem/lexico.md#L01) e [L07](../modelagem/lexico.md#L07)
* Recursos: [US07](../modelagem/agil/userStories.md#US07) depende de recursos de [INT](../elicitacao/introspeccao.md) e [BSM](../elicitacao/brainstorming.md)

<div id="EF14"></div>

#### 4.1.14 EF14

**Categoria**: Desenvolvimento

**Requisito**: [RF24](../elicitacao/resultadoElicitacao.md#RF24)

**Elementos Rastreáveis**:

* [BSM](../elicitacao/brainstorming.md)
* [STL](../elicitacao/Storytelling.md)
* [QST](../elicitacao/questionario.md)
* [C07](../modelagem/cenarios.md#C07)
* [L01](../modelagem/lexico.md#L01)
* [L22](../modelagem/lexico.md#L22)
* [US07](../modelagem/agil/userStories.md#US07) 

**Elos**:

* Agregação: [US07](../modelagem/agil/userStories.md#US07) agrega [L01](../modelagem/lexico.md#L01), [L22](../modelagem/lexico.md#L22), [BSM](../elicitacao/brainstorming.md), [STL](../elicitacao/Storytelling.md) e [QST](../elicitacao/questionario.md)
* Representação: [C07](../modelagem/cenarios.md#C07) representa [BSM](../elicitacao/brainstorming.md), [STL](../elicitacao/Storytelling.md) e [QST](../elicitacao/questionario.md)
* Recurso: [C07](../modelagem/cenarios.md#C07) depende de recursos de  [BSM](../elicitacao/brainstorming.md), [STL](../elicitacao/Storytelling.md) e [QST](../elicitacao/questionario.md)

<div id="EF15"></div>

#### 4.1.15 EF15

**Categoria**: Desenvolvimento

**Requisito**: [RF33](../elicitacao/resultadoElicitacao.md#RF33)

**Elementos Rastreáveis**:

* [BSM](../elicitacao/brainstorming.md)
* [L01](../modelagem/lexico.md#L01)
* [L06](../modelagem/lexico.md#L06)
* [L07](../modelagem/lexico.md#L07)
* [L22](../modelagem/lexico.md#L22)
* [US07](../modelagem/agil/userStories.md#US07) 

**Elos**:

* Agregação: [US07](../modelagem/agil/userStories.md#US07) agrega [L01](../modelagem/lexico.md#L01), [L06](../modelagem/lexico.md#L06), [L07](../modelagem/lexico.md#L07), [L22](../modelagem/lexico.md#L22) e [BSM](../elicitacao/brainstorming.md)

<div id="EF16"></div>

#### 4.1.16 EF16

**Categoria**: Desenvolvimento

**Requisito**: [RF42](../elicitacao/resultadoElicitacao.md#RF42)

**Elementos Rastreáveis**:

* [BSM](../elicitacao/brainstorming.md)
* [L01](../modelagem/lexico.md#L01)
* [L07](../modelagem/lexico.md#L07)
* [US07](../modelagem/agil/userStories.md#US07) 

**Elos**:

* Agregação: [US07](../modelagem/agil/userStories.md#US07) agrega [L01](../modelagem/lexico.md#L01), [L07](../modelagem/lexico.md#L07) e [BSM](../elicitacao/brainstorming.md)

<div id="EF17"></div>

#### 4.1.17 EF17

**Categoria**: Desenvolvimento

**Requisito**: [RF19](../elicitacao/resultadoElicitacao.md#RF19)

**Elementos Rastreáveis**:

* [RP02](../pre-rastreabilidade/richpicture.md#RP02)
* [RPF](../pre-rastreabilidade/richpicture.md#RPF)
* [INT](../elicitacao/introspeccao.md)
* [BSM](../elicitacao/brainstorming.md)
* [STL](../elicitacao/Storytelling.md)
* [QST](../elicitacao/questionario.md)
* [C03](../modelagem/cenarios.md#C03)
* [L01](../modelagem/lexico.md#L01)
* [L18](../modelagem/lexico.md#L18)
* [L19](../modelagem/lexico.md#L19)
* [US09](../modelagem/agil/userStories.md#US09) 

**Elos**:

* Agregação: Agregação: [US09](../modelagem/agil/userStories.md#US09) agrega [L01](../modelagem/lexico.md#L01), [L01](../modelagem/lexico.md#L18), [L19](../modelagem/lexico.md#L19), [INT](../elicitacao/introspeccao.md), [BSM](../elicitacao/brainstorming.md), [STL](../elicitacao/Storytelling.md) e [QST](../elicitacao/questionario.md)
* Recursos: [US09](../modelagem/agil/userStories.md#US09) depende de recursos de [INT](../elicitacao/introspeccao.md), [BSM](../elicitacao/brainstorming.md), [STL](../elicitacao/Storytelling.md) e [QST](../elicitacao/questionario.md)
* Representação: [C03](../modelagem/cenarios.md#C03) representa [INT](../elicitacao/introspeccao.md), [BSM](../elicitacao/brainstorming.md), [STL](../elicitacao/Storytelling.md) e [QST](../elicitacao/questionario.md)

<div id="EF18"></div>

#### 4.1.18 EF18

**Categoria**: Desenvolvimento

**Requisito**: [RF38](../elicitacao/resultadoElicitacao.md#RF38)

**Elementos Rastreáveis**:

* [BSM](../elicitacao/brainstorming.md)
* [C11](../modelagem/cenarios.md#C11)
* [C12](../modelagem/cenarios.md#C12)
* [L01](../modelagem/lexico.md#L01)
* [US10](../modelagem/agil/userStories.md#US10) 

**Elos**:

* Recurso: [US10](../modelagem/agil/userStories.md#US10) depende de recursos de [BSM](../elicitacao/brainstorming.md)
* Agregação: [US10](../modelagem/agil/userStories.md#US10) agrega [L01](../modelagem/lexico.md#L01)
* Representação: [C11](../modelagem/cenarios.md#C11) e [C12](../modelagem/cenarios.md#C12)  representam [BSM](../elicitacao/brainstorming.md)

<div id="EF19"></div>

#### 4.1.19 EF19

**Categoria:** Desenvolvimento

**Requisito:** [RF41](../elicitacao/resultadoElicitacao.md#RF41)

**Elementos rastreáveis:**

- [BSM](../elicitacao/brainstorming.md)
- [L17](../modelagem/lexico.md#L17)
- [US12](../modelagem/agil/userStories.md#US10)

**Elos**:

* Agregação: [US12](../modelagem/agil/userStories.md#US10) agrega [L17](../modelagem/lexico.md#L17)
* Recurso: [US12](../modelagem/agil/userStories.md#US12) depende de recursos de [BSM](../elicitacao/brainstorming.md)


<div id="EF20"></div>

#### 4.1.20 EF20

**Categoria:** Desenvolvimento

**Requisito:** [RF43](../elicitacao/resultadoElicitacao.md#RF43)

**Elementos rastreáveis:**

- [BSM](../elicitacao/brainstorming.md)
- [C13](../modelagem/cenarios.md#C13)
- [US11](../modelagem/agil/userStories.md#US11)

**Elos:**

- Representação: [C13](../modelagem/cenarios.md#C13) representa [BSM](../elicitacao/brainstorming.md)
- Agregação: [US11](../modelagem/agil/userStories.md#US12) agrega [BSM](../elicitacao/brainstorming.md) e [C13](../modelagem/cenarios.md#C11)

<div id="EF21"></div>

#### 4.1.21 EF21

**Categoria:** Desenvolvimento

**Requisito:** [RF37](../elicitacao/resultadoElicitacao.md#RF37)

**Elementos rastreáveis:**

- [BSM](../elicitacao/brainstorming.md)
- [C11](../modelagem/cenarios.md#C11)
- [US12](../modelagem/agil/userStories.md#US12)

**Elos:**

- Representação: [C11](../modelagem/cenarios.md#C11) representa [BSM](../elicitacao/brainstorming.md)
- Agregação: [US12](../modelagem/agil/userStories.md#US12) agrega [BSM](../elicitacao/brainstorming.md) e [C11](../modelagem/cenarios.md#C11)

<div id="EF22"></div>

#### 4.1.22 EF22

**Categoria:** Desenvolvimento

**Requisito:** [RF03](../elicitacao/resultadoElicitacao.md#RF03)

**Elementos rastreáveis:**

- [RP02](../pre-rastreabilidade/richpicture.md#RP02)
- [RPF](../pre-rastreabilidade/richpicture.md#RPF)
- [STL](../elicitacao/Storytelling.md)
- [L01](../modelagem/lexico.md#L01)
- [L06](../modelagem/lexico.md#L06)
- [US13](../modelagem/agil/userStories.md#US13)

**Elos:**

- Representação: [RP02](../pre-rastreabilidade/richpicture.md#RP02) e [RPF](../pre-rastreabilidade/richpicture.md#RPF) representam [US13](../modelagem/agil/userStories.md#US13)
- Recurso: [US13](../modelagem/agil/userStories.md#US13) depende de recursos de [STL](../elicitacao/Storytelling.md)
- Agregação: [US13](../modelagem/agil/userStories.md#US13) agrega [L01](../modelagem/lexico.md#L01) e [L06](../modelagem/lexico.md#L06)

<div id="EF23"></div>

#### 4.1.23 EF23

**Categoria:** Desenvolvimento

**Requisito:** [RF04](../elicitacao/resultadoElicitacao.md#RF04)

**Elementos rastreáveis:**

- [RP02](../pre-rastreabilidade/richpicture.md#RP02)
- [RPF](../pre-rastreabilidade/richpicture.md#RPF)
- [INT](../elicitacao/introspeccao.md)
- [L01](../modelagem/lexico.md#L01)
- [L06](../modelagem/lexico.md#L06)
- [UC03](../modelagem/casos_de_uso.md#UC03)
- [US13](../modelagem/agil/userStories.md#US13)

**Elos:**

- Representação: [RP02](../pre-rastreabilidade/richpicture.md#RP02), [RPF](../pre-rastreabilidade/richpicture.md#RPF) e [UC03](../modelagem/casos_de_uso.md#UC03) representam [US13](../modelagem/agil/userStories.md#US13)
- Recurso: [UC03](../modelagem/casos_de_uso.md#UC03) depende de recursos de [INT](../elicitacao/introspeccao.md)
- Recurso: [US13](../modelagem/agil/userStories.md#US13) depende de recursos de [INT](../elicitacao/introspeccao.md)
- Agregação: [US13](../modelagem/agil/userStories.md#US13) agrega [L01](../modelagem/lexico.md#L01) e [L06](../modelagem/lexico.md#L06)

<div id="EF24"></div>

#### 4.1.24 EF24

**Categoria:** Desenvolvimento

**Requisito:** [RF17](../elicitacao/resultadoElicitacao.md#RF17)

**Elementos rastreáveis:**

- [INT](../elicitacao/introspeccao.md)
- [L01](../modelagem/lexico.md#L01)
- [US14](../modelagem/agil/userStories.md#US14)

**Elos:**

- Recurso: [US14](../modelagem/agil/userStories.md#US14) depende de recursos de [INT](../elicitacao/introspeccao.md)
- Agregação: [US14](../modelagem/agil/userStories.md#US14) agrega [L01](../modelagem/lexico.md#L01)

<div id="EF25"></div>

#### 4.1.25 EF25

**Categoria:** Desenvolvimento

**Requisito:** [RF28](../elicitacao/resultadoElicitacao.md#RF28)

**Elementos rastreáveis:**

- [QST](../elicitacao/questionario.md)
- [STL](../elicitacao/Storytelling.md)
- [L01](../modelagem/lexico.md#L01)
- [L06](../modelagem/lexico.md#L06)
- [L10](../modelagem/lexico.md#L10)
- [US14](../modelagem/agil/userStories.md#US14)

**Elos:**

- Recurso: [US14](../modelagem/agil/userStories.md#US14) depende de recursos de [QST](../elicitacao/questionario.md) e [STL](../elicitacao/Storytelling.md)
- Agregação: [US14](../modelagem/agil/userStories.md#US14) agrega [L01](../modelagem/lexico.md#L01), [L06](../modelagem/lexico.md#L06) e [L10](../modelagem/lexico.md#L10)

<div id="EF26"></div>

#### 4.1.26 EF26

**Categoria:** Desenvolvimento

**Requisito:** [RF31](../elicitacao/resultadoElicitacao.md#RF31)

**Elementos rastreáveis:**

- [BSM](../elicitacao/brainstorming.md)
- [L06](../modelagem/lexico.md#L06)
- [L10](../modelagem/lexico.md#L10)
- [US14](../modelagem/agil/userStories.md#US14)

**Elos:**

- Recurso: [US14](../modelagem/agil/userStories.md#US14) depende de recursos de [BSM](../elicitacao/brainstorming.md)
- Agregação: [US14](../modelagem/agil/userStories.md#US14) agrega [L06](../modelagem/lexico.md#L06) e [L10](../modelagem/lexico.md#L10)

<div id="EF27"></div>

#### 4.1.27 EF27

**Categoria:** Desenvolvimento

**Requisito:** [RF07](../elicitacao/resultadoElicitacao.md#RF07)

**Elementos rastreáveis:**

- [RP02](../pre-rastreabilidade/richpicture.md#RP02)
- [RPF](../pre-rastreabilidade/richpicture.md#RPF)
- [INT](../elicitacao/introspeccao.md)
- [QST](../elicitacao/questionario.md)
- [BSM](../elicitacao/brainstorming.md)
- [L01](../modelagem/lexico.md#L01)
- [L06](../modelagem/lexico.md#L06)
- [US15](../modelagem/agil/userStories.md#US15)

**Elos:**

- Recurso: [US15](../modelagem/agil/userStories.md#US15) depende de recursos de [INT](../elicitacao/introspeccao.md), [QST](../elicitacao/questionario.md) e [BSM](../elicitacao/brainstorming.md)
- Representação: [RP02](../pre-rastreabilidade/richpicture.md#RP02) e [RPF](../pre-rastreabilidade/richpicture.md#RPF) representam [US15](../modelagem/agil/userStories.md#US15)
- Agregação: [US15](../modelagem/agil/userStories.md#US15) agrega [L01](../modelagem/lexico.md#L01) e [L06](../modelagem/lexico.md#L06)

<div id="EF28"></div>

#### 4.1.28 EF28

**Categoria:** Desenvolvimento

**Requisito:** [RF08](../elicitacao/resultadoElicitacao.md#RF08)

**Elementos Rastreáveis:**

- [RP02](../pre-rastreabilidade/richpicture.md#RP02)
- [RPF](../pre-rastreabilidade/richpicture.md#RPF)
- [INT](../elicitacao/introspeccao.md)
- [BSM](../elicitacao/brainstorming.md)
- [L01](../modelagem/lexico.md#L01)
- [US15](../modelagem/agil/userStories.md#US15)

**Elos:**

- Recurso: [US15](../modelagem/agil/userStories.md#US15) depende de recursos de [INT](../elicitacao/introspeccao.md) e [BSM](../elicitacao/brainstorming.md)
- Representação: [RP02](../pre-rastreabilidade/richpicture.md#RP02) e [RPF](../pre-rastreabilidade/richpicture.md#RPF) representam [US15](../modelagem/agil/userStories.md#US15)
- Agregação: [US15](../modelagem/agil/userStories.md#US15) agrega [L01](../modelagem/lexico.md#L01)

<div id="EF29"></div>

#### 4.1.29 EF29

**Categoria:** Desenvolvimento

**Requisito:** [RF04](../elicitacao/resultadoElicitacao.md#RF04)

**Elementos rastreáveis:**

- [RP02](../pre-rastreabilidade/richpicture.md#RP02)
- [RPF](../pre-rastreabilidade/richpicture.md#RPF)
- [INT](../elicitacao/introspeccao.md)
- [L01](../modelagem/lexico.md#L01)
- [L06](../modelagem/lexico.md#L06)
- [UC03](../modelagem/casos_de_uso.md#UC03)
- [US16](../modelagem/agil/userStories.md#US16)

**Elos:**

- Recurso: [US16](../modelagem/agil/userStories.md#US16) depende de recursos de [INT](../elicitacao/introspeccao.md)
- Representação: [RP02](../pre-rastreabilidade/richpicture.md#RP02) e [RPF](../pre-rastreabilidade/richpicture.md#RPF) representam [US16](../modelagem/agil/userStories.md#US16)
- Agregação: [US16](../modelagem/agil/userStories.md#US16) agrega [L01](../modelagem/lexico.md#L01) e [L06](../modelagem/lexico.md#L06)

<div id="EF30"></div>

#### 4.1.30 EF30

**Categoria:** Desenvolvimento

**Requisito:** [RF09](../elicitacao/resultadoElicitacao.md#RF09)

**Elementos rastreáveis:**

- [RP02](../pre-rastreabilidade/richpicture.md#RP02)
- [RPF](../pre-rastreabilidade/richpicture.md#RPF)
- [INT](../elicitacao/introspeccao.md)
- [L01](../modelagem/lexico.md#L01)
- [UC03](../modelagem/casos_de_uso.md#UC03)
- [US16](../modelagem/agil/userStories.md#US16)

**Elos:**

- Recurso: [US16](../modelagem/agil/userStories.md#US16) depende de recursos de [INT](../elicitacao/introspeccao.md)
- Representação: [RP02](../pre-rastreabilidade/richpicture.md#RP02) e [RPF](../pre-rastreabilidade/richpicture.md#RPF) representam [US16](../modelagem/agil/userStories.md#US16)
- Agregação: [US16](../modelagem/agil/userStories.md#US16) agrega [L01](../modelagem/lexico.md#L01)

<div id="EF31"></div>

#### 4.1.31 EF31

**Categoria:** Desenvolvimento

**Requisito:** [RF18](../elicitacao/resultadoElicitacao.md#RF18)

**Elementos rastreáveis:**

- [RP02](../pre-rastreabilidade/richpicture.md#RP02)
- [RPF](../pre-rastreabilidade/richpicture.md#RPF)
- [INT](../elicitacao/introspeccao.md)
- [QST](../elicitacao/questionario.md)
- [C04](../modelagem/cenarios.md#C04)
- [L01](../modelagem/lexico.md#L01)
- [L06](../modelagem/lexico.md#L06)
- [UC03](../modelagem/casos_de_uso.md#UC03)
- [US16](../modelagem/agil/userStories.md#US16)

**Elos:**

- Recurso: [US16](../modelagem/agil/userStories.md#US16) depende de recursos de [INT](../elicitacao/introspeccao.md) e [QST](../elicitacao/questionario.md)
- Representação: [RP02](../pre-rastreabilidade/richpicture.md#RP02) e [RPF](../pre-rastreabilidade/richpicture.md#RPF) representam [US16](../modelagem/agil/userStories.md#US16)
- Representação: [C04](../modelagem/cenarios.md#C04) representa [US16](../modelagem/agil/userStories.md#US16)
- Representação: [UC03](../modelagem/casos_de_uso.md#UC03) representa [US16](../modelagem/agil/userStories.md#US16)
- Agregação: [US16](../modelagem/agil/userStories.md#US16) agrega [L01](../modelagem/lexico.md#L01) e [L06](../modelagem/lexico.md#L06)
- Agregação: [C04](../modelagem/cenarios.md#C04) agrega [L01](../modelagem/lexico.md#L01) e [L06](../modelagem/lexico.md#L06)

<div id="EF32"></div>

#### 4.1.32 EF32

**Categoria:** Desenvolvimento

**Requisito:** [RF25](../elicitacao/resultadoElicitacao.md#RF25)

**Elementos rastreáveis:**

- [BSM](../elicitacao/brainstorming.md)
- [L01](../modelagem/lexico.md#L01)
- [L06](../modelagem/lexico.md#L06)
- [US16](../modelagem/agil/userStories.md#US16)

**Elos:**

- Recurso: [US16](../modelagem/agil/userStories.md#US16) depende de recursos de [BSM](../elicitacao/brainstorming.md)
- Agregação: [US16](../modelagem/agil/userStories.md#US16) agrega [L01](../modelagem/lexico.md#L01) e [L06](../modelagem/lexico.md#L06)

<div id="EF33"></div>

#### 4.1.33 EF33

**Categoria:** Desenvolvimento

**Requisito:** [RF32](../elicitacao/resultadoElicitacao.md#RF32)

**Elementos rastreáveis:**

- [BSM](../elicitacao/brainstorming.md)
- [L06](../modelagem/lexico.md#L06)
- [L03](../modelagem/lexico.md#L03)
- [US17](../modelagem/agil/userStories.md#US17)

**Elos:**

- Recurso: [US17](../modelagem/agil/userStories.md#US17) depende de recursos de [BSM](../elicitacao/brainstorming.md)
- Agregação: [US17](../modelagem/agil/userStories.md#US17) agrega [L03](../modelagem/lexico.md#L03) e [L06](../modelagem/lexico.md#L06)

<div id="EF34"></div>

#### 4.1.34 EF34

**Categoria:** Desenvolvimento

**Requisito:** [RF21](../elicitacao/resultadoElicitacao.md#RF21)

**Elementos rastreáveis:**

- [INT](../elicitacao/introspeccao.md)
- [L01](../modelagem/lexico.md#L01)
- [US18](../modelagem/agil/userStories.md#US18)

- Recurso: [US18](../modelagem/agil/userStories.md#US18) depende de recursos de [INT](../elicitacao/introspeccao.md)
- Agregação: [US18](../modelagem/agil/userStories.md#US18) agrega [L01](../modelagem/lexico.md#L01)

<div id="EF35"></div>

#### 4.1.35 EF35

**Categoria:** Desenvolvimento

**Requisito:** [RF30](../elicitacao/resultadoElicitacao.md#RF30)

**Elementos rastreáveis:**

- [QST](../elicitacao/questionario.md)
- [C09](../modelagem/cenarios.md#C09)
- [L01](../modelagem/lexico.md#L01)
- [L22](../modelagem/lexico.md#L22)
- [US19](../modelagem/agil/userStories.md#US19)

**Elos:**

- Recurso: [US19](../modelagem/agil/userStories.md#US19) depende de recursos de [QST](../elicitacao/questionario.md)
- Representação: [C09](../modelagem/cenarios.md#C09) representa [US19](../modelagem/agil/userStories.md#US19)
- Agregação: [US19](../modelagem/agil/userStories.md#US19) agrega [L01](../modelagem/lexico.md#L01) e [L22](../modelagem/lexico.md#L22)
- Agregação: [C09](../modelagem/cenarios.md#C09) agrega [L01](../modelagem/lexico.md#L01) e [L22](../modelagem/lexico.md#L22)

<div id="EF36"></div>

#### 4.1.36 EF36

**Categoria:** Desenvolvimento

**Requisito:** [RF34](../elicitacao/resultadoElicitacao.md#RF34)

**Elementos rastreáveis:**

- [STL](../elicitacao/Storytelling.md)
- [L01](../modelagem/lexico.md#L01)
- [US20](../modelagem/agil/userStories.md#US20)

**Elos:**

- Recurso: [US20](../modelagem/agil/userStories.md#US20) depende de recursos de [STL](../elicitacao/Storytelling.md)
- Agregação: [US20](../modelagem/agil/userStories.md#US20) agrega [L01](../modelagem/lexico.md#L01)

<div id="EF37"></div>

#### 4.1.37 EF37

**Categoria:** Desenvolvimento

**Requisito:** [RF36](../elicitacao/resultadoElicitacao.md#RF36)

**Elementos rastreáveis:**

- [BSM](../elicitacao/brainstorming.md)
- [C10](../modelagem/cenarios.md#C10)
- [L01](../modelagem/lexico.md#L01)
- [US20](../modelagem/agil/userStories.md#US20)

**Elos:**

- Recurso: [US20](../modelagem/agil/userStories.md#US20) depende de recursos de [BSM](../elicitacao/brainstorming.md)
- Representação: [C10](../modelagem/cenarios.md#C10) representa [US20](../modelagem/agil/userStories.md#US20)
- Agregação: [C10](../modelagem/cenarios.md#C10) agrega [L01](../modelagem/lexico.md#L01)
- Agregação: [US20](../modelagem/agil/userStories.md#US20) agrega [L01](../modelagem/lexico.md#L01)

<div id="EF38"></div>

#### 4.1.38 EF38

**Categoria:** Desenvolvimento

**Requisito:** [RF39](../elicitacao/resultadoElicitacao.md#RF39)

**Elementos rastreáveis:**

- [BSM](../elicitacao/brainstorming.md)
- [L01](../modelagem/lexico.md#L01)
- [US20](../modelagem/agil/userStories.md#US20)

**Elos:**

- Recurso: [US20](../modelagem/agil/userStories.md#US20) depende de recursos de [BSM](../elicitacao/brainstorming.md)
- Agregação: [US20](../modelagem/agil/userStories.md#US20) agrega [L01](../modelagem/lexico.md#L01)

<div id="EF39"></div>

#### 4.1.39 EF39

**Categoria:** Desenvolvimento

**Requisito:** [RF40](../elicitacao/resultadoElicitacao.md#RF40)

**Elementos Rastreáveis:**

- [BSM](../elicitacao/brainstorming.md)
- [STL](../elicitacao/Storytelling.md)
- [C10](../modelagem/cenarios.md#C10)
- [L01](../modelagem/lexico.md#L01)
- [US20](../modelagem/agil/userStories.md#US20)

**Elos:**

- Recurso: [US20](../modelagem/agil/userStories.md#US20) depende de recursos de [BSM](../elicitacao/brainstorming.md) e [STL](../elicitacao/Storytelling.md)
- Representação: [C10](../modelagem/cenarios.md#C10) representa [US20](../modelagem/agil/userStories.md#US20)
- Agregação: [C10](../modelagem/cenarios.md#C10) agrega [L01](../modelagem/lexico.md#L01)
- Agregação: [US20](../modelagem/agil/userStories.md#US20) agrega [L01](../modelagem/lexico.md#L01)

### 4.2 Elos não funcionais

<div id="ENF01"></div>

#### 4.2.1 ENF01

**Categoria:** Desenvolvimento

**Elementos rastreáveis:**

- [INT](../elicitacao/introspeccao.md)
- [STL](../elicitacao/Storytelling.md)
- [NFR02](../modelagem/NFRframework.md#NFR02)

**Elos:** Não há elo para representar

<div id="ENF02"></div>

#### 4.2.2 ENF02

**Categoria:** Desenvolvimento

**Elementos rastreáveis:**

- [INT](../elicitacao/introspeccao.md)
- [STL](../elicitacao/Storytelling.md)
- [NFR04](../modelagem/NFRframework.md#NFR04)

**Elos:** Não há elo para representar

<div id="ENF03"></div>

#### 4.2.3 ENF03

**Categoria:** Desenvolvimento

**Elementos rastreáveis:**

- [INT](../elicitacao/introspeccao.md)
- [STL](../elicitacao/Storytelling.md)
- [NFR01](../modelagem/NFRframework.md#NFR01)

**Elos:** Não há elo para representar

<div id="ENF04"></div>

#### 4.2.4 ENF04

**Categoria:** Desenvolvimento

**Elementos rastreáveis:**

- [INT](../elicitacao/introspeccao.md)
- [STL](../elicitacao/Storytelling.md)
- [NFR03](../modelagem/NFRframework.md#NFR03)

**Elos:** Não há elo para representar

<div id="ENF05"></div>

#### 4.2.5 ENF05

**Categoria:** Desenvolvimento

**Elementos rastreáveis:**

- [INT](../elicitacao/introspeccao.md)
- [STL](../elicitacao/Storytelling.md)
- [NFR02](../modelagem/NFRframework.md#NFR02)

**Elos:** Não há elo para representar

## 5. Referências Bibliográficas

> [1] SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado. Rastreabilidade de Requisitos. 2005. 26 f. Tese (Doutorado) - Curso de Ciência da Computação, Pontifícia Universidade Católica do Rio de Janeiro, Rio de Janeiro, 2005. Cap. 2.

## 6. Histórico de versão

|  Versão  |   Data   |                      Descrição                      |    Autor(es)   |  Revisor(es)  |
| -------- | -------- | --------------------------------------------------- | -------------- | ------------- |
|  `1.0`   | 28/06/23 | Criação e organização da primeira versão | Pedro Muniz       | Felipe Corrêa  |
|  `1.1`   | 28/06/23 | Adição dos elos | Felipe Corrêa       | Pedro Muniz  |