📊 Dashboard de Performance de Vendas (E-commerce)
Este projeto apresenta uma solução de ponta a ponta para análise de vendas, abrangendo desde a extração e tratamento de dados brutos com Python até a criação de um dashboard executivo interativo no Power BI.

🚀 Visão Geral do Projeto
O objetivo foi transformar uma base de dados bruta de vendas em insights acionáveis. O projeto foca em KPIs críticos como Faturamento Total, Ticket Médio e performance regional.

🛠️ Stack Tecnológica
Python (Jupyter Notebook): Utilizado para o processo de ETL (Extração, Transformação e Carga).

Pandas: Manipulação, limpeza e tratamento dos dados brutos.

Power BI: Modelagem visual e criação de medidas em DAX.

Excel/CSV: Fonte de dados original.

⚙️ Processo de Engenharia de Dados (ETL)
Em vez de realizar o tratamento diretamente no Power BI, optei por uma abordagem de Engenharia de Dados utilizando Python para garantir a qualidade dos dados antes da visualização:

Limpeza: Remoção de duplicatas e tratamento de valores ausentes.

Tipagem: Conversão de formatos de data e valores numéricos para otimização de performance.

Preparação: Geração de uma Flat Table otimizada para consumo rápido no Power BI.

Você pode conferir o código completo no arquivo: miniprojeto1.ipynb

📊 Visualização e Insights
O dashboard foi desenhado com foco em UX (User Experience), utilizando um tema escuro moderno para facilitar a leitura dos KPIs:

Faturamento Global: Visão consolidada da receita.

Ticket Médio: Valor médio gasto por transação.

Ranking de Produtos: Identificação dos itens mais vendidos (ex: Eletrônicos e Laptops Gamer).

Distribuição Geográfica: Faturamento detalhado por estado (destaque para SP e CE).

📸 Demonstração
Visão geral dos principais indicadores de vendas.

Exemplo de interatividade e comportamento dos dados sob filtros específicos.
<img width="1955" height="1096" alt="image" src="https://github.com/user-attachments/assets/78f05a49-c7a5-4e7c-a79c-63fc045ae9cc" />


📂 Estrutura do Repositório
/img: Prints do dashboard.

dados_vendas_ecommerce.xlsx: Base de dados original utilizada.

miniprojeto1.ipynb: Notebook com todo o tratamento de dados em Python.

VendasDashboard.pbix: Arquivo fonte do Power BI.

✍️ Autor
Renato Batista Analista de Dados Jr. | Estudante de Engenharia de Dados [https://www.linkedin.com/in/renato-santos1978/] | [nato_rj@yahoo.com.br]
