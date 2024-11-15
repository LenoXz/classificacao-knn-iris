# Classificação de Flores com KNN

Este projeto classifica tipos de flores usando o algoritmo K-Nearest Neighbors (KNN) no dataset 'iris'. Utiliza-se os métodos Cross Validation e Holdout para avaliar o desempenho do modelo.

## Descrição

O dataset 'iris' é composto por três espécies de flores: Setosa, Versicolour e Virginica. O objetivo é aplicar o KNN para distinguir entre essas espécies utilizando duas abordagens de validação:

- **Cross Validation**: Validação cruzada para generalização do modelo.
- **Holdout**: Divisão simples em conjuntos de treino e teste para avaliação direta.

## Bibliotecas Necessárias

As seguintes bibliotecas Python são utilizadas:

- `scikit-learn`
- `pandas`
- `plotly`
- `seaborn`
- `numpy`

## Guia de Instalação

1. Clone o repositório:
```bash
-  git clone https://github.com/LenoXz/classificacao-knn-iris.git
- cd classificacao-knn-iris
```
2. Instale as dependências:
```bash
- pip install -r requirements.txt
```

3.Execução do Projeto:
```bash
No diretório do projeto, execute:
- python main.ipynb
```
## O script irá:

- Carregar o dataset.
- Implementar e avaliar o KNN utilizando Cross Validation e Holdout.
- Gerar e exibir matrizes de confusão.
## Resultados
O projeto gera visualizações gráficas da matriz de confusão para as duas abordagens:

Exemplos de Matriz de Confusão
- **Cross Validation**: Matriz de Confusão Cross Validation

- **Holdout**: Matriz de Confusão Holdout

## Estrutura do Projeto
- **data/**: Diretório para armazenar os datasets
- **main.ipynb**: Implementação principal do projeto.
- **resultados/**: Diretório para armazenar os gráficos gerados.
