# Criar tabela em banco de dados MySQL

Grupo:
  - Beatriz Paulina
  - Eduardo Aguiar
  - Gabriel Viegas
  - Isaac Alves

## Abrir o MySQL Workbench

  1. Inicie o MySQL Workbench.
  2. Conecte-se ao seu servidor MySQL. Clique na conexão que você configurou.

## Criar um Banco de Dados

  1. No menu superior, clique em File e depois em New Query Tab.
  2. Na nova aba de consulta, digite o seguinte comando para criar um banco de dados:
     ```MySQL
     CREATE DATABASE nome_do_banco;
     ```
     Substitua `nome_do_banco` pelo nome que você deseja dar ao seu banco de dados.
  3. Execute o comando clicando no ícone de raio (Execute) ou pressionando `Ctrl + Shift + Enter`.
  4. Para usar o banco de dados recém-criado, digite:
    ```MySQL
    USE nome_do_banco;
    ```
