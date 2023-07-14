# Desafio Cientista de Dados 2023 - Lighthouse Indicium - Cássio Costa

## Desafio Cientista de Dados - Precificação de Veículos Usados
Este repositório contém a solução para o Desafio Cientista de Dados proposto pela Indicium. O objetivo do desafio é resolver um problema de negócio relacionado à revenda de veículos usados por meio da análise de dados e construção de um modelo preditivo de precificação.

### Contexto
O cliente em questão é uma empresa de compra e venda de veículos usados que está enfrentando dificuldades em sua área de revenda. Para resolver esse problema, a empresa adquiriu uma base de dados de um marketplace de compra e venda para entender melhor o mercado nacional e precificar seu catálogo de forma mais competitiva.

### Dados
O desafio fornece dois conjuntos de dados: "cars_training" para treinamento, composto por 29 colunas, incluindo a variável alvo "preco", e "cars_test" para teste, sem a coluna "preco". O conjunto de treinamento contém informações descritivas sobre os veículos, como marca, modelo, ano de fabricação, hodômetro, tipo de câmbio, número de portas, entre outras.

### Etapas
O desafio é dividido em várias etapas principais:

Análise Exploratória de Dados (EDA): Foi realizada uma análise detalhada dos dados, incluindo a análise das principais estatísticas descritivas das variáveis, visualização gráfica das variáveis e identificação de insights relevantes. Foram respondidas perguntas de negócio e formuladas hipóteses relacionadas à venda de carros em diferentes estados, tipos de veículos e características específicas.

Modelagem Preditiva: Com base nos dados analisados, foi desenvolvido um modelo preditivo para precificar os carros do cliente. Foram utilizadas técnicas de pré-processamento de dados, seleção de variáveis e construção de um pipeline de modelagem. O modelo escolhido foi o XGBoost, devido à sua capacidade de lidar com dados complexos e fornecer resultados precisos.

Avaliação do Modelo: O modelo foi avaliado usando métricas adequadas para problemas de regressão, como R-squared, MAE, MSE, RMSE e MAPE. Essas métricas forneceram uma medida do desempenho do modelo em relação aos valores reais de preço dos carros.

Resultados: Os resultados finais do modelo foram apresentados em um arquivo CSV contendo as colunas "id" e "preco", que representa as previsões de preço para os veículos do conjunto de teste.

### Estrutura do Repositório
data/: Pasta contendo os conjuntos de dados fornecidos.
notebooks/: Pasta contendo os notebooks Jupyter utilizados para a análise exploratória dos dados e construção do modelo preditivo.
reports/: Pasta contendo os relatórios gerados durante a análise exploratória dos dados.
predicted.csv: Arquivo CSV contendo as previsões de preço para os veículos do conjunto de teste.
requirements.txt: Arquivo contendo as dependências do projeto e suas respectivas versões.
Instruções de Uso
Clone o repositório para sua máquina local.

Certifique-se de ter todas as dependências necessárias instaladas executando o comando **pip install -r requirements.txt**.

Explore os notebooks na pasta notebooks/ para entender o processo de análise exploratória dos dados e construção do modelo.

Execute o código presente nos notebooks ou adapte-o conforme necessário para ajustar ao seu ambiente e dados.

### Considerações Finais
Este desafio foi uma ótima oportunidade para aplicar conceitos estatísticos e técnicas de modelagem de dados para resolver um problema de negócio real. A análise exploratória dos dados permitiu entender melhor o mercado de revenda de veículos usados, identificar padrões e insights importantes e tomar decisões fundamentadas.

O modelo preditivo desenvolvido apresentou resultados promissores e foi capaz de precificar os veículos de forma mais próxima dos valores de mercado. No entanto, é importante destacar que a melhoria contínua do modelo e sua validação contínua são essenciais para garantir sua eficácia.

Espero que este projeto demonstre minhas habilidades e conhecimentos como Cientista de Dados e contribua para o sucesso do desafio proposto pela Indicium.
