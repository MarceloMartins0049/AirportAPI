# ✈️ Airport Management System API

Uma **WebAPI** robusta desenvolvida em **C# / .NET** para o gerenciamento completo de operações aeroportuárias, focada em escalabilidade e performance.

## 🚀 Sobre o Projeto

Este sistema foi projetado para centralizar o controle de voos, gestão de frotas de aeronaves e processamento de passageiros. A API segue os princípios de **Clean Architecture** e utiliza as melhores práticas do ecossistema .NET moderno.

## 🛠️ Tecnologias e Ferramentas

* **Linguagem:** C# (.NET 9)
* **Framework:** ASP.NET Core WebAPI
* **Persistência:** Entity Framework Core
* **Banco de Dados:** SQL Server / PostgreSQL (via Docker)
* **Documentação:** Swagger (OpenAPI)
* **Containerização:** Docker & Docker Compose

## 📌 Funcionalidades Principais

- [x] **Gestão de Aeronaves:** Cadastro, manutenção e status de disponibilidade.
- [x] **Controle de Destinos:** Cadastro de aeroportos e rotas internacionais.
- [ ] **Monitoramento de Voos:** Painel de partidas e chegadas em tempo real.
- [ ] **Sistema de Check-in:** Alocação de assentos e validação de passageiros.
- [ ] **Relatórios:** Emissão de logs de tráfego aéreo e ocupação.

## 📦 Como Rodar o Projeto

### Pré-requisitos
* SDK do .NET (versão 9.0+)
* Docker instalado (opcional, para banco de dados)

### Instalação

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/nome-do-repo.git](https://github.com/seu-usuario/nome-do-repo.git)
    ```

2.  **Restaure as dependências:**
    ```bash
    dotnet restore
    ```

3.  **Execute as Migrations (Banco de Dados):**
    ```bash
    dotnet ef database update
    ```

4.  **Inicie a aplicação:**
    ```bash
    dotnet run
    ```

Acesse a documentação interativa em: `https://localhost:5001/swagger`

## 🏗️ Estrutura de Pastas

* `src/Application`: Regras de negócio e DTOs.
* `src/Domain`: Entidades e interfaces centrais.
* `src/Infrastructure`: Repositórios e conexões externas.
* `src/API`: Controllers e configurações de entrada.

---
⌨️ desenvolvido por [Seu Nome] - 2026
