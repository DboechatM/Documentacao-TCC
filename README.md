
# Modelagem de Propriedades Físico-Químicas e Termodinâmicas do Óleo e Gás Utilizando Inteligência Artificial



![alt text](https://images.pexels.com/photos/87236/pexels-photo-87236.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940)

Documentação do Projeto Final apresentado ao Curso de Graduação em Engenharia Química, oferecido pelo departamento de Engenharia Química e de Petróleo da Escola de Engenharia da Universidade Federal Fluminense, como requisito parcial para obtenção do Grau de Bacharel em Engenharia Química.

Maio/2021

## 1. The Problem

A estimação de propriedades PVT (Pressão, Volume, Temperatura), como pressão de bolha, solução gás-óleo e fator de volume de formação de óleo são fundamentais para a indústria do petróleo, principalmente na determinação de cálculos de performance do reservatório, e estimativas de reserva. 

A precisão desses cálculos depende da exatidão na previsão das propriedades, que variam de acordo com a localização geográfica da reserva de óleo e gás e, idealmente, devem ser determinadas a partir de análises laboratoriais das amostras. Entretanto o custo envolvido e os tempos relativamente altos da análise incentivam a busca por outras ferramentas de previsão de tais propriedades, mas os erros nas predições introduzem distúrbios significativos nos cálculos inerentes às reservas.

Apesar dessas correlações apresentarem aproximações aceitáveis nas predições nesse setor, ainda existe a necessidade do desenvolvimento de técnicas otimizadas, dada a complexidade de caracterização dos fluidos de petróleo, seja pelo grau API, composição química ou localização geográfica

Alinhado a isso, a evolução crescente de metodologia de inteligência artificial torna possível o desenvolvimento de técnicas mais confiáveis e precisas para previsão de propriedades PVT de óleos crus.

## 2. Solution Strategy

To solve the business problem of the bank, the following steps will be done:
- Data Description: Identify data contaning on the dataset.
- Data Cleaning: Check for null values and duplicated data and solve them.
- Exploratory Data Analysis: Explore the data to find insights and to understand how the variables impact the price of the used car.
- Machine Learning Models: Build machine learning models to predict oil properties.
- Avaliation of the Machine Learning results: Check the results provided by the models.
- Clarify points for improvement, future work and real applications.


## 3. Machine Learning Model Applied

It has tested a list of Machine Learning regression algorithms and the one with the best performance was chosen to be used in future predictions.

- Decision Tree
- Random Forest
- SVR
- Neural Network


## 4. Machine Learning Model Performance and Results


Os comparativos entre os modelos de previsão obtidos e as correlações empíricas foram realizados mediante análise estatística de erros do conjunto de dados destinado aos testes, utilizando a metodologia proposta por Ikiensikimama e Azubuike, 2012, o qual ranqueia os modelos pelo somatório de pesos atribuídos a diferentes avaliadores estatíticos.

A escolha de tais pesos foi realizada de forma a integrar tanto o grau de acurácia do modelo justificado pela análise dos erros relativos e absolutos. quanto a dispersão dos erros de predição dos modelos gerados, considerando a análise dos desvios padrões e coeficiente de correlação.

Após a classificação dos modelos de previsão, o somatório com o menor valor foi selecionado como o melhor previsor da propriedade PVT analisada.


**IKIENSIKIMAMA, S. S. e AZUBUIKE, I. I.**, *Modeling Approach for Niger-Delta Oil Formation Volume Factor Prediction Using Artificial Neural Network*, In: CONFERÊNCIA E EXPOSIÇÃO ANUAL INTERNACIONAL DA NIGÉRIA, Abuja, Nigeria, Agosto, 2012.


| Model | R2 Adjusted Metric | Overall Points |
| ------- | ------- | ------- |
| Standing | 0.8511 | 0.553948 |
| Vasquez-Beggs |  0.8002 | 0.719749 |
| Glaso |  0.828 |  0.571705 |
| Al-Marhoun |  0.749 |  0.804580 |
| Petroski-Farshad |  0.7494 | 1.061715 |
| Decision Tree |  0.8455 | 0.549201 |
| Random Forest |  0.9149 | 0.301216 |
| **SVR** | **0.9507** | **0.150000** |
| Neural Network | 0.8906 | 0.423335 |


## 5. Conclusion

Objetivo deste trabalho foi verificar o poder de precisão de modelos criados por inteligência artificial a partir de um conjunto de dados. Como resultado, foi possível formular modelos de previsão de pressão de bolha e fator volume de formação de óleo mais eficazes que as correlações empíricas amplamente utilizadas para determinação destas propriedades.

Dessa forma, é demostrada a possibilidade da formulação de modelos capazes de prever, com menores erros, propriedades de petróleo a partir de um grande conjunto de dados. 

Tal fato minimiza desvios de cálculos referentes ao gerenciamento de reservas de petróleo, causados por previsões com consideradas porcentagens de erros associadas.

## Notebook solution of the problem

[Click here to see the notebook with the solution of this problem](https://github.com/DboechatM/Documentacao-TCC/blob/main/TCC_DOC.ipynb)


## TCC Submitted
[Click here to see the PDF](https://app.uff.br/riuff/handle/1/22026)
