# datasets-for-colab

# 📊 Datasets for Colab

This repository contains public datasets used for data analysis and machine learning experiments.

The main goal is to provide **easy and direct access** to datasets using Google Colab, without requiring downloads or authentication.

---

## 🚀 How to use

You can load any dataset directly into your Colab notebook using `pandas`:

```python id="p9x2k1"
import pandas as pd

url = "https://raw.githubusercontent.com/<your-username>/<repo-name>/main/<file>.csv"
df = pd.read_csv(url)

df.head()
```

---

## 📁 Available datasets

* Titanic

  * `titanic.csv`
  * Source: Kaggle

---

## 📌 Notes

* All datasets in this repository are publicly available.
* Files are kept as simple as possible (CSV format preferred).
* This repository is intended for **educational purposes**.

---

## ⚠️ Disclaimer

Datasets may contain missing values or require preprocessing.

---

## 🇧🇷 Versão em português

Este repositório contém datasets públicos utilizados em análises de dados e experimentos de machine learning.

O objetivo principal é permitir **acesso fácil e direto** aos dados usando o Google Colab, sem necessidade de download ou autenticação.

### 🚀 Como usar

```python id="2r7kqs"
import pandas as pd

url = "https://raw.githubusercontent.com/<seu-usuario>/<repo>/main/<arquivo>.csv"
df = pd.read_csv(url)

df.head()
```

### 📁 Datasets disponíveis

* Titanic

  * `titanic.csv`
  * Fonte: Kaggle

### 📌 Observações

* Todos os datasets são públicos.
* Os arquivos estão preferencialmente em formato CSV.
* Este repositório é voltado para fins educacionais.

---

## 👤 Author

Maintained by Rickemberg Araújo Silva (@rick-as08)
