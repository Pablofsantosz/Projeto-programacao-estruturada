# Sistema de Gerenciamento de Consultas Veterinárias 🐾

Este projeto em linguagem C tem como objetivo gerenciar registros de consultas veterinárias. Através de um menu interativo, o usuário pode cadastrar, listar, buscar, atualizar e remover registros de clientes e seus respectivos animais.

## 📋 Funcionalidades

- **Adicionar Consulta:** Cadastro de cliente, animal e agendamento da consulta.
- **Listar Consultas:**
  - Primeiros 5 registros
  - Últimos 5 registros
  - Todos os registros
- **Buscar Consulta:** Busca detalhada por UID gerado automaticamente.
- **Atualizar Consulta:** Permite editar qualquer informação de um registro.
- **Remover Consulta:** Deleta um registro com base no UID.

## 💾 Estruturas Utilizadas

- `struct Animal` – Dados do animal (nome, espécie, porte, idade, condição especial)
- `struct Data` – Data da consulta
- `struct Cliente` – Dados do cliente (nome, telefone, e-mail, número de animais)
- `struct Consulta` – Agrupa as structs anteriores com o horário da consulta

## 📁 Arquivo de Saída

As informações listadas são gravadas em um arquivo chamado `Consulta.txt`, que é sobrescrito a cada listagem.


