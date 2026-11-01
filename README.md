<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=58A6FF&center=true&vCenter=true&width=780&lines=Hi%2C+I'm+Anish+%F0%9F%91%8B;I+build+AI+that+shows+its+evidence.;Forensics+%C2%B7+Health+%C2%B7+Compliance+%C2%B7+Hiring+AI;Tests+decide.+Models+explain.;From+research+idea+%E2%86%92+tested%2C+shipped+system" alt="Typing SVG" />

<a href="https://www.linkedin.com/in/anish-g-858660317"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://leetcode.com/u/Anish_1"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" /></a>
<a href="mailto:anish.g1835@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<img src="https://komarev.com/ghpvc/?username=Anish-185&style=for-the-badge&color=58A6FF&label=PROFILE+VIEWS" />

</div>

---

## 🧭 About Me

I'm a student at **CBIT, Hyderabad** who builds AI systems that **show their working**. My projects combine machine learning,
graph analytics, OCR and LLMs, with one rule: **the data is the source of truth, not the model.** Every score, ranking and
generated sentence traces back to real evidence, and when the evidence isn't strong enough, the system abstains instead of guessing.

I take ideas all the way from research to a shipped product: data pipelines, interpretable models, sandboxed execution,
FastAPI / Django backends, Next.js / React / React Native frontends, Docker deployments and **1,000+ automated tests** across my flagship work.

```yaml
focus:      [Explainable AI, Graph ML, LLM systems & agents, Applied ML, Backend Engineering]
building:   Forensics tools, health-screening apps, compliance AI, fair technical hiring
principles: [evidence over generation, abstain rather than guess, test everything]
learning:   [System Design, Distributed ML pipelines, Computational Neuroscience]
```

---

## 🏅 Highlights

<table>
<tr>
<td width="50%" valign="top">

🇮🇳 **Smart India Hackathon 2026: two problem statements**<br/>
<sub>Built [btc-intel](https://github.com/Anish-185/btc-intel) for **PS 26146 (NTRO)** and [MetrIQ](https://github.com/Anish-185/sih26) for **PS 26107 (BIS)**</sub>

🎃 **CBIT Hacktoberfest '26** (Team JL)<br/>
<sub>Built [Areté](https://github.com/Anish-185/portfolio-driven-assessment), a sandboxed, test-graded assessment platform</sub>

🩺 **SFIC 2026**: shipped an Android APK<br/>
<sub>[Shravan Setu](https://github.com/Anish-185/shravan-setu), an offline hearing-screening and referral system for schools</sub>

</td>
<td width="50%" valign="top">

🧠 **Open-source contributor to [Brian2](https://github.com/brian-team/brian2)**<br/>
<sub>4 merged PRs to the spiking-neural-network simulator used in computational neuroscience research</sub>

📄 **Wrote a research paper** on neuroevolution<br/>
<sub>[FlappyBirdAI](https://github.com/Anish-185/FlappyBirdAI): 606 logged runs, statistical analysis, reproducible figures</sub>

🧪 **Testing is part of the product**<br/>
<sub>486 tests in Shravan Setu · 395 in MetrIQ · adversarial & prompt-injection suites · **0** hallucinated standards</sub>

</td>
</tr>
</table>

---

## 🏆 Flagship Projects

### 🏛️ [Areté](https://github.com/Anish-185/portfolio-driven-assessment): Portfolio-Driven Coding Assessment Platform
> *A coding test built from the candidate's own portfolio, graded only by tests.* Built at **CBIT Hacktoberfest '26** with Team JL.

Areté turns a résumé, GitHub, LeetCode and Codeforces profile into a **validated 60-minute assessment in the candidate's own
domain and stack**: one real-codebase task and one DSA task at a Novice, Adept or Master tier.

- 🏗️ **Tasks prove themselves first:** a validation gate checks that the reference passes 3× in a row, the starter fails and the statement doesn't leak the fix. Bugs come from a **LibCST mutation engine**
- 🔒 **Sealed sandboxes:** a fresh Docker container per run with no network and capped CPU, memory, PIDs and time. Hidden tests run in their own sandbox
- ⚖️ **Deterministic scoring:** fail-to-pass grading (SWE-bench style). **No LLM ever decides a score**, and a Re-grade button shows the same score every time
- 🪽 **Guarded AI helpers:** a hint assistant that refuses to give answers, a *Labyrinth* code-comprehension round, a consented AI voice interviewer, and a *Trail Map* replay of how the candidate moved through the code

`FastAPI` `Next.js` `TypeScript` `Docker sandboxes` `PostgreSQL` `Redis + Celery` `Monaco` `LibCST`

---

### 👂 [Shravan Setu](https://github.com/Anish-185/shravan-setu): Offline Hearing Screening That Follows Through
> *Others built a hearing test. We built the system that makes sure the child actually gets treated.* Built for **SFIC 2026**.

A teacher screens a class on an ordinary Android phone with wired earphones and no internet. Each child who needs care becomes a
referral case that the school tracks through triage, batched ear-camp requests, missed visits and reschedules until the child is treated.

- 🎧 **Smart screening:** PASS / RETEST / REFER at 0.5–4 kHz. Silent catch trials detect random tapping, and the mic rejects tones masked by noise
- 📴 **Offline-first and Telugu-first:** full Telugu UI and recorded voice instructions, plus idempotent sync to a laptop server
- 🔐 **Tamper-evident:** SHA-256 hash-chained audit log of consents, results and status changes
- ⚡ Cut audio start delay from **486 ms to 60 ms**, and checked the screening rules against **5,456 real NHANES audiograms**

| 486 | ₹0 | ₹14.9 | 📲 |
|:---:|:---:|:---:|:---:|
| tests passing | software cost | equipment per child per year (proposed) | [APK release](https://github.com/Anish-185/shravan-setu/releases/tag/v1.0-sfic) |

`Expo / React Native` `TypeScript` `Django` `SQLite` `Offline sync` `Telugu + English`

---

### 🔗 [btc-intel](https://github.com/Anish-185/btc-intel): Offline Bitcoin Forensics for Investigators
> *Follow the coin back to the hand that sent it.* Built for **Smart India Hackathon 2026 (PS 26146, NTRO)**.

An air-gapped investigator console that clusters wallets into real-world owners, flags laundering patterns, traces funds to
their cash-out points, and estimates which IP first broadcast a transaction from P2P relay timing.

- 🧠 **Multi-engine detection:** rules, anomaly detection and a **Graph Neural Network**, fused by a stacker with exact **SHAP** explanations
- 🛡️ **Live red-team mode:** inject a laundering pattern and see whether the stack catches it, with no retraining
- 📜 **Court-ready evidence:** a hash-chained chain-of-custody ledger (ISO/IEC 27037 style) and one-page PDF case reports

| 5 / 5 | 0.934 | 0 / 949 | 20 / 30 |
|:---:|:---:|:---:|:---:|
| illicit operations detected | alert precision | false alerts on a clean dataset | live red-team attacks caught |

<sub>Benchmarks on simulated generator data, as documented in the repo.</sub>

`Python` `PyTorch (GNN)` `NetworkX` `SHAP` `React` `TypeScript` `Fully offline`

---

### ⚖️ [MetrIQ](https://github.com/Anish-185/sih26): Evidence-Backed Assistant for Indian Standards & BIS Services
> Built for **Smart India Hackathon 2026 (PS 26107)**.

Ask in English, Hindi or Telugu, or just photograph a product label. MetrIQ finds the governing Indian Standard,
explains *why* it matched, and links the official BIS source behind every answer.

- 🔍 **Retrieval-first design:** deterministic code picks the answer, and the LLM only explains what retrieval found
- 📷 **Local OCR label inspection:** every extracted value links back to the exact pixel box it came from
- 🧪 **Battle-tested:** adversarial and prompt-injection queries produce **zero** hallucinated standard numbers

| 505 | 98.1% | 0 | 395 |
|:---:|:---:|:---:|:---:|
| verified standards indexed | correct standard in top-5 | invented standard numbers | tests passing |

`FastAPI` `React 19` `PostgreSQL` `ONNX OCR` `Local LLM (Qwen3)` `Multilingual`

---

### 💬 [Aminobots Chat Triage Agent](https://github.com/Anish-185/aminobots-chat-triage-agent): Bounded-Autonomy LLM Agent
An agent that reads code-mixed **Telugu–English WhatsApp** partner group chats and lists every real request: who asked and whether
that's confirmed, a grade (*act / seek approval / hand off / refuse*), the numbered policy rule behind it, and the messages it relied on.

- 🧭 **The LLM describes and code decides:** identity, grade and rule come from a written policy (R1–R10) run in code, where the most cautious match wins
- 📈 Iterated from **v0.1 to v1.0** with a proper eval harness: grade accuracy **0.89 → 0.94**, approval load **0.44 → 0.18**
- 🛡️ **Zero over-autonomy** on high-risk requests, 100% evidence validity, and prompt-injection cases included
- 💸 Runs on **free models only ($0)**, with a local website that walks through every decision

| 0.89 | 0.94 | 1.00 | 0 |
|:---:|:---:|:---:|:---:|
| detection F1 | grade accuracy | sender attribution | high-risk over-autonomy |

`Python` `OpenRouter (free LLMs)` `rule-engine` `Pydantic` `uv` `Eval harness`

---

### 🔬 [SideEffect2Cure AI](https://github.com/Anish-185/sideeffect2cure): AI-Driven Drug Repurposing · [Live demo ↗](https://sideeffect2cure.vercel.app)
For any disease, which already-approved drugs are promising repurposing candidates, and *why*?

- 🧬 A transparent **10-stage pipeline** linking disease genes → biological pathways → drug targets → side-effect profiles
- 📉 Narrows a **~1,430-drug universe** to biologically connected candidates, scored by an interpretable ML model
- 🗂️ Built on real biomedical data: **SIDER · ChEMBL · Open Targets · Reactome**
- 🤖 LLM-written explanations grounded in pipeline outputs, with a deterministic fallback

`FastAPI` `scikit-learn` `NetworkX` `React + TypeScript` `Vercel`

---

### 🐦 [FlappyBirdAI](https://github.com/Anish-185/FlappyBirdAI): Neuroevolution Research Study
A genetic algorithm learns to play Flappy Bird, written up as a full research paper:
*"Neuroevolution of a Flappy Bird Controller: An Empirical Study of Genetic Operators, Evaluation Noise and Generalisation."*

- ⚡ A headless simulator compiled with **numba** for high-speed training
- 📊 **606 logged training runs**, statistical analysis and fully reproducible figures
- 🧪 Tests how evolved controllers generalise to unseen levels

---

## 🌍 Open Source

| Project | Contribution |
|---|---|
| 🧠 [**Brian2**](https://github.com/brian-team/brian2), a spiking neural network simulator | ✅ [#1882](https://github.com/brian-team/brian2/pull/1882) Replace deprecated pyparsing `parseAll` with `parse_all` in `parse_statement` |
| | ✅ [#1884](https://github.com/brian-team/brian2/pull/1884) Remove obsolete Python linting settings from the devcontainer |
| | ✅ [#1888](https://github.com/brian-team/brian2/pull/1888) Add a VS Code task to run the test suite |
| | ✅ [#1889](https://github.com/brian-team/brian2/pull/1889) Skip submodule fetches when pulling upstream tags in the docs build workflow |

---

## 🛠️ More Things I've Built

| Project | What it does | Stack |
|---|---|---|
| 🏭 [Production Line Performance Checker](https://github.com/Anish-185/Production-Line-Performance-Checker) | Predictive maintenance from sensor data with SHAP explainability, **deployed on Render** | FastAPI · Docker · SHAP |
| ⚙️ [Minimal MLOps Batch Pipeline](https://github.com/Anish-185/minimal-mlops-batch-pipeline) | Config-driven, validated and logged batch pipeline for financial time series | Python · Docker · YAML |
| ✨ [Halo](https://github.com/Anish-185/halo) | Cinematic marketing site for an AI call copilot, with generative canvas backgrounds and pointer-reactive motion | Next.js 16 · Tailwind 4 · Motion |
| 👁️ [Smart Vision Assistant](https://github.com/Anish-185/Smart-Vision-Assistant-YOLO-for-Multi-Object-Recognition) | Real-time multi-object detection agent | YOLOv8 · OpenCV |
| 🧩 [CppKit](https://github.com/Anish-185/cppkit) | VS Code extension with fast C++ and competitive-programming snippets | VS Code API |
| 🏏 [IPL Prediction System](https://github.com/Anish-185/IPL-PRECTION-SYSTEM) | Match outcome prediction from historical IPL data | scikit-learn · Pandas |
| 📈 [Sales Forecasting](https://github.com/Anish-185/FUTURE_ML_01) | Time-series forecasting with a Power BI insights dashboard | Python · Power BI |
| 📉 [Customer Churn Prediction](https://github.com/Anish-185/FUTURE_ML_02) | Churn risk modelling with business-ready retention insights | scikit-learn · XGBoost |
| ⏱️ [Focus Pomodoro](https://github.com/Anish-185/Focus-Pomodoro) | Productivity timer web app | React · TypeScript · Vite |

<details>
<summary><b>📚 ML foundations & practice notebooks</b> (click to expand)</summary>
<br/>

| Area | Repos |
|---|---|
| 🧠 Deep learning | [3-or-7 Neural Net Classifier](https://github.com/Anish-185/3-or-7-Classifier-Using-Neural-Nets) · [Cat & Dog Breed Classifier](https://github.com/Anish-185/Cat-and-Dog-breed-Classifier) · [MNIST 5-Classifier](https://github.com/Anish-185/MNIST-5classifier) |
| 🌲 Classical ML | [Breast Cancer (XGBoost)](https://github.com/Anish-185/Breast-cancer-using-xgb) · [Decision Trees on make_moons](https://github.com/Anish-185/DecisionTrees_using_makemoons) · [MNIST with SVM](https://github.com/Anish-185/MNIST-using-SVR) · [California Housing with SVR](https://github.com/Anish-185/California-housing-using-SVR) |
| 📊 Analytics | [Instructor Effectiveness Modeling](https://github.com/Anish-185/Instructor-Effectiveness-Modeling) · [Champions League 25/26 Analysis](https://github.com/Anish-185/Champions_League_Match_Analysis25-26) · [Pearson's r on California Housing](https://github.com/Anish-185/Pearsons-coeff-with-california-housing) |
| 🧮 DSA | [LeetCode Submissions](https://github.com/Anish-185/LeetCode-Submissions) · [NeetCode Submissions](https://github.com/Anish-185/neetcode-submissions) (C++) |

</details>

---

## 💻 Tech Stack

**Languages**<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
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
<img src="https://img.shields.io/badge/LLM_Agents-191919?style=flat-square&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/numba-00A3E0?style=flat-square&logo=numba&logoColor=white" />

**Data**<br/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white" />
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square" />
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" />

**Backend**<br/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" />
<img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />

**Frontend & Mobile**<br/>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />

**DevOps & Tools**<br/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black" />
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white" />

---

## 🧱 How I Build

| | |
|---|---|
| 🔎 **Evidence over generation** | LLMs explain results; they never invent them. |
| ⚖️ **Tests decide, models assist** | Scores, grades and verdicts come from deterministic code, never from a model's opinion. |
| 🤚 **Abstain rather than guess** | If the data can't support an answer, the system says so. |
| 🧪 **Tests are part of the product** | Hundreds of automated tests per project, adversarial and prompt-injection cases included. |
| 🔒 **Offline-first when it matters** | Sensitive and low-connectivity workloads run fully offline, with no cloud dependency. |
| 📖 **Document like it's a paper** | Every claim in a README is backed by a script or a documented condition. |

---

## 📊 GitHub & LeetCode Stats

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Anish-185&theme=tokyonight" width="100%" />

<img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Anish-185&theme=tokyonight" />
<img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Anish-185&theme=tokyonight" />

<img src="https://streak-stats.demolab.com?user=Anish-185&theme=tokyonight&hide_border=true" />

<a href="https://leetcode.com/u/Anish_1"><img src="https://leetcard.jacoblin.cool/Anish_1?theme=dark&font=Fira%20Code&ext=heatmap" /></a>

</div>

---

<div align="center">

### 🤝 Open to collaborating on Explainable AI, LLM agents, Graph ML, Healthcare AI and Backend Engineering

*Fun fact: I once wrote a research paper about teaching a bird to flap.* 🐤

</div>
