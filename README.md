# RNN-Predicao-Serie-Temporal-de-Manchas-Solares
- Fonte do dataset: 'https://raw.githubusercontent.com/jbrownlee/Datasets/master/monthly-sunspots.csv'
- Problema: A fonte possui a quantidade de manchas solares do ano de 1749 a 1983, onde através dessa série, pretende-se fazer a predição futura, juntamente com a verificação da acertividade. O modelo é treinado usando os dados de treinamento trainX e trainY, validado com os dados de teste testX e testY.
- Objetivo: Criar um modelo de rede neural recorrente (RNN) para previsão de séries temporais.
- Observação: Se aumentarmos a quantidade de hidden_units, que é o número de unidades ocultas na camada LSTM, a Perda (loss) e Erro Quadrático Médio (RMSE) podem diminuir ou aumentar.
