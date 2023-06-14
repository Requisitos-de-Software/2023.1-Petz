# Verificação Backlog do produto

## 1. Introdução

O backlog do produto é parte importante dos processos ágeis de desenvolvimento de software. Para Pressman (2021), "é uma lista priorizada de requisitos ou características do artefato que agregam valor de negócio para o cliente" [2]. Assim, este artefato compila os resultados da verificação deste artefato para o grupo 8 - [Twitch](https://requisitos-de-software.github.io/2023.1-Twitch/).

## 2. Metodologia

A verificação a seguir segue a metodologia proposta no [planejamento](../planejamento.md)[1], onde serão utilizados _[checklists](../../planejamento/glossario.md#Checklist)_ para a verificação dos conteúdos presentes no artefato, buscando encontrar erros e elementos faltantes no mesmo.

Abaixo seguem as verificações de conteúdo elaboradas, contendo a justificativa de cada uma além de sua fonte:

### 2.1 Verificação 1 - Os épicos definem um agrupamento coerente de histórias de usuário?

Apesar de um tanto enevoados em relação às histórias de usuário, os épicos do backlog do produto definem um agrupamento de histórias voltadas para um objetivo específico. Dessa forma, as histórias dentro do mesmo devem ser coerentes com o épico.

`SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 15. Páginas 11-15.`

### 2.2 Verificação 2 - A escrita das histórias de usuário possui o ator, a ação e a razão dessa ação?

As histórias de usuário devem ser assim escritas para respeitar as regras de metodologias ágeis sobre histórias de usuário.

`SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 15. Página 12.`

### 2.3 Verificação 3 - Os requisitos representados pelas histórias de usuário são rastreáveis?

A rastreabilidade é fundamental para a elicitação de requisitos, permitindo a representação da relação entre os requisitos de software e outros artefatos.

`PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. Porto Alegre: Amgh Editora, 2021. Página 249.`

### 2.4 Verificação 4 - Os épicos são coerentes com o sistema analisado?

Os épicos devem ser representações de ideias gerais de funcionalidades ou atributos do sistema. Assim, sua coerência com o sistema é necessária.

`SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 15. Páginas 11-15.`

### 2.5 Verificação 5 - O backlog do poduto define temas?

Os temas são ainda maiores que os épicos, representando uma ideia geral de uma funcionalidade do sistema.

`SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 15. Páginas 13-15.`

## 3. Desenvolvimento

### 3.1 Padronização

Na tabela 1, se encontra o _[checklist](../../planejamento/glossario.md#Checklist)_ de padronização preenchido após a realização da verificação.

| ID  | Verificação                                                          | Realizado |
| --- | -------------------------------------------------------------------- | --------- |
| 1   | Possui ortografia correta e formal?                                  | Sim       |
| 2   | Possui introdução?                                                   | Sim       |
| 3   | Possui links necessários?                                            | Não       |
| 4   | As tabelas e imagens possuem legenda padronizada e chamada no texto? | Incompleto|
| 5   | As tabelas e imagens estão totalmente em português?                  | Sim       |
| 6   | Possui bibliografia?                                                 | Incompleto|
| 7   | A bibliografia está em ordem alfabética?                             | Sim       |
| 8   | Possui histórico de versão padronizado?                              | Incompleto|
| 9   | O histórico de versão possui autor(es) e revisor(es)?                | Sim       |

<h6 align = "center"> Tabela 1: Verificação de padronização do backlog do produto </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

### 3.2 Conteúdo

Na tabela 2, se encontra o _[checklist](../../planejamento/glossario.md#Checklist)_ de conteúdo preenchido após a realização da verificação. As verificações realizadas foram obtidas a partir da apresentação em PowerPoint de Milene e Maurício Serrano [4].

| ID| Verificação                                | Ocorrências | Acertos | Erros |
| - | ------------------------------------------ | ----------- | ------- | ----- |
| 1 | Os épicos definem um agrupamento coerente de histórias de usuário?[3] | 3 | 2 | 1 |
| 2 | A escrita das histórias de usuário possui o ator, a ação e a razão dessa ação?[3]| 34 | 0 | 34 |
| 3 | Os requisitos representados pelas histórias de usuário são rastreáveis?[3] | 34 | 34 | 0 |
| 4 | Os épicos são coerentes com o sistema analisado?[3] | 3 | 0 | 3 |
| 5 | O backlog do produto define temas?[3] | 0 | - | - |

<h6 align = "center"> Tabela 2: Verificação de conteúdo do backlog do produto </h6>
<h6 align = "center"> Fonte: Autor, 2023 </h6>

### 3.3 Problemas encontrados - padronização

#### 3.3.1 Verificação 3 - Possui links necessários?

Os requisitos representados pelas histórias de usuário não são ligados aos artefatos que os originaram.

#### 3.3.2 Verificação 4 - As tabelas e imagens possuem legenda padronizada e chamada no texto?

As tabelas possuem legendas mas não são adequadamente chamadas no texto.

#### 3.3.3 Verificação 6 - Possui bibliografia?  

A bibliografia do artefato é existente. Porém, não segue o padrão de outros artefatos ou alguma norma técnica e não apresenta a fonte das infomações de forma a permitir a rastreabilidade.

#### 3.3.4 Verificação 8 - Possui histórico de versão padronizado?

O histórico de versão deste artefato não segue o mesmo padrão do histórico de versão da página inicial. A versão do artefato e a data estão em posições diferentes.

### 3.4 Problemas encontrados - conteúdo

#### 3.4.1 Verificação 1 - Os épicos definem um agrupamento coerente de histórias de usuário?

O épico de "Plataforma" do artefato não agrupa as histórias de forma coerente. Dentro deste épico estão as histórias USB34 e USB36, que dizem respeito a configurações de conta da Twitch.

#### 3.4.2 Verificação 2 - A escrita das histórias de usuário possui o ator, a ação e a razão dessa ação?

Nenhuma das histórias de usuário possui as razões pelas quais um ator usaria uma funcionalidade do software, não respeitando as determinações de metodologias ágeis. 

#### 3.4.3 Verificação 4 - Os épicos são coerentes com o sistema analisado?

Os épicos são amplos demais para serem coerentes com o sistema em si, sendo mais adequados como temas. Não é visível uma ideia geral de uma funcionalidade ou atributo do sistema nos épicos.

#### 3.4.4 Verificação 5 - O backlog do produto define temas?

Não há temas definidos para o backlog do produto.

## 5. Referências bibliográficas

> [1] Artefato de planejamento da verificação, acesso em 13 de junho de 2023. Para mais informações acesse: [link](../planejamento.md)

> [2] PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. Porto Alegre: Amgh Editora, 2021. Disponível em: https://www.academia.edu/89376481/PRESSMAN_Engenharia_de_software_Uma_Abordagem_Profissional_9a_Ed. Acesso em 13 de junho de 2023;

> [3] SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 15. Apresentação em PowerPoint. Disponível em: https://aprender3.unb.br/pluginfile.php/2523115/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf. Acesso em: 13 de junho de 2023.

## 6. Histórico de versão

| Versão | Data     | Descrição | Autor(es) | Revisor(es) |
| ------ | -------- | --------- | --------- | ----------- |
| `1.0`  | 14/06/2023 | Criação do artefato e adição do conteúdo | Felipe Corrêa | Magno Luiz |
