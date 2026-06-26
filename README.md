# 📊 Análise de Salários na Área de Tecnologia

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte da disciplina de Novas Tecnologias da Universidade Católica de Brasília (UCB) e tem como objetivo analisar salários de profissionais da área de tecnologia utilizando técnicas de Análise Exploratória de Dados (EDA) e Machine Learning.

Através de uma base de dados contendo informações de milhares de profissionais do setor, foram realizadas análises estatísticas, visualizações gráficas e a construção de modelos preditivos para estimar salários com base em diferentes características profissionais.

---

## 🎯 Objetivos

* Realizar a limpeza e o tratamento dos dados;
* Explorar estatisticamente a base de dados;
* Identificar os fatores que mais influenciam os salários;
* Criar visualizações para facilitar a interpretação dos dados;
* Desenvolver modelos de Machine Learning para previsão salarial;
* Comparar o desempenho dos modelos desenvolvidos.

---

## 📁 Base de Dados

### Dataset Utilizado

**Data Science Salaries 2024**

A base contém informações de profissionais da área de tecnologia entre os anos de 2020 e 2024.

### Principais Variáveis

* `job_title` – Cargo do profissional
* `experience_level` – Nível de experiência
* `employment_type` – Tipo de contratação
* `work_models` – Modalidade de trabalho
* `employee_residence` – País de residência
* `company_size` – Porte da empresa
* `salary_in_usd` – Salário anual em dólares

---

## 🛠️ Tecnologias Utilizadas

* Python 3.x
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## 📂 Estrutura do Projeto

```text
AT5_Salarios_TI/

├── data_science_salaries.csv
├── AT5_Salarios_TI_Real.ipynb
├── imagens/
│   ├── distribuicao_salarios.png
│   ├── salarios_experiencia.png
│   ├── salarios_cargos.png
│   ├── salarios_paises.png
│   └── correlacao.png
│
├── README.md
```

---

## 📊 Análise Exploratória dos Dados

Durante o desenvolvimento do projeto foram realizadas:

### Estatísticas Descritivas

* Média salarial
* Mediana
* Valores mínimos e máximos
* Desvio padrão

### Verificação dos Dados

* Identificação de valores nulos
* Verificação dos tipos de dados
* Distribuição das variáveis

### Visualizações

* Distribuição dos salários
* Salários por nível de experiência
* Salários por cargo
* Salários por país
* Modalidade de trabalho x salário
* Evolução salarial ao longo dos anos

---

## 🤖 Modelos de Machine Learning

Foram avaliados os seguintes algoritmos:

### Regressão Linear

Modelo utilizado como referência inicial para comparação de desempenho.

### Random Forest Regressor

Modelo baseado em árvores de decisão que apresentou excelente capacidade preditiva.

### Gradient Boosting Regressor

Modelo avançado utilizado para melhorar a precisão das previsões.

---

## 📈 Métricas de Avaliação

Os modelos foram avaliados utilizando:

* **MAE (Mean Absolute Error)**
* **RMSE (Root Mean Squared Error)**
* **R² Score (Coeficiente de Determinação)**

---

## 🏆 Melhor Modelo

O algoritmo **Random Forest Regressor** apresentou os melhores resultados para previsão salarial, demonstrando maior precisão e menor taxa de erro quando comparado aos demais modelos testados.

---

## 🔍 Principais Resultados

* Profissionais com maior experiência possuem salários significativamente mais altos.
* Cargos relacionados à Inteligência Artificial e Machine Learning apresentam as maiores remunerações.
* O trabalho remoto está associado a salários médios mais elevados.
* Os Estados Unidos concentram os maiores salários da base analisada.
* Os salários apresentaram crescimento constante entre 2020 e 2024.

---

## ▶️ Como Executar o Projeto

### 1. Clonar o Repositório

```bash
git clone https://github.com/SEU-USUARIO/AT5_Salarios_TI.git
```

### 2. Acessar a Pasta

```bash
cd AT5_Salarios_TI
```

### 3. Instalar as Dependências

```bash
pip install -r requirements.txt
```

### 4. Executar o Notebook

```bash
jupyter notebook
```

Abra o arquivo:

```text
AT5_Salarios_TI_Real.ipynb
```

---

## 👨‍💻 Integrantes

| Nome         | Responsabilidade               |
| ------------ | ------------------------------ |
| AILTON DOS SANTOS DA SILVA | Análise Exploratória dos Dados |
| ANTONIO VINÍCIUS ALVINO SILVA  | Modelagem e Machine Learning   |

---

## 🎓 Disciplina

Novas tecnologias

**Universidade Católica de Brasília (UCB)**

---

## 🔗 Repositório


```text
https://www.kaggle.com/datasets/sazidthe1/data-science-salaries?resource=download
```

---

## 📄 Licença

Este projeto foi desenvolvido exclusivamente para fins acadêmicos e educacionais.
