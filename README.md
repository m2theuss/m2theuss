<h1 align="center">Matheus de Oliveira Mota</h1>

<h3 align="center">Full Stack Developer | C# / .NET | Angular | Cloud (AWS & Azure)</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/mmota-matheus/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:motamatheusdev@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="E-mail" /></a>
  <a href="https://motamatheus.com.br/"><img src="https://img.shields.io/badge/Portf%C3%B3lio-24292F?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfólio" /></a>
</p>

<p align="center">
  <a href="#sobre-mim">Sobre</a> |
  <a href="#stack-técnica">Stack Técnica</a> |
  <a href="#projetos-em-destaque">Projetos</a> |
  <a href="#princípios-de-engenharia">Engenharia</a> |
  <a href="#contato">Contato</a>
</p>

---

## Sobre mim

Desenvolvedor Full Stack com mais de 2 anos de experiência profissional no desenvolvimento, manutenção e sustentação de sistemas web, APIs RESTful, integrações entre serviços e bancos de dados relacionais.

Meu foco principal está no ecossistema **C# / .NET**, desenvolvimento frontend com **Angular** e ambientes cloud (**AWS** e **Azure**). Tenho atuação prática na resolução de gargalos de performance em produção, otimização de consultas e procedures SQL, controle de concorrência e construção de aplicações testáveis com foco em segurança e manutenibilidade.

* **Localização:** Cachoeiro de Itapemirim, ES, Brasil
* **Formação:** Bacharelado em Sistemas de Informação (em andamento)
* **Idiomas:** Português (Nativo) | Inglês (Avançado)

## Stack técnica

<p align="left">
  <a href="https://skillicons.dev" aria-label="Tecnologias principais">
    <img src="https://skillicons.dev/icons?i=cs,dotnet,angular,ts,aws,azure,postgres,docker,git&perline=9" alt="C#, .NET, Angular, TypeScript, AWS, Azure, PostgreSQL, Docker e Git" />
  </a>
</p>

| Área | Tecnologias e Ferramentas |
| :--- | :--- |
| **Backend & APIs** | C#, .NET / ASP.NET Core, Entity Framework Core, Java, Spring Boot, Node.js, APIs RESTful, Mensageria (Kafka, SQS/SNS) |
| **Frontend** | Angular, TypeScript, JavaScript (ES6+), RxJS, React, HTML5, CSS3 |
| **Dados & Cache** | PostgreSQL, SQL Server, Oracle PL/SQL, MySQL, SQLite, Redis, Otimização de Queries e Stored Procedures |
| **Cloud & DevOps** | AWS (EC2, S3, Lambda, API Gateway), Microsoft Azure (App Service, Azure SQL, Blob Storage, Azure DevOps), Docker, Docker Compose, CI/CD, Git |
| **Engenharia & Qualidade** | Arquitetura em Camadas, POO, SOLID, Clean Code, Design Patterns, Testes Unitários (xUnit, JUnit 5, Moq, Mockito) |

## Projetos em destaque

### [Overload | API REST de Treinos e Rotinas](https://github.com/m2theuss/overload-csharp)

<p align="left">
  <a href="https://github.com/m2theuss/overload-csharp"><img src="https://img.shields.io/badge/Status-Em%20desenvolvimento-D97706?style=flat-square" alt="Em desenvolvimento" /></a>
  <a href="https://github.com/m2theuss/overload-csharp"><img src="https://img.shields.io/badge/.NET-10%20%7C%20C%23%2012-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET 10 e C# 12" /></a>
  <a href="https://github.com/m2theuss/overload-csharp"><img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" /></a>
  <a href="https://github.com/m2theuss/overload-csharp"><img src="https://img.shields.io/badge/Testes-29%20aprovados-2F855A?style=flat-square" alt="29 testes aprovados" /></a>
</p>

API RESTful desenvolvida em C# e ASP.NET Core 10 para gerenciamento de catálogos de exercícios e organização de rotinas semanais de treino. O projeto implementa autenticação stateless com JWT, proteção de senhas com BCrypt, controle de acesso por proprietário e tratamento padronizado de exceções com `ProblemDetails`.

* **Arquitetura e persistência:** Separação em camadas (Controllers, Services, DTOs, Entities, Data e Exceptions) com Entity Framework Core, migrations e PostgreSQL.
* **Qualidade e testes:** Suíte com 29 testes unitários automatizados utilizando xUnit, Moq e SQLite em memória, validando regras de domínio e autenticação sem depender de banco externo.
* **Documentação de uso:** Coleção de requisições HTTP estruturada no Bruno e instruções completas de configuração via variáveis de ambiente.

**Tecnologias:** C# 12, ASP.NET Core 10, Entity Framework Core, PostgreSQL, JWT, BCrypt, xUnit, Moq.

[Ver código e documentação](https://github.com/m2theuss/overload-csharp)

---

### [Makro Bank | Aplicação Bancária em Camadas](https://github.com/m2theuss/makro-bank)

<p align="left">
  <a href="https://github.com/m2theuss/makro-bank"><img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-2F855A?style=flat-square" alt="Concluído" /></a>
  <a href="https://github.com/m2theuss/makro-bank"><img src="https://img.shields.io/badge/Java-21-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java 21" /></a>
  <a href="https://github.com/m2theuss/makro-bank"><img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" /></a>
</p>

Aplicação bancária desenvolvida em Java puro para consolidar fundamentos de arquitetura em camadas, persistência relacional e orientação a objetos sem dependência de frameworks. Suporta cadastro e autenticação de contas, consultas de saldo, depósitos, saques e transferências.

**Tecnologias:** Java 21, JDBC, SQLite, Maven, Arquitetura em Camadas.

[Ver código e instruções de execução](https://github.com/m2theuss/makro-bank)

## Princípios de engenharia

* **Manutenibilidade e Clareza:** Código estruturado com responsabilidades bem definidas, nomes expressivos e complexidade proporcional ao problema.
* **Contratos e Confiabilidade:** APIs RESTful com validação rigorosa de entrada, autenticação segura e tratamento consistente de erros.
* **Performance e Dados:** Atenção contínua a planos de execução, controle de concorrência em transações e modelagem relacional eficiente.
* **Testabilidade e Entrega:** Automação de testes unitários no padrão AAA e configuração externalizada para ambientes reproduzíveis.

## Contato

<p align="left">
  <a href="https://www.linkedin.com/in/mmota-matheus/">LinkedIn</a> |
  <a href="mailto:motamatheusdev@gmail.com">motamatheusdev@gmail.com</a> |
  <a href="https://motamatheus.com.br/">motamatheus.com.br</a>
</p>
