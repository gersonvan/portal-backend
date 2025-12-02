# Portal Administrativo - Backend

## 🎯 Sobre

API REST do Portal Administrativo para AVP e Unigrande. Construída com NestJS 10, TypeScript e SQL Server.

## 🏗️ Arquitetura Polirepo

- **[portal-frontend](https://github.com/gersonvan/portal-frontend)** - Interface Next.js
- **[portal-backend](https://github.com/gersonvan/portal-backend)** ← Você está aqui
- **[portal-infrastructure](https://github.com/gersonvan/portal-infrastructure)** - Docker, CI/CD
- **[portal-docs](https://github.com/gersonvan/portal-docs)** - Documentação

## 🚀 Stack Tecnológica

- **Framework:** NestJS 10
- **Linguagem:** TypeScript
- **Database:** SQL Server 2022
- **ORM:** TypeORM (ou Prisma)
- **Auth:** Azure AD + JWT
- **Storage:** Azure Blob Storage

## 📋 Pré-requisitos

- Node.js 20.x
- SQL Server 2022
- npm 10.x

## 🔧 Quick Start

```bash
git clone https://github.com/gersonvan/portal-backend.git
cd portal-backend
npm install

# Configure .env
cp .env.example .env

# Inicie
npm run start:dev
```

API disponível em: http://localhost:3001

## 📝 Variáveis de Ambiente

```env
DATABASE_HOST=localhost
DATABASE_PORT=1433
DATABASE_USERNAME=sa
DATABASE_PASSWORD=senha
DATABASE_NAME=PortalAdministrativo
JWT_SECRET=seu-secret
AZURE_AD_TENANT_ID=
AZURE_AD_CLIENT_ID=
```

## 🧪 Testes

```bash
npm run test          # Unit tests
npm run test:e2e      # E2E tests
npm run test:cov      # Coverage
```

## 📚 Documentação

Ver [portal-docs](https://github.com/gersonvan/portal-docs)

## 🔗 Repositórios Relacionados

- [Frontend](https://github.com/gersonvan/portal-frontend)
- [Infrastructure](https://github.com/gersonvan/portal-infrastructure)
- [Docs](https://github.com/gersonvan/portal-docs)
