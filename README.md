# Criar tabela em banco de dados MySQL

Grupo:
  - Beatriz Paulina
  - Eduardo Aguiar
  - Gabriel Viegas
  - Isaac Alves

## Criar Banco de Dados

  1. Conecte-se ao MySQL Workbench.
  2. Execute o seguinte comando para criar um banco de dados:
     ```MySQL
     CREATE DATABASE nome_do_banco;
     USE nome_do_banco;
     ```

## Criar Tabela

3. Execute o seguinte comando para criar uma tabela:
    ```MySQL
    CREATE TABLE nome_da_tabela (
      id INT AUTO_INCREMENT PRIMARY KEY,
      nome VARCHAR(100),
      idade INT,
      data_nascimento DATE
    );
    ```
    
## Visualizar Dados

4. Para visualizar a tabela (caso haja dados):
  ```MySQL
  SELECT * FROM nome_da_tabela;
  ```

## Dicas
  - Altere `nome_do_banco` e `nome_da_tabela` conforme necessário.
  - Use o comando `SHOW TABLES`; para listar as tabelas em um banco de dados.



