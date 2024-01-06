# Mini projetos em em Machine Learning

Este repositório contém mini-projetos que exploram modelos de classificação e regressão, além de incluir análises exploratórias de dados.

## Classificação

O projeto **Classificação e Avaliação de Risco de Crédito** tem como propósito desenvolver um modelo preditivo destinado a classificar o risco associado à concessão de crédito a clientes 
de uma instituição bancária. Nesse contexto, enfrentamos um desafio de classificação no qual o resultado do modelo determina se um cliente é considerado bom ou mau pagador.
Para alcançar esse objetivo, empregamos três algoritmos: o GLM (General Linear Model), Naive Bayes e Random Forest. Anteriormente, aplicamos técnicas de balanceamento de dados, 
como SMOTE e ROSE, visando melhorar a performance do modelo diante de desequilíbrios na distribuição dos dados.  
O notebook deste projeto encontra-se disponível [aqui](https://github.com/leticiadluz/mini_projetos_ML_R/blob/main/Classificacao_avaliacao_risco_credito_R.ipynb)

## Análise Exploratória de Dados
O projeto de **Análise Exploratória em Dados Socioeconômicos** visa abordar cinco questões fundamentais:
Pergunta 1: O aumento do PIB per capita em um país influencia positivamente a expectativa de vida ao nascer? Qual é a correlação entre essas duas variáveis?
Pergunta 2: Existe uma correlação entre a expectativa de vida e a consciência pública sobre a corrupção nos setores público e privado? Qual é a correlação entre essas variáveis?
Pergunta 3: O aumento na expectativa de vida tem algum impacto na média de felicidade geral da população? Qual é a correlação entre essas variáveis?
Pergunta 4: Países com baixo índice de suporte social apresentam maior percepção de corrupção em empresas e governo?
Pergunta 5: Indivíduos mais generosos tendem a ser mais felizes?
Neste projeto, utilizamos engenharia de atributos, juntamente com técnicas avançadas de análise exploratória de dados para investigar e responder a essas perguntas.  
O notebook deste projeto encontra-se disponível [aqui](https://github.com/leticiadluz/mini_projetos_ML_R/blob/main/AED_dados_socioeconomicos.ipynb)

## Prevendo o Consumo de Energia de Carros Elétricos

O projeto **Prevendo o Consumo de Energia de Carros Elétricos** tem como propósito desenvolver um modelo de Machine Learning capaz de prever o consumo de energia de carros elétricos. Isso será feito considerando uma variedade de fatores, incluindo o tipo e quantidade de motores elétricos no veículo, seu peso, capacidade de carga e outros atributos relevantes. Na construção do modelo, empregou-se a biblioteca RandomForest para avaliar a importância das variáveis. Ao final desse processo, optou-se pela utilização do modelo de regressão linear para a criação do modelo final.  Já a avaliação de desempenho do modelo de regressão inclui a análise de métricas fundamentais, como o Erro Quadrático Médio (MSE), a Raiz do Erro Quadrático Médio (RMSE) e o Coeficiente de Determinação (R²). Além disso, são realizadas verificações adicionais, como a avaliação da homocedasticidade para assegurar a constância da variância dos resíduos ao longo dos valores preditos, assim como a verificação da normalidade dos resíduos.

## Ferramentas utilizadas

* Jupyter Notebook

## Linguagem utilizada

* R
