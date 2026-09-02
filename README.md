# 🚀 Aula 03 — Projetos com Frameworks Front-end

> 💡 **Objetivo da aula:** conhecer os principais frameworks e bibliotecas front-end e desenvolver projetos utilizando **React, Vue, Angular e Next.js**.

---

## 🧭 Índice

- [📚 Introdução aos Frameworks](#-introdução-aos-frameworks-front-end)
- [⚖️ Framework × Biblioteca](#️-framework--biblioteca)
- [✨ Por que utilizar Frameworks?](#-por-que-utilizar-frameworks)
- [🧩 Características dos Frameworks](#-características-dos-frameworks-front-end)
- [🔄 Comparação entre Tecnologias](#-comparação-entre-frameworks)
- [⚛️ React](#️-react)
- [🅰️ Angular](#️-angular)
- [🟢 Vue.js](#-vuejs)
- [▲ Next.js](#-nextjs)
- [📥 Importando Projetos](#-importando-projetos)
- [🎯 Atividades](#-atividades)
- [🔗 Links das Entregas](#-links-das-entregas)

---

# 📚 Introdução aos Frameworks Front-end

Um **framework front-end** é um conjunto de ferramentas, bibliotecas e convenções que ajuda a **padronizar e acelerar o desenvolvimento de interfaces web**.

## 🔎 Comparação rápida

| Sem Framework | Com Framework |
|---|---|
| Código mais manual | Estrutura pré-definida |
| Maior repetição | Componentes reutilizáveis |
| Manutenção mais difícil | Código mais organizado |
| Manipulação manual | Atualizações eficientes |

---

# ⚖️ Framework × Biblioteca

## 🏗️ Framework

- Controla o fluxo da aplicação.
- Exige uma estrutura mais definida.
- Exemplos: **Angular e Vue**.

## 📦 Biblioteca

- O desenvolvedor controla quando e como utilizar.
- Possui maior flexibilidade.
- Exemplos: **React e jQuery**.

> 💡 **Resumo:** no framework, a estrutura possui regras próprias. Na biblioteca, o desenvolvedor possui maior controle sobre quando utilizar seus recursos.

---

# ✨ Por que utilizar Frameworks?

- 🚀 **Maior produtividade:** soluções prontas para tarefas comuns.
- 🧹 **Organização:** uso de componentes e padrões.
- 🔧 **Manutenção facilitada:** código mais estruturado.
- 👥 **Comunidade e suporte:** documentação, plugins e soluções.
- ⚡ **Melhor desempenho:** ferramentas e otimizações integradas.

---

# 🧩 Características dos Frameworks Front-end

## 🧱 Estrutura e Componentização

Componentes permitem dividir a interface em partes independentes e reutilizáveis.

## 🔄 Programação Reativa

A interface pode ser atualizada automaticamente quando o estado da aplicação é alterado.

## 🛠️ Build e Bundling

Ferramentas podem:

- Minificar arquivos;
- Transpilar código;
- Combinar arquivos;
- Melhorar a compatibilidade.

## 🧭 Sistema de Rotas

Permite criar aplicações com navegação entre diferentes páginas ou telas.

## 🔌 Integração com APIs

Facilita a comunicação entre a interface e serviços externos.

## ♿ Acessibilidade e Design

Ajuda na utilização de boas práticas e componentes mais inclusivos.

## 🧪 Testes

Possibilita testes unitários e de integração para aumentar a confiabilidade.

---

# 🔄 Comparação entre Frameworks

A escolha da tecnologia pode depender de:

- 📊 Complexidade do projeto;
- 📚 Curva de aprendizado;
- ⚡ Desempenho;
- 🔧 Manutenção;
- 📈 Escalabilidade;
- 👥 Comunidade e suporte.

---

# ⚛️ React

O **React** é uma biblioteca JavaScript utilizada para criar interfaces de usuário e aplicações web.

## 🪝 Principais conceitos

### `useState`

Gerencia o estado de componentes.

### `useEffect`

Trabalha com efeitos colaterais, como chamadas de APIs.

---

## 🧩 JSX

Permite utilizar uma sintaxe semelhante ao HTML dentro do JavaScript.

Principais características:

- Uso de `{}` para expressões JavaScript;
- Uso de `className` no lugar de `class`;
- Tags devem ser fechadas, como `<img />`.

---

## 🧠 Gerenciamento de Estado

- **Context API:** indicada para situações mais simples.
- **Redux:** utilizada para estados mais complexos e compartilhados.

---

## 🌳 DOM e Virtual DOM

O **DOM** representa a estrutura da página.

O **Virtual DOM**, utilizado pelo React, permite comparar alterações antes de atualizar o DOM real, contribuindo para atualizações mais eficientes.

---

# 🅰️ Angular

O **Angular** é um framework completo para desenvolvimento de aplicações web.

## 📋 Requisitos

- Node.js instalado;
- Conhecimento de Programação Orientada a Objetos (POO).

---

## ⭐ Destaques

- 🧭 Roteamento;
- 🌐 Cliente HTTP;
- 💉 Injeção de dependências;
- 🔷 TypeScript;
- 🏗️ Arquitetura organizada;
- ⌨️ Angular CLI;
- ⚡ Change Detection.

---

## 🧩 Conceitos Fundamentais

- **Componentes:** combinam estrutura, estilo e lógica.
- **Módulos:** organizam funcionalidades.
- **Serviços:** reutilizam lógicas.
- **Data Binding:** conecta dados e interface.
- **Injeção de Dependência:** facilita o gerenciamento de recursos.
- **Roteamento:** permite navegar entre diferentes views.

---

## 💻 Criando um Projeto Angular

```bash
# Instalar o Angular CLI
npm install -g @angular/cli

# Criar o projeto
ng new meu-app-angular

# Entrar na pasta
cd meu-app-angular

# Abrir no VS Code
code .

# Executar
ng serve
