# Desafio Cientista de Dados 2023 - Lighthouse Indicium - Cássio Costa

## Desafio Cientista de Dados - Precificação de Veículos Usados
Este repositório contém a solução para o Desafio Cientista de Dados proposto pela Indicium. O objetivo do desafio é resolver um problema de negócio relacionado à revenda de veículos usados por meio da análise de dados e construção de um modelo preditivo de precificação.

### Contexto
O cliente em questão é uma empresa de compra e venda de veículos usados que está enfrentando dificuldades em sua área de revenda. Para resolver esse problema, a empresa adquiriu uma base de dados de um marketplace de compra e venda para entender melhor o mercado nacional e precificar seu catálogo de forma mais competitiva.

### Dados
O desafio fornece dois conjuntos de dados: "cars_training" para treinamento, composto por 29 colunas, incluindo a variável alvo "preco", e "cars_test" para teste, sem a coluna "preco". O conjunto de treinamento contém informações descritivas sobre os veículos, como marca, modelo, ano de fabricação, hodômetro, tipo de câmbio, número de portas, entre outras.

**OBS:** O relatório contendo as respostas das 3 hipóteses de negócio propostas pelo desafio, juntamente com as 3 hipóteses elaboradas e respondidas por mim, está disponível no arquivo Jupyter Notebook **1 - EDA_desafio_lighthouse.ipynb**, localizado na pasta "Códigos" do repositório. Nesse arquivo, você encontrará uma análise exploratória detalhada dos dados, as perguntas de negócio respondidas e as respectivas conclusões obtidas.

### Etapas
O desafio é dividido em várias etapas principais:

Análise Exploratória de Dados (EDA): Foi realizada uma análise abrangente dos dados, abordando tanto a análise univariada quanto a multivariada. Isso incluiu a investigação das principais estatísticas descritivas das variáveis, a visualização gráfica dos dados e a identificação de insights relevantes. Além disso, foram respondidas as perguntas de negócio propostas e formuladas novas hipóteses relacionadas à venda de carros.

Pré-Processamento: Foram realizadas exclusões de colunas incorretas e irrelevantes para o modelo, bem como a criação de novas colunas com base nas existentes.

Modelagem Preditiva: Com base na análise dos dados, foi desenvolvido um modelo preditivo para precificar os carros. Os algoritmos foram divididos em dois grupos e testados em um loop: o primeiro grupo contendo algoritmos diversos e o segundo grupo contendo algoritmos baseados em árvores. Foi construído um pipeline de modelagem para esse propósito. O modelo escolhido como o mais adequado foi o XGBoost, devido à sua capacidade de lidar com dados complexos e fornecer resultados precisos.

Avaliação do Modelo: O modelo foi avaliado usando métricas adequadas para problemas de regressão, como R-squared, MAE, MSE, RMSE e MAPE. Essas métricas forneceram uma medida do desempenho do modelo em relação aos valores reais de preço dos carros.

Resultados: Os resultados finais do modelo foram apresentados em um arquivo CSV contendo as colunas "id" e "preco", que representa as previsões de preço para os veículos do conjunto de teste.

### Estrutura do Repositório
Dados/: Pasta contendo os conjuntos de dados fornecidos e criados durante o processo.

Códigos/: Pasta contendo os notebooks Jupyter utilizados para a análise exploratória dos dados e construção do modelo preditivo.

Modelo/: Pasta contendo o modelo final.

Predicted/: Pasta contendo o Arquivo CSV com as previsões de preço para os veículos do conjunto de teste.

Requirements/: Pasta contendo um Arquivo txt com as dependências do projeto e suas respectivas versões.

Instruções/: Pasta contendo as intruções para esse projeto.

#### Instruções de Uso
Clone o repositório para sua máquina local.

Certifique-se de ter todas as dependências necessárias instaladas executando o comando **pip install -r requirements.txt**.

Explore os notebooks na pasta Códigos/ para entender o processo de análise exploratória dos dados e construção do modelo.

Execute o código presente nos notebooks ou adapte-o conforme necessário para ajustar ao seu ambiente e dados.

### Considerações Finais
Este desafio foi uma ótima oportunidade para aplicar conceitos estatísticos e técnicas de modelagem de dados para resolver um problema de negócio real. A análise exploratória dos dados permitiu entender melhor o mercado de revenda de veículos usados, identificar padrões e insights importantes e tomar decisões fundamentadas.

O modelo preditivo desenvolvido apresentou resultados promissores e foi capaz de precificar os veículos de forma mais próxima dos valores de mercado. No entanto, é importante destacar que a melhoria contínua do modelo e sua validação contínua são essenciais para garantir sua eficácia.

Espero que este projeto demonstre minhas habilidades e conhecimentos como Cientista de Dados e contribua para o sucesso do desafio proposto pela Indicium.
