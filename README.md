# 💳 Hora de Codar 5 - Sistema de Caixa Eletrônico (JavaScript)

Este projeto simula um sistema básico de caixa eletrônico utilizando JavaScript, com foco no uso de funções para organizar a lógica do programa.

## 🚀 Funcionalidades

- Exibição de saldo
- Saque com validação de saldo
- Depósito com validação de valor
- Transferência entre contas
- Visualização de extrato com dados fictícios
- Autenticação por senha para operações sensíveis

## 🧠 Conceitos aplicados

### 🔹 Uso de Functions
O sistema foi estruturado utilizando funções para separar responsabilidades, como:
- `inicio()` → menu principal
- `fazer_saque()` → realiza saques
- `fazer_deposito()` → realiza depósitos
- `fazer_extrato()` → exibe o extrato
- `fazer_transferencia()` → realiza transferências
- `erro()` → trata opções inválidas

Isso torna o código mais organizado, reutilizável e fácil de manter.

---

## 🔐 Validações implementadas

- Senha obrigatória (3589) para:
  - saldo
  - saque
  - extrato
  - transferência

- Operações bloqueadas quando:
  - valor ≤ 0
  - saldo insuficiente
  - senha incorreta

- Transferência:
  - aceita apenas números como conta
  - valida saldo disponível

---

## 📊 Extrato

O extrato utiliza um **array global (`extratoLista`)** para armazenar movimentações fictícias, como:

- Depósitos
- Saques
- Compras

Os dados são exibidos utilizando `join('\n')` para formatação.

---

## 📋 Menu principal

Ordem das opções:

1. Saldo  
2. Extrato  
3. Saque  
4. Depósito  
5. Transferência  
6. Sair  

---

## ✨ Melhorias realizadas

- Uso de `switch/case` para controle do menu
- Correção de mensagens do sistema
- Organização do código com funções
- Implementação de validações em todas as operações
- Mensagem personalizada ao entrar e sair do sistema

---

## 🧪 Objetivo

Este projeto foi desenvolvido com o objetivo de praticar:
- Lógica de programação
- Estruturação com funções
- Manipulação de arrays
- Validação de dados
