# Projeto IADT Colab — Classificação de Câncer de Mama

Repositório destinado à entrega acadêmica dos notebooks desenvolvidos no Google Colab para o Tech Challenge 1 da pós-graduação, contemplando análise de dados, Machine Learning e um notebook complementar de Visão Computacional com CNN.

---

## Estrutura do Projeto
```text
projeto-IADT-colab/
│
├── notebook-extra/
│   └── Visao_Computacional_CNN_Diagnostico_de_Cancer.ipynb
│
├── notebook-tech-challenge/
│   └── Tech_Challenge_1_POSTECH_v1.ipynb
│
├── data/
│   └── data.csv
│
├── requirements.txt
├── README.md
└── .gitignore
```
---

## Notebooks

### Tech Challenge 1 — Machine Learning — Classificação de Câncer de Mama

Arquivo:
notebook-tech-challenge/Tech_Challenge_1_POSTECH_v1.ipynb

Este notebook realiza a classificação de tumores mamários (benigno/maligno) utilizando técnicas clássicas de Machine Learning.

### Principais etapas realizadas:
- Carregamento e análise do dataset;
- Análise exploratória dos dados;
- Tratamento e preparação das variáveis;
- Normalização com StandardScaler;
- Codificação da variável alvo;
- Treinamento de modelos de Machine Learning;
- Avaliação com matriz de confusão, relatório de classificação e curva ROC.

### Modelos utilizados:
- Logistic Regression
- SVM
- KNN
- Random Forest

### Dataset:
Breast Cancer Wisconsin (Diagnostic) Data Set (Kaggle)

https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

## Apresentação
A apresentação do projeto está disponível em:
https://youtu.be/IPdttGBSu9U 

---

### Projeto Extra — Deep Learning (CNN)

Arquivo:
notebook-extra/Visao_Computacional_CNN_Diagnostico_de_Cancer.ipynb

Aplicação de Redes Neurais Convolucionais (CNN) para classificação de imagens médicas.

### Principais etapas realizadas: 
- Download do dataset via Kaggle;
- Preparação das imagens;
- Pré-processamento;
- Data augmentation;
- Construção de modelo com Transfer Learning;
- Utilização da arquitetura MobileNetV2;
- Treinamento da CNN;
- Avaliação do modelo;
- Fine-tuning;
- Análise de predições e matriz de confusão.

### Técnicas:
- TensorFlow/Keras;
- MobileNetV2;
- Transfer Learning;
- Data Augmentation;
- avaliação por matriz de confusão e relatório de classificação.

### Dataset:
CBIS-DDSM: Breast Cancer Image Dataset (Kaggle)

https://www.kaggle.com/datasets/awsaf49/cbis-ddsm-breast-cancer-image-dataset

---

## Dataset local
Arquivo local:
data/data.csv

Esse arquivo corresponde ao dataset Breast Cancer Wisconsin, utilizado no notebook principal.

Observação: o notebook também pode realizar o download do dataset via `kagglehub`, caso seja executado no Google Colab ou em ambiente com autenticação configurada.


---

## Tecnologias Utilizadas
O projeto utiliza as seguintes bibliotecas principais:

- Python;
- Pandas;
- NumPy;
- Matplotlib;
- Seaborn;
- Scikit-learn;
- TensorFlow/Keras;
- Kaggle;
- KaggleHub.

---

## Como Executar

### Google Colab (Recomendado)
Abra os notebooks diretamente no Colab e execute célula por célula.

---

### Ambiente Local
Clone o repositório:

git clone https://github.com/SEU-USUARIO/projeto-IADT-colab.git

Acesse:
cd projeto-IADT-colab

Instale dependências:
pip install -r requirements.txt

Execute:
jupyter notebook

---

## Configuração Kaggle (para CNN)

No Google Colab, configure:

KAGGLE_USERNAME  
KAGGLE_KEY  

---

## Objetivo Acadêmico

Demonstrar a aplicação de técnicas de Machine Learning e Deep Learning na área da saúde, com foco em classificação de câncer de mama.

---

## Autor

Grupo:
```text
Gabriel Paoliello RM370704 - ga.paoliello@gmail.com
Pedro Rogala RM372338 - pedrorogala@gmail.com
Sandro Felipe RM372111 - kleyguerth@gmail.com
Rafaella Reis RM373710 - rafaelareis20@gmail.com
Wisley Siqueira RM374052 - dev.wisleysiqueira@gmail.com
```
Turma: 9IADT

Curso: Pós-graduação  
Instituição: POSTECH
