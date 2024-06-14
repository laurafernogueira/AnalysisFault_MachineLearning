## Classificação de Faltas em Linhas de Transmissão usando Machine Learning

Este repositório contém notebooks Jupyter usados para classificar tipos de faltas em linhas de transmissão utilizando diferentes algoritmos de machine learning. Os modelos incluídos são KNN, Regressão Logística, Floresta Aleatória, SVM e Redes Neurais Artificiais.

## Descrição dos Arquivos

- R1_KNN.ipyn*: Implementação do algoritmo K-Nearest Neighbors (KNN) para a classificação de faltas. 

- R1_Logistic_Regression.ipynb: Implementação do modelo de Regressão Logística para a classificação de faltas. Inclui o pré-processamento dos dados, normalização e treinamento do modelo.

- R1_RandomF.ipynb: Implementação do algoritmo de Floresta Aleatória para a classificação de faltas. Inclui a seleção de hiperparâmetros e avaliação do desempenho do modelo.

- R2_SVM.ipynb: Implementação da Máquina de Vetores de Suporte (SVM) para a classificação de faltas. Utiliza kernel e inclui a otimização de parâmetros usando validação cruzada.

- R2_RNA.ipynb: Implementação de Redes Neurais Artificiais (RNA) para a classificação de faltas. Inclui a criação da arquitetura da rede, treinamento e avaliação do modelo.

## Arquivos de Simulação

- pos0091_AB_resistencia_001_0.csv: Exemplo de um arquivo de simulação contendo dados de uma falta do tipo AB. Este arquivo contém 5000 linhas de valores de tensão e corrente registrados durante uma falta simulada em uma linha de transmissão.
- Os dados são usados para treinar e testar os modelos de machine learning.

Os arquivos de simulação são armazenados em subpastas de acordo com os tipos de falta, como AB, ABC, AC, ACG, AG, ABG, BC, BCG, BG, CG e NO FAULT. Cada arquivo CSV segue o formato:

| Tempo | Tensão_Fase_A | Tensão_Fase_B | Tensão_Fase_C | Corrente_Fase_A | Corrente_Fase_B | Corrente_Fase_C |
|-------|----------------|----------------|----------------|------------------|------------------|------------------|
| ...   | ...            | ...            | ...            | ...              | ...              | ...              |

## Estrutura dos Dados

Os dados utilizados neste projeto estão armazenados em arquivos CSV e são organizados em subpastas correspondentes aos tipos de faltas: AB, ABC, AC, ACG, AG, ABG, BC, BCG, BG, CG. Cada arquivo CSV contém 5000 linhas de valores de tensão e corrente.

## Pré-processamento dos Dados

Os notebooks incluem etapas de pré-processamento dos dados, como:

- Limpeza de dados
- Tratamento de valores ausentes
- Normalização dos dados
- Segmentação temporal em janelas de tempo relevantes


## Modelos de Machine Learning

Os seguintes modelos são testados para a classificação de faltas:

1. K-Nearest Neighbors (KNN)
2. Regressão Logística
3. Floresta Aleatória
4. Máquina de Vetores de Suporte (SVM)
5. Redes Neurais Artificiais (RNA)

## Métricas de Avaliação

Para avaliar o desempenho dos modelos, as seguintes métricas são utilizadas:

- Acurácia
- Precisão
- Recall
- F1-Score
- Matriz de Confusão

## Instruções de Uso

1. Clone este repositório:

   bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   

2. Navegue até o diretório do projeto:

   bash
   cd seu-repositorio
  

3. Abra um dos notebooks Jupyter:

   bash
   jupyter notebook R1_KNN.ipynb
   
4. Execute as células para treinar e avaliar o modelo.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests para melhorias.

