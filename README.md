# 📒 AGENDA DE CONTATOS - FABPROG

Este é um programa simples de linha de comando desenvolvido em Python, com o objetivo de gerenciar uma agenda de contatos. Ele permite **cadastrar**, **listar** e **excluir** contatos, funcionando em um loop contínuo até que o usuário decida encerrar.

---

## 🧩 Funcionalidades

1. **Cadastrar contato**
   - O usuário insere o nome, telefone e e-mail.
   - Os dados são armazenados como uma lista dentro de uma lista principal (`contatos`).

2. **Listar contatos**
   - Exibe todos os contatos cadastrados, com numeração iniciando de 1.
   - Mostra os dados em formato legível: Nome, Telefone, E-mail.

3. **Excluir contato**
   - Lista os nomes de todos os contatos com numeração.
   - Solicita ao usuário o número do contato que deseja excluir.
   - Remove o contato selecionado, se a entrada for válida.

4. **Sair**
   - Encerra o programa com uma mensagem de despedida.

---

## ▶️ Como usar

1. Execute o script em um terminal com Python 3:

   ```bash
   python agenda.py
