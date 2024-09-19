# CoinGeckoAPIML

É possível baixar e utilizar com o ambiente Jupyter Notebook. Mas para comodidade é apresentando no Google Colab na seguinte URL:
https://colab.research.google.com/drive/19CgUSKWm7-wEW-IB20jWHZW8KsWJU7ia?usp=sharing


# Resumo deste Notebook:

Foi utilizado principalmente o Pandas para tratamento de dados e Tensorflow/Keras para criação do modelo de ML a ser treinado.

O modelo utilizado para treinamento foi LSTM (Long Short-Term Memory), própria para valores de séries temporais. Já que o valor atual de uma bolsa de valores segue a tendência dos valores passados, é perfeito para a aplicação de LSTM.

Foram testados modelos de 3 moedas: Bitcoin, Ethereum e Dogecoin.

### O que pode ser expandido em futuras análises:
- Mais moedas? (O limite de uso da API limitou mais moedas.)
- Mais dados históricos? (A API limita a 365 dias para o uso gratuito.)
- O dia da semana influência no valor? (Dias de segundas normalmente seguem a tendência da Sexta-Feira anterior. "Monday Effect".)
- O mês influência no valor? (O mercado é mais pessimista em Setembro. "September Effect".)

