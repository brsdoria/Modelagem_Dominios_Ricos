# Modelagem de Domínios Rico 

## 📝️ Escopo do Projeto

<p align="justify"> 
O projeto tem como objetivo ensinar a aplicação prática de padrões de modelagem de domínios ricos, com foco em DDD (Domain-Driven Design), CQRS e Event Sourcing. Além da teoria essencial, será utilizado .NET C# com orientação a objetos correta, incorporando os princípios do SOLID e Design Patterns. Envolve também o desenvolvimento de uma aplicação de e-commerce, abordando conceitos como carrinho de compras, clientes e pedidos. Aprenderemos a aplicar DDD e entender quando é adequado adotar ou simplificar certos padrões, reconhecendo a importância de escolher a complexidade correta para a solução.
</p>

## 🛠️ Construído com

* [Visual Studio 2022](https://learn.microsoft.com/pt-br/visualstudio/windows/?view=vs-2022) - Ferramenta de desenvolvimento, que permite realizar todo o ciclo de desenvolvimento em um só lugar.

## 📚 Principais Bibliotecas, Frameworks e Comandos do NuGet Utilizados

* [netcoreapp2.2](https://learn.microsoft.com/pt-br/dotnet/core/whats-new/dotnet-core-2-2) - Versão específica do .NET Core, que é uma plataforma de desenvolvimento da Microsoft para criar aplicações modernas e multiplataforma. O .NET Core 2.2 foi uma das versões do .NET Core lançadas em 2018.

```
NuGet\Install-Package Microsoft.NETCore.App -Version 2.2.0
```

* [Microsoft.AspNetCore.Http](https://learn.microsoft.com/pt-br/dotnet/core/whats-new/dotnet-core-2-2) - Namespace no ASP.NET Core que fornece classes e interfaces essenciais para o trabalho com requisições HTTP (requests), respostas HTTP (responses), cookies, sessões, cabeçalhos, entre outros aspectos relacionados ao protocolo HTTP em aplicações web.

```
NuGet\Install-Package Microsoft.AspNetCore.Http -Version 2.2.0
```

* [MediatR](https://medium.com/tableless/mediatr-com-asp-net-core-7b98ba0ca640) - Padrão de projeto para promove o baixo acoplamento entre os objetos e a aplicação, permitindo que se comuniquem sem conhecer suas estruturas.

```
NuGet\Install-Package MediatR -Version 7.0.0
```

* [AutoMapper](https://automapper.org/) - Biblioteca de mapeamento de objetos facilita a conversão de dados entre objetos de tipos diferentes, evitando código repetitivo.

```
NuGet\Install-Package AutoMapper -Version 6.1.1
``` 

* [Microsoft.NET.Test.Sdk](https://learn.microsoft.com/pt-br/dotnet/core/tools/dotnet-test) - Fornece o suporte necessário para executar testes unitários. Ele é uma parte fundamental do framework de testes para projetos que utilizam ferramentas como o xUnit, NUnit ou MSTest.

```
NuGet\Install-Package Microsoft.NET.Test.Sdk -Version 16.0.1
```

* [FluentValidation](https://docs.fluentvalidation.net/en/latest/) - Biblioteca de validação de dados para aplicações .NET que permite validar objetos.

```
NuGet\Install-Package FluentValidation -Version 8.4.0
```

* [xunit](https://xunit.net/) - Framework de testes unitários para aplicações .NET

```
NuGet\Install-Package xunit -Version 2.4.0
```

* [Microsoft.EntityFrameworkCore](https://learn.microsoft.com/pt-br/ef/core/get-started/overview/install) - ORM para interagir com bancos de dados usando objetos.

```
NuGet\Install-Package Microsoft.EntityFrameworkCore -Version 2.2.6
```

## 🚧 Descrição da Estrutura do Projeto

A estrutura do projeto segundo a imagem abaixo é composta da seguinte forma:

![EstruturaDoProjeto](screenshots/estrutura.PNG)

## ⚠️ Atenção

Destinado exclusivamente para fins de estudo.

---
⌨️ por [Byron Doria](https://github.com/brsdoria) 😊
