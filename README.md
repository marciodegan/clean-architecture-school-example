### This is a project to demonstrate Clean Architecture based on Alura course: https://cursos.alura.com.br/course/java-clean-architecture

#### Somes notes:
- Componentes do software e suas relações
- Infraestrutura do software
- Estrutura e design do código
- Suporte aos requisitos de negócio
- Simplificar evoluções no software
- Arquitetura também está fortemente relacionada com os Requisitos não funcionais do software: Performance, Escalabilidade, Disponibilidade, Confiabilidade, Segurança, Manutenibilidade e Extensibilidade.
- More: https://resources.sei.cmu.edu/library/asset-view.cfm?assetid=513807

- Arquitetura em Camadas: MVC -> User Interface, Business (regras de negócio), Data(persistencia de dados)
- Onion Architecture: 
- Clean Architecture: Isolar o codigo de dominio da aplicacao, pra fazer a ponte é usado inversão de dependencias atraves de interfaces.
- Favorece boas práticas de OO
- Codigo de dominio com alta "testabilidade"
- Independencia de frameworks e detalhes de infraestrutura

- Screaming Architecture: https://blog.cleancoder.com/uncle-bob/2011/09/30/Screaming-Architecture.html
- o nosso domínio (camada mais interna) é independente de qualquer detalhe exterior. Nossa aplicação depende apenas do nosso domínio, e não conhece detalhes de infraestrutura. A camada de infraestrutura apoia as camadas mais interiores.

>Ao desenvolver um sistema complexo, o domínio deve ser o foco. Por isso, ele é a camada central dos padrões de arquitetura.
>
>Web, frameworks e mecanismos de persistência (como bancos de dados) são meros detalhes. São ferramentas para executar suas regras de negócio.
>
>Executar a sua aplicação pela CLI deve ser tão fácil quanto através de uma API. O mesmo vale para uma interface Web.
>
>O conceito de modelarmos a nossa aplicação pensando primeiramente no domínio é chamado de Domain Driven Design, ou design orientado a domínio.
> 
>Munidos desta mentalidade, podemos garantir uma melhor manutenibilidade e extensibilidade de nosso projeto.