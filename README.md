# Análise de dados Petlove - Investigação sobre o Churn da empresa

Essa análise de dados tem foco em investigar e entender o porquê do churn em uma empresa, para que possamos tomar providências em um futuro próximo e diminuir a perca de assinantes.


## Documentação Técnica

A análise foi feita em um notebook python, onde foram usadas as bibliotecas: 
- pandas
- matplotlib
- geopandas
- numpy

Foi feita a leitura do arquivo [CSV -  amostra](https://drive.google.com/file/d/1DS8eJZOJknolLVDHxWj-75w-G_trrYyj/view?usp=sharing) com pandas e em seguida uma rápida conversão dos tipos de dados.

Após isso, foi feita uma série de gráficos de rosca, barras e de linha, para uma melhor visualização dos dados, com matplotib.

Os cálculos foram feitos  de forma simples ou com a utilização do numpy.

O mapa do Brasil foi feito a partir do geopandas. Foi usado como base para a criação do mapa os dados geoespaciais das [malhas territoriais](https://www.ibge.gov.br/geociencias/organizacao-do-territorio/malhas-territoriais/15774-malhas.html) do IBGE. 
  - É necessário baixar os dados [Brasil - Unidade de Federação](https://geoftp.ibge.gov.br/organizacao_do_territorio/malhas_territoriais/malhas_municipais/municipio_2022/Brasil/BR/BR_UF_2022.zip) e ajustar o caminho do arquivo shapefile.

