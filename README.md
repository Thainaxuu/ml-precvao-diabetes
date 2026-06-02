# Previsão de Resultados Clínicos com Machine Learning

Projeto acadêmico desenvolvido em equipe na Universidade de Mogi das Cruzes (UMC), apresentado na UMC Summit 3ª Edição com apoio de CNPq e FAEP.

## Objetivo

Avaliar o desempenho de técnicas de Machine Learning na previsão de diagnóstico de diabetes, investigando como diferentes estratégias de validação cruzada impactam a confiabilidade dos resultados.

## Dataset

Pima Indians Diabetes Dataset — 768 amostras, 8 variáveis preditoras e 1 variável alvo (Outcome).

## O que foi feito

- Pré-processamento: substituição de zeros por NaN e imputação pela média
- Normalização com StandardScaler
- Modelagem com Support Vector Machine (SVM), kernels linear e RBF
- Otimização de hiperparâmetros com GridSearchCV
- Comparação entre KFold-10 e StratifiedShuffleSplit como estratégias de validação cruzada
- Análise de acurácia, matriz de confusão, precision e recall

## Resultados

O StratifiedShuffleSplit se mostrou mais robusto para dados biomédicos desbalanceados, fornecendo estimativas mais consistentes e representativas em comparação ao KFold tradicional.

## Tecnologias

Python, scikit-learn, Pandas, NumPy, Matplotlib, Google Colab

## Autores

Projeto desenvolvido em equipe — Universidade de Mogi das Cruzes, São Paulo, Brasil.
