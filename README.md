# 📉 Previsão de Evasão de Clientes — Telecom X

Este projeto de Machine Learning tem como objetivo identificar quais clientes de uma empresa fictícia de telecomunicações, chamada **Telecom X**, estão propensos a cancelar seus contratos. Todo o desenvolvimento foi realizado no **Google Colab**, utilizando bibliotecas populares como `pandas`, `scikit-learn`, `matplotlib` e `seaborn`.

## 📂 Estrutura do Projeto

- `notebooks/`: Contém os notebooks Colab com a análise exploratória, modelagem e avaliação dos modelos.
- `data/`: Base de dados fictícia utilizada no projeto (simulada).
- `models/`: Treinamento dos modelos preditivos: Regressão Logística, Árvore de Decisão, Random Forest, SVM, e KNN.

## 🚀 Tecnologias Utilizadas

- Python 3
- Google Colab
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

## 📊 Metodologia

1. **Análise exploratória** dos dados e correlação entre variáveis.
2. **Visualização** de relações entre atributos como tempo de contrato e gasto mensal vs. churn.
3. **Divisão da base** entre treino (80%) e teste (20%).
4. **Treinamento** dos modelos:
   - Regressão Logística
   - Árvore de Decisão
   - Random Forest
   - KNN
   - SVM
5. **Avaliação** com métricas como acurácia, precisão, recall, F1-score e matriz de confusão.
6. **Interpretação dos fatores mais relevantes** para a evasão com base na importância das variáveis.

## 📌 Principais Fatores que Influenciam o Churn

- Valor total e mensal de cobranças
- Tempo de contrato (`tenure`)
- Tipo de pagamento (`electronic check`)
- Uso de serviços como fibra óptica, segurança online e suporte técnico

## 🛡️ Estratégias de Retenção Propostas

- Personalização de planos para clientes com altas tarifas
- Programas de fidelização progressiva
- Migração de métodos de pagamento para opções mais práticas
- Melhoria nos serviços digitais e suporte técnico
- Ações proativas com modelos preditivos

## 📈 Resultados

O modelo que apresentou melhor desempenho foi o **Random Forest**, equilibrando boa capacidade preditiva e interpretabilidade. Outros modelos como Regressão Logística e Árvore de Decisão também forneceram insights valiosos para o entendimento do comportamento dos clientes.

## 🧠 Autoria

Projeto desenvolvido por **Marcos Papa**, utilizando recursos 100% em ambiente colaborativo no Google Colab.

---
