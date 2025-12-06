

---

# 🌿 Malwee Dashboard

O **Malwee Dashboard** é um sistema de Integração e Monitoramento da Produção Têxtil desenvolvido com **React**, **TypeScript**, **Tailwind CSS** e a **biblioteca interna da Malwee** para garantir padronização visual e consistência com a identidade da empresa.
O projeto oferece um dashboard moderno para acompanhar métricas, status e dados de máquinas têxteis, incluindo autenticação segura via **JWT**.

---

## 🚀 Tecnologias Utilizadas

* **React** — Interface dinâmica e componentizada
* **TypeScript** — Tipagem estática para maior segurança
* **Tailwind CSS** — Estilização rápida e responsiva
* **Biblioteca de componentes da Malwee** — Identidade visual oficial e consistência de UI
* **JWT (JSON Web Token)** — Autenticação segura e controle de acesso

---

## 🔐 Autenticação JWT

O sistema utiliza **JWT** para autenticar usuários e proteger as rotas internas do dashboard.
Isso garante que apenas usuários autorizados possam visualizar informações de produção.

Principais pontos:

* Geração de token no login
* Armazenamento seguro no cliente
* Validação do token em rotas privadas
* Renovação e tratamento de sessão expirada

---

## 📊 Funcionalidades

* Monitoramento de máquinas têxteis
* Dashboard com métricas e indicadores
* Layout padronizado com a biblioteca Malwee
* Autenticação JWT integrada
* Interface limpa, rápida e responsiva
* Estrutura modular escalável

---

## 📁 Estrutura do Projeto (Resumo)

```
/src
 ├── components/       # Componentes reutilizáveis e UI Malwee
 ├── pages/            # Páginas principais do sistema
 ├── hooks/            # Lógica de estados e funcionalidades
 ├── context/          # Contexto de autenticação (JWT)
 ├── services/         # Requisições para API e validação de token
 ├── styles/           # Configurações do Tailwind e tema Malwee
 └── utils/            # Funções auxiliares
```

---

## ▶️ Como Rodar o Projeto

1. **Clone o repositório**

   ```bash
   git clone <url-do-repositorio>
   ```

2. **Instale as dependências**

   ```bash
   npm install
   ```

3. **Inicie o projeto**

   ```bash
   npm run dev
   ```

4. Acesse no navegador:

   ```
   http://localhost:5173
   ```

---

## 🛠️ Melhorias Futuras

* Integração com dados IoT em tempo real
* Gráficos avançados e alertas operacionais
* Dashboard configurável por usuário* Relatórios exportáveis

---

## 🎯 Objetivo

O **Malwee Dashboard** foi criado para oferecer uma solução moderna, segura e visualmente alinhada à identidade da Malwee, facilitando a análise de dados têxteis e apoiando a tomada de decisão no ambiente produtivo.

---




