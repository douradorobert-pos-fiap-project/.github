# FIAP — Tech Challenge | Software Architecture

Repositórios do projeto desenvolvido durante a pós-graduação em Arquitetura de Software da FIAP.

O projeto consiste no desenvolvimento e na evolução arquitetural de um sistema de gerenciamento de oficina mecânica, contemplando clientes, veículos, ordens de serviço, orçamentos e execução de serviços.

## Evolução arquitetural

### Fase 3 — Arquitetura em nuvem e observabilidade

Implementação de uma aplicação backend com FastAPI, executada em ambiente Kubernetes na AWS.

Principais tecnologias:

- Python e FastAPI
- PostgreSQL
- AWS EKS, RDS, API Gateway e Lambda
- Docker e Kubernetes
- Terraform
- GitHub Actions
- New Relic

**Status:** Entrega finalizada.

A versão entregue está preservada nas releases `fase-3-final` dos respectivos repositórios.

### Fase 4 — Arquitetura de microsserviços

Evolução da aplicação para uma arquitetura distribuída, com serviços independentes e comunicação assíncrona.

Principais objetivos:

- Separação das responsabilidades de negócio em microsserviços.
- Bancos de dados independentes.
- Comunicação orientada a eventos.
- Implementação do Saga Pattern.
- Resiliência e consistência de transações distribuídas.
- Pipelines independentes de CI/CD.

**Status:** Planejamento.

## Repositórios

### Aplicação e infraestrutura da Fase 3

| Repositório | Responsabilidade |
|---|---|
| [tech-challenge-fiap](https://github.com/douradorobert-pos-fiap-project/tech-challenge-fiap) | Aplicação backend original |
| [shared-infra](https://github.com/douradorobert-pos-fiap-project/shared-infra) | Infraestrutura AWS compartilhada |
| [database-infra](https://github.com/douradorobert-pos-fiap-project/database-infra) | Infraestrutura de banco de dados |
| [cpf-validator](https://github.com/douradorobert-pos-fiap-project/cpf-validator) | Serviço serverless de validação de CPF |

### Documentação técnica

A documentação arquitetural está centralizada no repositório:

[architecture-docs](https://github.com/douradorobert-pos-fiap-project/architecture-docs)

Nele estão registrados os diagramas, as integrações, as decisões arquiteturais e as referências das entregas.

## Versionamento

As versões finais de cada fase são identificadas por GitHub Releases.

A documentação preserva as referências dos componentes utilizados em cada entrega, permitindo consultar a evolução da solução ao longo do curso.