# Modelo de IA - Previsão de sucesso de filmes
 
# Objetivo

Este projeto foi desenvolvido com o objetivo de realizar a previsão de sucesso de novos filmes lançados no cinema. Através da aplicação de técnicas de Machine Learning, treinei uma IA para analisar padrões e características de uma ampla gama de filmes já lançados. Com isso, a IA realiza a previsão do potencial de sucesso dos novos filmes, baseado nos dados fornecidos sobre eles.

# Como funciona

Para começar, o código recebe uma base de dados com mais de 800 filmes contendo várias informações, como diretor, atores, descrição, gênero, entre outras. Após tratar os dados, apliquei o LabelEncoder para transformar as colunas de texto relevantes em colunas de números, como a coluna de diretor e de atores. Com isso, separei as informações em dados de treinos e dados de testes para treinar a IA. Com o treinamento concluído, pedi para o ChatGPT gerar dados de 3 filmes fictícios e transformá-los em um arquivo .csv semelhante ao arquivo original dos filmes, para assim, permitir a IA prever o sucesso desses novos filmes fictícios.

# Modelos usados

Para este projeto, usei 4 modelos:

- Regressão Logística, com aproximadamente 92% de acurácia
- k-NN (K-Nearest Neighbors), com aproximadamente 89% de acurácia
- SVM (Support Vector Machine), com aproximadamente 91% de acurácia
- Árvore de Decisão (Random Forest Classifier), com aproximadamente 99% de acurácia

# Resultados

De acordo com os modelos, os resultados para os 3 filmes fictícios são estes:

Nome do filme: Secrets of the Cosmos  
Previsão de Regressão Logistica para o filme: Filme NÃO vai ser um sucesso  
Previsão de k-NN para o filme: Filme NÃO vai ser um sucesso  
Previsão de SBM para o filme: Filme NÃO vai ser um sucesso  
Previsão de Árvore de Decisão para o filme: Filme NÃO vai ser um sucesso  
  

Nome do filme: The Enchanted Quest  
Previsão de Regressão Logistica para o filme: Filme vai ser um sucesso!  
Previsão de k-NN para o filme: Filme NÃO vai ser um sucesso  
Previsão de SBM para o filme: Filme NÃO vai ser um sucesso  
Previsão de Árvore de Decisão para o filme: Filme NÃO vai ser um sucesso  
  

Nome do filme: Rise of Legends  
Previsão de Regressão Logistica para o filme: Filme vai ser um sucesso!  
Previsão de k-NN para o filme: Filme NÃO vai ser um sucesso  
Previsão de SBM para o filme: Filme NÃO vai ser um sucesso  
Previsão de Árvore de Decisão para o filme: Filme vai ser um sucesso!  

# Detalhes

- **Arquivos necessários**: para rodar sem problemas, deixe os arquivos `movie_success_rate.csv` e `filme_ficticio.csv` na mesma pasta do código.
- **Ferramentas usadas**: usei pandas e scikit-learn para desenvolver o projeto. Se você não tem instalado, use o comando `pip install pandas scikit-learn` no seu terminal.
- **Acurácia**: vale lembrar que, mesmo com todo esse trabalho, a IA não é perfeita e pode errar nas previsões, esse é apenas um projeto para predições de diferentes modelos.
