# Pydaboard_Cocode
Aprenda a realizar CRUD do DataFrame (Google Colab)
No curso Dasboard Python Alura 2025, foi dividido em 4 etapas:

Nesta primeira aula, denominada Análise de Dados com Pandas, utilizaremos a biblioteca do Python (Pandas), à Análise de Dados.
O código utiliza a biblioteca Pandas em Python para realizar uma análise exploratória de um conjunto de dados sobre empregos na área de dados. Inicialmente, os dados são carregados de um arquivo CSV hospedado no GitHub e analisados com métodos como head(), info() e describe(), permitindo visualizar a estrutura, os tipos de dados e estatísticas básicas do dataset.
Em seguida, as colunas do DataFrame são traduzidas para português para facilitar a compreensão. O código também analisa categorias como nível de senioridade, tipo de contrato, regime de trabalho e tamanho das empresas, utilizando value_counts() para contar a frequência de cada categoria.
Depois, as siglas dessas categorias são substituídas por nomes descritivos em português, tornando os dados mais legíveis. Por fim, é gerado um resumo estatístico das colunas categóricas, identificando as categorias mais frequentes, como cargos, moeda utilizada e localização predominante das empresas e profissionais.

Nesta segunda aula, chamada Preparação e Limpeza de Dados, utilizaremos a mesma biblioteca mencionada na primeira aula.
Nesta aula, foram apresentadas técnicas de preparação e limpeza de dados utilizando Pandas em Python. O código identificou valores nulos com métodos como isnull() e realizou diferentes formas de tratamento desses dados, como substituição pela média, mediana, preenchimento sequencial (ffill e bfill) e uso de valores padrão em campos categóricos. Por fim, foi utilizado o método dropna() para remover linhas com dados ausentes, garantindo um conjunto de dados mais limpo e consistente para análise.

Nesta aula, foram utilizadas as bibliotecas Matplotlib, Seaborn e Plotly em Python para criar visualizações de dados. Foram desenvolvidos gráficos de barras, histogramas, boxplots e gráficos de pizza para analisar distribuição salarial, níveis de senioridade, tipos de trabalho e médias salariais por país. A aula mostrou como a visualização de dados ajuda a identificar padrões, tendências e diferenças de forma clara e intuitiva.
