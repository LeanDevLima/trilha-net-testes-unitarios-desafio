# DIO - Trilha .NET - Testes Unitários com C#
[www.dio.me](www.dio.me)

## Desafio de projeto

Este projeto é parte do desafio proposto no módulo de Testes Unitários com C# e xUnit na trilha .NET da DIO.

## Objetivo do Desafio

O objetivo deste desafio é implementar testes unitários em um sistema que enfrenta problemas frequentes, como bugs, funcionalidades quebradas e problemas de validação. A proposta é utilizar testes unitários para garantir a qualidade do código e melhorar a confiança no sistema.

## Status do Desafio

O desafio foi concluído com sucesso. Foram implementados testes unitários para as classes `ValidacoesLista` e `ValidacoesString`, abrangendo diversos cenários positivos e negativos.

## Estrutura do Projeto

O projeto possui dois componentes principais:
- **Projeto Console:**
  - Classes principais: `ValidacoesLista` e `ValidacoesString`.
  - Métodos com lógicas de validação.

- **Projeto de Testes (xUnit):**
  - Classes de teste: `ValidacoesListaTests` e `ValidacoesStringTests`.
  - Métodos de teste para validar as lógicas do projeto console.

## Premissas

O sistema tem lógicas nas classes `ValidacoesLista` e `ValidacoesString`, enquanto os testes estão em projetos separados com classes de teste incompletas. O objetivo é implementar os métodos de teste necessários.

## Execução do Projeto

1. Clone o repositório.
2. Abra o terminal na raiz do projeto.
3. Execute `dotnet test` para executar os testes.

## Resultados Esperados

- Os testes devem passar com sucesso, cobrindo os cenários propostos, essa é a lista de testes disponíveis:

```bash
$ dotnet test
  Determinando os projetos a serem restaurados...
  Todos os projetos estão atualizados para restauração.
  TestesUnitarios.Desafio.Console -> C:\Users\Leanderson\OneDrive\Documentos\GitHub\trilha-net-testes-unitarios-desafio\TestesUnitarios.Desafio.Console\bin\Debug\net6.0\TestesUnitarios.Desafio.Console.dll
  TestesUnitarios.Desafio.Tests -> C:\Users\Leanderson\OneDrive\Documentos\GitHub\trilha-net-testes-unitarios-desafio\TestesUnitarios.Desafio.Tests\bin\Debug\net6.0\TestesUnitarios.Desafio.Tests.dll
Execução de teste para C:\Users\Leanderson\OneDrive\Documentos\GitHub\trilha-net-testes-unitarios-desafio\TestesUnitarios.Desafio.Tests\bin\Debug\net6.0\TestesUnitarios.Desafio.Tests.dll (.NETCoreApp,Version=v6.0)
Ferramenta de Linha de Comando de Execução de Teste da Microsoft (R) Versão 17.0.0
Copyright (c) Microsoft Corporation. Todos os direitos reservados.

Iniciando execução de teste, espere...
1 arquivos de teste no total corresponderam ao padrão especificado.

```
- A implementação deve fornecer rastreabilidade e controle do código gerando esse resultado:

```bash
$ dotnet test
  Determinando os projetos a serem restaurados...
  Todos os projetos estão atualizados para restauração.
  TestesUnitarios.Desafio.Console -> C:\Users\Leanderson\OneDrive\Documentos\GitHub\trilha-net-testes-unitarios-desafio\TestesUnitarios.Desafio.Console\bin\Debug\net6.0\TestesUnitarios.Desafio.Console.dll
  TestesUnitarios.Desafio.Tests -> C:\Users\Leanderson\OneDrive\Documentos\GitHub\trilha-net-testes-unitarios-desafio\TestesUnitarios.Desafio.Tests\bin\Debug\net6.0\TestesUnitarios.Desafio.Tests.dll
Execução de teste para C:\Users\Leanderson\OneDrive\Documentos\GitHub\trilha-net-testes-unitarios-desafio\TestesUnitarios.Desafio.Tests\bin\Debug\net6.0\TestesUnitarios.Desafio.Tests.dll (.NETCoreApp,Version=v6.0)
Ferramenta de Linha de Comando de Execução de Teste da Microsoft (R) Versão 17.0.0
Copyright (c) Microsoft Corporation. Todos os direitos reservados.

Iniciando execução de teste, espere...
1 arquivos de teste no total corresponderam ao padrão especificado.

Aprovado!  - Com falha:     0, Aprovado:     9, Ignorado:     0, Total:     9, Duração: 5 ms - TestesUnitarios.Desafio.Tests.dll (net6.0)
```


## Contribuição

Sinta-se à vontade para contribuir e melhorar este projeto. Se encontrar problemas ou melhorias, abra uma issue ou envie um pull request.

---

*Este readme foi gerado para documentar o desafio de testes unitários na trilha .NET da DIO.*
