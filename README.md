# 🏦 Sistema Bancário em Python

Este projeto é um **simulador de banco**, desenvolvido como exercício prático de lógica de programação em Python utilizando **Programação Orientada a Objetos (POO)**.  
Ele permite criar usuários, criar contas, realizar depósitos, saques e consultar extratos, **sem precisar de dados reais**.  

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
