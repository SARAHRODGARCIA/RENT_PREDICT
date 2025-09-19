# 📊 Estudo Guiado: Regressão Polinomial para Previsão de Aluguel

Este estudo tem como objetivo explorar a relação entre **metragem de imóveis** e o **valor do aluguel**, utilizando **Regressão Polinomial**. O foco é entender como diferentes graus de polinômio afetam o ajuste do modelo e como interpretar os resultados de forma clara.

---

## 🎯 Objetivo
- Compreender a relação entre metragem e valor do aluguel.
- Aplicar técnicas de regressão polinomial.
- Avaliar modelos de diferentes graus usando métricas de desempenho.
- Aprender a interpretar coeficientes e gráficos para tirar insights.

---

## 🛠️ Etapas do Estudo

1. **Leitura e preparação dos dados**
   - Arquivo usado: `ALUGUEL_MOD12.csv`.
   - Variável independente: **Metragem**.
   - Variável dependente: **Valor do Aluguel**.
   
2. **Divisão em treino e teste**
   - Treino: 70% dos dados.
   - Teste: 30% dos dados.
   
3. **Construção do modelo**
   - Pipeline com `PolynomialFeatures`.
   - Teste de graus de polinômio. 
   - Seleção do melhor grau usando `GridSearchCV`.

4. **Avaliação do desempenho**
   - Métricas: **R²** (quanto o modelo explica a variação) e **MSE** (erro médio das previsões).
   - Comparação dos diferentes graus de polinômio.

5. **Visualização**
   - Gráfico de dispersão dos dados reais.
   - Curva do modelo ajustado.
   - Tabela com coeficientes para interpretar o impacto de cada termo.
   - 

## 📝 Conclusão e Aprendizado
- Para este conjunto de dados, **modelos simples são suficientes**.  
- O estudo permite entender:
  - A interpretação de coeficientes polinomiais.
  - A importância de métricas como R² e MSE.
  - Quando aumentar a complexidade do modelo não compensa.

---

## 🔍 Próximos Passos
- Testar outras variáveis que possam influenciar o aluguel (ex: localização, número de quartos).  
- Aplicar técnicas de regularização para modelos polinomiais maiores.  
- Explorar visualizações mais avançadas para comunicar os resultados de forma clara.
