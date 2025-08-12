# Grupos de Interesse para Marketing

Este projeto utiliza o algoritmo de clusterização K-means para identificar e prever agrupamentos de interesses de usuários, com o objetivo de direcionar campanhas de marketing de forma mais eficaz.

## Descrição

A aplicação permite segmentar o público em grupos de interesse, possibilitando a criação de campanhas personalizadas e mais assertivas, com base nos padrões de comportamento e preferências de cada grupo.

## Como usar

1. **Clone o repositório e acesse a pasta do projeto.**
2. **Instale as dependências:**
   ```sh
   pip install -r requirements.txt

##Execute a aplicação:
  streamlit run App.py
  
## Na interface web, faça o upload de um arquivo CSV com os dados dos usuários.

## Baixe o resultado com os grupos previstos.

## Estrutura dos Grupos
Grupo 0: Público jovem com forte interesse em moda, música e aparência.
Grupo 1: Associado a esportes (futebol americano, basquete) e atividades culturais como banda e rock.
Grupo 2: Perfil equilibrado, com interesses em música, dança e moda.

## Arquivos
App.py: Código principal da aplicação Streamlit.
encoder.pkl, scaler.pkl, kmeans.pkl: Modelos treinados para pré-processamento e clusterização.
requirements.txt: Dependências do projeto.
.devcontainer/: Configuração para desenvolvimento em containers.

##Observações
Certifique-se de que os arquivos .pkl estejam presentes na raiz do projeto para o correto funcionamento.
O arquivo CSV de entrada deve conter uma coluna sexo e demais colunas compatíveis com o modelo.
Desenvolvido para fins de demonstração de segmentação de marketing com Machine Learning.
