# CP02.NET

## Descrição

O **CP2 Application** é uma aplicação web desenvolvida com **ASP.NET Core**, que utiliza **Entity Framework Core** para interações com banco de dados Oracle. A aplicação permite gerenciar **vendedores** e **fornecedores**, incluindo funcionalidades como criar, editar, deletar e listar registros. Esta aplicação segue uma arquitetura organizada em camadas (Domain, Application, Data, API, IoC).

## Estrutura do Projeto

O projeto é dividido em várias camadas:

- **CP2.Domain**: Contém as entidades e interfaces do domínio da aplicação.
- **CP2.Application**: Contém a lógica de negócios e as regras de validação. Esta camada implementa os serviços que utilizam os repositórios.
- **CP2.Data**: Responsável pela interação com o banco de dados utilizando o Entity Framework Core.
- **CP2.API**: Fornece a API RESTful, com endpoints para as operações CRUD de fornecedores e vendedores.
- **CP2.IoC**: Configura a Injeção de Dependência (Dependency Injection) para os serviços e repositórios.

## Funcionalidades

- **Gerenciamento de Fornecedores**:
  - Adicionar, editar, deletar e listar fornecedores.
- **Gerenciamento de Vendedores**:
  - Adicionar, editar, deletar e listar vendedores.

## Tecnologias Utilizadas

- **ASP.NET Core 8.0**
- **Entity Framework Core 8.0** (com suporte para Oracle)
- **Oracle Database** para armazenamento de dados
- **Swagger** para documentação automática da API
- **FluentValidation** para validações nos DTOs

## Instalação

### Pré-requisitos

- **.NET 8.0 SDK** ou superior
- **Banco de Dados Oracle** configurado
- **Oracle Entity Framework Core Package** instalado
- Um editor como **Visual Studio** ou **Visual Studio Code**
