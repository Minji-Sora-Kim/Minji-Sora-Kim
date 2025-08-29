<!-- =========================================
   PROFILE README — Fancy Edition
   TODO:
   3) Keep or tweak color presets below
========================================= -->

<!-- Header (pick ONE of the 3 presets) -->
<!-- Gradient A: Purple → Blue -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&height=160&color=0:6a11cb,100:2575fc&text=Hi%20there%20👋&fontColor=ffffff&fontSize=38&fontAlign=50&fontAlignY=32&animation=twinkling&reversal=true" />
  <img alt="header" src="https://capsule-render.vercel.app/api?type=waving&height=160&color=0:6a11cb,100:2575fc&text=Hi%20there%20👋&fontColor=ffffff&fontSize=38&fontAlign=50&fontAlignY=32&animation=twinkling"/>
</picture>

<!-- Gradient B: Neon Mint → Blue (uncomment to use)
<picture>
  <img alt="header" src="https://capsule-render.vercel.app/api?type=waving&height=160&color=0:00ffa3,100:00b3ff&text=Hi%20there%20👋&fontColor=0E1117&fontSize=38&fontAlign=50&fontAlignY=32&animation=twinkling"/>
</picture>
-->

<!-- Gradient C: Sunset (uncomment to use)
<picture>
  <img alt="header" src="https://capsule-render.vercel.app/api?type=waving&height=160&color=0:ff7a18,100:af002d&text=Hi%20there%20👋&fontColor=ffffff&fontSize=38&fontAlign=50&fontAlignY=32&animation=twinkling"/>
</picture>
-->

<div align="center">

### Building **RAG-driven KMS** & **Domain-Tuned LLMs**
*Less hallucination. More citations. Faster answers.*

<!-- Quick Links -->
<a href="https://huggingface.co/QuantCat" target="_blank">
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=000"/>
</a>
<a href="https://minji-sora-kim.tistory.com/" target="_blank">
  <img src="https://img.shields.io/badge/Tistory-Blog-000?style=for-the-badge&logo=tistory&logoColor=white"/>
</a>

<!-- Tech Badges (key tools) -->
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=fff"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=fff"/>
  <img src="https://img.shields.io/badge/Ollama-333333?style=for-the-badge&logo=ollama&logoColor=fff"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=fff"/>
  <img src="https://img.shields.io/badge/LlamaIndex-0B5FFF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2Zy8+"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=Chainlink&logoColor=fff"/>
  <img src="https://img.shields.io/badge/ChromaDB-323330?style=for-the-badge&logo=sqlite&logoColor=fff"/>
  <img src="https://img.shields.io/badge/Transformers-FFBF00?style=for-the-badge&logo=transformers&logoColor=000"/>
  <img src="https://img.shields.io/badge/TRL-0A0A0A?style=for-the-badge&logo=openai&logoColor=fff"/>
  <img src="https://img.shields.io/badge/Unsloth-6A5ACD?style=for-the-badge&logo=slack&logoColor=fff"/>
</p>

</div>

---

## 🔭 What I’m shipping
- **KMS Backend (FastAPI + LlamaIndex + Chroma)**: hybrid retrieval (Dense + BM25) → SBERT re-rank → SSE streaming with first-frame references.
- **GPT-OSS-20B (QLoRA/Unsloth) fine-tuning** on internal DB for hallucination mitigation & schema-controlled answers.
- **Computer Vision for Sustainability**: YOLOv8 + captioning + Gradio UI for clothing classification & contamination detection.

---

## 🧩 Featured Projects

### 1) KMS-RAG Backend
[![repo](https://img.shields.io/badge/GitHub-Repo-181717?logo=github)](https://github.com/Minji-Sora-Kim/SOMANSA-KMS)
[![last-commit](https://img.shields.io/github/last-commit/<OWNER>/<REPO_KMS>?label=last%20commit)](https://github.com/<OWNER>/<REPO_KMS>/commits)
[![issues](https://img.shields.io/github/issues/<OWNER>/<REPO_KMS>)](https://github.com/<OWNER>/<REPO_KMS>/issues)

- **Dual stores** (chunks/issues), **Dense+BM25** blend, **SBERT rerank**, **SSE streaming** with references.

### 2) GPT-OSS-20B-KMS (QLoRA/Unsloth)
[![repo](https://img.shields.io/badge/GitHub-Repo-181717?logo=github)](https://github.com/Minji-Sora-Kim/gpt-oss-20b-finetuning)
[![hf-model](https://img.shields.io/badge/HuggingFace-Model-FFD21E?logo=huggingface&logoColor=000)](<REPO_URL_HF_MODEL>)

- **QLoRA** fine-tuning with Unsloth/TRL → **LoRA merge (FP16)** → **GGUF Q4_K_M** for `llama.cpp` / Open WebUI.

### 3) clothes-recycle-vision
[![repo](https://img.shields.io/badge/GitHub-Repo-181717?logo=github)](https://github.com/Minji-Sora-Kim/gpt-oss-20b-finetuning)
[![demo](https://img.shields.io/badge/Demo-Gradio-3F85F7?logo=python&logoColor=fff)](<REPO_URL_GRADIO_DEMO>)

- YOLOv8 detection + captioning for **recyclable / disposable / reusable** triage.

---

## 🧪 Highlights
- **Hybrid Retrieval** → Dense (chunk) + BM25 (issue) weighted scoring → **SBERT top-3** rerank.  
- **Streaming UX** → OpenAI-style `choices[].delta` SSE + **first-frame references** (context preview).  
- **Model Lifecycle** → QLoRA train → **LoRA merge (FP16)** → **GGUF Q4_K_M quant** → serve with `llama.cpp`.

---

## 📈 GitHub Stats
<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=<Minji-Sora-Kim>&show_icons=true&theme=tokyonight&hide_title=true" />
  <img height="160" src="https://github-readme-streak-stats.herokuapp.com/?user=<Minji-Sora-Kim>&theme=tokyonight" />
</p>

---

## 📮 Contact
- 🤗 Hugging Face: **QuantCat**  
- 📝 Blog: **Tistory** — research notes, troubleshooting logs, and write-ups  
- 📫 Prefer issues on project repos, or email via profile.

<!-- Footer (same gradient as header; pick matching preset) -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:2575fc,100:6a11cb&reversal=true"/>
  <img alt="footer" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:2575fc,100:6a11cb"/>
</picture>
