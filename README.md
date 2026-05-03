# Analise-e-modelagem-de-dados-agricolas
Este projeto analisa a relação entre a concentração de água residuária tratada e a eficiência do uso da água (EUA) em mudas de maracujá-amarelo. O foco foi identificar o modelo que melhor descreve o comportamento dos dados e extrair insights práticos.


⚙️ Pipeline
- Ingestão de dados: leitura e tratamento de dados experimentais (Excel)
- EDA: análise exploratória com gráficos e estatísticas descritivas
- Modelagem: regressões linear, quadrática e cúbica
- Validação: métricas de erro + LOOCV
- Diagnóstico: análise de resíduos e ANOVA

📈 Resultados
- O modelo cúbico apresentou o melhor ajuste
- Relação não linear entre concentração e eficiência
- Identificação de ponto ótimo:
- EUA máxima: 2,43 g L⁻¹
- Concentração ótima: 68,32%

🧠 Insights
- Modelos simples (linear) não capturam bem o fenômeno
- A validação cruzada reforça a robustez do modelo escolhido
- Existe um nível ideal de aplicação → útil para tomada de decisão agronômica
