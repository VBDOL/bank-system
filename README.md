# Sistema Bancário em Python

## Sobre o Desafio

Este projeto consiste em um **sistema bancário simples**, onde o usuário pode realizar operações como **depósito, saque e exibição de extrato**. O objetivo é criar um programa interativo que permita gerenciar um saldo bancário, respeitando limites de saque e registrando todas as transações.

### Funcionalidades:
- **Depositar**: O usuário informa um valor válido e o saldo é atualizado.
- **Sacar**: O saque é validado conforme o saldo disponível, limite por saque e número máximo de saques permitidos.
- **Extrato**: Exibe todas as transações realizadas e o saldo atual.
- **Sair**: Encerra o programa.

## Melhorias Implementadas

Para tornar o código mais estruturado e eficiente, foram aplicadas **melhorias** na implementação original:

### 🔹 **Modularização**
- O código agora possui **funções separadas** para cada operação: `depositar()`, `sacar()` e `exibir_extrato()`.
- Isso melhora a **organização**, facilitando futuras alterações e manutenção.

### 🔹 **Uso de Listas para Extrato**
- O extrato agora é armazenado em uma **lista**, em vez de uma única string.
- Isso permite manipulação mais eficiente dos dados e evita problemas de formatação.

### 🔹 **Feedback mais intuitivo**
- Adicionados **mensagens de confirmação** para cada operação bem-sucedida, melhorando a experiência do usuário.

### 🔹 **Validação da Entrada**
- Padronização do input do menu (`input(menu).lower()`), permitindo que o usuário utilize letras **maiúsculas ou minúsculas** sem erro.

## Como Executar o Programa

1️⃣ Execute o script em um ambiente Python (`python3 main.py`).

2️⃣ Escolha uma das opções do menu:
[d] Depositar [s] Sacar [e] Extrato [q] Sair

3️⃣ Siga as instruções para **realizar operações bancárias** interativamente.

---
