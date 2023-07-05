## 1. Introdução

O diagrama de casos de uso é uma ferramenta gráfica de modelagem utilizada na engenharia de software para representar as funcionalidades de um sistema a partir da perspectiva do usuário. É uma das técnicas mais utilizadas para elicitação e documentação de requisitos funcionais, pois permite identificar os atores envolvidos no sistema e descrever como eles interagem com o mesmo.

## 2. Metodologia

Para a realização da atividade de diagramação no artefato, foi utilizada a ferramenta de representação de diagramas [LucidChart](https://www.lucidchart.com/pages/pt). O diagrama de casos de uso irá demonstrar os casos de uso principais do sistema, que são representados por elipses, e os atores envolvidos no sistema, que são representados por retângulos. Os casos de uso são conectados aos atores através de linhas, que indicam a interação entre eles. Além disso, é possível incluir descrições detalhadas de cada caso de uso, com informações sobre pré-condições, pós-condições, fluxos alternativos e exceções.

## 3. Representação do Diagrama UML - Casos de Uso

### 3.1 Ator(es)

 Atores são caracterizados por serem os usuários do sistema ou um tipo de usuário[1]. Sua representação nos diagramas pode ser vista na figura 1.
<center>

![Ator](../assets/casos_de_uso/elemento_ator.png)

</center>

<h6 align = "center"> Figura 1: Ator </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

### 3.2 Caso de uso

Caso de uso é uma tarefa ou funcionalidade realizada pelo ator[1]. Sua representação nos diagramas pode ser vista na figura 2.

<center>

![Caso de uso](../assets/casos_de_uso/elemento_caso_de_uso.png)

</center>

<h6 align = "center"> Figura 2: Caso de uso </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

### 3.3 Cenário 

Cenário é uma sequência de eventos que estão acontecendo enquanto o usuário interage com o sistema[1]. Sua representação nos diagramas pode ser vista na figura 3.

<center>

![Cenário](../assets/casos_de_uso/elemento_cenario.png)

</center>

<h6 align = "center"> Figura 3: Cenário </h6>
<h6 align = "center"> Fonte: Autor,2023 </h6>

### 3.4 Pontos de extensão

Ponto de extensão é a especificação de um caso de uso base, sendo referido por um relacionamento de extensão entre o caso de uso e base e o de extensão[2]. Sua representação nos diagramas pode ser vista na figura 4.

<center>

![Pontos de extensão](../assets/casos_de_uso/elemento_ponto_de_ext.png)

</center>

<h6 align = "center"> Figura 4: Pontos de extensão </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

### 3.5 Comunicação 

É o procedimento que liga o ator ao caso de uso, como demonstrado na Figura 5, possui variações. A comunicação apresenta duas notações de relacionamentos:

**Include**: Relação de um caso de uso que necessita executar o caso de uso através da chamada de outro caso de uso[1]. 
- Notação na diagramação: <<include\>\>


**Extend**: Relação de um caso de uso que executa sem necessidade de outro caso de uso, entretanto, pode ter novas etapas. Sendo assim o caso de uso extendido pode ou não ser executado[3].
- Notação na diagramação: <<extend\>\>

<center>

 ![Comunicação](../assets/casos_de_uso/elemento_comunica.png)
 ![Comunicação2](../assets/casos_de_uso/elemento_comunica2.png)   

</center>

<h6 align = "center"> Figura 5: Comunicação </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>



## 4. Diagramas de Casos de Uso

Na figura 6 observa-se o diagrama geral dos casos de uso do sistema.

<center>

![Diagrama Geral](../assets/casos_de_uso/caso_de_uso_geral.png)

</center>

<h6 align = "center"> Figura 6: Caso de uso geral </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>


<div id="UC01"></div>

## UC01 - Realizar Cadastro

Na figura 7 observa-se o diagrama de caso de uso referente ao cadastro. Abaixo na tabela 1 se encontra a especificação do diagrama.

<center>

![Cadastro](../assets/casos_de_uso/fluxo_cadastro.png)
 
</center>

<h6 align = "center"> Figura 7: Realizar cadastro </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

| UC01	| Realizar cadastro |
| ----- | ------------- |
| **Descrição** |Funcionalidade que permite o cadastro do usuário na aplicação.	 |
| **Ator(es)**	| Usuário. |
| **Pré-Condições** | O Usuário não deve estar logado na aplicação. |
| **Pós-Condições** | O Usuário deve acessar conseguir acessar a conta cadastrada.|
| **Fluxo Principal** |	**[FP01] Realizar cadastro** <br/> 1. O Usuário seleciona " Ainda não tem conta? Clique aqui". <br/> 2. O Usuário preenche os dados cadastrais. <br/> 3. O Sistema valida os dados preenchidos. <br/> 4. O Sistema autentica o usuário. <br/> 5. O Usuário é redirecionado para a página de Login.|
| **Fluxo(s) Alternativo(s)** | - | 
| **Ponto(s) de Extensão**	|**[PE01] Efetuar Login** <br/> 1. O Usuário acessa a página de Login.|
| **Fluxo(s) de Exceção** | **[FE01] Dados cadastrais inválidos** <br/> 1. O Sistema apresenta uma mensagem informando os campos inválidos.|

<h6 align = "center"> Tabela 1: Realizar cadastro </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

<div id="UC02"></div>

## UC02 - Efetuar Login

Na figura 8 observa-se o diagrama de caso de uso referente ao login. Abaixo na tabela 2 se encontra a especificação do diagrama.

<center>

![Login](../assets/casos_de_uso/fluxo_login.png)

</center>

<h6 align = "center"> Figura 8: Efetuar Login </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

| UC02	| Efetuar Login |
| ----- | ------------- |
| **Descrição** |	Funcionalidade que possibilidade o usuário efetuar login |
| **Ator(es)**	| Usuário e Sistema(Aplicação Petz) |
| **Pré-Condições** | O Usuário não deve estar logado na aplicação |
| **Pós-Condições** |  O Usuário estará logado na aplicação <br/> O Usuário tem acesso as funcionalidades que requerem login |
| **Fluxo Principal** |	**[FP02] Efetuar Login** <br/>1. O Usuário inicia a aplicação. <br/>2. O Usuário preenche com Email ou CPF e com a senha o campo de login. <br/> 3. O Usuário clica em "Entrar". <br/> 4. O Sistema autentica o usuário. <br/> 5. O Sistema redireciona o usuário para a aplicação principal. |
| **Fluxo(s) Alternativo(s)** | **[FA01] Acessar rapidamente** <br/>1. O Usuário seleciona a opção "Receber código de acesso rápido". <br> 2. O Usuário escolhe a forma de receber o código(Email ou SMS). <br> 3. O Usuário digita o código de verificação para a autenticação. <br> 4. O Sistema autentica o usuário. <br> 5. O Sistema redireciona o usuário para a aplicação principal. | 
| **Ponto(s) de Extensão**	| **[PE02] Alterar Senha** <br/>1. O Usuário clica em " Esqueci minha senha". <br/> 2. O Usuário escolhe a forma de recuperar a senha(Email ou SMS). <br/> 3. O Sistema envia um código de recuperação através do meio escolhido. <br/> 4. O Usuário preenche o campo com o código de vericação. <br/> 5. O Usuário altera a senha. <br/>**[PE03] Realizar Cadastro** <br/> 1.  **UC01**| 
| **Fluxo(s) de Exceção** | **[FE02] Dados inválidos** <br>1. O Sistema apresenta uma mensagem de alerta, avisando que os dados preenchidos são inválidos(Email, CPF/CPNJ ou senha). |

<h6 align = "center"> Tabela 2: Efetuar Login </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

<div id="UC03"></div>

## UC03 - Compra de produto

Na figura 9 observa-se o diagrama de caso de uso referente à compra de um produto. Abaixo na tabela 3 se encontra a especificação do diagrama.

<center>

![Compra](../assets/casos_de_uso/fluxo_compra.png)

</center>

<h6 align = "center"> Figura 9: Compra de produto </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

| UC03	| Compra de produto |
| ----- | ------------- |
| **Descrição** | Funcionalidade que permite efetuar a compra de produtos |
| **Ator(es)**	| Usuário e Sistema(Aplicação Petz)|
| **Pré-Condições** | O Usuário deve estar logado na aplicação.  |
| **Pós-Condições** | O Usuário deve ter o pedido realizado. |
| **Fluxo Principal** |	**[FP03] Compra de produto** <br/>1. O Usuário seleciona item. <br/> 2. O Usuário adiciona o item ao carrinho. <br/> 3. O Usuário preenche o campo de CEP. <br/> 4. O Usuário seleciona como receber o produto(Retirar na loja ou solicitar envio). <br/> 5. O Sistema redireciona o usuário para a página de pagamento.|
| **Fluxo(s) Alternativo(s)** | - | 
| **Ponto(s) de Extensão**	| **[PE04] Inserir Cupom** <br/> 1. O Usuário insere um cupom no campo válido. <br/> 2. O Sistema valida o cupom. <br/> 3. O Sistema retorna o novo valor do produto.|
| **Fluxo(s) de Exceção** | **[FE03] Produto Esgotado** <br/> 1. O Sistema informa que o item não está disponível para compra. <br/> **[FE04] Cupom inválido** <br/> 1. O Sistema informa que o cupom não é válido.|

<h6 align = "center"> Tabela 3: Compra de produto </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

<div id="UC04"></div>

## UC04 - Efetuar Pagamento

Na figura 10 observa-se o diagrama de caso de uso referente ao pagamento. Abaixo na tabela 4 se encontra a especificação do diagrama.

<center>

![Pagamento](../assets/casos_de_uso/fluxo_pagamento.png)

</center>

<h6 align = "center"> Figura 10: Pagamento </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

| UC04| Efetuar Pagamento |
| ----- | ------------- |
| **Descrição** |	Funcionalidade que permite a realização de pagamentos na aplicação |
| **Ator(es)**	| Usuário e Sistema(Aplicação Petz) |
| **Pré-Condições** | O Usuário deve estar logado na aplicação. <br/> O Usuário deve ter realizado um pedido. |
| **Pós-Condições** | O Usuário deve ter realizado o pagamento do pedido. <br/> O Usuário deve se capaz de acomapanhar o pedido.|
| **Fluxo Principal** |	**[FP04] Efetuar Pagamento** <br/>1. O Usuário deve ter escolhido o meio de entrega(Retirar na loja ou solicitar envio). <br/>2. O Usuário seleciona o método de pagamento. <br/> 3. O Usuário realiza o pagamento. <br/> 4. O Sistema autentica o pagamento. <br/> 5. O Usuário pode acompanhar o pedido. |
| **Fluxo(s) Alternativo(s)** | - | 
| **Ponto(s) de Extensão**	| **[PE05] Retirar na loja** <br/> 1. O Sistema não adiciona taxa de entrega. <br/> 2. O Sistema sinaliza a loja que pode ocorrer a retirada. <br/> **[PE06] Solicitar envio** <br/> 1. O Usuário adiciona o endereço de envio. <br/> 2. O Sistema retorna o valor de envio.|
| **Fluxo(s) de Exceção** | **[FE05] Pagamento Inválido** <br/> 1. O Sistema informa uma mensagem de erro sobre a situação do pagamento. |

<h6 align = "center"> Tabela 4: Efetuar pagamento </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

<div id="UC05"></div>

## UC05 - Consultar conta 

Na figura 11 observa-se o diagrama de caso de uso referente à consulta de conta. Abaixo na tabela 5 se encontra a especificação do diagrama.

<center>

![Conta](../assets/casos_de_uso/fluxo_conta.png)

</center>

<h6 align = "center"> Figura 11: Conta </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>


| UC05	| Consultar conta |
| ----- | ------------- |
| **Descrição** | Funcionalidade que permite consultar os dados atrelados a conta do usuário. |
| **Ator(es)**	| Usuário e Sistema(Aplicação Petz).|
| **Pré-Condições** | O Usuário deve estar logado na aplicação. |
| **Pós-Condições** | O Usuário visualiza as informações pretendidas. <br/> O Usuário edita as informações pretendidas.<br/> O Usuário pode sair da conta.|
| **Fluxo Principal** |	**[FP05] Consultar dados da conta** <br/>1. O Usuário seleciona "Minha Conta". <br/> 2. O Usuário seleciona a opção em "Meus dados" (cadastro, alterar senha, endereço, pets, favoritos, carteira). <br/> 3. O Usuário visualiza ou edita os dados. |
| **Fluxo(s) Alternativo(s)** | **[FA02] Acompanhar pedido** <br/> 1. O Usuário seleciona "Acompanhar pedido". <br/> 2. O Sistema retorna as informações dos pedidos realizados.<br/> **[FA03] Editar assinaturas** <br/> 1. O Usuário seleciona "Editar assinaturas". <br/> 2. O Sistema retorna as assinaturas vigentes. <br/> 3. O Usuário seleciona a assinatura para editar. <br/> **[FA04] Serviços** <br/> 1. O Usuário seleciona entre "Banho e Tosa" e "Lojas". <br/> 2a. O Usuário seleciona o agendamento de "Banho e Tosa" <br/> 2b. O Usuário visualiza as lojas Petz.| 
| **Ponto(s) de Extensão**	| **[PE07] Código de verificação** <br/> 1. O Sistema envia o código de verificação para alterar a senha. |
| **Fluxo(s) de Exceção** | **[FE06] Edição de dados inválida** <br> 1. O Usuário recebe uma mensagem de erro ao preencher dados inválidos. <br> **[FE07] Falta de dados obrigatórios** <br> 1a. O Sistema apresenta uma mensagem explicitando como inválido um campo cadastral obrigatório faltante.|

<h6 align = "center"> Tabela 5: Consultar conta </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

## UC06 - Atendimento

Na figura 12 observa-se o diagrama de caso de uso referente ao atendimento e comunicação com a Petz. Abaixo na tabela 6 se encontra a especificação do diagrama.

<center>

![Atendimento](../assets/casos_de_uso/fluxo_atendimento.png)

</center>

<h6 align = "center"> Figura 12: Atendimento </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>


| UC06	| Atendimento |
| ----- | ------------- |
| **Descrição** | Funcionalidade que permite comunicação para retirar dúvidas e reportar falhas.|
| **Ator(es)**	|<br>**1.Principal**: Usuário. <br>**2. Secundário**: Atendente, Sistema.|
| **Pré-Condições** | O Usuário deve ter acesso a aplicação.|
| **Pós-Condições** | <br> 1. O Usuário deve conseguir comunicar-se com a Loja. <br>2. O Usuário deve ter suas dúvidas sanadas.|
| **Fluxo Principal** |	**[FP06] Selecionar atendimento** <br>1. O Usuário seleciona "Atendimento".<br>2. O Usuário seleciona uma das opções frequentes. <br> 3. O Sistema retorna as respostas adequadas. |
| **Fluxo(s) Alternativo(s)** |**[FA05] Selecionar chat online**<br>1. O Usuário seleciona "chat online".<br>2. O Usuário responde a pesquisa inicial com seus dados(Nome,CPF,Email e Número do pedido).<br>3. O Usuário comunica-se com o Atendente. <br>4. O Atendente responde ao Usuário. **[FA06] Enviar Email** <br>1. O Usuário seleciona a opção "Enviar E-mail".<br>2. O Usuário preenche as informações necessárias. <br>3. O Usuário seleciona "Enviar". <br> 4. O Atendente responde ao Email recebido.<br>**[FA06] Digitar dúvida** <br>1. O Usuário digitará no campo "Digitar dúvida".<br>2. O Sistema retorna respostas pré-estabelecidas que possuem relação com o digitado pelo Usuário.| 
| **Ponto(s) de Extensão**	| **[PE08] Acompanhar pedido**<br>1. O Sistema retorna uma página de acompanhamento de pedido. <br>**[PE09]Disponibilidade de produtos**<br>1. O Sistema retorna uma resposta padrão.<br>**[PE010]Agendamento de serviços**<br>1. O Sistema redireciona para uma página em que é possível baixar o aplicativo. <br>**[PE011]Trocas e devoluções**<br>1. O Sistema redireciona para uma página com uma explicação sobre o processo. **[PE012]Horários de funcionamento**<br>1. O Sistema redireciona para uma página com o link para as lojas Petz. <br> **[PE013]Mudanças de Assinaturas**<br>1. O Sistema redireciona para uma página com uma explicação sobre o processo.|
| **Fluxo(s) de Exceção** | **[FE08] Falta de dados obrigatórios** <br> 1. O Sistema apresenta uma mensagem explicitando como inválido um da pesquisa inicial obrigatório faltante. <br>**[FE09] Não é possível gerar resultados** <br>1a. O Sistema não gera resultados possíveis para o **[FA06]**. |

<h6 align = "center"> Tabela 6: Atendimento </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>



## UC07 - Repetir pedido

Na figura 13 observa-se o diagrama de caso de uso referente à consulta de conta. Abaixo na tabela 7 se encontra a especificação do diagrama.

<center>

![Repetir pedido](../assets/casos_de_uso/fluxo_repetir.png)

</center>

<h6 align = "center"> Figura 13: Repetir pedido </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>


| UC07	| Repetir pedido |
| ----- | ------------- |
| **Descrição** | Funcionalidade que permite a repetição de um pedido anterior.|
| **Ator(es)**	| Usuário|
| **Pré-Condições** | <br>1. O Usuário deve estar logado. <br>2. O Usuário já deve ter realizado um pedido anteriormente.|
| **Pós-Condições** | O Usuário deve ter sido capaz de repetir um pedido anterior.|
| **Fluxo Principal** |	**[FP07] Repetir pedido** <br>1. O Usuário seleciona "Repetir pedido" na página inicial.<br>2. O Usuário seleciona o pedido que deseja repetir.<br>3. O Usuário adiciona o pedido ao carrinho. <br> 4. O Usuário procede para a fase de compra do produto.<br> 5. O Usuário efetua o pagamento.<br> 6. O Sistema valida o pagamento.|
| **Fluxo(s) Alternativo(s)** | **[FA07] Meus Pedidos**<br>1. O Usuário seleciona "Meus Pedidos".<br> 2. O Usuário seleciona um pedido feito anteriormente.<br>3. O Usuário adiciona o pedido ao carrinho. <br> 4. O Usuário procede para a fase de compra do produto.<br> 5. O Usuário efetua o pagamento.<br> 6. O Sistema valida o pagamento.<br>**[FA08] Agendar serviço**<br> 1. O Usuário seleciona "Repetir pedido" na página inicial.<br>2. O Usuário seleciona o pedido que deseja repetir.<br>3a. O Usuário procede a agendar o serviço. <br> 4a. O Usuário efetua o pagamento.<br>5a. O Sistema valida o pagamento.| 
| **Ponto(s) de Extensão**	| **[PE014] Agendar serviços**<br>1. O Usuário seleciona o serviço que deseja agendar.<br>**[PE015] Adicionar ao carrinho**<br>1. O Usuário seleciona o(s) produto(s) que deseja adicionar ao carrinho de compras.|
| **Fluxo(s) de Exceção** | **[FE010] Não é possível realizar o pedido**<br> 1. O Sistema apresenta uma mensagem de erro sinalizando que não é possível realizar o pedido por não ter disponibilidade.<br>**[FE011] Não existem pedidos anteriores** <br> 1.O Sistema não apresenta pedidos anteriores.|

<h6 align = "center"> Tabela 7: Repetir pedido </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

## UC08 - Cadastrar meu pet

Na figura 14 observa-se o diagrama de caso de uso referente à consulta de conta. Abaixo na tabela 8 se encontra a especificação do diagrama.

<center>

![Cadastrar meu pet](../assets/casos_de_uso/fluxo_petcadastro.png)

</center>

<h6 align = "center"> Figura 14: Cadastrar meu pet </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>


| UC08	| Cadastrar meu pet |
| ----- | ------------- |
| **Descrição** | Funcionalidade que permite o cadastro do animal de estimação.|
| **Ator(es)**	| Usuário |
| **Pré-Condições** | O Usuário deve estar logado na aplicação.|
| **Pós-Condições** | O Usuário deve ter sido capaz de cadastrar um animal de estimação.|
| **Fluxo Principal** |	**[FP08] Cadastrar meu pet** <br>1. O Usuário seleciona "Mais".<br>2. O Usuário seleciona "Meus Pets".<br>3. O Usuário seleciona "Cadastrar meu pet".<br>4. O Usuário preenche os dados cadastrais requiridos(Nome,Tipo,Raça,Peso,Sexo,Data de nascimento, Microchip e Foto).<br>5. O Usuário confirma o cadastro. <br>6. O Sistema salva os dados. |
| **Fluxo(s) Alternativo(s)** |**[FA09] Adicionar outro pet** <br>1. O Usuário seleciona "Mais".<br>2. O Usuário seleciona "Meus Pets".<br>3a. O Usuário seleciona o botão "+" ou "Adicionar novo pet".<br>4a. O Usuário preenche os dados cadastrais requiridos(Nome,Tipo,Raça,Peso,Sexo,Data de nascimento, Microchip e Foto).<br>5a. O Usuário confirma o cadastro. <br>6a. O Sistema salva os dados.| 
| **Ponto(s) de Extensão**	| **[PE016] Adicionar novo pet** <br> 1. O Usuário pode cadastrar novos animais de estimação após o cadastro de um primeiro.|
| **Fluxo(s) de Exceção** | **[FE012] Não é possível realizar o cadastro**<br> 1. O Sistema retorna uma mensagem de erro.<br> 2a. O Sistema comunica que não foi possível salvar os dados cadastrados.<br>2b. O Sistema comunica que os dados cadastrados são inválidos.|

<h6 align = "center"> Tabela 8:  </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>


## 5. Validação com o usuário,

Devido a divergência de horários, não foi possível que um Usuário da aplicação estivesse disponível para a validação dos casos de usos atualizados e corrigidos pela equipe de desenvolvimento do projeto.




## 6. Referências Bibliográficas

> [1] DevMedia. O que é UML e Diagramas de Caso de Uso: Introdução Prática à UML. 2012. DevMedia. Disponível em: https://www.devmedia.com.br/o-que-e-uml-e-diagramas-de-caso-de-uso-introducao-pratica-a-uml/23408. Acessado em 16 de maio de 2023.

> [2] IBM. Pontos de extensão. IBM. Disponível em: https://www.ibm.com/docs/pt-br/rational-soft-arch/9.6.1?topic=cases-extension-points. Acessado em 16 de maio de 2023.

> [3] SERRANO M., SERRANO M. Requisitos - Aula 13. Disponível na plataforma Aprender3. Acessado em 16 de maio de 2023.


## 7. Histórico de versão

| Versão | Data     | Descrição                                  | Autor(es)     | Revisor(es)   |
| ------ | -------- | ------------------------------------------ | ------------- | ------------- |
| `1.0`  | 16/05/23 | Criação do artefato de casos de uso | Magno Luiz |  Pedro Muniz |
| `1.1`  | 19/06/23 | Correções de padronização | Pedro Muniz |  Felipe Corrêa |
| `1.2`  | 28/06/23 | Correções de diagramação e fluxos | Magno Luiz |  Pedro Muniz |
| `1.3`  | 05/07/23 | Adição de novos casos de usos | Magno Luiz |  Pedro Muniz |