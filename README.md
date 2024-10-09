# Criar tabela em banco de dados MySQL

Grupo:
  - Beatriz Paulina
  - Eduardo Aguiar
  - Gabriel Viegas
  - Isaac Alves


## Criar Banco de Dados

  1. Conecte-se ao MySQL Workbench clicando em `Local instance`.

     ![image](https://github.com/user-attachments/assets/9868dbd8-9bfa-4433-9f74-98403e3ad44a)


  3. Execute o seguinte comando em `Querry` para criar um banco de dados:
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

## Adicionar itens

4. Execute o seguinte comando para adicionar itens a uma tabela:
   ```MySQL
   INSERT INTO nome_da_tabela (id, nome, idade, data_nascimento) VALUES
   (1, 'Alice', 30, '1993-05-15'),
   (2, 'Bruno', 25, '1998-08-20'),
   (3, 'Carla', 40, '1983-12-01'),
   (4, 'David', 22, '2001-03-10'),
   (5, 'Eva', 35, '1988-07-22');
   ```

    
## Visualizar Dados

4. Para visualizar a tabela (caso haja dados):
  ```MySQL
  SELECT * FROM nome_da_tabela;
  ```

### Dicas
  - Altere `nome_do_banco` e `nome_da_tabela` conforme necessário.
  - Use o comando `SHOW TABLES`; para listar as tabelas em um banco de dados.



