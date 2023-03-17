## O código consiste em criar um pipeline, e então fazer uma seleção de modelos utilizando o GridSearch

É dividido nas seguintes etapas:
1 - Criar um pipeline com todos os componentes necessários para a sua solução de ML (e.g. pre-processing, transformação de dados, normalização, redução de dimensionalidade, classificação)
2 - Faça um gridsearch para achar os melhores parâmetros dos componentes da sua solução de ML
3 - Estime, em cima da base de dados de teste, a acurácia final, usando a melhor combinação de hyperparâmetros possíveis