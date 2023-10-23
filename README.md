# # Entendendo os custos de seguro saúde

## Visão Geral

Neste projeto, vamos analisar os dados disponíveis, no conjunto de dados de custos médicos dos EUA do kaggle.

Você pode conferir o dataset e o projeto na íntegra clicando abaixo:

Link dataset: https://www.kaggle.com/datasets/annetxu/health-insurance-cost-prediction

Link do código do projeto: https://github.com/gustavoptavares/Seguro-Saude/blob/main/Seguro_Sa%C3%BAde.ipynb

## Problema e Solução

Vamos analisar os dados o conjunto de dados de custos médicos. Com a pandemia de Covid-19, o seguro saúde tornou-se uma das áreas de investigação mais proeminentes, vamos entender, no detalhe, aspectos relacionados a custos, como:

• Enteder o conjunto de dados com os dados relacionadas aos custos.

• Previsão do custo do seguro e a relação com as variáveis. 

## O Processo

O primeiro passo do projeto foi adquirir os dados. Utilizamos os dados do portal Kaagle, carregando-o no Google Colab, para a exploração e análise dos dados utilizando a linguagem de programação Python e suas bibliotecas, como Pandas, Matplotlib e Scikit-Learn. Foi feita análise exploratória, visualização dos dados, e foi aplicado o modelo de machine learning de regressão, utilizando o algoritmo de regressão linear para previsão do custo de seguro.

## Resultados

As métricas de avaliação para o modelo de regressão linear:

Erro Médio Quadrático (MSE): 31,827,950.23

Raiz do Erro Médio Quadrático (RMSE): 5,641.63

Coeficiente de Determinação (R²): 0.7999 - Isso indica que aproximadamente 80% da variabilidade da variável resposta (charges) é explicada pelo modelo.

## Conclusões

A variável mais impactante nos custos do seguro é se a pessoa é fumante ou não. Fumantes tendem a ter custos de seguro significativamente mais altos do que não fumantes.

A idade e o índice de massa corporal (BMI) também desempenham papéis importantes na determinação dos custos do seguro.

A região em que uma pessoa vive e o gênero têm impactos menores nos custos.

É importante observar que estes insights são específicos deste conjunto de dados e do modelo de regressão linear. Em diferentes contextos ou com diferentes modelos, as conclusões podem variar.
