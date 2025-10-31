# LSTM_Prevencao_de_Acidentes
Modelo LSTM para prever a probabilidade de ocorrência de acidentes em determinado período nas rodovias brasileiras.

## Descrição
Projeto desenvolvido como parte do Sprint Challenge 4 da disciplina de Redes Neurais.  
O objetivo é prever a probabilidade de ocorrência de acidentes em determinado período nas rodovias brasileiras usando redes LSTM e dados da PRF.

## Target
O modelo prevê a **probabilidade de ocorrência de acidentes** em determinados períodos.

## Tratamento de Dados
- Limpeza de valores nulos e inconsistentes.  
- Conversão de datas para séries temporais.  
- Normalização e criação de sequências para entrada na LSTM.

## Arquitetura do Modelo
- Camada LSTM (64 neurônios)  
- Dropout (0.2)  
- LSTM (32 neurônios)  
- Dense (16 neurônios, ReLU)  
- Saída (1 neurônio, sigmoid)

## Métricas
- Accuracy: 0.89  
- ROC-AUC: 0.50  
- Observação: o modelo precisa de ajuste para lidar com desbalanceamento de classes.

