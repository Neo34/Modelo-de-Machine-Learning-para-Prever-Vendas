# 📊 Previsão de Vendas de Sorvete com Machine Learning

## 📌 Objetivo do Projeto
O objetivo deste projeto é desenvolver um modelo de regressão preditiva para prever as vendas de sorvete com base na temperatura do dia. Para isso, utilizaremos Machine Learning, MLflow para gerenciamento do modelo e uma implementação na nuvem para previsões em tempo real.

## 🏗️ Estrutura do Repositório

📁 **inputs/** → Contém os dados de entrada usados para treinar e testar o modelo.  
📁 **notebooks/** → Jupyter Notebooks com a análise exploratória e desenvolvimento do modelo.  
📁 **src/** → Scripts Python para processamento de dados, treinamento e inferência.  
📁 **models/** → Modelos treinados e logs do MLflow.  
📁 **deployment/** → Scripts para disponibilizar o modelo via API.  
📄 **README.md** → Documentação detalhada do projeto.

## 🔧 Tecnologias Utilizadas
- **Python** (Pandas, Scikit-Learn, Matplotlib, Seaborn)
- **MLflow** (Gerenciamento de experimentos e modelos)
- **Flask/FastAPI** (Para criar a API de inferência)
- **Azure Cloud** (Para hospedar o modelo)
- **Docker** (Para containerização da aplicação)

## 📊 Análise Exploratória
Abaixo estão alguns insights obtidos durante a análise exploratória dos dados:
- As vendas de sorvete aumentam significativamente conforme a temperatura sobe.
- Existe uma correlação positiva forte entre temperatura e vendas.
- Algumas variações inesperadas podem ser explicadas por fatores externos, como promoções ou feriados.

### 📌 Gráfico: Relação entre Temperatura e Vendas
*(Inserir print do gráfico gerado no notebook)*

## 📈 Desenvolvimento do Modelo
1. **Coleta e limpeza dos dados**
2. **Análise exploratória**
3. **Divisão dos dados em treino e teste**
4. **Treinamento do modelo de regressão**
5. **Avaliação usando métricas como RMSE e R²**
6. **Registro do modelo no MLflow**

### 🏆 Melhor Modelo Obtido
*(Inserir prints das métricas do modelo e comparação entre diferentes abordagens)*

## 🚀 Implementação em Produção
Para permitir previsões em tempo real, criamos uma API usando **Flask/FastAPI** e implantamos na **Azure Cloud**.

### Como Testar a API Localmente
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/icecream-sales-prediction.git
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Rode a API:
   ```bash
   uvicorn src.api:app --reload
   ```
4. Envie uma requisição para prever as vendas:
   ```bash
   curl -X POST "http://127.0.0.1:8000/predict" -H "Content-Type: application/json" -d '{"temperatura": 30}'
   ```

## 📌 Conclusão e Possíveis Melhorias
- O modelo conseguiu prever vendas com boa precisão, mas há espaço para melhorias.
- Poderíamos incluir mais variáveis, como dia da semana, feriados e fatores sazonais.
- Implementar um dashboard interativo para facilitar a visualização das previsões.

## 📜 Licença
Este projeto está sob a MIT License. Sinta-se à vontade para usar e contribuir! 😊

# Modelo-de-Machine-Learning-para-Prever-Vendas
