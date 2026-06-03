# 💰 Planej.ai - Planejador Financeiro Inteligente com IA

![React](https://img.shields.io/badge/React-19-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-blue)
![Vite](https://img.shields.io/badge/Vite-Latest-purple)
![Google Gemini](https://img.shields.io/badge/Google-Gemini-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 📖 Sobre o Projeto

O **Planej.ai** é uma aplicação web desenvolvida com React, TypeScript e Inteligência Artificial Generativa para auxiliar usuários no planejamento financeiro pessoal.

A plataforma permite que o usuário informe sua situação financeira atual, defina uma meta financeira e receba uma análise personalizada gerada por IA, contendo diagnósticos, sugestões de economia, ideias de renda extra e recomendações para alcançar seus objetivos.

O projeto foi desenvolvido com foco em boas práticas de desenvolvimento Front-End, componentização, gerenciamento de estado, persistência local de dados e integração com APIs de Inteligência Artificial.

---

# 🎯 Objetivos

- Auxiliar usuários no planejamento financeiro.
- Demonstrar integração entre React e IA Generativa.
- Aplicar conceitos modernos de Front-End.
- Utilizar TypeScript para tipagem segura.
- Trabalhar com persistência de dados locais.
- Criar uma interface moderna e responsiva.

---

# 🚀 Funcionalidades

## 📋 Formulário Multi-Step

O usuário preenche informações financeiras em etapas:

- Renda mensal
- Custos fixos
- Dívidas e parcelas
- Nome da meta financeira
- Valor da meta
- Prazo desejado

---

## 📊 Simulação Financeira

Após preencher os dados, o sistema calcula automaticamente:

- Economia mensal disponível
- Valor necessário para atingir a meta
- Viabilidade financeira do objetivo
- Saldo restante após planejamento

---

## 🤖 Inteligência Artificial

Integração com a API do Google Gemini para gerar:

### Diagnóstico Financeiro

Análise da situação financeira atual.

### Sugestões de Economia

Recomendações para reduzir gastos.

### Fontes de Renda Extra

Ideias de geração de renda complementar.

### Recomendações de Investimento

Sugestões de investimentos compatíveis com o perfil informado.

### Mensagem Motivacional

Mensagem personalizada baseada na meta do usuário.

---

## 🌗 Sistema de Temas

A aplicação possui:

- Tema Claro
- Tema Escuro
- Salvamento automático da preferência do usuário

---

## 🕒 Histórico de Simulações

Permite:

- Armazenar simulações realizadas
- Consultar simulações anteriores
- Recuperar resultados por identificador único

---

# 🛠 Tecnologias Utilizadas

## Front-End

- React
- TypeScript
- Vite
- React Router DOM

## Interface

- Tailwind CSS
- Lucide React
- React Loading Skeleton

## Gerenciamento de Estado

- React Hooks
- Context API

## Persistência

- LocalStorage

## Inteligência Artificial

- Google Gemini API

---

# 📂 Estrutura do Projeto

```text
src
│
├── assets
│   └── images
│
├── components
│   ├── features
│   │   ├── Insights
│   │   ├── Simulation
│   │   └── SimulationResults
│   │
│   ├── layout
│   └── shared
│
├── context
│   └── theme
│
├── data
│
├── hooks
│
├── pages
│
├── services
│
├── utils
│
├── router.tsx
├── App.tsx
└── main.tsx
```

---

# 🔄 Fluxo da Aplicação

### 1️⃣ Nova Simulação

O usuário inicia uma nova simulação financeira.

### 2️⃣ Preenchimento

Os dados são coletados através de um formulário multi-step.

### 3️⃣ Armazenamento

As informações são salvas no LocalStorage.

### 4️⃣ Processamento

O sistema calcula:

- Economia mensal disponível
- Valor necessário para atingir a meta
- Viabilidade financeira

### 5️⃣ Inteligência Artificial

Os dados são enviados para o Google Gemini através de um prompt estruturado.

### 6️⃣ Resultado

A IA retorna um diagnóstico financeiro personalizado.

---

# 📸 Funcionalidades da Interface

### Página Inicial

- Hero principal
- Formulário multi-step
- Barra de progresso

### Página de Resultado

- Cards informativos
- Diagnóstico financeiro
- Sugestões da IA

### Página de Histórico

- Lista de simulações realizadas
- Acesso rápido aos resultados anteriores

---

# 🔐 Variáveis de Ambiente

Criar o arquivo:

```env
.env.local
```

Adicionar:

```env
VITE_GEMINI_API_KEY=SUA_CHAVE_AQUI
```

---

# ⚙️ Instalação

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/planej-ai.git
```

Entre na pasta:

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

# 📦 Dependências Principais

```json
{
  "react": "^19",
  "react-dom": "^19",
  "react-router-dom": "^7",
  "lucide-react": "^0.500.0",
  "react-loading-skeleton": "^3",
  "typescript": "^5",
  "vite": "^7"
}
```

---

# 💡 Principais Conceitos Aplicados

- Componentização
- React Hooks
- Context API
- React Router
- LocalStorage
- Consumo de APIs REST
- Prompt Engineering
- Integração com IA Generativa
- Responsividade
- TypeScript
- Boas práticas de Front-End

---

# 🎓 Aprendizados Obtidos

Durante o desenvolvimento deste projeto foram aplicados conhecimentos relacionados a:

- Desenvolvimento Front-End moderno
- Criação de interfaces reutilizáveis
- Gerenciamento de estados globais
- Persistência de dados no navegador
- Integração com Inteligência Artificial
- Engenharia de Prompt
- Consumo de APIs externas
- Estruturação de aplicações React em larga escala

---

# 🚀 Melhorias Futuras

- Autenticação de usuários
- Banco de dados online
- Dashboard financeiro completo
- Exportação de relatórios em PDF
- Gráficos financeiros
- Integração com Open Finance
- Comparação entre múltiplas metas
- Aplicativo mobile com React Native

---

# 👨‍💻 Autor

Desenvolvido para fins acadêmicos e educacionais, aplicando conceitos de React, TypeScript e Inteligência Artificial Generativa.

---

# 📄 Licença

Este projeto está sob a licença MIT.

Sinta-se livre para utilizar, estudar e aprimorar o código.
