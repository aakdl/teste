# PPC Prevision App

Este projeto é um aplicativo web React + Vite com login Microsoft (Azure AD), integração futura com API Prevision e painel PPC.

---

## ✅ Funcionalidades Atuais

- Login via Microsoft (Azure AD)
- Controle de acesso apenas para e-mails da empresa
- Rotas protegidas (Dashboard e Atividades)
- Estrutura pronta para consumo da API Prevision

---

## 🚀 Rodar no GitHub Codespaces (sem instalar nada)

### Pré-requisitos

- Conta GitHub com acesso ao Codespaces
- Este repositório clonado ou forkado na sua conta

### Passo a passo

1. Acesse este repositório no GitHub
2. Clique em **<> Code** → **Codespaces** → **Create codespace on main**
3. Aguarde abrir o VS Code Web
4. No terminal (inferior), rode:

```bash
npm install
npm run dev
```

5. Acesse a aplicação pela aba “Ports” → clique no link HTTP (ex: 3000)

---

## 📂 Estrutura

```bash
src/
├── App.tsx
├── main.tsx
├── auth/
│   └── msalConfig.ts
├── components/
│   ├── Header.tsx
│   └── PrivateRoute.tsx
└── pages/
    ├── Activities.tsx
    └── Dashboard.tsx
```

---

## 🔐 Configuração do Login Microsoft (Azure AD)

Já configurado para:

- Client ID: `dc784c34-xxxx`
- Tenant ID: `26bef5f1-xxxx`
- Redirect: `http://localhost:3000`
- Apenas contas organizacionais da empresa

---

## 📅 Próximas funcionalidades (em desenvolvimento)

- Listagem de atividades da semana via API GraphQL do Prevision
- Atualização de status (realizada/não realizada/restrição)
- Dashboard PPC com filtros por semana, obra, status
- Análise de restrições

---
