# Metodologia

## 1. Introdução
Para gestão do projeto, serão necessárias metodologias de gestão e organização assim como políticas de padronização para manter o projeto consistente durante seu desenvolvimento.

## 2. Gestão de projeto

### 2.1 SCRUM
Método ágil para gerência de projetos, o SCRUM visa dividir o projeto em iterações(sprints) com o objetivo de possibilitar entregas nos prazos corretos, assim como fornecer maior liberdade para os integrantes e maior velocidade no desenvolvimento. Para nosso projeto, cada sprint será delimitada pelas datas de entrega para cada etapa. Totalizando assim 7 sprints.

### 2.2 Quadro KanBan
Utilizado para organização das etapas de projetos, utilizaremos o quadro em conjunto com as sprints para gerir as etapas e tarefas de cada sprint. Para gestão do quador será utilizada a ferramenta [Trello](https://trello.com).

## 3. Políticas

### 3.1 Política de branchs
Para inserção de novo conteúdo na documentação do projeto será necessário a criação de uma branch específica para a tarefa a ser realizada. Após o término deve-se abrir um _pull request_ para a branch _main_, onde deve haver apenas conteúdo realizado, revisado e integralizado.

### 3.2 Integração contínua
Os membros do projeto devem estar sempre de prontidão para revisar, alterar e integralizar cada tarefa terminada, fazendo com que a documentação do projeto esteja sempre em conformidade com os artefatos produzidos.

### 3.3 Política de commits
Os commits realizados pelos membros deve seguir o seguinte padrão:

1. Termo em inglês indicando a finalidade do commit, sendo um destes:
    * create
    * delete
    * change
    * fix
2. Descrição breve em português das alterações realizadas pelo commit.
Exemplo de commit para o projeto:
    `git commit -m "create: Artefato de metodologia"`

### 3.4 Política de _issue_
As tarefas de cada sprint serão documentadas através de _issues_ no repositório GitHub do projeto, seguindo o seguinte template:

> # Issue name
> 
> ## 📝 Descrição
> 
> Descrição detalhada da tarefa
> 
> ## 👩‍💻 Revisor(es)
> 
> Marcação do revisor da issue
> 
### 3.5 Política de _pull request_
 
Assim como as _issues_, os _pull requests_ também devem seguir um template, sendo este:
 
> | Issue |
> |:-----:|
> |fixes #|
> 
> # Pull Request
> 
> ## 📖 Descrição
> 
> 
> Descrição do que foi feito.
> 
> 
> ### 🎫 Issues
> 
> 
> Listar e linkar a issues que foram finalizadas.
> 
> 
> ## 👩‍💻 Revisor(es)
> 
> 
> Comentarios para o revisor e marca-lo aqui.

## 4. Bibliografia

> [1] REHKOPF, Max. O que é um painel Kanban? Disponível em: https://www.atlassian.com/br/agile/kanban/boards. Acesso em: 13 abr. 2023.
>
> [2] SCHWABER, Ken; SUTHERLAND, Jeff. The 2020 Scrum Guide. Disponível em: https://scrumguides.org/scrum-guide.html. Acesso em: 13 abr. 2023.

## 5. Histórico de versão

|  Versão  |   Data   |                      Descrição                      |    Autor(es)   |  Revisor(es)  |
| -------- | -------- | --------------------------------------------------- | -------------- | ------------- |
|  `1.0`   | 13/04/23 | Criação e organização do artefato | Pedro Muniz | Samuel Alves |