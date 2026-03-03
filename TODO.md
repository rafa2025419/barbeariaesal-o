# Plan: Exibir nome do usuário na tela de profissional

## Objetivo
Atualizar o sistema para que o nome inserido na tela de login seja exibido na tela do profissional, substituindo o nome hardcoded "João Silva".

## Tarefas

### 1. Modificar index.html (tela de login)
- [] Adicionar campo "Nome" ao formulário de login
- [] Salvar o nome no localStorage ao fazer login (para perfil profissional)
- [] Passar o nome para profissional.html via localStorage

### 2. Modificar profissional.html (tela do profissional)
- [] Ler o nome do localStorage ao carregar a página
- [] Atualizar o elemento `.pro-name` com o nome do usuário
- [] Atualizar as iniciais do avatar (`.pro-avatar`) com base no nome

## Implementação
- Usar localStorage para persistir o nome do profissional entre as páginas
- Quando o profissional fazer login, salvar o nome no localStorage
- Na página profissional.html, verificar e exibir o nome salvo
