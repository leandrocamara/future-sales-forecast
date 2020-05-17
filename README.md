# Previsão de Vendas com Prophet
Utilizando a biblioteca para construção de séries temporais do _Facebook_ – denominada _Prophet_,
pretende-se elaborar um modelo, que seja capaz de prever os próximos 5 meses de vendas e receita da empresa.

## Descrição dos Dados

### Arquivos
* **sales.csv** - Dados históricos (vendas diárias) de Janeiro de 2013 a Outubro de 2015;
* **items.csv** - Informações complementares sobre os itens/produtos;
* **item_categories.csv**  - Informações complementares sobre as categorias de itens.

### Campos
* **shop_id** - Identificador da loja;
* **item_id** - Identificador do produto;
* **item_category_id** - Identificador da categoria do produto;
* **item_cnt_day** - Quantidade de produtos vendidos;
* **item_price** - Preço do produto;
* **date** - Data no formato “dd.mm.YYYY”;
* **date_block_num** - Número sequencial dos meses entre Janeiro de 2013 (0) e Outubro de 2015 (33);
* **item_name** - Nome do produto;
* **item_category_name** - Nome da categoria do produto.