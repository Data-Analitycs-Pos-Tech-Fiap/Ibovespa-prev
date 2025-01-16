
# Previsão de Séries Temporais do Ibovespa

Este projeto apresenta uma análise detalhada dos dados históricos do Ibovespa e a aplicação de técnicas de machine learning para realizar previsões precisas sobre os valores de fechamento do índice. O foco principal está em explorar padrões, tendências e desenvolver modelos preditivos para dados financeiros.

---

## Resumo do Conteúdo
1. **Análise Exploratória de Dados (EDA):**
   - Transformação de dados, visualização e decomposição de séries temporais.
   - Identificação de sazonalidade, tendências e ruídos.
2. **Modelagem Preditiva:**
   - Comparação entre os modelos **ARIMA**, **Naive** e **Prophet**.
   - Escolha do modelo com melhor desempenho baseado em métricas como Acurácia e WMAPE.
3. **Resultados:**
   - O modelo **ARIMA** demonstrou a melhor performance geral, superando os demais modelos.

---

## Características do Projeto
- **Período dos Dados:** Janeiro de 2000 a Janeiro de 2025.
- **Frequência:** Diária.
- **Principais Variáveis:**
  - Data: Data de fechamento.
  - Último: Valor de fechamento diário.
  - Abertura, Máxima, Mínima, Volume e Variação Percentual (%).
- **Técnicas Utilizadas:**
  - Conversão de formatos de dados e manipulação de séries temporais.
  - Análise estatística com o teste de Dickey-Fuller Aumentado (ADF).
  - Aplicação de janelas móveis para detecção de tendências.

---

## Ferramentas Utilizadas
- **Linguagens e Bibliotecas:**
  - Python (Pandas, Numpy, Matplotlib, Seaborn).
  - Statsmodels (ARIMA).
  - Facebook Prophet.
- **Fontes de Dados:**
  - Dados históricos extraídos do site da Ibovespa.
- **Ambiente de Desenvolvimento:**
  - Jupyter Notebook para prototipação e análise interativa.

---

## Aplicações
- Este projeto pode ser usado para:
  - Tomar decisões informadas no mercado financeiro com base em previsões confiáveis.
  - Desenvolver pipelines automatizados de análise e previsão de séries temporais.
  - Criar visualizações para explorar dados históricos e suas implicações.

---

## Como Executar
1. Certifique-se de ter o Python 3.9+ instalado.
2. Instale as bibliotecas utilizando o comando:
   ```bash
   pip install 
