# Cookin'UP – Curso de Vue.js: Entendendo Componentes, Diretivas e Reatividade

Este é o repositório desenvolvido durante o curso **"Vue 3: entendendo componentes, diretivas e reatividade no framework"** da [Alura](https://www.alura.com.br/), ministrado pelo instrutor Antônio Evaldo.

## 📚 Sobre o Curso

Neste curso, aprendemos a criar um projeto Vue.js do zero, utilizando **componentes**, **diretivas** e explorando os conceitos de **estado** e **reatividade**. Também abordamos a **comunicação entre componentes** via `props` e `eventos`, além dos **ciclos de vida** como o `created`.

A proposta é construir uma aplicação real, o **Cookin'UP**, que permite ao usuário selecionar ingredientes disponíveis em casa e receber sugestões de receitas compatíveis.

## 🚀 Tecnologias Utilizadas

- [Vue.js 3](https://vuejs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- HTML5, CSS3 e JavaScript ES6+
- Vite para build e desenvolvimento
- Figma (protótipo visual)

## 🛠️ Atividades Desenvolvidas

- Criação de um projeto Vue com Vite
- Estruturação de componentes reutilizáveis
- Utilização de diretivas como `v-if`, `v-for`, `v-model`
- Manipulação de estado e aplicação de reatividade
- Comunicação entre componentes com `props` e `emit`
- Organização de interfaces e serviços HTTP com TypeScript
- Aplicação de métodos do ciclo de vida (`created`)
- Implementação de lógica de seleção de ingredientes e exibição de receitas

## 🧩 Estrutura do Projeto

```plaintext
21lucasbarros-cookin-up-alura/
├── public/
│   └── imagens/
│       ├── icones/
│       │   └── categorias_ingredientes/
│       └── receitas/
└── src/
    ├── App.vue
    ├── main.ts
    ├── assets/
    │   ├── main.css
    │   └── images/
    │       └── icones/
    ├── components/
    │   ├── Banner.vue
    │   ├── BotaoPrincipal.vue
    │   ├── CardCategoria.vue
    │   ├── CardReceitas.vue
    │   ├── ConteudoPrincipal.vue
    │   ├── IngredienteSelecionavel.vue
    │   ├── MostrarReceitas.vue
    │   ├── Rodape.vue
    │   ├── SelecionarIngredientes.vue
    │   ├── SuaLista.vue
    │   └── Tag.vue
    ├── http/
    │   └── index.ts
    ├── interfaces/
    │   ├── ICategoria.ts
    │   └── IReceitas.ts
    └── operacoes/
        └── listas.ts
```

## 🎨 Protótipo no Figma

Você pode acessar o protótipo do projeto no Figma por este link:  
👉 [Figma - Cookin'UP](https://www.figma.com/file/0YlJl7HQ7flDoEZZ8tB88A/Cookin'UP-%7C-Vue-1?node-id=1901%3A2&mode=dev)

## 📌 Pré-requisitos

Antes de começar, é importante já ter noções básicas de:

- HTML e CSS
- JavaScript (intermediário)
- TypeScript (básico)
- Terminal e Node.js

## ✅ Status

✔️ Projeto finalizado como parte do curso.  
🔧 Possíveis melhorias e refatorações podem ser aplicadas futuramente.

---

**Bons estudos e bom código!**
