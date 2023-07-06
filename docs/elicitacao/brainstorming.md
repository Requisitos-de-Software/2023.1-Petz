# Brainstorming

## 1. Introdução

_Brainstorming_ é uma técnica de elicitação de requisitos de software que objetiva aprender o tipo de características que os usuários desejam em um produto. É uma técnica que consiste em permitir aos membros da reunião responder a perguntas sobre um determinado produto ideal com ideias em um espaço sem juízo de valor das mesmas a fim de garantir variação e criatividade [1].

## 2. Informações

### 2.1 Local

A reunião foi executada via Google Meet.

### 2.2 Data e Horário

A reunião ocorreu das 20h às 20:40h do dia 28/04/2023.

### 2.3 Participantes

Houveram, além de Felipe Mastromauro Corrêa e Pedro Ferreira Muniz, outros quatro participantes na reunião. Para a preservação de sua anonimidade, seus nomes não serão descritos neste ou em qualquer outro artefato a ser produzido pelo grupo. No entanto, a fim de registrar uma lista de participantes, serão criados nomes falsos a partir da ferramenta [Fake Name Generator](https://www.fakenamegenerator.com/) e estes serão registrados na tabela 1 com uma letra F entre parênteses (F), junto aos nomes dos membros da equipe.

<center>

**Participantes**

| Nome                       | Cargo | Papel |
| -------------------------- | ----- | ----- |
| Bruno Cavalcanti Gomes (F) | Usuário | Participante |
| Davi Costa Dias (F)        | Usuário | Participante |
| Felipe Mastromauro Corrêa  | Eq. desenvolvimento | Moderador e Relator |
| Murilo Castro Ferreira (F) | Usuário | Participante |
| Pedro Ferreira Muniz       | Eq. desenvolvimento | Encenação de persona |
| Tânia Silva Barbosa (F)    | Usuário | Participante |

</center>

<h6 align = "center"> Tabela 1: Lista de participantes da reunião</h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

### 2.4 Termo de consentimento

O termo de consentimento foi disponibilizado para todos os quatro participantes da reunião por compartilhamento de documento na plataforma Google Docs. Cada participante recebeu uma cópia do termo de consentimento no dia 28 de abril de 2023 e a assinou em sua conta do Google, sendo essas mudanças registradas pelo histórico de versão destes documentos.

O documento 1 incorporado abaixo descreve o modelo do termo de consentimento entregue aos participantes.


## TERMO DE CONSENTIMENTO

Somos o grupo 06 da turma 02 da disciplina de Requisitos de Software do professor André Barros de Sales ministrada no campus do Gama da Universidade de Brasília - UnB. Estamos em uma etapa do desenvolvimento do projeto em que desejamos conhecer o que algumas das pessoas que usarão o sistema imaginam que ele deva conter ou realizar.

Para a realização desta pesquisa, solicitamos o seu consentimento para a realização de uma sessão de brainstorming online via Google Meet. Para isso, é necessário que saiba das seguintes informações:

- Os requisitos extraídos durante a reunião de brainstorming destinam-se estritamente a atividades de análise do aplicativo Petz.
- Nossa equipe tem o compromisso de divulgar os resultados da pesquisa para o professor e os alunos da disciplina de requisitos de software, bem como em página de documentação, disponível em <https://requisitos-de-software.github.io/2023.1-Petz>.
- O anonimato dos participantes da reunião será mantido incólume em qualquer documento elaborado por nossa equipe.
- O consentimento para a atividade é uma escolha livre, feita mediante a prestação de todos os esclarecimentos necessários sobre a pesquisa.
- A entrevista pode ser interrompida a qualquer momento, segundo a sua disponibilidade e vontade.
- A equipe encontra-se disponível para contato através do e-mail <211029263@aluno.unb.br>.

De posse dessas informações, gostaríamos que você se pronunciasse acerca da entrevista:

( ) Dou meu consentimento para a sua realização.

( ) Não consinto com a sua realização.

## 3. Requisitos elicitados

Para a organização dos requisitos elicitados na sessão de _brainstorming_, cada requisito será marcado com uma _tag_ específica. A legenda abaixo marca o significado das tags e de outras uas siglas relevantes para o processo de elicitação de requisitos.

Legendas:

- BR: Brainstorming
- RF - Requisito Funcional
- RNF - Requisito Não Funcional

A tabela 2 detalha os requisitos elicitados com esta técnica e separ-os entre funcionais e não funcionais.

<center>

| Tag  | Requisito                                                                                 | Tipo |
| ---- | ----------------------------------------------------------------------------------------- | ---- |
| BR01 | Eu, como usuário, devo conseguir comprar ração                                            | RF   |
| BR02 | Eu, como usuário, devo poder assinar produtos pelo aplicativo                             | RF   |
| BR03 | O sistema deve ter uma pesquisa eficiente                                                 | RNF  |
| BR04 | O usuário deve ser capaz de registrar uma lista de compras frequentes                     | RF   |
| BR05 | Eu, como usuário, devo conseguir criar perfil para o pet                                  | RF   |
| BR06 | O sistema deve realizar a sugestão de produtos a partir de um perfil                      | RF   |
| BR07 | Eu, como usuário, devo ser capaz de marcar banho e tosa no aplicativo                     | RF   |
| BR08 | Eu, como usuário, devo poder acessar a avaliação e recomendações de um produto            | RF   |
| BR09 | Eu, como usuário, devo poder consultar e me beneficiar de promoções                       | RF   |
| BR10 | Eu, como usuário, devo poder acessar um blog com dicas sobre pets no aplicativo           | RF   |
| BR11 | Eu, como usuário, devo ser capaz de consultar a loja mais próxima                         | RF   |
| BR12 | Eu, como usuário, devo ser capaz de marcar consulta veterinária                           | RF   |
| BR13 | O sistema deve permitir a solicitação de um sistema de trasporte para pets                | RF   |
| BR14 | Eu, como usuário, devo poder consultar uma página para eventos(adoção, vacinação, etc...) | RF   |
| BR15 | Eu, como usuário, devo poder solicitar a entrega de produtos                              | RF   |
| BR16 | O sistema deve realizar recomendações eficientes baseadas no perfil do usuário            | RNF  |
| BR17 | Eu, como usuário, desejo poder acessar uma aba de comunidade                              | RF   |
| BR18 | Eu, como usuário, desejo receber avisos médcos para meu pet                               | RF   |
| BR19 | Eu, como usuário, desejo receber avisos sobre vacinas a partir do perfil do pet           | RF   |
| BR20 | Eu, como usuário, desejo ter a opção de um plano de assinatura a partir de meu perfil     | RF   |
| BR21 | Eu, como usuário, desejo poder cadastrar-me em um plano de fidelidade com descontos       | RF   |
| BR22 | O sistema deve possuir filtros e classificação por categorias para os produtos            | RF   |
| BR23 | Eu, como usuário, desejo poder solicitar um serviço de hotelaria/creche para meu pet      | RF   |
| BR24 | Eu, como usuário, desejo poder solicitar um serviço de adestramento para meu pet          | RF   |
| BR25 | Eu, como usuário, desejo poder visualizar eventos e locais pet-friendly próximos          | RF   |

</center>

<h6 align = "center"> Tabela 2: Requisitos extraídos durante a reunião de brainstorming</h6>
<h6 align = "center"> Fonte: Autores, 2023 </h6>

## 4. Referências Bibliográficas

> [1] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021). Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.

## 5. Histórico de versão

| Versão | Data     | Descrição                                  | Autor(es)     | Revisor(es)   |
| ------ | -------- | ------------------------------------------ | ------------- | ------------- |
| `1.0`  | 26/04/23 | Criação da página da técnica de elicitação | Felipe Corrêa | Pedro Muniz   |
| `1.1`  | 28/04/23 | Adição dos requisitos                      | Felipe Corrêa | Magno Luiz    |
| `1.2`  | 30/04/23 | Padronização de legendas                   | Pedro Muniz   | Felipe Corrêa |
| `1.3`  | 04/05/23 | Adição de termo de consentimento           | Felipe Corrêa | Samuel Sato   |
| `1.4` | 04/07/23  | Adição dos papéis no brainstorm | Pedro Muniz | Felipe Corrêa |