# Resultados de Busca de CPUs na Amazon - Análise de Dados
Este projeto é uma demonstração de habilidades em raspagem de dados na web com Python, limpeza de dados e visualização de dados. Os dados analisados consistem nos 10 principais resultados de pesquisa para CPUs Intel e AMD na Amazon.com, incluindo marca, título (nome do modelo), preço (em dólares americanos), frequência máxima prometida (GHz), TDP prometido (potência em watts), classificação média (de 0 a 5 estrelas) e os URLs para cada produto.

--- Coleta de Dados ---

Para raspar os dados, um script Python foi desenvolvido usando as bibliotecas Request, BeautifulSoup e OpenPyXL. O script analisa os resultados de pesquisa da Amazon.com para CPUs Intel e AMD e salva os dados relevantes em uma tabela do Excel. A classificação média (de 0 a 5 estrelas) também foi coletada, mas não foi considerada relevante na visualização.

--- Análise de Dados ---

Os dados mostram que as CPUs AMD têm um preço médio mais baixo e um TDP (potência) médio mais baixo em comparação com as CPUs Intel. Especificamente, o TDP médio para CPUs AMD é de 90W, enquanto o TDP médio para CPUs Intel é de 133W. Essa diferença no TDP resulta em um menor consumo de energia médio e temperaturas mais baixas para as CPUs AMD.

--- Visualização ---

Os dados foram visualizados no PowerBI, com gráficos e tabelas mostrando as diferenças entre as CPUs Intel e AMD em termos de preço e TDP. Essas visualizações destacam as vantagens das CPUs AMD em termos de eficiência energética e acessibilidade.

--- Conclusão ---

Este projeto demonstra a capacidade de coletar dados de sites usando Python e analisá-los para obter insights. Os resultados mostram que as CPUs AMD oferecem vantagens sobre as CPUs Intel em termos de preço e eficiência energética, o que pode ser uma informação útil para aqueles que estão no mercado em busca de uma nova CPU.

Para ver o código usado para coletar e analisar os dados, consulte o script Python, que inclui comentários detalhados explicando o processo de pensamento por trás de cada linha de código.






# Amazon CPU Search Results - Data Analysis

This project is a demonstration of web data scraping with Python, data cleaning, and data visualization skills. The data analyzed consists of the top 10 search results for Intel and AMD CPUs on Amazon.com, including brand, title (model name), price (in US dollars), advertised maximum clock speed (GHz), advertised TDP (wattage), average rating (from 0 to 5 stars), and the URLs for each product.

--- Data Collection ---

To collect the data, a Python script was developed using the Request, BeautifulSoup, and OpenPyXL libraries. The script scrapes Amazon.com search results for both Intel and AMD CPUs and saves the relevant data to an Excel table. The average rating (from 0 to 5 stars) was also scraped, but it was not found to be relevant in the visualization.

--- Data Analysis ---

The data shows that AMD CPUs have a lower average price and lower average TDP compared to Intel CPUs. Specifically, the average TDP for AMD CPUs is 90W, while the average TDP for Intel CPUs is 133W. This difference in TDP results in lower average power draw and temperatures for AMD CPUs.

--- Visualization ---

The data was visualized in PowerBI, with charts and tables showing the differences between Intel and AMD CPUs in terms of price and TDP. These visualizations highlight the advantages of AMD CPUs in terms of energy efficiency and affordability.

--- Conclusion ---

This project demonstrates the ability to scrape data from websites using Python and analyze it to gain insights. The results show that AMD CPUs offer advantages over Intel CPUs in terms of price and energy efficiency, which could be useful information for those in the market for a new CPU.

To see the code used to collect and analyze the data, please consult the Python script, which includes detailed commentary explaining the thought process behind each line of code.
