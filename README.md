# 📊 Projeto de Análise de Preços de Aluguéis em São Paulo

Este projeto realiza uma análise exploratória e modelagem preditiva dos preços de aluguéis na cidade de São Paulo utilizando a linguagem Python e a biblioteca Pandas. O objetivo é explorar as variáveis que mais influenciam o valor dos aluguéis e ajustar um modelo de regressão linear para prever esses valores com base nas características dos imóveis.

## Introdução

O mercado imobiliário de São Paulo é dinâmico e complexo, com uma grande variação nos preços dos aluguéis dependendo de diversos fatores, como localização, área, número de quartos, entre outros. Este projeto visa entender esses fatores e construir um modelo preditivo para estimar o preço dos aluguéis.

## Objetivo

- Realizar uma análise exploratória dos dados de aluguéis em São Paulo.
- Ajustar um modelo de regressão linear para prever o preço dos aluguéis.
- Avaliar o impacto de diferentes variáveis no preço dos aluguéis.
- Testar a robustez do modelo com e sem a presença de outliers.

## Etapas do Projeto

1. **Importação e Limpeza dos Dados**: Carregamento dos dados e tratamento de valores ausentes.
2. **Análise Descritiva**: Cálculo de estatísticas descritivas e visualização de distribuições.
3. **Modelagem Preditiva**: Ajuste de um modelo de regressão linear, incluindo regularização com Ridge.
4. **Remoção de Outliers**: Avaliação do impacto da remoção de outliers no desempenho do modelo.
5. **Visualização dos Resultados**: Geração de gráficos de dispersão, resíduos e heatmaps.
6. **Conclusões**: Interpretação dos resultados e discussão sobre a eficácia do modelo.

## Resultados

- **Desempenho do Modelo**: O modelo de regressão linear apresentou um bom ajuste para prever os preços dos aluguéis, com a área sendo a variável mais influente.
- **Remoção de Outliers**: A remoção dos outliers não resultou em uma melhora significativa no modelo, indicando que os dados são robustos mesmo com a presença de valores extremos.

## Conclusões

O modelo linear ajustado foi capaz de capturar bem as variáveis mais importantes que influenciam o preço dos aluguéis em São Paulo. No entanto, a ausência de melhora após a remoção dos outliers sugere que o modelo é resistente à presença desses pontos extremos, ou que os outliers representam variações reais e significativas no mercado.
