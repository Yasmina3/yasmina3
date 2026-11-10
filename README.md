<h1 align="center">Yasmina Medjri</h1>
<h3 align="center">AI & HPC Engineer · I make AI models smarter, and make them run faster</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/yasmina-medjri-ai-engineer/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:yasmina.medjri@ensia.edu.dz"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://huggingface.co/yasmina3"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" /></a>
  <img src="https://img.shields.io/badge/Paris%2C%20France-0055A4?style=for-the-badge" />
</p>

---

### 👋 About me

- 🎓 **M2 High Performance Computing & Simulation (CHPS)** at Université Paris-Saclay / UVSQ (2026–2027)
- 🎓 **State Engineer + Master in AI & Data Science**, ENSIA Algiers (2021–2026), top 15 of ~100
- 🔬 Final-year research project at **FEMTO-ST (CNRS)**: physics simulation + graph neural networks for breast cancer detection
- 💼 Part-time **AI automation & software developer** at SQPS (Switzerland)
- 🔭 **Looking for a 4–6 month internship from March 2027** combining **AI and HPC**: GPU optimization, AI for science, efficient training and inference
- 🗣️ Arabic (native) · French (C1) · English (C1)

---

### ⭐ Featured work

**⚡ [cuda-sgemm](https://github.com/Yasmina3/cuda-sgemm): a CUDA matrix multiply at 97.5% of cuBLAS**
Hand-written FP32 GEMM on an H100 (46.2 vs 47.3 TFLOP/s), built up in 8 explained steps from 1% to 97.5% of cuBLAS. Includes a TF32 tensor-core kernel written with PTX `mma.sync` (+52% over WMMA), an autotuner over 169+ configurations, roofline and SASS analysis, and a 29-case correctness suite. Runs on the ROMEO supercomputer via Slurm.
`CUDA` `PTX` `Nsight` `Slurm` `Python`

**🩺 Breast cancer detection with wearable thermography** *(ENSIA × FEMTO-ST, private)*
Physics simulation (COMSOL), a reduced-order model ~10,000× faster than the simulator (0.045 °C error), and graph neural networks with sim-to-real transfer reaching **AUC 0.95** on real patient data.
`PyTorch` `GNN` `COMSOL` `Scientific ML`

**📚 [Algerian History AI Tutor](https://github.com/Yasmina3/algerian-history-ai-tutor)**
Llama 3.2 3B fine-tuned with QLoRA on Arabic Q&A ([model on Hugging Face](https://huggingface.co/yasmina3/History-final-Llama-3.2-3B-Instruct-bnb-4bit)), RAG over ~200k chunks, and Llama 70B calling the fine-tuned model as a tool.
`Unsloth` `LoRA` `RAG` `Pinecone` `Groq`

**🌲 [GeoForest-AI](https://github.com/Yasmina3/multispectral-forest-classifier)** · 🏆 1st place, Mathix 2025 (Algerian Space Agency)
Forest mapping on 6M multispectral satellite pixels, **98.3% accuracy on an unseen region**.
`XGBoost` `Rasterio` `Geospatial`

**🔥 [Wildfire AI Guard](https://github.com/Yasmina3/WILDFIRE-AI-GUARD-DEMO)** · 🏆 1st place, Huawei Tech4Connect 2026
AI + 5G + drones system for wildfire detection and spread prediction. [Live 3D demo](https://yasmina3.github.io/WILDFIRE-AI-GUARD-DEMO/).
`Computer Vision` `Three.js`

**🤖 AutoJobAgent** *(SQPS, [autojobagent.ch](https://autojobagent.ch))*
Autonomous job-search agent I built solo: CV parsing, multi-platform scraping, AI match scoring and tailored applications.
`FastAPI` `React` `LLM agents` `Docker`

---

### 🛠️ Toolbox

| Area | Tools |
|---|---|
| **HPC & GPU** | CUDA, PTX / tensor cores, Nsight Systems, compute-sanitizer, Slurm, C/C++, performance analysis (roofline, SASS) |
| **AI / ML** | PyTorch, TensorFlow, scikit-learn, XGBoost, graph neural networks, computer vision, reinforcement learning |
| **LLMs** | Hugging Face, LoRA/QLoRA, Unsloth, RAG, FAISS / ChromaDB / Pinecone, agents & function calling |
| **Simulation** | COMSOL (FEM), reduced-order models, Monte Carlo, numerical optimization |
| **Software** | Python, FastAPI, Flask, React, Flutter, PostgreSQL, Redis, Docker, Linux, Git / CI |

---

### 🏆 Highlights

- 🥇 **3 first places and 7 podiums** in 15+ hackathons, always as team lead and pitcher
- 🌍 Selected for **MenaML Winter School 2026** at KAUST (~300 of ~2,500 applicants)
- 🟩 **NVIDIA Deep Learning Institute** certified
- 🎤 ~10 talks and workshops on machine learning and AI for healthcare

<p align="center"><i>Always happy to talk about GPUs, LLMs, or AI for science. Reach out on LinkedIn!</i></p>
