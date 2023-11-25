# Classificação de Imagens com Perceptron

O objetivo principal é classificar imagens de pessoas com expressões faciais neutras e felizes (sorrindo), onde em opções binárias, 1 representa face neutra e 0 face feliz, apresentar também uma abordagem detalhada, desde o pré-processamento das imagens até uma análise minuciosa dos resultados obtidos com o modelo Perceptron.

# Conclusão

O projeto proporcionou uma introdução prática à aplicação de aprendizado de máquina em tarefas de classificação de imagens. As métricas indicam um desempenho consistente e promissor. Futuramente irei explorar abordagens mais avançadas e ajustar hiperparâmetros para aprimorar o modelo em aplicações práticas.

# Interpretação das Métricas

- **Precisão (Precision):** A precisão mede a proporção de instâncias positivas que foram corretamente previstas pelo modelo em relação ao total de instâncias positivas previstas. Uma precisão de 0.91 indica que aproximadamente 91% das previsões positivas feitas pelo modelo estão corretas.

- **Recall (Sensibilidade):** O recall mede a proporção de instâncias positivas que foram corretamente previstas pelo modelo em relação ao total de instâncias positivas reais. Neste caso, um recall de 0.95 significa que o modelo está identificando corretamente 95% das instâncias positivas reais.

- **F1-score:** O F1-score é uma média harmônica entre precisão e recall. Ele fornece uma medida única que equilibra ambas as métricas. Uma pontuação de 0.93 indica um equilíbrio sólido entre precisão e recall.

# Análise da Matriz de Confusão

- **Verdadeiro Positivo (TP):** 42 instâncias foram corretamente classificadas como positivas.

- **Falso Negativo (FN):** 2 instâncias positivas foram erroneamente classificadas como negativas.

- **Falso Positivo (FP):** 4 instâncias negativas foram erroneamente classificadas como positivas.

- **Verdadeiro Negativo (TN):** 32 instâncias foram corretamente classificadas como negativas.
  
Essa matriz permite uma análise mais granular do desempenho do modelo. Por exemplo, o valor baixo de falsos positivos (FP = 4) é um bom indicativo de que o modelo está rotulando erroneamente pouquíssimas instâncias negativas como positivas. A presença de poucos falsos negativos (FN = 2) sugere que o modelo está identificando corretamente quase todas as instâncias positivas, o que é refletido no recall alto (95%).

## Próximos Passos

Os próximos passos incluirão a exploração de abordagens mais avançadas, ajustes de hiperparâmetros e a aplicação prática do modelo em cenários do mundo real. Contribuições e sugestões são bem-vindas para enriquecer minha caminhada de aprendizado em ciência de dados.
