# Projeto de Classificação com Árvore de Decisão - Wine Dataset

Este projeto implementa uma pipeline de aprendizado de máquina utilizando a base de dados Wine do repositório UCI.

## Etapas do projeto

1. Carregamento da base de dados Wine (UCI)
2. Análise estatística descritiva
3. Transformações nos dados:
   - Normalização da variável 'alcohol'
   - Remoção de outliers da variável 'malic_acid' (acima do 90º percentil)
4. Divisão dos dados:
   - Treino (60%)
   - Validação (20%)
   - Teste (20%)
5. Treinamento de um modelo de Árvore de Decisão
6. Avaliação do modelo (acurácia e matriz de confusão)
7. Visualização da árvore de decisão
8. Predição da classe para uma amostra do conjunto de teste

## Como executar

1. Clone este repositório ou baixe os arquivos:
```bash
git clone <URL_DO_REPOSITORIO>
cd wine_decision_tree_project
```

2. Instale as dependências necessárias:
```bash
pip install -r requirements.txt
```

Se preferir, instale manualmente os principais pacotes:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

3. Execute o notebook no Jupyter Notebook ou no VS Code.

## Vídeo de Apresentação

[Adicione aqui o link do vídeo de apresentação após gravar e publicar no YouTube]

](https://archive.ics.uci.edu/dataset/109/wine)](https://archive.ics.uci.edu/dataset/109/wine)
