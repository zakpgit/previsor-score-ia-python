<h1 align="center">🧠 Inteligência Artificial: Previsor de Score de Crédito</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

## 📝 Sobre o Projeto
Este projeto aplica técnicas de **Machine Learning** para resolver um problema real do setor bancário: a classificação automática do Score de Crédito de clientes. 

O objetivo é analisar o histórico financeiro e comportamental de uma base de dados de clientes e treinar uma Inteligência Artificial capaz de prever se o score de um novo cliente será **Ruim (Poor), Padrão (Standard) ou Bom (Good)**, automatizando a esteira de análise de crédito.

## ⚙️ Arquitetura e Pipeline de Dados
O projeto foi estruturado seguindo as melhores práticas de Ciência de Dados:

1. **Pré-processamento e Encoding:** Utilização do `LabelEncoder` para transformar variáveis categóricas (como profissão e comportamento de pagamento) em variáveis numéricas compreensíveis pelos algoritmos.
2. **Divisão de Dados:** Separação da base de treino e teste utilizando `train_test_split` para garantir a validação isenta do modelo.
3. **Competição de Algoritmos:** Treinamento simultâneo de dois modelos clássicos de classificação para determinar a melhor performance:
   * **Random Forest Classifier** (Árvore de Decisão)
   * **K-Nearest Neighbors** (KNN)

## 🏆 Resultados e Desempenho
Após o treinamento e teste com dados não vistos pela IA, avaliamos a acurácia (precisão) dos modelos:

* **Random Forest:** Mais de 80% de precisão 🥇
* **Modelo KNN:** ~73% de precisão

Com base nos resultados, o modelo **Random Forest** foi eleito como o algoritmo principal do projeto. Na última etapa do notebook, simulamos a entrada de novos clientes no banco, e o modelo classificou instantaneamente o score de cada um com sucesso.

## 🛠️ Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/zakpgit/previsor-score-ia-python.git
   ```
2. Instale as dependências:
   ```bash
   pip install pandas scikit-learn nbformat
   ```
3. Certifique-se de que os arquivos `clientes.csv` e `novos_clientes.csv` estejam na raiz do projeto.
4. Execute o arquivo Jupyter Notebook (`.ipynb`) em sua IDE.

## 👨‍💻 Autor
[Isaac Celestino Penco Maria](https://github.com/zakpgit) - Desenvolvedor Python

---

<h1 align="center">🧠 Artificial Intelligence: Credit Score Predictor</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

## 📝 About the Project
This project applies **Machine Learning** techniques to solve a real-world banking problem: the automatic classification of customer Credit Scores.

The goal is to analyze the financial and behavioral history of a customer database and train an Artificial Intelligence capable of predicting whether a new customer's score will be **Poor, Standard, or Good**, thereby automating the credit analysis pipeline.

## ⚙️ Architecture and Data Pipeline
The project was structured following Data Science best practices:

1. **Pre-processing and Encoding:** Utilizing `LabelEncoder` to transform categorical variables (such as profession and payment behavior) into numerical variables that algorithms can understand.
2. **Data Splitting:** Separating the training and testing sets using `train_test_split` to ensure unbiased model validation.
3. **Algorithm Competition:** Simultaneous training of two classic classification models to determine the best performance:
   * **Random Forest Classifier**
   * **K-Nearest Neighbors** (KNN)

## 🏆 Results and Performance
After training and testing with unseen data, we evaluated the accuracy of the models:

* **Random Forest:** Over 80% accuracy 🥇
* **KNN Model:** ~73% accuracy

Based on these results, the **Random Forest** model was chosen as the main algorithm for the project. In the final step of the notebook, we simulated the entry of new customers into the bank, and the model successfully classified the credit score of each one instantly.

## 🛠️ How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/zakpgit/previsor-score-ia-python.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas scikit-learn nbformat
   ```
3. Ensure the files `clientes.csv` and `novos_clientes.csv` are in the project's root folder.
4. Execute the Jupyter Notebook file (`.ipynb`) in your IDE.

## 👨‍💻 Author
[Isaac Celestino Penco Maria](https://github.com/zakpgit) - Python Developer
