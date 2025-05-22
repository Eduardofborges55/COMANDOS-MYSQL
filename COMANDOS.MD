PARA CRIAR TABELA USE

//CREATE TABLE Clientes (
  Id int AUTO_INCREMENT PRIMARY KEY,
  Nome VARCHAR (100),
  CPF VARCHAR (100),
  Email VARCHAR (100),
  Telefone VARCHAR (100)
)

PARA COMENTAR A TABELA CRIADA

/*CREATE TABLE Clientes (
  Id int AUTO_INCREMENT PRIMARY KEY,
  Nome VARCHAR (100),
  CPF VARCHAR (100),
  Email VARCHAR (100),
  Telefone VARCHAR (100)
)*/

// DELETE FROM Vendas = DELETA AS INFORMAÇÕES ADICIONADAS NA TABELA

// DROP TABLE = DELETA A TABELA

// Select * From Produto = Seleciona toda(*) a tabela Produto

// update Produto set qtde_Estoque = 10 where id = 1; // = update é alto explicativo mas where é a clausula que filtra registros em uma instrução SQL


INSERT INTO Produto (Id_Produto, Id_fornecedor, data_entrada, quantidade) VALUES

(1, 1, '2025-05-22' 20)


INSERT INTO Produto (Id_Produto, Id_fornecedor, data_entrada, quantidade) VALUES
SELECT p.id, f.id,
FROM Produto p = vai até a tabela e pesquisa
CROSS JOIN Fornecedor f.id = CROSS JOIN faz um print com a informação no insert.


