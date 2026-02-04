# 📊 Análise de Churn em Telecomunicações

## 📌 Sobre o projeto

Este projeto tem como objetivo **analisar o churn (evasão de clientes)** em uma empresa de telecomunicações, identificando os principais fatores associados à saída de clientes e propondo **ações estratégicas para retenção**.

A análise foi conduzida a partir de dados contratuais, financeiros, comportamentais, demográficos e de serviços adicionais, utilizando **Python e bibliotecas de análise de dados**.

## 🎯 Objetivos

* Identificar **padrões de churn** nos dados
* Analisar a relação entre churn e:

  * tempo de contrato
  * tipo de contrato
  * cobrança mensal
  * método de pagamento
  * serviços adicionais
  * gênero
* Gerar **insights acionáveis** para reduzir a evasão de clientes

## 🧠 Principais insights

* O churn é **mais elevado nos primeiros meses de contrato**
* Contratos **month-to-month** apresentam maior evasão
* Clientes com **cobrança mensal mais alta** tendem a churnar mais
* Métodos de pagamento **manuais** estão associados a maior churn
* A **ausência de serviços adicionais**, especialmente suporte técnico e segurança online, aumenta significativamente o churn
* **Gênero não é um fator determinante** para a evasão

## 🛠️ Tecnologias e bibliotecas utilizadas

* Python 3
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📁 Estrutura do projeto

```
📦 churn-analysis
 ┣ 📂 data
 ┃ ┗ telecom_churn.csv
 ┣ 📂 notebooks
 ┃ ┗ churn_analysis.ipynb
 ┣ 📂 images
 ┃ ┗ graficos_churn.png
 ┣ 📄 README.md
```

## 📊 Análises realizadas

* Churn por tempo de contrato (tenure)
* Churn por tipo de contrato
* Churn por cobrança mensal (MonthlyCharges)
* Churn por método de pagamento
* Churn por serviços adicionais (comparação tem vs não tem)
* Churn por gênero

As análises foram apresentadas por meio de:

* gráficos de barras
* gráficos de barras agrupadas
* gráficos de densidade (KDE)
* boxplots e visualizações comparativas

## 🚀 Como executar o projeto

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/churn-analysis.git
```

2. Acesse a pasta do projeto:

```bash
cd churn-analysis
```

3. Instale as dependências:

```bash
pip install pandas matplotlib seaborn
```

4. Execute o notebook:

```bash
jupyter notebook notebooks/churn_analysis.ipynb
```

## 🔁 Possíveis ações de negócio propostas

* Implementação de **onboarding ativo** para novos clientes
* Incentivo à migração para **contratos de longo prazo**
* Redução de fricções no pagamento por meio de métodos automáticos
* Oferta de **bundles com serviços adicionais**
* Reforço do valor percebido em planos de maior custo

## 📌 Conclusão

A análise evidencia que o churn está fortemente associado a **fatores contratuais, financeiros e de valor percebido**, e não a características demográficas. Estratégias focadas na experiência inicial do cliente e no aumento do valor agregado têm alto potencial de reduzir a evasão.
