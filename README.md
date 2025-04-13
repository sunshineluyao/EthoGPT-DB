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

Beyond GPT-4, we aim to benchmark cultural reasoning across a diverse range of frontier models:

- ![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4o-7348bd?logo=openai&logoColor=white&style=flat-square)  
  **GPT-4o** – Multimodal with long context and faster response times [@lund2024gpt4o]

- ![Google](https://img.shields.io/badge/Google-Gemini%201.5%20Pro-4285F4?logo=google&logoColor=white&style=flat-square)  
  **Gemini 1.5 Pro** – 1M-token context window and strong reasoning abilities [@gemini2024]

- ![Anthropic](https://img.shields.io/badge/Anthropic-Claude%203%20Opus-121212?logo=anthropic&logoColor=white&style=flat-square)  
  **Claude 3 Opus** – Emphasizes safety, interpretability, and ethical alignment [@claude]

- ![Zhipu AI](https://img.shields.io/badge/Zhipu%20AI-GLM-blue?style=flat-square)  
  **GLM** – Chinese open-source model advancing transparency and inclusivity [@GLM]

- ![DeepSeek](https://img.shields.io/badge/DeepSeek-V3-222222?style=flat-square)  
  **DeepSeek V3** – Mixture-of-experts model with 671B parameters [@DeepSeek]

- ![Alibaba Cloud](https://img.shields.io/badge/Alibaba-Qwen2.5-FE9600?logo=alibabacloud&logoColor=white&style=flat-square)  
  **Qwen2.5** – Instruction-tuned, multilingual, and optimized for long-text generation [@Qwen]

Evaluating these models will illuminate how model architecture, training data, and geographic origin shape cultural alignment and value representation in AI systems.


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
