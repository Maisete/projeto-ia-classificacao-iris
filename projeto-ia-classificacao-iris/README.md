# Projeto-Desafio IA na Prática – Classificação Iris

## Descrição  
Este projeto tem como objetivo desenvolver um sistema de predição usando técnicas de Aprendizado de Máquina para classificar espécies da flor Iris com base em suas medidas. O projeto inclui análise exploratória, pré-processamento dos dados, treinamento e avaliação de modelos de classificação, além de uma interface gráfica para predição em tempo real.

## Base de Dados  
Utilizou-se a base pública Iris, disponível no scikit-learn:  
https://archive.ics.uci.edu/ml/datasets/iris

## Etapas realizadas  
- Carregamento e análise exploratória dos dados (gráficos com seaborn e matplotlib)  
- Pré-processamento e codificação da variável alvo  
- Treinamento e avaliação de dois modelos: Decision Tree e Random Forest  
- Avaliação estatística com 30 execuções para medir média e desvio padrão da acurácia  
- Seleção do melhor modelo com base na acurácia média  
- Salvamento do modelo final usando pickle  
- Criação de interface gráfica para entrada dos dados e predição com Gradio

## Como usar  
1. Clone o repositório  
2. Execute o notebook `Projeto_IA_Iris.ipynb` para treinar os modelos e gerar o arquivo do modelo salvo  
3. Execute o código da interface Gradio para testar predições em tempo real  
4. Arquivos gerados:  
   - `melhor_modelo.pkl` (modelo treinado)  
   - `iris_pairplot.png` (gráfico exploratório)  
   - `relatorio_projeto_ia.txt` (relatório do projeto)

## Tecnologias  
- Python 3  
- Bibliotecas: pandas, scikit-learn, seaborn, matplotlib, pickle, gradio  
