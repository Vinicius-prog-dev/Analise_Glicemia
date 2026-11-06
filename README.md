# Análise Estatística de um Experimento de Redução da Glicemia

Este repositório contém um notebook em Python desenvolvido no Google Colab focado em **análise estatística de dados de saúde**, explorando o impacto de medicamentos e dietas na redução dos níveis glicêmicos de pacientes.

---

### 📊 Visão Geral do Projeto

O projeto realiza uma análise ponta a ponta (desde a importação e limpeza de dados até a modelagem estatística e visualização gráfica) utilizando conjuntos de dados simulados de pacientes diabéticos ou em tratamento.

#### **Etapas Principais da Análise:**
1. **Preparação e Limpeza de Dados:**
   - Importação de bibliotecas essenciais para manipulação e estatística (`pandas`, `numpy`, `scipy.stats`, `statsmodels`).
   - Leitura de arquivos de dados, tratamento de conversões numéricas e remoção de valores nulos ou inconsistentes.
2. **Análise 1: Efeito do Tratamento na Glicemia**
   - Avaliação da queda dos níveis glicêmicos antes e depois do tratamento utilizando o **Teste T Emparelhado** (`stats.ttest_rel`).
   - Geração de gráficos de caixa (*boxplots*) para visualização comparativa[cite: 1].
3. **Análise 2: Comparação entre Medicamentos**
   - Investigação estatística por meio do **Teste T para grupos independentes** (`stats.ttest_ind`) para verificar se diferentes medicamentos geram impactos distintos na redução da glicemia.
4. **Análise 3 e 4: Influência da Dieta e Confiabilidade**
   - Padronização de variáveis textuais (como a adesão ou não à dieta).
   - Construção de gráficos multivariados para isolar efeitos e cálculo de **Intervalos de Confiança de 95%** para mensurar a força estatística das diferenças entre as médias dos grupos.

---

### 🛠️ Tecnologias e Bibliotecas Utilizadas

* **Linguagem:** Python
* **Manipulação e Estruturação:** `pandas`, `numpy`
* **Estatística e Testes de Hipóteses:** `scipy.stats`, `statsmodels` (ANOVA e modelos de regressão)
* **Visualização de Dados:** `matplotlib`, `seaborn` (com temas customizados e gráficos estatísticos refinados)

---

### 🚀 Como Executar

Você pode clonar este repositório e abrir o arquivo `.ipynb` diretamente no seu ambiente Jupyter Notebook ou enviá-lo para o **Google Colab**.
