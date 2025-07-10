# 🔢 PCA aplicado ao Reconhecimento de Dígitos - EP1 de Álgebra Linear Computacional

![Badge Concluído](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)  
![Feito em Python](https://img.shields.io/badge/Python-Feito%20em-blue)  
![Feito em Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)

## 📚 Descrição

Este notebook é parte do **Exercício de Programação 1 (EP1)** da disciplina **Álgebra Linear Computacional - 2025.1 - DCC/UFMG**.  
O objetivo principal é implementar e aplicar a técnica de **Análise de Componentes Principais (PCA)** para o **reconhecimento de dígitos manuscritos**, reduzindo a dimensionalidade das imagens e facilitando a classificação.

## 🧠 Contexto

- O notebook introduz o conceito de **PCA** com um exemplo visual utilizando **eigenfaces** da base Yale Faces, apenas para fins ilustrativos.
- Em seguida, o foco passa para a aplicação prática da técnica no **reconhecimento de dígitos manuscritos**.
- O reconhecimento é feito comparando as representações reduzidas de treino e teste, utilizando a distância euclidiana no espaço projetado.

## ✨ Objetivos do Projeto

- Implementar PCA "na mão", usando conceitos de álgebra linear.
- Aplicar PCA a um conjunto de imagens de dígitos.
- Reduzir a dimensionalidade dos dados sem perda significativa de informação.
- Realizar reconhecimento de dígitos com base nos componentes principais.
- Analisar o impacto do número de componentes na taxa de acerto.

## 🧰 Tecnologias Utilizadas

- **Python 3**
- **Jupyter Notebook**
- **NumPy**
- **Matplotlib**
- **Scikit-learn**
- **Pillow** (para leitura de imagens no exemplo das faces)

## 📁 Estrutura Esperada

Certifique-se de que os dados estejam organizados da seguinte forma:

```
Projeto/
├── EP1_PCA_Eigenfaces.ipynb
├── README.md
├── DadosYaleFaces/
│   └── Faces3/
│       ├── s1.jpg
│       ├── s2.jpg
│       └── ...
├── images/

```

## 🧪 Requisitos

Para executar o notebook:

```bash
pip install numpy matplotlib scikit-learn Pillow
```

## 📊 Resultados

- O notebook permite testar diferentes quantidades de componentes principais.
- Gera gráficos mostrando a **porcentagem da variância explicada**.
- Exibe a **taxa de acerto** do reconhecimento de dígitos conforme a dimensão reduzida.

## 👨‍🎓 Autor

**Matheus Soares dos Santos de Freitas**  
Matrícula: 2024080043
