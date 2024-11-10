# Roteiro de Agrupamento com K-Means

Este repositório contém um roteiro desenvolvido em Jupyter Notebook para agrupar dados não rotulados usando o algoritmo K-Means. O objetivo é identificar o número ideal de clusters com base nas características dos dados, buscando otimizar métricas de avaliação. O roteiro utiliza uma base de dados do Kaggle e foi desenvolvido para auxiliar no aprendizado e experimentação com algoritmos de clusterização não supervisionados.

## Estrutura do Projeto

- **[Equipe_02]_ROTEIRO_K_MEANS.ipynb**: Notebook principal com o código, visualizações e etapas de análise.
- **data/**: Diretório sugerido para armazenar os conjuntos de dados do Kaggle necessários para a execução do roteiro.

## Principais Recursos do Roteiro

- **Pré-processamento de Dados**: Limpeza e preparação dos dados para clusterização.
- **Escolha do Número de Clusters (K)**: Uso de métodos como o "Elbow Method" para determinar o número ideal de clusters.
- **Visualização de Resultados**: Gráficos de dispersão e de métricas para análise dos clusters gerados.
- **Otimização de Métricas**: Avaliação de diferentes métricas para medir a qualidade dos agrupamentos, como a inércia e o coeficiente de Silhouette.

## Como Usar

1. **Obtenha os dados**: Baixe os dados necessários do Kaggle e armazene-os no diretório `data/`.
2. **Execute o Notebook**: Abra o arquivo `.ipynb` em um ambiente Jupyter Notebook ou Google Colab e siga as instruções.
3. **Analise os Resultados**: Utilize as visualizações e métricas para interpretar os clusters formados e o número ideal de grupos.

## Requisitos

- Python 3.x
- Bibliotecas: `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`

Para instalar as bibliotecas necessárias, execute:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Resultado
[Clique aqui para assistir ao resultado do código](https://drive.google.com/file/d/14E9oSWY6skQAlY19bA-fVkMWqhGkWsj-/view?usp=sharing)


## Contribuição

Este roteiro foi desenvolvido pela Equipe_02 para fins educacionais e de pesquisa. Contribuições são bem-vindas para otimizar o código, explorar novas métricas de avaliação ou incluir novos conjuntos de dados.

---
