
# 💰 Planej.ai

## 📖 Sobre o Projeto

O Planej.ai é uma aplicação web desenvolvida em React e TypeScript que auxilia usuários a planejarem metas financeiras de forma simples e inteligente.

Através de um formulário interativo, o usuário informa sua renda, despesas, dívidas e objetivo financeiro. Com base nessas informações, a aplicação gera uma análise personalizada utilizando Inteligência Artificial (Google Gemini), oferecendo sugestões práticas para alcançar a meta desejada.

---

## 🎯 Objetivo

Auxiliar pessoas a:

* Organizar suas finanças pessoais;
* Compreender sua situação financeira atual;
* Definir metas financeiras realistas;
* Receber orientações personalizadas;
* Melhorar hábitos financeiros.

---

## 🚀 Funcionalidades

### 📋 Simulação Financeira

* Cadastro da renda mensal;
* Cadastro de despesas fixas;
* Cadastro de dívidas e parcelas;
* Definição de metas financeiras;
* Definição de prazo para atingir a meta.

### 📊 Análise Financeira

* Cálculo automático da economia mensal;
* Verificação da viabilidade da meta;
* Diagnóstico financeiro personalizado;
* Cálculo do valor necessário para atingir o objetivo.

### 🤖 Inteligência Artificial

Integração com Google Gemini para gerar:

* Diagnóstico financeiro;
* Sugestões de economia;
* Ideias de renda extra;
* Recomendações de investimentos;
* Mensagem motivacional personalizada.

### 🌙 Temas

* Tema Claro
* Tema Escuro
* Salvamento da preferência no navegador

### 💾 Persistência de Dados

* Armazenamento das simulações no LocalStorage;
* Recuperação de simulações anteriores;
* Identificação única para cada simulação.

---

## 🛠 Tecnologias Utilizadas

### Frontend

* React
* TypeScript
* Vite
* React Router DOM

### Interface

* Tailwind CSS
* Lucide React
* React Loading Skeleton

### Inteligência Artificial

* Google Gemini API

### Armazenamento

* LocalStorage

---

## 📂 Estrutura do Projeto

```text
src/
│
├── assets/
├── components/
│   ├── features/
│   ├── layout/
│   └── shared/
│
├── context/
├── data/
├── hooks/
├── pages/
├── services/
├── utils/
│
├── App.tsx
├── router.tsx
└── main.tsx
```

---

## 🔄 Fluxo da Aplicação

1. Usuário inicia uma nova simulação.
2. Preenche o formulário financeiro.
3. Os dados são armazenados no LocalStorage.
4. É gerado um identificador único.
5. O sistema envia os dados para a IA.
6. A IA gera um diagnóstico personalizado.
7. O usuário visualiza os resultados.
8. O histórico permanece salvo para consultas futuras.

---

## 📷 Principais Telas

### Página Inicial

Formulário multi-step para coleta das informações financeiras.

### Resultado da Simulação

Exibição de:

* Economia mensal;
* Prazo da meta;
* Diagnóstico financeiro;
* Recomendações personalizadas.

### Histórico

Listagem das simulações realizadas anteriormente.

---

## ⚙️ Instalação

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/planej-ai.git
```

Acesse a pasta:

```bash
cd planej-ai
```

Instale as dependências:

```bash
pnpm install
```

Execute o projeto:

```bash
pnpm dev
```

---

## 🔑 Configuração da API Gemini

Crie um arquivo:

```env
.env.local
```

Adicione sua chave:

```env
VITE_GEMINI_API_KEY=SUA_CHAVE_AQUI
```

---

## 👨‍💻 Autor

Projeto desenvolvido para fins educacionais utilizando React, TypeScript e Inteligência Artificial Generativa.
