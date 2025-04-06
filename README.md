# Segmentação RFV (Recência, Frequência e Valor)

Este projeto tem como objetivo aplicar a técnica de **Segmentação RFV (Recência, Frequência e Valor)** para análise e categorização de clientes com base em seu comportamento de compra. Essa segmentação é muito utilizada em estratégias de marketing e CRM para identificar grupos de clientes com características semelhantes e aplicar ações específicas para cada grupo.

## RFV (Recência, Frequência e Valor)

É uma técnica de segmentação de clientes que
analisa o comportamento do cliente com base em
três componentes: recência, frequência e valor.

## 📊 O que é RFV?

- **Recência (R):** Tempo desde a última compra do cliente.
- **Frequência (F):** Número de compras realizadas pelo cliente em um período.
- **Valor (V):** Quantia total gasta pelo cliente.

## 🧠 Objetivo

Através do RFV, conseguimos agrupar os clientes em segmentos (por exemplo, clientes fiéis, clientes inativos, etc.) e criar estratégias de retenção, fidelização e reativação.

## 🛠️ Tecnologias utilizadas

- Jupyter Notebook
- Python3
- Bibliotecas:
- ``Pandas``
- ``NumPy``
- ``Streamlit``
- ``Datetime``
- ``Pil``
- ``io``

## 📂 Estrutura do Projeto

📁 RFV-Segmentacao/ 
* ├── dados/ │ └── base_clientes.csv 
* ├── notebooks/ │ └── rfv_segmentacao.ipynb 
* ├── imagens/ │ └── segmentos.png └── README.md

## ⚙️ Como usar

1. Clone o repositório:
```bash
git clone https://github.com/fabiooliveira95/RFV-Segmentacao.git
```
2.Instale os requisitos (se necessário):
```bash
pip install -r requirements.txt
```
3.Execute o notebook:
```bash
jupyter notebook notebooks/rfv_segmentacao.ipynb
```
📌 Resultados Esperados

  * Cálculo das métricas RFV por cliente.
  * Criação de clusters utilizando algoritmos como K-Means.
  * Visualização dos segmentos com gráficos.
  * Interpretação de perfis de clientes com base em RFV.

📬 Contato

  Fábio Oliveira
  🔗 [LinkedIn](https://www.linkedin.com/in/fabio-oliveira-araujo-cientista/)
  📧 fabiooliveira0067@gmail.com

📄 Licença

* ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

