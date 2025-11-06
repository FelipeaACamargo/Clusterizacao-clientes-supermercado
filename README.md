# Clusterização de Clientes de Supermercado

Este projeto demonstra, de forma didática e passo a passo, como segmentar clientes de um shopping de supermercado utilizando clustering em Python, com foco em análise exploratória, K-Means e agrupamento hierárquico.

Utilizamos o banco de dados “Mall Customers” baixado do Kaggle ([link aqui](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)), que contém informações dos clientes como: gênero, idade, renda anual e pontuação de gastos.

## Etapas do projeto

1. **Carregamento e análise dos dados:**
   - Estatísticas descritivas para identificar padrões e possíveis outliers.
   - Visualizações como histogramas, boxplots e gráficos de dispersão para explorar relações entre variáveis.

2. **Pré-processamento:**
   - Normalização das variáveis relevantes para clusterização: renda anual e pontuação de gastos.

3. **Clusterização com K-Means:**
   - Determinação do número ideal de clusters via método do cotovelo.
   - Aplicação do algoritmo K-Means.
   - Cálculo do Silhouette Score para avaliar a qualidade dos agrupamentos.
   - Visualização dos resultados.

4. **Clusterização Hierárquica:**
   - Execução de agrupamento hierárquico (linkage de Ward).
   - Construção e análise do dendrograma.

## Para quem é

Ideal para iniciantes, estudantes e profissionais que desejam aprender, na prática, como aplicar e interpretar técnicas de segmentação de clientes com Python.

**Referência do dataset:** Kaggle — [Mall Customers Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
