# Análise de Preços de Automóveis

## Descrição do Projeto
Teste técnico para a vaga de estágio em ciência de dados na CVM
Este projeto tem como objetivo analisar e prever os preços de automóveis utilizando um modelo de regressão linear. Os dados foram extraídos de um conjunto de dados de automóveis e foram processados para construir um modelo preditivo.

## Dados
O conjunto de dados contém informações sobre características dos automóveis, como:
- engine-size
- horsepower
- city-mpg
- highway-mpg
- price

## Estrutura do Código
1. **Carregamento dos Dados**: Os dados são carregados a partir de um arquivo CSV.
2. **Tratamento de Dados**: Conversão de colunas para tipos numéricos e remoção de valores nulos.
3. **Criação de Variáveis**: Uma nova coluna `logPrice` é criada para transformar a distribuição de preços.
4. **Normalização**: Os dados são normalizados para facilitar a modelagem.
5. **Modelagem**: Um modelo de regressão linear é treinado e avaliado.
6. **Visualização**: Gráficos são gerados para visualizar os resultados.

## Resultados
- O coeficiente de determinação (R²) para o conjunto de treino foi de **X.XX**.
- O coeficiente de determinação (R²) para o conjunto de teste foi de **Y.YY**.

## Como Executar
1. Certifique-se de ter as bibliotecas necessárias instaladas (`pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`).
2. Execute o script Python para ver a análise e as visualizações.

## Conclusão
Este projeto demonstra a capacidade de manipular dados e aplicar técnicas de modelagem preditiva em Python.
