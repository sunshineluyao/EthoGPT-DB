# EthosGPT: Mapping Human Value Diversity to Advance Sustainable Development Goals (SDGs)


<p align="center">
  <img src="https://img.shields.io/badge/OpenAI-GPT--4-purple?logo=openai&logoColor=white&style=for-the-badge"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Colab-Launch-orange?logo=googlecolab&logoColor=white&style=for-the-badge" />
</p>

<div align="center">
  <img src="https://sdgs.un.org/sites/default/files/goals/E_SDG_Icons-10.jpg" alt="SDG 10: Reduced Inequalities" height="65"/>
  <img src="https://sdgs.un.org/sites/default/files/goals/E_SDG_Icons-11.jpg" alt="SDG 11.4: Cultural Heritage" height="65"/>
  <img src="https://sdgs.un.org/sites/default/files/goals/E_SDG_Icons-16.jpg" alt="SDG 16: Peace and Justice" height="65"/>
</div>

---

<div align="justify">

<h3>📄 Abstract</h3>

<p>
🌐 <strong>Large Language Models (LLMs)</strong> are reshaping global decision-making and societal systems through their ability to process vast and diverse datasets. However, their potential to homogenize human values—mirroring the risks of biodiversity loss in ecosystems—poses serious challenges to cultural diversity and ethical resilience.

🚀 This study introduces <strong>EthosGPT</strong>, an open-source framework designed to systematically <em>map and evaluate LLMs</em> against a globally representative spectrum of human values. 

📊 By integrating cross-cultural survey data, interactive prompt-based evaluations with measurable outputs, and comparative statistical analyses, EthosGPT quantifies the cultural adaptability of LLMs while identifying critical disparities between AI-generated value indices and those of human populations across 100+ countries.

🧩 Findings reveal that while LLMs demonstrate partial alignment with localized cultural norms, significant gaps persist—especially in underrepresented regions. To mitigate these issues, EthosGPT offers actionable strategies for building inclusive AI systems:
<ul>
  <li>📚 Diversifying training datasets</li>
  <li>🏛️ Digitally preserving endangered cultural heritage</li>
</ul>

🎯 These efforts support the following UN Sustainable Development Goals (SDGs):
<ul>
  <li>🔟 <strong>SDG 10:</strong> Reduced Inequalities</li>
  <li>🏛️ <strong>SDG 11.4:</strong> Cultural Heritage Preservation</li>
  <li>⚖️ <strong>SDG 16:</strong> Peace, Justice & Strong Institutions</li>
</ul>

🌱 <strong>EthosGPT</strong> positions value diversity as a cornerstone of societal innovation and sustainable prosperity. Through open-source tools and interdisciplinary collaboration, it advocates for AI systems that harmonize <em>technical rigor</em> with <em>ethical pluralism</em>. By bridging cultural gaps in machine learning, this work advances global AI governance frameworks toward a more inclusive and equitable future.

</p>

</div>


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

EthosGPT lays the foundation for more inclusive, culturally aware AI. The roadmap below outlines key future directions to scale its impact and global relevance.

---

### 🌳 Overview Tree

```plaintext
EthosGPT Roadmap
├── 🧩 Expand Cultural Indices
│   ├── Hofstede Dimensions
│   ├── ESS/EVS Distance Indices
│   ├── GLOBE Leadership Study
│   ├── D-PLACE (Ethnography & Ecology)
│   └── Ecology-Culture Dataset
├── 🧠 Evaluate Diverse LLMs
│   ├── GPT-4o (OpenAI)
│   ├── Gemini 1.5 Pro (Google)
│   ├── Claude 3 (Anthropic)
│   ├── GLM (Zhipu AI)
│   ├── DeepSeek V3
│   └── Qwen2.5 (Alibaba)
└── 🧬 Enhance Underrepresented Voices
    ├── 3D Cultural Digitization
    ├── Inclusive Training Filters
    ├── Socioeconomic Prompting
    ├── CCSV Self-Assessment
    └── CultureLLM Fine-Tuning
```

---

### 🧩 1. Expanding Cultural Indices

| Dataset                  | Focus Area                         | Reference                              |
|--------------------------|-------------------------------------|-----------------------------------------|
| Hofstede Dimensions      | Cultural value scoring across 6 axes| [@hofstede2011dimensionalizing]         |
| ESS/EVS Distance Indices | Regional value differences in Europe| [@kaasa2016dataset]                     |
| GLOBE Study              | Leadership & society-wide values    | [@house2004globe]                      |
| D-PLACE                  | Culture–language–environment links  | [@kirby2016dplace]                      |
| Ecology-Culture Dataset  | Environmental effects on culture    | [@wormley2022ecology]                   |

Expanding EthosGPT's coverage with these datasets will strengthen its analytical power and global representation.

---

### 🧠 2. Benchmarking Frontier LLMs

We aim to evaluate the cultural alignment of the most advanced LLMs available today:

| Model          | Developer      | Key Features                                 | Badge |
|----------------|----------------|----------------------------------------------|--------|
| GPT-4o         | OpenAI         | 🔁 Multimodal, long context, fast response    | ![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4o-7348bd?logo=openai&logoColor=white&style=flat-square) |
| Gemini 1.5 Pro | Google DeepMind| 📚 1M-token context, strong reasoning         | ![Google](https://img.shields.io/badge/Google-Gemini%201.5%20Pro-4285F4?logo=google&logoColor=white&style=flat-square) |
| Claude 3 Opus  | Anthropic      | 🧠 Ethical alignment & interpretability       | ![Anthropic](https://img.shields.io/badge/Anthropic-Claude%203%20Opus-121212?logo=anthropic&logoColor=white&style=flat-square) |
| GLM            | Zhipu AI       | 🌏 Open-source, community-driven              | ![Zhipu AI](https://img.shields.io/badge/Zhipu%20AI-GLM-blue?style=flat-square) |
| DeepSeek V3    | DeepSeek       | 🤖 MoE architecture, 671B parameters          | ![DeepSeek](https://img.shields.io/badge/DeepSeek-V3-222222?style=flat-square) |
| Qwen2.5        | Alibaba         | 🧾 Instruction-tuned, multilingual            | ![Alibaba](https://img.shields.io/badge/Alibaba-Qwen2.5-FE9600?logo=alibabacloud&logoColor=white&style=flat-square) |

This benchmark will reveal how architecture and data origin influence cultural representation.

---

### 🧬 3. Enhancing Representation of Underrepresented Perspectives

| Strategy                      | Description                                                                  | Reference                              |
|-------------------------------|------------------------------------------------------------------------------|------------------------------------------|
| 🏛️ Cultural Digitization      | 3D scanning and virtual records to preserve heritage                        | [@ocon2021digitalising]                 |
| 🌍 Inclusive Data Filtering    | Cultural/socioeconomic-aware dataset curation                               | [@pouget2024filterculturalsocioeconomicdiversity] |
| 🧭 Prompt Personalization      | Injecting regional & class-aware variables into prompts                     | [@nwatu2024upliftinglowerincomedatastrategies] |
| 🗳️ CCSV Self-Voting           | Use model critiques & voting for demographic fairness                      | [@lahoti-etal-2023-improving]           |
| 🧠 CultureLLM Fine-Tuning      | Semantic augmentation & culture-specific alignment                          | [@li2024culturellmincorporatingculturaldifferences] |

These innovations aim to improve the fairness, inclusivity, and ethical sensitivity of LLM outputs.

---

✨ *These roadmap pillars ensure that EthosGPT evolves as a globally inclusive, interdisciplinary, and ethically grounded framework for cultural intelligence in AI.*

---

## 🏆 Recognition

> 🥇 **1st Prize – AI Governance Award**  
> Awarded by [AI Safety Fundamentals](https://aisafetyfundamentals.com/projects/ethosgpt-charting-the-human-values-landscape-on-a-global-scale)  
> For the project:  
> **EthosGPT: Charting the Human Values Landscape on a Global Scale**

---

## 📜 License

This repository is released under the [MIT License](LICENSE).
