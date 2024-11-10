# 🦠 Análise de Dados da Dengue no Distrito Federal e Rio de Janeiro

Este repositório contém o código e a análise utilizados no estudo intitulado **"Análise de dados das ocorrências da dengue no Distrito Federal e Rio de Janeiro: uma verificação da consistência dos dados amostrais por meio de modelos preditivos de aprendizado de máquina"**. Este trabalho destaca a importância de dados significativos e consistentes para análises confiáveis e modelos preditivos precisos.

## 📄 Descrição do Projeto

O projeto aplica a metodologia **Design Science Research** para coletar, processar e analisar dados sobre casos de dengue em duas regiões brasileiras: Distrito Federal (DF) e Rio de Janeiro (RJ). O estudo inclui análises descritivas detalhadas e modelos preditivos para verificar a consistência dos dados e explorar relações entre variáveis.

### Objetivos:
- **Análise estatística descritiva** para mapear padrões de incidência e avaliar a relação com variáveis ambientais e demográficas.
- **Predição de casos de dengue** utilizando modelos de aprendizado de máquina, como regressão logística, árvore de decisão e SVM.

### 📊 Estrutura dos Dados

- **Distrito Federal (DF)**: Dados coletados do site `saude.df`, abrangendo 2019 a 2023.
- **Rio de Janeiro (RJ)**: Dados extraídos do portal `sistemas.saude.rj`, abrangendo 2016 a 2023, com foco em municípios específicos com dados mais completos.

Variáveis incluídas no estudo:
- 🌡️ Temperatura máxima e mínima
- 💧 Umidade máxima e mínima
- 🌧️ Precipitação média
- 👥 Densidade populacional

### 🛠️ Ferramentas Utilizadas

- **Linguagem de programação**: ![Python Logo](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
- **Bibliotecas principais**: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit-learn`
- **Ambiente de desenvolvimento**: Jupyter Notebook

## 🔍 Metodologia

### 1. Coleta e Pré-processamento de Dados
Os dados foram pré-processados com interpolação para lidar com valores faltantes e normalizados usando **Min-Max Scaling** para uniformizar as variáveis.

### 2. Análise Estatística Descritiva
Análise exploratória que inclui gráficos de dispersão, cálculos de correlação e visualização de padrões de casos de dengue.

### 3. Análise Multivariada
A regressão logística multivariada foi utilizada para avaliar a relação entre variáveis independentes (climáticas e demográficas) e os casos de dengue. Os coeficientes de significância foram analisados para determinar a relevância de cada variável.

### 4. Predição e Comparação de Modelos
Foi realizada uma análise preditiva para prever a incidência de casos de dengue nas próximas 52 semanas. Três modelos foram comparados:
- **Regressão Logística**
- **Árvore de Decisão**
- **Support Vector Machine (SVM)**

Cada modelo foi avaliado quanto à acurácia, e a comparação revelou que o modelo de **Árvore de Decisão** apresentou melhor desempenho em algumas regiões, enquanto o **SVM** se destacou em outras, ultrapassando a marca de 70% de acurácia.

## 📈 Resultados

- 👥 **Densidade populacional** foi a variável mais correlacionada com os casos de dengue.
- 📊 **Modelos de predição** mostraram que a eficácia varia por município, com a árvore de decisão e SVM apresentando os melhores desempenhos em regiões específicas.
- ✅ **Análise preditiva** indicou picos de casos no primeiro trimestre do ano, validando a importância das variáveis climáticas no comportamento sazonal da doença.

## ⚠️ Limitações e Trabalhos Futuros

- **Limitações**: Dados incompletos no DF afetaram a robustez da análise preditiva nessa região.
- **Melhorias futuras**: Sugere-se a inclusão de variáveis socioeconômicas e a ampliação da coleta de dados para melhorar a precisão das previsões.

## 👥 Autores
- **Lucas Santos Dalmaso** – [📧 Email](mailto:lucassdalmaso25@gmail.com)
- **Sabrina Mendes Braga** – [📧 Email](mailto:sabrinamendesbraga@gmail.com.br)
- **Raul Carvalho de Souza (Orientador)** – [📧 Email](mailto:raul.souza@iesb.edu.br)

## 🙏 Agradecimentos
Agradecemos ao **IESB** pelo suporte acadêmico e ao professor **Raul Carvalho de Souza** por sua orientação e apoio durante o desenvolvimento deste projeto.
