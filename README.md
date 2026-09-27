# Hello World xUnit

Projeto desenvolvido para a disciplina de Garantia da Qualidade de Software / Gestão e Qualidade de Software.

## Sobre o projeto

O projeto consiste na criação de uma solução .NET com dois projetos:

- **MeuPrimeiroTeste.App**: projeto da aplicação, contendo a classe `HelloWorldService`, responsável por retornar a mensagem "Hello, World!".
- **MeuPrimeiroTeste.Tests**: projeto de testes unitários utilizando xUnit para verificar o funcionamento da aplicação.

O objetivo é praticar a criação de uma solução .NET, a implementação de testes unitários e o versionamento do código utilizando Git e GitHub.

## Tecnologias utilizadas

- .NET 10
- C#
- xUnit
- Git
- GitHub

## Estrutura do projeto

```text
olamundo-net-xunit/
├── MeuPrimeiroTeste.App/
│   ├── HelloWorldService.cs
│   ├── MeuPrimeiroTeste.App.csproj
│   └── Program.cs
│
├── MeuPrimeiroTeste.Tests/
│   ├── HelloWorldServiceTests.cs
│   └── MeuPrimeiroTeste.Tests.csproj
│
├── MeuPrimeiroTeste.slnx
├── .gitignore
├── LICENSE
└── README.md
```

## Como executar

### Executar a aplicação

No terminal, dentro da pasta do projeto, execute:

```bash
dotnet run
```

### Executar os testes

Para executar os testes unitários, utilize:

```bash
dotnet test
```

Os testes devem ser executados com sucesso.

## Objetivo

Praticar a criação de uma solução .NET, o desenvolvimento de testes unitários com xUnit e o versionamento de projetos utilizando Git e GitHub.


## Sobre os Autores
- Alice Fernandes Barbosa - @alicefbarbosa - 326128348
- Ana Carolina de Sousa Freitas - @AnaFreitas1 - 325132932

