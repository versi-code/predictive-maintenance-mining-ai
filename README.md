# Manutenção Preditiva de Máquinas Industriais com IA

Este projeto utiliza Inteligência Artificial para prever falhas em equipamentos industriais de mineração, utilizando dados elétricos e mecânicos simulados. 
O objetivo geral é demonstrar de forma prática como aplicar aprendizado de máquina em manutenção preditiva.

## Objetivos

- Criar dataset sintético com métricas reais de operação de máquinas.
- Analisar os dados para encontrar padrões de falhas.
- Treinar modelos de IA: Random Forest, SVM e Logistic Regression.
- Criar protótipo simples em Python para previsão de falhas.

## Estrutura do Projeto
- Dataset (CSV e Excel)

├── data/

- Notebooks de EDA e Modelagem
  
├── notebooks/ 

- Scripts de pré-processamento e modelos
  
├── src/ 

- Este arquivo de descrição
  
├── README.md

- Dependências do projeto
  
├── requirements.txt 


## Dataset

O dataset contém leituras de sensores de máquinas industriais:

- Temperatura (°C)
- Vibração RMS (mm/s)
- Corrente (A)
- Tensão (V)
- Potência (kW)
- Velocidade de rotação (RPM)
- Torque (Nm)
- Pressão (bar)
- Nível de óleo (%)
- Desgaste da ferramenta (%)
- RUL (Remaining Useful Life)
- Flag de falha (0 = normal, 1 = falha)
- Tipo de falha (bearing_fault, imbalance, electrical_fault, overheating, none)

## Modelos de IA

Random Forest

Support Vector Machine (SVM)

Logistic Regression

Métricas avaliadas: acurácia, precisão, recall e F1-score.

## Resultados Esperados

Identificação de padrões de falha em máquinas industriais.

Protótipo em Python para predição de falhas.

Demonstração didática do uso de IA em manutenção preditiva.

## Roadmap

Mês 1: Definição do problema, levantamento de bibliografia e criação do dataset sintético.

Mês 2: Análise exploratória dos dados e pré-processamento.

Mês 3: Treinamento e avaliação de modelos de IA.

Mês 4: Criação do protótipo, documentação final e entrega.



