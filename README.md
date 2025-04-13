# EthosGPT: Mapping Human Value Diversity to Advance Sustainable Development Goals (SDGs)

[![GitHub Repo](https://img.shields.io/badge/GitHub-sunshineluyao%2FEthoGPT--DB-blue?logo=github)](https://github.com/sunshineluyao/EthoGPT-DB)
[![Colab Notebook](https://img.shields.io/badge/Open%20in-Google%20Colab-orange?logo=googlecolab)](https://colab.research.google.com/github/sunshineluyao/EthoGPT-DB/blob/main/ChatGPT/EthoGPT_ChatGPT_Comparatives.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made with GPT-4](https://img.shields.io/badge/Made%20with-GPT--4-purple?logo=openai)](https://openai.com/gpt-4)


---

## 🧭 Project Overview

**EthosGPT** is an open-source framework for benchmarking cultural alignment in large language models (LLMs). It maps GPT-generated responses against global human values using survey data and cultural indices across countries and regions. Inspired by the philosophical concept of *ēthos* — moral character rooted in cultural identity — the project investigates how LLMs reflect or diverge from cultural plurality.

This repository supports the paper:

> 📝 **"EthosGPT: Mapping Human Value Diversity to Advance Sustainable Development Goals (SDGs)"**  


---

## 📁 Repository Structure

- `ChatGPT/` — Main datasets, notebooks, and high-resolution figures  
  📄 See full details in [`ChatGPT/README.md`](https://github.com/sunshineluyao/EthoGPT-DB/blob/main/ChatGPT/README.md)

- `figs/` — Exported visualizations and plots

- `data/` — Cleaned cultural index files and regional metrics

- `LICENSE` — MIT License

---

## 🚀 Key Features

- Cultural index simulation using GPT-4 (e.g., Traditional vs. Secular)
- Comparative visualizations between AI and survey-based responses
- Region-level error metrics (MSE, MAE)
- Tools for fairness, cross-cultural validation, and model benchmarking

---

## 🔭 Roadmap & Future Research

This project lays the groundwork for ongoing exploration into culturally inclusive AI. Below are several future directions:

### 🧩 1. Expanding Cultural Indices

To better evaluate cultural alignment, future extensions will integrate datasets beyond the World Values Survey, including:

- **Hofstede’s Cultural Dimensions** for global cultural value scoring [@hofstede2011dimensionalizing]
- **ESS/EVS Cultural Distance Indices** for European regional comparisons [@kaasa2016dataset]
- **GLOBE Study** on leadership and societal culture [@house2004globe]
- **D-PLACE**: linking geography, ecology, and ethnography [@kirby2016dplace]
- **Ecology-Culture Dataset** for environment–culture correlation [@wormley2022ecology]

Incorporating these data sources will expand EthosGPT’s cultural breadth.

---

### 🧠 2. Evaluating Additional LLMs

Beyond GPT-4, we aim to benchmark cultural reasoning across diverse models:

- **GPT-4o** (OpenAI): Multimodal with long context [@lund2024gpt4o]  
- **Gemini 1.5 Pro** (Google): 1M-token context model [@gemini2024]  
- **Claude 3 Opus** (Anthropic): Ethical reasoning focus [@claude]  
- **GLM** (Zhipu AI): Open-source Chinese-led LLM [@GLM]  
- **DeepSeek V3**: Mixture-of-experts model with 671B parameters [@DeepSeek]  
- **Qwen2.5** (Alibaba): Instruction-tuned and multilingual [@Qwen]

Evaluating these models will illuminate how architecture and training data impact cultural representation.

---

### 🧬 3. Enhancing Underrepresented Perspectives

We will prioritize:

- **Digitizing endangered cultures** using techniques like 3D scanning [@ocon2021digitalising]
- **Diversifying training corpora** by filtering for cultural and socioeconomic inclusion [@pouget2024filterculturalsocioeconomicdiversity]
- **Prompt engineering** to foreground underrepresented voices [@nwatu2024upliftinglowerincomedatastrategies]
- **Collective critiques + self-voting** (CCSV) to improve demographic equity [@lahoti-etal-2023-improving]
- **CultureLLM-style fine-tuning** with semantic augmentation [@li2024culturellmincorporatingculturaldifferences]

These strategies will improve LLM fairness, accountability, and cultural adaptability.

---

## 🏆 Recognition

> 🥇 **1st Prize – AI Governance Award**  
> Awarded by [AI Safety Fundamentals](https://aisafetyfundamentals.com/projects/ethosgpt-charting-the-human-values-landscape-on-a-global-scale)  
> For the project:  
> **EthosGPT: Charting the Human Values Landscape on a Global Scale**

---

## 📜 License

This repository is released under the [MIT License](LICENSE).
