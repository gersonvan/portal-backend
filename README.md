# Portal Administrativo - AVP/Unigrande

## Visão Geral

Este repositório contém a documentação técnica e de planejamento para o projeto do novo Portal Administrativo unificado para as empresas AVP e Unigrande. O objetivo é criar uma plataforma moderna, escalável e multi-tenant, que servirá como uma base ("rack") para diversos módulos de negócios, como o "Diploma Digital", entre outros.

A documentação aqui presente é um espelho da fonte de verdade mantida no Github, servindo como um recurso essencial para a equipe de desenvolvimento.

## Estrutura da Documentação

Toda a documentação do projeto está centralizada na pasta `/docs`. A estrutura foi reorganizada por domínios para facilitar a escalabilidade:

- **/docs/management**: Documentação de Gestão e Produto.
  - [Roadmap Executivo](docs/management/ROADMAP_EXECUTIVO.md): Visão macro do projeto, fases e entregas.
  - [Backlog](docs/management/BACKLOG.md): Backlog de funcionalidades e requisitos.
  - [Requisitos Gerais](docs/management/REQUIREMENTS.md): Requisitos de alto nível.
  - [Plano de Migração](docs/management/MIGRATION_PLAN.md): Estratégia de migração do legado.
- **/docs/technical**: Documentação Técnica e Arquitetural.
  - [Arquitetura Core](docs/technical/architecture/CORE_ARCHITECTURE.md): Detalhes da arquitetura multi-tenant, tecnologias e padrões.
  - [Arquitetura Multi-Tenant](docs/technical/architecture/MULTI_TENANT.md): Detalhes específicos da implementação multi-tenant.
  - [Diagramas](docs/technical/architecture/DIAGRAMAS.md): Fluxos e desenhos técnicos.
  - [Padrões de Desenvolvimento](docs/technical/standards/DEVELOPMENT_STANDARDS.md): Padrões de código, commits e branchs.
- **/docs/business-modules**: Documentação específica por Módulo de Negócio.
  - **/academico/diploma-digital**:
    - [Gerenciamento de Projeto](docs/business-modules/academico/diploma-digital/PROJECT_MANAGEMENT.md): Documentação do módulo Diploma Digital.
- **/docs/legacy**: Arquivos de trabalho e versões antigas da documentação.

## Arquitetura e Tecnologias

A solução está sendo desenvolvida com uma arquitetura de micro-serviços e front-end desacoplado, utilizando as seguintes tecnologias:

- **Frontend**: React 18 + Next.js 14.x (TypeScript)
- **Backend**: Node.js + NestJS 10.x (TypeScript)
- **Banco de Dados**: SQL Server (Infra Local / On-Premise)
- **Autenticação**: Azure AD
- **Armazenamento**: Azure Blob Storage

Para mais detalhes, consulte o documento de [Arquitetura Core](docs/technical/architecture/CORE_ARCHITECTURE.md).

## Como Começar

1.  **Explore a Documentação**: Comece pelo [Roadmap Executivo](docs/management/ROADMAP_EXECUTIVO.md) para uma visão geral e depois mergulhe nos documentos de [Arquitetura Core](docs/technical/architecture/CORE_ARCHITECTURE.md).
2.  **Ambiente de Desenvolvimento**: Siga as instruções em [Padrões de Desenvolvimento](docs/technical/standards/DEVELOPMENT_STANDARDS.md) para configurar seu ambiente e entender nosso fluxo de trabalho com Git.
3.  **Backlog**: Consulte o [Backlog](docs/management/BACKLOG.md) para entender as próximas tarefas.

## Contato

- **Product Owner**: Gerson
- **Tech Lead**: Rayan
- **UX**: Bianca
- **Front-End**: Pedro Henrique
- **Back-End**: Guilherme / Pedro Soeiro
