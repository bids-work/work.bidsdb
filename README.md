📊 Previsão de Estoque Inteligente na AWS com SageMaker Canvas
Desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas.


🎯 Objetivos Deste Desafio de Projeto (Lab)

1. Selecionar conjunto de dados
A partir do repositório repositório: digitalinnovationone/lab-aws-sagemaker-canvas-estoque, selecionado o arquivo: dataset-1000-com-preco-promocional-e-renovacao-estoque.csv
Realizado uplado do conjunto de dados no SageMaker Canvas.

2. Construir/Treinar
No SageMaker Canvas, importado o conjunto de dados: dataset-1000-com-preco-promocional-e-renovacao-estoque.csv
Realizado o treinamento do modelo.

3. Analisar
Examinadas as métricas de desempenho do modelo, destacamos as análises abaixo:
Avg.wQL 0.018; indicando que tem alguma variabilidade, mas não excessivamente dispersos, portanto confiáveis.
MAPE 0.021; considerando que 2,1% seja a previsão de erro em relação aos valores reais, a previsão é precisa. 
WAPE 0.020; sendo uma previsão de erro de 2%, é uma métrica útil.
RMSE 3.475
MASE 0.700

Para as outras métricas, precisaríamos aprofundar as pesquisas e comparativos com outros modelos, mas a interpretação é de que trata-se de um modelo confiável.


5. Prever
Utilizado o modelo treinado com as seguintes análises preditivas:
Interessante as análises preditivas de P10, P50 e P90 (visão pessimista, médida ou provável e otimista).
Para o item 1000, por exemplo, com estoque de 156.179 com range entre 08/02/2024 e 09/02/2024 são, respectivamente: P10: 132.177; P50: 153.809 e P90: 153;.997.
Para ao item 1014, P10: 120.866 e P50: 130.355.
Podendo realizar as análises preditivas para cada item, separadamente, o que poderia ser um critério importante para apoio na avaliação para previsão de estoque.


7. Observações
Conforme comentários no Fórum, gostaria de aprofundar nos treinamentos do modelo e análises, mas em virtude da AWS continuar gerando cobrança ainda que tenhamos estabelecido os alertas para o budget estabelecido de uso gratuito, continua gerando cobranças. Com isso, preferi não dar continuidade para evitar cobranças adicionais não programadas.
Mas o conteúdo e a ferramenta se apresentaram muito interessantes e pretendo prosseguir oportunamente.
