# 📝 Ata de Reunião - Kickoff Fase 0 & Validação

**Data:** 26/11/2025
**Horário:** 10h30
**Local:** Presencial

## 👥 Participantes
*   **Gerson** (Product Owner)
*   **Rayan** (Tech Lead)
*   **Bianca** (UX)
*   **Pedro Henrique** (Front-End)
*   **Pedro Soeiro** (Front-End)
*   **Guilherme** (Back-End)
*   **Mariana** (Usuária Principal)
*   **Johnatan** (DBA)

---

## 🗣️ Discussão e Definições

### 1. Validação Técnica (Infra & Arquitetura)
*   **Arquitetura Multi-Tenant:** ✅ Aprovada. Confirmado o uso de isolamento lógico via coluna `empresa_id` e Middleware para interceptação de contexto.
*   **Stack Tecnológica:** ✅ Confirmada.
    *   **Backend:** NestJS
    *   **Frontend:** Next.js
    *   **Banco de Dados:** SQL Server
*   **Infraestrutura de Banco de Dados:**
    *   Será utilizada a infraestrutura local (on-premise) que já possui alta capacidade.
    *   **Ponto de Atenção:** Necessidade de evolução na estratégia de backup (servidor físico externo/off-site), porém isso foi definido como **fora do escopo** deste projeto específico.
*   **Ambientes e Deploy:**
    *   **Dev:** Local.
    *   **Homologação/Prod:** Cloud (Azure).
    *   **CI/CD:** Pipeline via GitHub Actions.
    *   **Containerização:** Padronização via Docker confirmada.

### 2. UX/UI
*   **Protótipos (Diploma Digital):** 🔄 Em andamento.
    *   As telas foram revisadas com a equipe técnica e com a usuária principal (Mariana).
    *   Sugestões de melhoria foram coletadas e serão incorporadas pela Bianca.
*   **Identidade Visual:** ✅ Definida.
    *   O design do "Seletor de Empresa" e o Layout Base do portal foram aprovados.

### 3. Processos e Ferramentas
*   **Jira:** 🔄 Em andamento. O setup do projeto e backlog ainda precisa ser finalizado.
*   **Git Flow:** 🔄 Em andamento. As definições de branches e política de Code Review estão sendo alinhadas.

---

## ✅ Decisões Tomadas

1.  **Arquitetura:** Aprovada (Multi-tenant lógico).
2.  **Stack:** Confirmada (NestJS + Next.js + SQL Server).
3.  **Infra DB:** Uso de servidor local potente; Backup off-site é responsabilidade externa ao projeto.

---

## 🚀 Plano de Ação (Próximos Passos)

| Tarefa | Responsável | Prazo | Status |
| :--- | :--- | :--- | :--- |
| Criar projeto base Backend (NestJS + Middleware) | *A definir* | 28/11 | ⬜ |
| Criar projeto base Frontend (Next.js + Auth) | *A definir* | 28/11 | ⬜ |
| Configurar Pipeline CI/CD (Homologação) | *A definir* | 30/11 | ⬜ |
| Criar cards da Sprint 1 no Jira | *A definir* | 27/11 | ⬜ |
| Finalizar protótipo Diploma Digital (com ajustes) | **Bianca** | 29/11 | ⬜ |

> **Nota:** Os responsáveis pelas tarefas técnicas (Backend/Frontend/DevOps) precisam ser atribuídos no Jira.

---

## 📅 Próxima Reunião
**Data:** A definir
**Objetivo:** Acompanhamento do Setup e Review dos ajustes de UX.
