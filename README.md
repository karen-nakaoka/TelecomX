# 📊 Telecom X — Análise de Evasão de Clientes (Churn)

## 📌 Sobre o projeto

Este projeto tem como objetivo analisar os fatores associados à **evasão de clientes (churn)** na empresa fictícia **Telecom X**. A evasão ocorre quando clientes cancelam seus serviços, o que pode impactar diretamente a receita e o crescimento da empresa.

A análise foi realizada utilizando **Python e bibliotecas de análise de dados**, com foco na **exploração, tratamento e visualização dos dados**, buscando identificar padrões que possam explicar o comportamento de cancelamento dos clientes.

Os insights obtidos podem auxiliar equipes de **Data Science e negócios** na criação de modelos preditivos e estratégias de retenção de clientes.

---

# 🎯 Objetivos da análise

- Entender a **distribuição da evasão de clientes**
- Identificar **padrões associados ao cancelamento**
- Explorar o impacto de variáveis como:
  - Tipo de contrato
  - Forma de pagamento
  - Tempo de contrato
  - Gasto mensal
- Gerar **visualizações e insights** que ajudem a compreender o comportamento dos clientes

---

# 📂 Estrutura do projeto


<img width="271" height="198" alt="image" src="https://github.com/user-attachments/assets/3f755906-729f-429e-8074-1ee533f1d4df" />


- **TelecomX_BR.ipynb** → notebook com toda a análise de dados  
- **TelecomX_Data.json** → dataset utilizado no projeto  
- **README.md** → documentação do projeto  

---

# 🔧 Tecnologias utilizadas

- Python
- Pandas
- Matplotlib
- Google Colab

---

# 📊 Etapas da análise

## 1️⃣ Extração e tratamento dos dados

Os dados foram obtidos a partir de um **arquivo JSON disponibilizado por uma API**. Algumas colunas estavam estruturadas de forma **aninhada**, sendo necessário normalizá-las para transformar os atributos em colunas individuais no DataFrame.

Durante o processo de limpeza dos dados foram realizadas:

- Verificação de valores ausentes  
- Identificação de duplicatas  
- Análise de inconsistências nas categorias  
- Ajuste de tipos de dados  
- Criação de novas variáveis auxiliares  

Também foi criada uma coluna adicional de **gasto diário**, derivada do gasto mensal.

---

## 2️⃣ Análise exploratória dos dados (EDA)

A análise exploratória foi realizada para identificar padrões e relações entre as características dos clientes e a evasão.

### Distribuição geral da evasão

Foi analisada a proporção de clientes que cancelaram e os que permaneceram no serviço.

### Evasão por variáveis categóricas

Foram analisadas variáveis como:

- Tipo de contrato  
- Método de pagamento  
- Gênero  

Os resultados indicaram que **clientes com contratos mensais apresentam maior taxa de evasão**.

Também foi observado que clientes que utilizam **Electronic Check** apresentam maior proporção de cancelamento.

### Evasão por variáveis numéricas

Foram analisadas variáveis como:

- Tempo de contrato  
- Gasto mensal  
- Gasto total  

Os resultados indicam que clientes com **menor tempo de contrato apresentam maior probabilidade de evasão**.

Além disso, clientes com **maior gasto mensal tendem a cancelar com maior frequência**.

---

# 📈 Principais insights

A análise revelou alguns fatores importantes associados à evasão:

- Clientes com **contratos mensais apresentam maior risco de cancelamento**
- Clientes com **menor tempo de permanência na empresa apresentam maior evasão**
- O método de pagamento **Electronic Check** apresenta maior proporção de cancelamentos
- Clientes com **planos mais caros tendem a cancelar mais frequentemente**

---

# 💡 Recomendações

Com base nos resultados obtidos, algumas estratégias podem ajudar a reduzir a evasão:

- Incentivar clientes a migrarem para **contratos de maior duração**
- Desenvolver estratégias de retenção para **clientes recém-adquiridos**
- Avaliar melhorias na experiência de pagamento
- Oferecer benefícios ou programas de fidelização para clientes com maior tempo de contrato

---

# 🚀 Possíveis próximos passos

- Desenvolvimento de **modelos de machine learning para previsão de churn**
- Criação de **segmentações de clientes**
- Implementação de **dashboards interativos**
