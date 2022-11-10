# Análise no Banco de Dados da Olist

<img src="https://github.com/jefferson-datascience/project_sql_analysis/blob/main/logo.jpg" alt="logo" style="zoom:80%;" />

## Questão de Negócio

Um dos maiores problemas dos comerciantes que possuem loja física, é cadastrar o mesmo produto em dezenas de e-commerce disponível no Brasil, para realizar vendas online.

Para resolver esse problema e facilitar o cadastro dos produtos em diferentes portais de venda, uma grande empresa de tecnologia desenvolveu um serviço que faz todo esse processo automaticamente, fazendo com que o comerciante venda seus produtos através de um único site. Quando o cliente realiza a compra de um produto em qualquer um dos portais, o comerciante é notificado para atender o pedido. Assim que o cliente receber o produto ou a data prevista para a entrega é igual a data do dia, o cliente recebe uma pesquisa de satisfação por e-mail, no qual ele pode avaliar a experiência de compra e anotar alguns comentários. Todas as informações sobre o produto, o cliente, o comerciante, o meio de pagamento, as avaliações e o pedido realizado são armazenados em um banco de dados. Os gerentes da empresa acreditam que há muitas informações valiosas armazenas nos dados, mas não tem habilidades para explorar e encontrar as respostas para validar ou refutar suas hipóteses de negócio. 

Portanto, eu foi contratado como Cientista de Dados para explorar os dados e trazer repostas sobre o que realmente está acontecendo com o negócio.

**OBSERVAÇÕES:** 

- Os dados estão disponíveis na plataforma kaggle que pode ser acessado pelo endereço 'https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce'. 
- Para que esse projeto fosse executado, esses dados foram baixados da plataforma kaggle como arquivos csv's e foram armazenados no banco de dados sqlite.
- As tabelas obtidas das requisições no banco de dados tiveram suas quantidades de linhas limitadas para que se pudesse ter uma pequena amostra dessas tabelas encontradas aqui no github para uma visualização rápida.

## Planejamento de Solução

### Qual é a solução?
- A solução para esse problemas é usar a linguagem de SQL para fazer requisições no banco de dados sqlite, onde estão armazenados 
    esses dados. O software usado para isso foi o Dbeaver, mas para deixar disponível no repositório como relatório e conseguir os csv's 
    com mais agilidade, usaremos o Jupyter Notebook.
    
### Como será a entrega do produto final?
- Em cada rodada de questões será disponibilizado os arquivos CSV's com as respostas de cada questão em um diretório que estará aqui 
    no repositório e, além disso, tem o relatório em jupyter notebook para mais detalhes do processo.
    
## Estratégia de Resolução

**0º Passo:** Escolher um software para realizar as requisições no banco de dados. Escolhemos o Dbeaver. Para deixar disponível o relatório e todo o processo realizado na análise no repositório, escolhemos o Jupyter Notebook. Além disso, conseguimos gerar os csv's com o Jupyter Notebook com muito mais agilidade.

**1º Passo:** Importar as bibliotecas necessárias para a análise, no caso, são as bibliotecas SQLalchemy e Pandas.

**2º Passo** Conectar-se ao banco de dados.

**3º Passo** Realizar as análises e responder as questões do CEO.




