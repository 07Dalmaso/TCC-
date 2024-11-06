# Análise de Dados da Dengue no Distrito Federal e Rio de Janeiro

Este repositório contém o código e a análise utilizados no estudo intitulado **"Análise de dados da dengue do Distrito Federal e Rio de Janeiro: verificação da consistência dos dados amostrais por meio de modelos preditivos de aprendizado de máquina"**. O objetivo principal é demonstrar a importância da qualidade e quantidade de dados para análises confiáveis, usando técnicas de estatística descritiva e aprendizado de máquina.

## Descrição do Projeto

Este projeto aplica a metodologia **Design Science Research** para coletar, processar e analisar dados relacionados aos casos de dengue no Distrito Federal (DF) e Rio de Janeiro (RJ). A análise foi feita a partir de dados de incidência de dengue, dados climáticos e demográficos, abordando os seguintes pontos principais:

- **Análise estatística descritiva** para identificar padrões de incidência de dengue e relações com variáveis climáticas.
- **Modelagem preditiva** usando regressão logística multivalorada para determinar a influência de variáveis como temperatura, umidade, precipitação e densidade populacional.

### Estrutura dos Dados

- **Distrito Federal (DF)**: Dados coletados do site `saude.df`, abrangendo boletins epidemiológicos de 2019 a 2023.
- **Rio de Janeiro (RJ)**: Dados extraídos do portal `sistemas.saude.rj`, cobrindo um período de 2016 a 2023.

As variáveis utilizadas incluem:
- Temperatura máxima e mínima
- Umidade máxima e mínima
- Precipitação média
- Densidade populacional

### Ferramentas Utilizadas

- **Linguagem de programação**: Python
- **Bibliotecas principais**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Ambiente de desenvolvimento**: Jupyter Notebook

## Metodologia

### 1. Coleta e Pré-processamento de Dados
Os dados foram normalizados usando a técnica **Min-Max Scaling** para uniformizar as variáveis. Técnicas de interpolação foram aplicadas para lidar com valores faltantes.

### 2. Análise Estatística Descritiva
Incluiu a análise de dispersão, gráficos de dispersão, e matrizes de correlação para identificar relações entre as variáveis climáticas e os casos de dengue. O código utilizado para esta etapa pode ser acessado [aqui](https://github.com/07Dalmaso/TCC-Analise-de-dados-da-dengue/blob/master/TCC%20-%20CODIGO%20FINAL/analise_caso_dengue.ipynb).

### 3. Modelagem Preditiva
Foi utilizada a **regressão logística multivalorada** para prever a incidência de casos de dengue e avaliar a significância das variáveis. O código da análise preditiva pode ser acessado [aqui](https://github.com/07Dalmaso/TCC-Analise-de-dados-da-dengue/blob/master/TCC%20-%20ANALISE%20PREDITIVA/anlise_preditiva.ipynb).

## Resultados

- A densidade populacional foi identificada como a variável com a maior correlação com os casos de dengue.
- O modelo de regressão foi moderadamente eficaz para a cidade do Rio de Janeiro (com Pseudo R2 de 0.63), mas menos eficaz para outros municípios.
- A análise mostrou a importância de dados completos e de qualidade para resultados preditivos confiáveis.

## Limitações e Trabalhos Futuros

- **Limitações**: Falta de dados completos para o DF, o que limitou a análise preditiva nesta região.
- **Melhorias sugeridas**: Inclusão de variáveis socioeconômicas e extensão do período de coleta de dados.

## Autores
- **Lucas Santos Dalmaso** – [email](mailto:lucassdalmaso25@gmail.com)
- **Sabrina Mendes Braga** – [email](mailto:sabrinamendesbraga@gmail.com.br)
- **Raul Carvalho de Souza (Orientador)** – [email](mailto:raul.souza@iesb.edu.br)

## Agradecimentos
Agradecemos à instituição de ensino **IESB** pelo suporte acadêmico e pela oportunidade de desenvolver esta pesquisa. Também expressamos nossa gratidão ao professor **Raul Carvalho de Souza**, cujo suporte e orientação foram fundamentais para a conclusão deste trabalho.
