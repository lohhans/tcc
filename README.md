# Trabalho de Conclusão de Curso - Graduação em [Ciência da Computação](http://bcc.ufape.edu.br/) da [Universidade Federal do Agreste de Pernambuco](http://ufape.edu.br/)

## Template do Documento
Este Trabalho pode ser utilizado como template para Trabalhos de Conclusão de Curso (TCC) na [Universidade Federal do Agreste de Pernambuco](http://ufape.edu.br/) (UFAPE) em formato Latex, deve ser editado preferencialmente no [Overleaf](https://www.overleaf.com/).

Disponibilizado pelos docentes da instituição acima citada e adaptado com as informações mais recentes por mim, Armstrong Lohãns, discente concluinte do curso de [Ciência da Computação](http://bcc.ufape.edu.br/) (BCC).

## Enzitech - Sistema de experimentos para cálculo de atividades enzimáticas do solo
![👋 Olá! (1)](https://user-images.githubusercontent.com/30741312/232361196-5d8dc1ca-6b6c-41df-8cc7-131cdba98591.png)

## Objetivo Geral
Este trabalho tem como objetivo detalhar a solução e o processo de desenvolvimento de uma aplicação para dispositivos móveis que informatize o método de fazer experimentos e análises do solo, aplicativo este desenvolvido usando padrões arquiteturais limpos, escaláveis, manuteníveis e testáveis.

## Objetivos específicos
Com base no objetivo geral, correspondem os objetivos específicos indicados a seguir:
- Implementar um sistema, acessível via aplicativo móvel, que permite criar e gerenciar experimentos que realizem cálculos das AEs do solo;
- Gerar resultados e planilhas de forma automática;
- Possibilitar a análise dos resultados;
- Proporcionar uma experiência fluida de navegação no aplicativo, ao utilizar boas práticas de desenvolvimento de software.


## Trabalho desenvolvido
* [Clique aqui para visualizar o TCC completo](https://github.com/lohhans/tcc/blob/main/tcc_armstrong.pdf)
* [Clique aqui para visualizar o resumo do TCC](https://github.com/lohhans/tcc/blob/main/tcc_resumido_armstrong.pdf)

---

## Tecnologias Utilizadas
O uso de tecnologias populares e bem consolidadas facilita o desenvolvimento e manutenção e também torna os sistemas compatíveis com a maioria dos dispositivos existentes no mercado.

## Prototipagem
A prototipagem do sistema foi feita majoritariamente no [Figma](https://www.figma.com/), devido sua facilidade de uso, colaboração em tempo real e recursos de design avançados.

### Banco de Dados
O [PostgreSQL](https://www.postgresql.org/) foi escolhido como sistema de gerenciamento de banco de dados devido sua confiabilidade, escalabilidade, suporte a recursos avançados, segurança e comunidade de desenvolvedores ativa.

### Back-end/API
A lógica de negócio foi desenvolvida utilizando a linguagem de programação [TypeScript](https://www.typescriptlang.org/), junto do framework [Nest.js](https://nestjs.com/), que auxilia o desenvolvimento de aplicações eficientes, escaláveis e confiáveis, em ambiente [Linux](http://www.linux.org). Com segurança e codificação totalmente orientada a objetos, o sistema aproveita os melhores recursos de segurança e desempenho do servidor.

### Comunicação
A comunicação entre o aplicativo mobile com o sistema do Enzitech implantado é feito utilizando o protocolo [HTTP](https://pt.wikipedia.org/wiki/Hypertext_Transfer_Protocol) e comunicação [REST](https://pt.wikipedia.org/wiki/REST) que não depende dos detalhes de implementação, temos assim a posibilidade de comunicação e integração com uma infinidade de outros sistemas e tecnologias.

### Sistema Mobile
Todo o aplicativo do Enzitech foi desenvolvido para a plataforma [Android](http://www.android.com). Utilizando o framework [Flutter](https://flutter.dev/) para o desenvolvimento da interface de usuário e a linguagem de programação [Dart](https://dart.dev/) para interação com a API.

## Modelagem do Banco de dados
![image](https://raw.githubusercontent.com/lohhans/tcc/main/images/er.jpg)

## Arquitetura simplificada da infraestrutura do Enzitech
![image](https://raw.githubusercontent.com/lohhans/tcc/main/images/arquitetura_enzitech.png)

> O código fonte do aplicativo e do back-end podem ser acessados nos links abaixo:
> - [Aplicativo](https://github.com/bcccoworkingufape/enzitech_app)
> - [Back-end](https://github.com/bcccoworkingufape/enzitech)

