# 🏦 Sistema Bancário em Python

Este projeto é um **simulador de banco**, desenvolvido como exercício prático de lógica de programação em Python utilizando **Programação Orientada a Objetos (POO)**.  
Ele permite criar usuários com validação da data de nascimento e cpf, criar contas, realizar depósitos, saques e consultar extratos. 

---

## 🚀 Funcionalidades

- 👤 **Criar Usuário**  
  - Crie um cliente usando qualquer CPF, nome, data de nascimento e endereço fictícios.  
  - Evita cadastros duplicados usando o mesmo CPF.  

- 🏦 **Criar Conta**  
  - Associa uma conta bancária a um usuário existente.  
  - Cada conta recebe um número sequencial automaticamente e está vinculada a uma agência padrão.  

- 📥 **Depósito**  
  - Adiciona saldo à conta.  

- 💸 **Saque**  
  - Retira valores da conta.  
  - Regras do saque:  
    - Máximo de **3 saques por dia**  
    - Limite de **R$1.000,00 por saque**  
    - Não é possível sacar mais do que o saldo disponível  

- 📊 **Extrato**  
  - Mostra o histórico de transações e o saldo atual.  

---

## 🖥️ Como testar no VS Code

1. Certifique-se de ter o **Python instalado** em sua máquina.  
2. Abra o **Visual Studio Code**.  
3. Crie um arquivo chamado `sistema_bancario.py`.  
4. Copie e cole **todo o código do sistema** dentro desse arquivo.  
5. Salve o arquivo (`Ctrl + S` ou `Cmd + S`).  
6. No terminal do VS Code, execute:  
   ```bash
   python sistema_bancario.py

## 📌 Exemplo de uso completo   
[1] Criar novo usuário

[2] Criar nova conta

[3] Depositar

[4] Sacar

[5] Extrato

[0] Sair


=> 1

Digite seu CPF (qualquer número serve): 000.000.000-00

Digite seu nome e sobrenome: João Teste

Digite sua data de nascimento (dd-mm-aaaa): 01-01-2000

Informe o endereço: Rua Fictícia, 123, Bairro Exemplo, Cidade/UF

===== Usuário criado com sucesso! =====


=> 2

Digite o CPF do usuário: 000.000.000-00

===== Conta criada com sucesso! =====


=> 3

Informe o valor do depósito: 500

===== Depósito efetuado com sucesso! =====


=> 4

Informe o valor do saque: 200

===== Saque efetuado com sucesso! =====


=> 5

========== EXTRATO ==========

Depósito: R$500.00

Saque: R$200.00

Saldo: R$300.00


=> 0

Sessão finalizada. Obrigado por ser nosso cliente!
