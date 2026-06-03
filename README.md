# 💰 Planej.ai - Planejador Financeiro Inteligente

## 📌 Sobre o Projeto

O Planej.ai é uma aplicação web desenvolvida com React, TypeScript e Inteligência Artificial Generativa que auxilia usuários a realizarem planejamentos financeiros personalizados.

O sistema coleta informações financeiras por meio de um formulário interativo e utiliza IA para gerar diagnósticos, recomendações e insights personalizados, ajudando o usuário a tomar decisões financeiras mais conscientes.

Este projeto foi desenvolvido como prática de integração entre React e IA Generativa, aplicando conceitos modernos de desenvolvimento front-end, gerenciamento de estado, roteamento e consumo de APIs.

---

## 🎯 Objetivos

* Aplicar conceitos de React e TypeScript.
* Construir interfaces modernas e responsivas.
* Implementar formulários multi-step.
* Integrar Inteligência Artificial Generativa.
* Trabalhar com persistência de dados utilizando LocalStorage.
* Gerar análises financeiras personalizadas.

---

## 🚀 Funcionalidades

### 📋 Simulação Financeira

O usuário informa:

* Renda mensal;
* Gastos fixos;
* Dívidas e parcelas;
* Objetivo financeiro;
* Valor da meta;
* Prazo desejado.

### 📊 Cálculos Automáticos

A aplicação calcula:

* Economia mensal disponível;
* Valor necessário para atingir a meta;
* Viabilidade financeira da meta;
* Saldo restante após a reserva financeira.

### 🤖 Inteligência Artificial

A integração com IA Generativa fornece:

* Diagnóstico financeiro personalizado;
* Sugestões de economia;
* Ideias para geração de renda extra;
* Recomendações de investimentos;
* Mensagem motivacional personalizada.

### 🌙 Sistema de Temas

* Tema Claro;
* Tema Escuro;
* Persistência da preferência do usuário.

### 💾 Histórico de Simulações

* Salvamento automático das simulações;
* Identificador único para cada registro;
* Recuperação dos dados armazenados.

---

## 🛠 Tecnologias Utilizadas

### Front-End

* React
* TypeScript
* Vite
* React Router DOM

### Estilização

* Tailwind CSS

### Componentes e Ícones

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

1. O usuário inicia uma nova simulação.
2. Preenche o formulário financeiro.
3. Os dados são armazenados localmente.
4. Um identificador único é gerado.
5. Os dados são enviados para a IA.
6. A IA gera um diagnóstico personalizado.
7. O resultado é exibido na tela.
8. A simulação fica salva para futuras consultas.

---

## 🔑 Configuração da API

Crie um arquivo:

```env
.env.local
```

Adicione sua chave da API Gemini:

```env
VITE_GEMINI_API_KEY=SUA_CHAVE_AQUI
```

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

## 👨‍💻 Autor

Projeto desenvolvido para fins educacionais com foco na utilização de React e Inteligência Artificial Generativa aplicada à educação financeira.

