<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=58A6FF&center=true&vCenter=true&width=760&lines=Hi%2C+I'm+Anish+%F0%9F%91%8B;I+build+AI+that+shows+its+evidence.;Forensics+%C2%B7+Drug+Discovery+%C2%B7+Compliance+AI;From+research+idea+%E2%86%92+tested%2C+deployed+system" alt="Typing SVG" />

### AI/ML Engineer building explainable, evidence-grounded systems, from Bitcoin forensics to drug discovery.

<a href="https://www.linkedin.com/in/anish-g-858660317"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://leetcode.com/u/Anish_1"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" /></a>
<a href="mailto:anish.g1835@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<img src="https://komarev.com/ghpvc/?username=Anish-185&style=for-the-badge&color=58A6FF&label=PROFILE+VIEWS" />

</div>

---

## 🧭 About Me

I build AI systems that **show their working**. My projects combine machine learning, graph analytics, OCR and LLMs,
but with one rule: **the data is the source of truth, not the model.** Every score, ranking and generated sentence
traces back to real evidence, and when the evidence isn't strong enough, the system abstains instead of guessing.

I take ideas all the way from research to production: data pipelines, interpretable models, FastAPI backends,
React + TypeScript frontends, Docker deployments and hundreds of automated tests.

```yaml
focus:      [Explainable AI, Graph ML, Applied ML, MLOps, Backend Engineering]
building:   Offline forensics tools, biomedical discovery pipelines, compliance AI
principles: [evidence over generation, abstain rather than guess, test everything]
learning:   [System Design, Distributed ML pipelines, Computational Neuroscience]
```

---

## 🏆 Flagship Projects

### 🔗 [btc-intel](https://github.com/Anish-185/btc-intel): Offline Bitcoin Forensics for Investigators
> *Follow the coin back to the hand that sent it.* Built for **Smart India Hackathon 2026 (PS 26146, NTRO)**.

An air-gapped investigator console that clusters wallets into real-world owners, flags laundering patterns, traces funds to
their cash-out points, and estimates which IP first broadcast a transaction from P2P relay timing.

- 🧠 **Multi-engine detection:** rules, anomaly detection and a **Graph Neural Network**, fused by a stacker with exact **SHAP** explanations
- 🛡️ **Live red-team mode:** inject a laundering pattern and watch whether the stack catches it, with nothing retrained
- 📜 **Court-ready evidence:** hash-chained chain-of-custody ledger (ISO/IEC 27037 style) and one-page PDF case reports

| 5 / 5 | 0.934 | 0 / 949 | 20 / 30 |
|:---:|:---:|:---:|:---:|
| illicit operations detected | alert precision | false alerts on a clean dataset | live red-team attacks caught |

<sub>Benchmarks on simulated generator data, as documented in the repo.</sub>

`Python` `PyTorch (GNN)` `NetworkX` `SHAP` `React` `TypeScript` `Fully offline`

---

### ⚖️ [MetrIQ](https://github.com/Anish-185/sih26): Evidence-Backed Assistant for Indian Standards & BIS Services
> Built for **Smart India Hackathon 2026 (PS 26107)**.

Ask in English, Hindi or Telugu, or simply photograph a product label, and MetrIQ identifies the governing standard,
explains *why* it matched, and links the official source behind every answer.

- 🔍 **Retrieval-first design:** deterministic code picks the answer; the LLM only explains what retrieval found
- 📷 **Local OCR label inspection:** every extracted value links back to the exact pixel box it came from
- 🧪 **Battle-tested:** adversarial and prompt-injection queries produce **zero** hallucinated standard numbers

| 505 | 98.1% | 0 | 395 |
|:---:|:---:|:---:|:---:|
| verified standards indexed | correct standard in top-5 | invented standard numbers | tests passing |

`FastAPI` `React 19` `PostgreSQL` `ONNX OCR` `LLM grounding` `Multilingual`

---

### 🔬 [SideEffect2Cure AI](https://github.com/Anish-185/sideeffect2cure): AI-Driven Drug Repurposing
For any disease, which already-approved drugs are promising repurposing candidates, and *why*?

- 🧬 A transparent **10-stage pipeline** linking disease genes → biological pathways → drug targets → side-effect profiles
- 📉 Narrows a **~1,430-drug universe** to biologically connected candidates, scored by an interpretable ML model
- 🗂️ Built on real biomedical data: **SIDER · ChEMBL · Open Targets · Reactome**
- 🤖 LLM-written explanations grounded in pipeline outputs, with a deterministic fallback

`FastAPI` `scikit-learn` `NetworkX` `React + TypeScript` `LLM explanations`

---

### 🐦 [FlappyBirdAI](https://github.com/Anish-185/FlappyBirdAI): Neuroevolution Research Study
A genetic algorithm learns to play Flappy Bird, written up as a full research paper:
*"Neuroevolution of a Flappy Bird Controller: An Empirical Study of Genetic Operators, Evaluation Noise and Generalisation."*

- ⚡ Headless simulator compiled with **numba** for high-speed training
- 📊 **606 logged training runs**, statistical analysis and fully reproducible figures
- 🧪 Tests generalisation of evolved controllers on unseen levels

---

## 🛠️ More Things I've Built

| Project | What it does | Stack |
|---|---|---|
| 🏭 [Production Line Performance Checker](https://github.com/Anish-185/Production-Line-Performance-Checker) | Predictive maintenance from sensor data with SHAP explainability, **live on Render** | FastAPI · Docker · SHAP |
| ⚙️ [Minimal MLOps Batch Pipeline](https://github.com/Anish-185/minimal-mlops-batch-pipeline) | Config-driven, validated, logged batch pipeline for financial time series | Python · Docker · YAML |
| 👁️ [Smart Vision Assistant](https://github.com/Anish-185/Smart-Vision-Assistant-YOLO-for-Multi-Object-Recognition) | Real-time multi-object detection agent | YOLOv8 · OpenCV |
| 🧩 [CppKit](https://github.com/Anish-185/cppkit) | VS Code extension with fast C++ and competitive-programming snippets | VS Code API |
| 📈 [Sales Forecasting](https://github.com/Anish-185/FUTURE_ML_01) | Time-series forecasting with a Power BI insights dashboard | Python · Power BI |
| 📉 [Customer Churn Prediction](https://github.com/Anish-185/FUTURE_ML_02) | Churn risk modelling with business-ready retention insights | scikit-learn · XGBoost |
| ⏱️ [Focus Pomodoro](https://github.com/Anish-185/Focus-Pomodoro) | Productivity timer web app | React · TypeScript · Vite |

---

## 💻 Tech Stack

**Languages**<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />

**AI / ML**<br/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
<img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" />
<img src="https://img.shields.io/badge/XGBoost-189FDD?style=flat-square" />
<img src="https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square&logoColor=black" />
<img src="https://img.shields.io/badge/SHAP-8A2BE2?style=flat-square" />
<img src="https://img.shields.io/badge/NetworkX-2C3E50?style=flat-square" />
<img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" />

**Data**<br/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white" />
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square" />
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" />

**Backend, Frontend & MLOps**<br/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white" />

---

## 🧱 How I Build

| | |
|---|---|
| 🔎 **Evidence over generation** | LLMs explain results; they never invent them. |
| 🤚 **Abstain rather than guess** | If the data can't support an answer, the system says so. |
| 🧪 **Tests are part of the product** | Hundreds of automated tests, adversarial and prompt-injection cases included. |
| 🔒 **Offline-first when it matters** | Sensitive workloads run fully air-gapped, with no cloud dependency. |
| 📖 **Document like it's a paper** | Every claim in a README is reproducible from one command. |

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Anish-185&theme=tokyonight&hide_border=true&show_icons=true&include_all_commits=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Anish-185&theme=tokyonight&hide_border=true&layout=compact" />

<img src="https://streak-stats.demolab.com?user=Anish-185&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Anish-185&theme=tokyo-night&hide_border=true&area=true" width="100%" />

</div>

---

<div align="center">

### 🤝 Open to collaborating on Explainable AI, Graph ML, Healthcare AI and Backend Engineering

*Fun fact: I once wrote a research paper about teaching a bird to flap.* 🐤

</div>
