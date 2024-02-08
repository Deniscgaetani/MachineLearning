# Projeto de Previsão de Modelos de Machine Learning

Olá! Este é o projeto de previsão de modelos de machine learning desenvolvido por mim, Denis Gaetani. Neste projeto, criei um modelo de previsão utilizando Azure Machine Learning e configurei seus pontos de extremidade para facilitar o acesso e utilização do modelo.

## Passo a Passo

### 1. Configuração do Ambiente
- Configurei o ambiente de desenvolvimento utilizando Azure Machine Learning no portal do Azure.
- Instalei as dependências necessárias para o projeto, incluindo as bibliotecas de machine learning.

### 2. Coleta e Pré-processamento dos Dados
- Utilizei um conjunto de dados históricos de vendas para prever as vendas futuras.
- Realizei a limpeza e pré-processamento dos dados, tratando valores ausentes e outliers.
- Dividi os dados em conjuntos de treinamento e teste.

### 3. Escolha do Algoritmo e Treinamento do Modelo
- Escolhi utilizar o algoritmo de regressão linear para este problema de previsão de vendas.
- Treinei o modelo utilizando os dados de treinamento e ajustei os hiperparâmetros usando o Azure Automated Machine Learning.
- Avaliei o desempenho do modelo utilizando métricas como o erro quadrático médio (MSE) e o coeficiente de determinação (R²).

### 4. Configuração dos Pontos de Extremidade (Endpoints)
- Configurei os pontos de extremidade do modelo utilizando os serviços de Azure AI Services.
- Forneço acesso aos endpoints através de uma API RESTful, permitindo que os usuários façam previsões de vendas enviando dados de entrada.

## Arquivos no Repositório

- `README.md`: Descreve o projeto e fornece instruções sobre o processo de criação do modelo e configuração dos pontos de extremidade.
- `endpoints.json`: Arquivo JSON contendo os detalhes dos pontos de extremidade configurados.

## Próximos Passos
- Pretendo expandir este projeto adicionando mais funcionalidades, como suporte a diferentes algoritmos de machine learning e aprimorando a interface da API.

---

### endpoints.json

```json
{
  "input_data": {
    "data": [
       {
         "day": 1,
         "mnth": 1,   
         "year": 2022,
         "season": 2,
         "holiday": 0,
         "weekday": 1,
         "workingday": 1,
         "weathersit": 2, 
         "temp": 0.3, 
         "atemp": 0.3,
         "hum": 0.3,
         "windspeed": 0.3 
       }
     ]
  }
}
```
```resultado.json
[
  361.95238671338427
]
```
