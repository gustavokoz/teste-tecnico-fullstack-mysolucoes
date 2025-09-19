# 📌 Desafio Técnico – TaskFlow (Mini Gerenciador de Tarefas)

Bem-vindo(a) ao desafio técnico da nossa equipe! 🎯  
O objetivo é avaliar suas habilidades em **desenvolvimento fullstack** utilizando as tecnologias que trabalhamos no dia a dia.  

Você terá até **7 dias** para concluir este desafio.  

---

## 📖 Descrição do Projeto

O desafio consiste em desenvolver um sistema chamado **TaskFlow**, um mini gerenciador de tarefas com autenticação.  

### Funcionalidades principais:
- **Cadastro e login de usuário** com autenticação via **JWT**.
- **CRUD de tarefas** (Criar, Listar, Atualizar, Excluir).
- Cada tarefa deve estar vinculada ao usuário logado.
- Validação de formulários no frontend.
- Estilização da aplicação com **TailwindCSS**.
- Integração entre frontend e backend via **API REST**.

---

## 🎯 Requisitos do Desafio

### **Backend**
- Utilizar **Node.js + Express + Typescript**.
- Banco de dados **MySQL** com **Sequelize (sequelize-typescript)** (usar migrations).
- Implementar **autenticação com JWT** (login e registro de usuários).
- Rotas protegidas para acesso às tarefas.
- CRUD de tarefas com os campos:
  - `id`
  - `title`
  - `description`
  - `status` (pendente, em andamento, concluída)
  - `deadline` (opcional)
  - `userId` (vinculado ao usuário logado)

---

### **Frontend**
- Desenvolvido em **React** (com `react-router-dom`) ou **Next.js**.
- Páginas:
  - **Login**
  - **Registro**
  - **Dashboard** (lista de tarefas do usuário logado)
  - **Criar/Editar tarefa**
- Formulários utilizando **react-hook-form** com **Zod** para validação.
- Consumo da API utilizando **Axios**.
- Rotas protegidas para páginas internas (dashboard, criar/editar).
- Estilização utilizando **TailwindCSS**.

---

### **Opcionais (Diferenciais)**
- Documentação da API com **Swagger** ou documentação organizada no README.
- Refresh token no fluxo de autenticação.
- Filtros na lista de tarefas (ex: por status).
- Boas práticas de commits (Git).

---

## 📅 Prazo
Você terá até **7 dias corridos** para entregar o desafio (porém não tem problema não atender a todos os requisitos porém precisamos que façam o melhor trabalho possivel dentro desse periodo para uma boa avaliação técnica).

---

## 📦 Entrega
- Enviar um repositório no GitHub/GitLab contendo:
  - Código do **frontend** e do **backend** (pode ser monorepo ou pastas separadas).
  - Um arquivo **README.md** explicando como rodar a aplicação localmente (passo a passo).
  - Scripts de inicialização claros (`npm run dev`, `npm run start`, etc).

---

## ✅ O que será avaliado
- Organização do código e boas práticas.
- Uso correto de **Typescript**.
- Implementação da **autenticação com JWT**.
- Modelagem e uso do **Sequelize** com MySQL.
- Integração do frontend com o backend.
- Uso de **react-hook-form + zod** para validações.
- Estilização com **styled-components ou TailwindCSS**.
- Clareza na documentação (README).

---

## 🚀 Tecnologias Esperadas
Não é necessário usar todas, mas quanto mais, melhor:
- **Backend:** Node.js, Express, Sequelize, MySQL, JWT.
- **Frontend:** React ou Next.js, react-router-dom, axios, react-hook-form, zod.
- **Estilo:** TailwindCSS (e alguma outra lib de estilo ao seu gosto).

---

🔎 **Dica:**  
Não se preocupe em fazer algo complexo. Prefira um sistema simples, mas **funcional, organizado e bem estruturado**.  
