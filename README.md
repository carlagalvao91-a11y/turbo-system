# 📘 CONECTA - HR Management SaaS Platform

## 🎯 Objetivo

Plataforma SaaS completa para gestão operacional de Departamento Pessoal de escritórios contábeis.

## 📋 Funcionalidades Principais

### Perfis de Acesso
- **Administrador**: Acesso total ao sistema
- **Gerente/Líder**: Gestão de equipe e tarefas
- **Consultor DP**: Acesso à sua carteira e tarefas

### Módulos Principais

1. **Gestão de Carteira**
   - Import de clientes via CSV
   - Atribuição exclusiva a consultores
   - Rastreamento de CNPJ, contato, WhatsApp, email

2. **Gestor de Tarefas**
   - Matriz de Eisenhower (Urgente/Importante)
   - Status: Não iniciada, Em andamento, Aguardando cliente, Concluída, etc
   - Anexos obrigatórios por tipo de tarefa
   - Rastreamento de tempo

3. **Integração Portal Onvio**
   - Sincronização automática de solicitações
   - Criação automática de tarefas
   - Sincronização de documentos

4. **Calendário Operacional**
   - Interface similar ao Google Calendar
   - Rastreamento de prazos legais (FGTS, DCTFWeb, eSocial, 13º, DIRF, RAIS)
   - Drag-and-drop de tarefas

5. **Sistema de Pontuação**
   - Gamificação com ranking
   - Bônus: Conclusão antecipada, sem retrabalho, feedback positivo
   - Penalidades: Atrasos, erros, retrabalho

6. **Notificações WhatsApp**
   - Comunicação automática com clientes
   - Alertas internos: férias, documentos vencendo, tarefas atrasadas

7. **Dashboards Analíticos**
   - Indicadores em tempo real
   - Produtividade da equipe
   - SLA tracking
   - Ranking de consultores

8. **IA Assistente**
   - Priorização automática de tarefas
   - Detecção de atrasos
   - Sugestões de redistribuição
   - Resumos diários/semanais/mensais

## 🛠️ Stack Tecnológico

### Backend
- **Framework**: NestJS
- **Banco de Dados**: PostgreSQL
- **ORM**: Prisma
- **Autenticação**: JWT + RBAC
- **Filas**: Redis + BullMQ
- **Storage**: S3 compatível

### Frontend
- **Framework**: React 18
- **Linguagem**: TypeScript
- **Styling**: Tailwind CSS
- **State**: Redux Toolkit
- **UI**: Material-UI

### Infraestrutura
- **Containerização**: Docker & Docker Compose
- **Banco de Dados**: PostgreSQL 15
- **Cache**: Redis 7
- **Storage**: MinIO (S3 compatível)

## 🚀 Como Começar

### Pré-requisitos
- Node.js 18+
- Docker e Docker Compose
- Git

### Instalação Rápida

1. **Clone o repositório**
```bash
git clone https://github.com/carlagalvao91-a11y/conecta.git
cd conecta
