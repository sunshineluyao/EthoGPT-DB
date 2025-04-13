# EthoGPT-DB

[![GitHub Repo](https://img.shields.io/badge/GitHub-sunshineluyao%2FEthoGPT--DB-blue?logo=github)](https://github.com/sunshineluyao/EthoGPT-DB)
[![Colab Notebook](https://img.shields.io/badge/Open%20in-Google%20Colab-orange?logo=googlecolab)](https://colab.research.google.com/github/sunshineluyao/EthoGPT-DB/blob/main/ChatGPT/EthoGPT_ChatGPT_Comparatives.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made with GPT-4](https://img.shields.io/badge/Made%20with-GPT--4-purple?logo=openai)](https://openai.com/gpt-4)

---

## 🧭 Overview

**EthoGPT-DB** provides an empirical framework and analysis toolkit to examine how large language models (LLMs) like ChatGPT simulate global cultural values. It compares model-generated responses with real-world survey data across value dimensions such as:

- **Traditional vs. Secular Values**
- **Survival vs. Self-Expression**

The repository enables comparative studies, visualizations, and cultural bias detection in LLM behavior, helping researchers evaluate AI alignment with diverse human values.

---

## 📘 Notebooks

### `EthosGPT_ChatGPT.ipynb`  
> 🧠 **A complete open-access framework** to simulate representative cultural agents using GPT-4 across diverse indices.

**Key Modules:**
- Survey simulation: Uses GPT-4 to mimic national responses to global values survey questions
- Index construction: Computes cultural value indices from model responses
- Output: Structured, country-specific index scores and GPT-generated data

---

### [`EthosGPT_ChatGPT_Comparatives.ipynb`](https://github.com/sunshineluyao/EthoGPT-DB/blob/main/ChatGPT/EthoGPT_ChatGPT_Comparatives.ipynb)  
> 📊 **An advanced comparative visualization and analysis suite**

**What it does:**
- Raw and absolute difference maps between ChatGPT and human data
- Regional error analysis (MSE, MAE) by cultural cluster
- Lollipop and choropleth plots with ACM-style fonts
- High-resolution PNG exports for Overleaf/paper figures

---

## 📁 Datasets

- `ChatGPT_Comparatives.csv`  
  Contains raw and absolute differences in cultural indices per country between ChatGPT and survey data.

- `ChatGPT_Comparatives_Region.csv`  
  Provides aggregated regional error metrics (MSE, MAE) by cultural cluster.

---

## 🔧 Installation

### Requirements (`requirements.txt`)
```txt
openai
pandas
tqdm
matplotlib
adjustText
plotly
```

### Setup

```bash
git clone https://github.com/sunshineluyao/EthoGPT-DB.git
cd EthoGPT-DB

python -m venv venv
source venv/bin/activate       # or venv\Scripts\activate on Windows

pip install -r requirements.txt
```

---

## 🚀 Usage

### 💻 Google Colab (Recommended)

👉 [Run in Colab](https://colab.research.google.com/github/sunshineluyao/EthoGPT-DB/blob/main/ChatGPT/EthoGPT_ChatGPT_Comparatives.ipynb)

Steps:
1. Mount Google Drive
2. Install required packages
3. Add your OpenAI API Key
4. Execute full analysis & export results

### 🖥️ Run Locally via Jupyter

```bash
jupyter notebook ChatGPT/EthoGPT_ChatGPT_Comparatives.ipynb
```

---

## 📊 Outputs

- 🌍 Global cultural index maps (ChatGPT vs. Survey)
- 🧭 Regional alignment diagnostics
- 📉 MSE & MAE charts by cultural cluster
- 🖼️ PNG exports of difference maps (raw and absolute)
- 📁 Country- and region-level CSVs for further analysis

---

## 🏆 Recognition

> 🥇 **1st Prize – AI Governance Award**  
> Presented by [AI Safety Fundamentals](https://aisafetyfundamentals.com/projects/ethosgpt-charting-the-human-values-landscape-on-a-global-scale/)  
> for the project:  
> **EthosGPT: Charting the Human Values Landscape on a Global Scale**

---

## 🤝 Contributing

We welcome your contributions!

- 💬 Open an issue for questions, feature requests, or bug reports
- 📬 Submit a pull request to add new notebooks, datasets, or visualizations

---

## 📜 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.

---
