# Análise Exploratória de Concessão de Crédito 📊

Este projeto faz parte do meu portfólio de Ciência de Dados e tem como objetivo identificar os principais fatores impulsionadores do limite de crédito concedido a clientes.

## 📌 Visão Geral do Projeto
A partir de uma base de dados de clientes, realizamos a limpeza e tratamento dos dados em Python (Pandas) e testamos hipóteses de negócio utilizando visualizações estáticas (Seaborn e Matplotlib).

---

## 🔍 Principais Insights Obtidos

1. **Renda vs. Limite:** Existe uma relação diretamente proporcional entre o salário do cliente e o limite de crédito liberado (analisado via *Scatter Plot*).
2. **Histórico de Inadimplência:** O histórico de restrição de crédito funciona como o principal fator penalizador. Mesmo clientes com salários elevados sofrem reduções drásticas no limite disponível caso tenham histórico de inadimplência.
3. **Garantia Patrimonial:** A posse de imóvel próprio atua como fator alavancador do limite de crédito (analisado via *Boxplot*), desde que o cliente seja adimplente.

---

## 🛠️ Tecnologias Utilizadas
* **Python** (Pandas, NumPy)
* **Seaborn & Matplotlib** (Visualização de Dados)
* **Jupyter Notebook / Google Colab**
