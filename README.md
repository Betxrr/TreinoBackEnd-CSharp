# 🚀 PoC: Migração de Arquitetura (Node.js para C# .NET 8)

**Este repositório registra o meu primeiro contato prático com o ecossistema .NET, replicando a lógica de uma API de fundamentos desenvolvida anteriormente em Node.js.**

## 🎯 Objetivo do Estudo
O foco deste projeto foi realizar um "De-Para" técnico: pegar os conceitos de rotas, controllers e integração com SQL Server aprendidos em JavaScript/Node e aplicá-los em um ambiente **fortemente tipado** e robusto como o C# .NET 8.

## 🧠 Desafios da Transição
Nesta Prova de Conceito (PoC), explorei as principais diferenças entre as stacks:

* **Tipagem Estática:** Adaptação da lógica flexível do JavaScript para o rigor das classes e tipos do C#.
* **Estrutura ASP.NET Core:** Entendimento do ciclo de vida de uma Web API em .NET 8.
* **Injeção de Dependência:** Primeiros passos com os padrões nativos do framework para gerenciar conexões e serviços.
* **ADO.NET / SQL Client:** Integração com SQL Server utilizando as bibliotecas nativas do ecossistema Microsoft.

## 🛠️ Stack Técnica
* **Linguagem:** C#
* **Framework:** .NET 8 (Web API)
* **Banco de Dados:** SQL Server
* **Ferramenta de Teste:** Postman / Swagger (OpenAPI)

## 🏗️ O que foi implementado
O projeto foca no núcleo de uma API de inventário:
1. Configuração de conexão com banco de dados via `appsettings.json`.
2. Criação de Controllers para manipulação de dados.
3. Modelagem simples de entidades para garantir a tipagem correta no tráfego de JSON.

---
*Este é um projeto de transição técnica e aprendizado inicial em C#. O objetivo é evoluir este código à medida que me aprofundo nos padrões Enterprise do .NET.*
