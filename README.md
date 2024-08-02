Qual a diferença entre Estatística Descritiva e Estatística Inferencial? 🤔

⦿ Minhas três publicações anteriores foram dedicadas à exploração da estatística descritiva. Aprendi como estudar os fenômenos numa análise visual, entendendo as métricas e o comportamento das variáveis, identificar padrões, encontrar outliers ou anomalias, com o uso de gráficos e retornos descritivos. É o que chamamos de (EDA) Análise Exploratória de Dados.

⦿ Agora, com a estatística inferencial, temos a capacidade de entender a probabilidade de um fenômeno acontecer, desde que satisfeitas um conjunto de condições teóricas. Com base em amostras de uma população (indivíduos, objetos, eventos, medidas ou qualquer outra categoria de dados relevantes para a análise em questão), usamos testes de hipóteses para determinar se há uma diferença significativa entre um ou mais grupos, ou se uma correlação observada é estatisticamente significativa. Os resultados desses testes são interpretados em termos de probabilidade (valor-p), ajudando a quantificar o nível de evidência contra uma hipótese nula. É o que veremos neste estudo de caso abaixo.

Exemplo da teoria aplicada na prática:

🔴 Identificando o problema
- Investidores querem saber se há uma diferença significativa nos retornos diários entre dois setores na Bolsa, no caso para os setores 'imobiliário' e 'industriais'.

🟢 Apontando a solução
- Para a comparação de dois grupos, é usado o Teste T de Student. Determinamos se os retornos diários dos setores são estatisticamente diferentes.

⦿ Formulação das Hipóteses:
- Hipótese Nula (H₀): Não há diferença significativa entre as médias dos retornos diários dos setores comparados.

- Hipótese Alternativa (H₁): Há uma diferença significativa entre as médias dos retornos diários dos setores.

Neste teste, estão definidos os tópicos:

⦿ Teste de Normalidade:
Confere se os retornos diários dos setores industriais e imobiliários são normalmente distribuídos

⦿ Teste de Levene:
Verifica se as variâncias dos retornos diários entre os setores industriais e imobiliários são homogêneas.

⦿ Cálculo do valor de p:
Se este valor de p vier a ser menor que o nível de significância (por exemplo, 0.05), indicaria a rejeição da hipótese nula.

⦿ Cálculo (d de Cohen):
Mesmo que um teste estatístico mostre uma diferença significativa (um p-valor baixo), o d de Cohen pode indicar se essa diferença é suficientemente grande para ser de interesse prático.

⦿ Resultados:
Rejeitamos H₀ em favor de H₁? Ou falhamos em rejeitar H₀?
Acesse o código completo com os resultados detalhados desta análise 🔍🤓
