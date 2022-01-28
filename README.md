# Retail Customer Churn Prediction
Analysis of customer data to detect whether or not the customer will remain using the institution's services - Supervised classification (PT-BR)

## Objetivo
Conforme proposto pela IBM :
“O desafio consiste de implementar um algoritmo de Machine Learning para classificação binária, capaz de identificar se um cliente será perdido ou não.”

## Resumo do desenvolvimento
Um arquivo .csv foi disponibilizado pela IBM, contendo informações sobre os consumidores sendo dados pessoais como idade, dados de consumo como possuir celular, e dados de pagamento com quanto mensalmente e pago em parcelas de produtos. 
Inicialmente e feito o consumo deste arquivo para o jupyter notebook, e feita a analise exploratória dos dados, tratando valores nulos (NAs) e transformando valores categóricos em numéricos(encoding) para que os modelos de aprendizado de maquina pudessem ter melhor performance,  após os dados tratados e feita a analise exploratória univariavel e bivariavel, separados os dados em conjuntos de treino e teste, aplicando 4 modelos de aprendizado de maquinas, regressão logística, naive bayes, agrupamento de vizinhos (KNN) e random forest, sendo o modelo que teve melhor performance foi o random forest, o modelo e treinado novamente com variações de seus parâmetros para realizar o ajuste fino. Após modelo escolhido e ajustado, a tabela resposta e aplicada.

## Conclusão
Por fazer parte da maratona Behind the code 2021 o tempo de desenvolvimento do projeto foi bem curto, sendo feito em apenas 1 dia, apesar do tempo curto de desenvolvimento foi possível um tratamento adequado dos dados antes do processamento dos modelos de aprendizado de maquina tendo um resultado razoável, utilizando a métrica F1, na qual analisa a media harmônica entre os testes de precisao e recall, focado nos valores positivos (falsos positivos e verdadeiros positivos)

Em vista do negocio, quanto maior o valor de confiança da métrica F1 com maior certeza se saberá se aquele cliente esta em Churn (para de contratar/utilizar/comprar os serviços) e pode-se fazer algumas estratégias para evitar isso como descontos ou novos produtos, também e possível fazer uma analise quanto ao tipo de publico que mais entra em churn e se interessante mante-los ou não.

