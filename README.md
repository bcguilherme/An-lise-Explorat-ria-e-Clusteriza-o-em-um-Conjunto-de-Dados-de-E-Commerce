Análise Exploratória e Clusterização em um Conjunto de Dados de E-Commerce

Este repositório contém um notebook Jupyter que realiza uma análise exploratória e aplicação do algoritmo K-Means em um conjunto de dados de e-commerce. O conjunto de dados inclui informações sobre pedidos, clientes, datas de pagamento e outras variáveis relevantes para a análise.

Conteúdo do Notebook:

Carregamento e Exploração Inicial do Conjunto de Dados
Pré-processamento de Dados: Tratamento de Valores Nulos e Duplicatas
Padronização de Variáveis Numéricas
Aplicação do Algoritmo K-Means para Clusterização
Análise de Recência e Boxplots
Outliers: Identificação e Tratamento
Visualização dos Resultados da Clusterização
Conclusões e Recomendações
Como Executar o Notebook:

Certifique-se de ter o ambiente Python configurado.
Instale as bibliotecas necessárias usando o seguinte comando:
bash
Copy code
pip install --upgrade jupyter pandas matplotlib scikit-learn yellowbrick
Execute o notebook Jupyter com o seguinte comando:
bash
Copy code
jupyter notebook ecommerce_analysis.ipynb
Observações:

O conjunto de dados é carregado a partir do arquivo CSV especificado (ecommerce.csv).
Algumas etapas envolvem a manipulação de datas, padronização de variáveis e aplicação do K-Means para identificar clusters nos dados.
O notebook inclui visualizações para ajudar na interpretação dos resultados.
