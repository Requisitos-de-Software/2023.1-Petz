## Introdução

Especificação Suplementar é um documento que descreve requisitos adicionais ou complementares a uma especificação principal de um sistema ou produto. É usada para fornecer informações detalhadas e específicas que não foram incluídas na especificação principal, como requisitos de desempenho, de segurança, de usabilidade, de confiabilidade, de interoperabilidade, entre outros.

## Metodologia
Para realizar a especificação suplementar será utilizado o método FURPS+. O método FURPS (Functionality, Usability, Reliability, Performance, Supportability) é um modelo utilizado para classificar e descrever os principais atributos de qualidade de um sistema de software.  O "+", por sua vez, indica que existem outras categorias adicionais que podem ser consideradas.  O método FURPS+ ajuda a abordar uma variedade de requisitos de software de forma organizada, garantindo que todas as principais áreas sejam consideradas na especificação. Ele auxilia na compreensão abrangente das necessidades do usuário e no desenvolvimento de um sistema que atenda a essas necessidades de maneira completa e eficaz.

## Funcionalidades

A maioria das funcionalidades já estão descritas nos artefatos de [priorização de requisitos](../elicitacao/resultadoPriorizacao.md) e de [casos de uso](casos_de_uso.md).

* O Aplicativo deve coletar a localização do usuário, se o mesmo permitir.
* O aplicativo deve ser capaz de coletar informações pessoais e financeiras do usuário, se o mesmo permitir.
* O Aplicativo deve permitir coletar fotos e videos selecionadas pelo usuário, se o mesmo permitir.
* O aplicativo deve coletar informações de atividade no app para fornecer sugestões personalizadas.
* O aplicativo deve fornecer a opção de deletar os dados do usuário, se o mesmo solicitar.
* Os dados utilizados no aplicativo devem ser criptogrados em trânsito na rede.

## Usabilidade
Diz respeito à facilidade de uso e experiência do usuário. Inclui requisitos relacionados à interface do usuário, como layout, design, intuitividade e facilidade de aprendizado.

* O Aplicativo deve possuir ícones intuitivos que facilitem a navegação do usuário.
* O usuário consegue executar ações criticas em até 6 clicks.
* Os produtos devem ser dispostos em cards que facilitem a visualização e navegabilidade do usuário.
* A disposição dos elementos da interface devem seguir os conceitos de padronização para facilitar o reconhecimento do usuário e facilitar a assimilação com outros aplicativos.
* As cores utilizadas devem possuir um contraste adequado.

## Confiabilidade

Refere-se à capacidade do sistema de realizar suas funções de forma confiável e consistente ao longo do tempo. Inclui requisitos relacionados à disponibilidade, tolerância a falhas, capacidade de recuperação e manutenção da integridade dos dados.

* ### Disponibilidade

Envolve requisitos relacionados ao desempenho do sistema, como velocidade, tempo de resposta, escalabilidade e eficiência no uso de recursos, como memória e processamento.


* O Sistema deve estar disponivel 24/7, ou seja, 24 horas 7 dias por semana, com exceções para manutenções criticas.
* ### Tolerância a falhas

* O aplicativo deve ser capaz de lidar com falhas de maneira adequada, minimizando o impacto no usuário. Isso pode incluir a detecção de falhas e a manutenção da integridade dos dados mesmo em caso de falha.

* ### Segurança dos dados

* O aplicativo deve garantir a segurança dos dados do usuário. Isso envolve o uso de medidas de criptografia para proteger informações confidenciais, como dados pessoais e informações de pagamento, e implementar mecanismos de autenticação e autorização adequados.

* Performance consistente: O aplicativo deve oferecer um desempenho consistente e responsivo, mesmo em condições de alto tráfego ou carga intensa. 

## Desempenho
* Tempo de carregamento de imagens e conteúdo: todas as imagens devem ser carregadas em até 2 segundo, em condições normais.
* O aplicativo deve ter tempos de resposta rápidos para garantir uma experiência ágil aos usuários. Em até 2 segundos, considerando boas conexões de internet.
* O aplicativo deve ser escalável para acomodar um aumento no número de usuários e dados.
* O aplicativo deve ser capaz de lidar com um número específico de usuários simultaneamente sem comprometer o desempenho. 

## Suportabilidade
 
* O aplicativo deve ter documentação clara e abrangente, que forneça informações detalhadas sobre seu funcionamento, recursos, configuração e solução de problemas. Isso inclui manuais do usuário, guias de administração e documentação técnica para os desenvolvedores.

* O aplicativo deve permitir atualizações e melhorias regulares, fornecendo um mecanismo fácil para a instalação de novas versões.

* O aplicativo deve ser capaz de interagir e integrar-se com outros sistemas ou plataformas, seguindo padrões e protocolos de comunicação comuns.

*  O aplicativo deve fornecer canais de suporte técnico eficientes para os usuários, como chat em tempo real ou suporte por telefone.


## Restrição Fisica

* O aplicativo Petz pode ter requisitos específicos de hardware, como processador mínimo, quantidade de memória RAM e espaço de armazenamento necessário para instalação.

* Os usuários devem ter conectividade com a Internet para acessar os recursos e funcionalidades do aplicativo.

* É importante definir requisitos relacionados à resolução e ao tamanho mínimo da tela para garantir que a interface do aplicativo seja adequadamente exibida nos dispositivos dos usuários

* Sensor de localização é necessárioa para utilizar recursos de localização, como para encontrar lojas próximas ou rastrear a localização de um animal de estimação.

## Requisitos de Licença

* O aplicativo deve apresentar termo de uso para que o usuário concorde ou não com as informações contidas neste documento.

## Jurídico, Copyright e Outros Avisos

* O aplicativo está sujeito a politicas de privacidade obrigatórias para a utilização.
* O app não deve compartilhar nenhum dado do usuário, que não tenha sido previamente autorizado, com terceiros.







## Referências bibliográficas

SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 13. 11 jan. 2019. Apresentação em pdf. Disponível em: link.  Acesso em 15 de Maio de 2022.

GOIS, Samily; SOBRINHO, Francisco: Projeto de Software Floricultura Beija-Flor - Especificação Suplementar, 27 outubro de 2012. Disponível em: [link](https://silo.tips/download/php-software-company-samily-rocha-gois-francisco-luiz-sobrinho-projeto-de-softwa). Acesso em 16 de Maio 2022

Desenvolver Especificações suplementares. disponivel em: [link](https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/tasks/develop_supplementary_specification_52FC4CAE.html). Acesso em 16 de maio de 2023
Aplicativo Petz. Disponível em : https://play.google.com/store/apps/details?id=br.com.petz



## Histórico de versão

|  Versão  |   Data   |                      Descrição                      |    Autor(es)   |  Revisor(es)  |
| -------- | -------- | --------------------------------------------------- | -------------- | ------------- |
|  `1.0`   | 16/05/23 | Criação da primeira versão do artefato Especificação suplementar | Vitor Manoel   | Felipe Corrêa |

