# carrinho_compras
# 🛒 Shopee Cart Simulator - Node.js

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## 📝 Descrição do Projeto
Este é um sistema de carrinho de compras inspirado na interface e lógica da Shopee, desenvolvido inteiramente em **Node.js** via terminal. O objetivo é simular as operações de backend de um e-commerce, aplicando conceitos fundamentais de desenvolvimento modular e lógica de programação assíncrona.

O projeto foi construído como parte de um desafio prático da [DIO (Digital Innovation One)](https://www.dio.me/).

---

## 🚀 Funcionalidades
* **Adicionar Itens**: Cria produtos com nome, preço e quantidade.
* **Cálculo de Subtotal**: Multiplicação automática de preço x quantidade por item.
* **Remover Item por Unidade**: Diminui a quantidade de um item no carrinho ou o remove se chegar a zero.
* **Deletar Item**: Remove completamente um produto do carrinho, independentemente da quantidade.
* **Cálculo Total**: Soma dinâmica de todos os itens considerando os descontos e quantidades.
* **Visualização Amigável**: Exibição formatada no terminal simulando uma fatura.

---

## 🛠️ Tecnologias Utilizadas
* **Node.js**: Ambiente de execução.
* **ES Modules (ESM)**: Sistema moderno de módulos (import/export).
* **JavaScript (ES6+)**: Lógica de programação e manipulação de arrays.

---

## 📂 Estrutura de Pastas
```text
shopee-cart/
├── src/
│   ├── index.js          # Ponto de entrada e simulação do fluxo
│   ├── services/
│   │   ├── item.js       # Regras de negócio para criação de produtos
│   │   └── cart.js       # Lógica principal do gerenciamento do carrinho
├── package.json          # Manifest do projeto e dependências
└── README.md             # Documentação do projeto