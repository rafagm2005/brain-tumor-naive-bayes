Link artigo overleaf: https://pt.overleaf.com/read/sdbsqpbrqcmm#bd77f3

---

Link colab: https://colab.research.google.com/drive/1NgJxlCNAwckasa2mGANvJ1HyGY5bQecd?usp=sharing

---

Link documento: https://docs.google.com/document/d/1xFmX4sUJVMUGJTZFGaEMXo7F_buZQ6-8AexNCdJHYAg/edit?usp=sharing

---

# Classificação de Tumores Cerebrais em Imagens de Ressonância Magnética Utilizando Naive Bayes

## Descrição

Este projeto apresenta uma abordagem de Machine Learning para classificação de tumores cerebrais em imagens de ressonância magnética (MRI) utilizando o algoritmo Gaussian Naive Bayes.

O objetivo é identificar automaticamente quatro categorias:

- Glioma
- Meningioma
- Pituitary Tumor
- No Tumor

---

## Dataset

Foi utilizado o conjunto de dados público:

**Brain Tumor MRI Dataset**

Disponível em:

https://www.kaggle.com/datasets/tombackert/brain-tumor-mri-data

O dataset contém aproximadamente 7.153 imagens distribuídas em quatro classes.

---

## Tecnologias Utilizadas

- Python
- Google Colab
- NumPy
- OpenCV
- Matplotlib
- Scikit-Learn

---

## Metodologia

### Pré-processamento

- Conversão das imagens para escala de cinza;
- Redimensionamento para 64 × 64 pixels;
- Vetorização dos pixels;
- Conversão para arrays NumPy.

### Divisão dos Dados

- 80% treinamento;
- 20% teste.

### Modelo Utilizado

- Gaussian Naive Bayes.

---

## Métricas Avaliadas

- Accuracy
- Precision
- Recall
- F1-Score
- Matriz de Confusão

---

## Resultados

### Acurácia

59,47%

### Matriz de Confusão

| Classe Real | Glioma | Meningioma | Pituitary | No Tumor |
|-------------|--------:|-----------:|----------:|----------:|
| Glioma | 292 | 10 | 22 | 0 |
| Meningioma | 213 | 68 | 30 | 44 |
| Pituitary | 58 | 16 | 276 | 2 |
| No Tumor | 52 | 106 | 27 | 215 |

### Relatório de Classificação

| Classe | Precision | Recall | F1-score |
|---------|----------:|-------:|---------:|
| Glioma | 0.47 | 0.90 | 0.62 |
| Meningioma | 0.34 | 0.19 | 0.25 |
| Pituitary | 0.78 | 0.78 | 0.78 |
| No Tumor | 0.82 | 0.54 | 0.65 |


---

## Autores

- Rafael Gusmão de Mendonça
- Matheus Passos Mendonça Alves
- Lucca Borela Toledo Correia

---

## Instituição

UNIMA – AFYA  
Centro Universitário de Maceió

---

## Ano

2026
