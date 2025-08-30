# 🏦 Sistema Bancário em Python

Este é um projeto desenvolvido como exercício prático de lógica de programação em Python.  
O objetivo é simular operações bancárias simples como **criação de usuários, criação de contas bancárias e movimentações financeiras (depósitos, saques e extratos)**.  
Além disso, o sistema aplica diferentes formas de passagem de argumentos em funções para fins de estudo.

---

## 🚀 Funcionalidades

- 👤 **Criar Usuário**  
  - Registra um cliente no sistema a partir do CPF, nome, data de nascimento e endereço.  
  - Impede cadastros duplicados com o mesmo CPF.  

- 🏦 **Criar Conta**  
  - Associa uma conta bancária a um usuário já cadastrado.  
  - Cada conta recebe automaticamente um número sequencial e está vinculada a uma agência padrão.  

- 📥 **Depósito**  
  - Adiciona saldo à conta.  
  - Implementado pela função `depositar`, que recebe parâmetros **somente por posição**.  

- 💸 **Saque**  
  - Permite retirar valores da conta.  
  - Implementado pela função `sacar`, que recebe parâmetros **somente por nome (keyword only)**.  
  - Regras:  
    - Máximo de **3 saques por dia**  
    - Limite de **R$1.000,00 por saque**  
    - Impede saques maiores que o saldo disponível. 

- 📊 **Extrato**  
  - Mostra o histórico de transações e o saldo atual.  
  - Implementado pela função `exibir_extrato`, que aceita parâmetros **por posição ou por nome**.

    ---
## 🖥️ Como testar no VS Code

1. Certifique-se de ter o **Python instalado** em sua máquina.

2. Abra o **Visual Studio Code**.  

4. Crie um novo arquivo chamado `sistema_bancario.py`.  

5. Copie e cole **todo o código do sistema** dentro desse arquivo.  

6. Salve o arquivo (`Ctrl + S` ou `Cmd + S` no Mac).  

7. No terminal do VS Code, execute:  
   ```bash
   python sistema_bancario.py

---

## 📌 Exemplo de uso

[1] Criar novo usuário

[2] Criar nova conta

[3] Depositar

[4] Sacar

[5] Extrato

[0] Sair

=> 1

Digite seu CPF: 123.456.789-00

Digite seu nome e Sobrenome: Felipe Ronni

Digite sua data de nascimento (dd-mm-aaaa): 04-11-2001

Informe o endereço (logradouro, nmro - bairro - cidade/sigla estado): Rua 1, 01, Bairro 1, Sp, SP

===== Usuário criado com sucesso! =====

=> 2

Digite seu CPF: 123.456.789-00

===== Conta criada com sucesso! =====

=> 3

Informe o valor do depósito: 250

===== Depósito efetuado com sucesso! =====

=> 4

Informe o valor do saque: 200

===== Saque efetuado com sucesso! =====


=> 5

========== EXTRATO ==========

Depósito: R$250.00

Saque: R$200.00

Saldo: R$50.00

=============================

=> 0

Sessão finalizada. Obrigado por ser nosso cliente!
