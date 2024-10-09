# Criar tabela em banco de dados MySQL

Grupo:
  - Beatriz Paulina
  - Eduardo Aguiar
  - Gabriel Viegas
  - Isaac Alves


## Criar Banco de Dados

  1. Conecte-se ao MySQL Workbench.
  2. Clique em new schema e mude o charset para utf-8, após isso clique em aplicar

![image](https://github.com/user-attachments/assets/7b98892b-6d87-4dbf-a59d-fa37edda8d54)

  3. Clique em tables no seu banco de dados e vá para Query 1

![image](https://github.com/user-attachments/assets/7479fed1-3873-4dc7-8163-3af4bc12133b)

  4. Execute o seguinte comando para criar um banco de dados:
     ```MySQL
     CREATE DATABASE nome_do_banco;
     USE nome_do_banco;
     ```

## Criar Tabela

5. Execute o seguinte comando para criar uma tabela:
    ```MySQL
    CREATE TABLE nome_da_tabela (
      id INT AUTO_INCREMENT PRIMARY KEY,
      nome VARCHAR(100),
      idade INT,
      data_nascimento DATE
    );
    ```
    
## Visualizar Dados

6. Para visualizar a tabela (caso haja dados):
  ```MySQL
  SELECT * FROM nome_da_tabela;
  ```

### Dicas
  - Altere `nome_do_banco` e `nome_da_tabela` conforme necessário.
  - Use o comando `SHOW TABLES`; para listar as tabelas em um banco de dados.



