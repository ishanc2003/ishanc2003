# Ishan Chakrabarti

**M.S. Computer Science (Artificial Intelligence)**, University of Southern California, Los Angeles
Software Engineering Intern @ CrossRoads · Graduating **May 2027**

Open to **part-time roles for Fall 2026**, and **full-time roles from Summer 2027 onwards**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/ishan-chakrabarti-42445422b)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:ichakra777@gmail.com)
![Location](https://img.shields.io/badge/Los_Angeles,_CA-333333?style=flat&logo=googlemaps&logoColor=white)

I build **local-first AI systems**: retrieval pipelines, on-device inference, and voice interfaces that run
without cloud APIs. Most of my recent work centers on making LLMs verifiable by grounding answers in retrieved
evidence, enforcing citations, and measuring when models are wrong.

---

## 🔬 Publications & Reports

**Unveiling Blockchain's Role in Cultivating Responsible Food Supply Chains**
Blockchain-based transparency and traceability mechanisms for agricultural supply chains, focusing on
accountability and sustainability across multiple supply stages. *(IJEMH, April 2025)*

**Diabetic Retinopathy Classification using Transfer Learning and CBAM-enhanced MobileNetV2**
Transfer learning with MobileNetV2 and CBAM attention for five-stage diabetic retinopathy classification on
Messidor-2, improving classification accuracy from 80% to 85%. *(Manuscript in submission)*

**Evidence-Based RAG for Hallucination-Resistant Multi-Hop Q&A**
Evidence-grounded RAG pipeline combining hybrid BM25 and FAISS retrieval, fuzzy title matching for iterative
two-hop retrieval, cross-encoder reranking, citation selection from pre-enumerated facts, and an NLI-based
verifier with a confidence-blending decider. Evaluated zero-shot on the full HotpotQA distractor development
set (7,405 examples). *(CSCI 566 course project report, USC, 2026)*

---

## 💼 Experience

**Software Engineering Intern @ CrossRoads** · Summer 2026
Hardened a Flutter/Dart and AWS social platform ahead of public launch: strengthened release-build
configuration handling, authored SpacetimeDB realtime release gates with unit tests and certification
runbooks, and built privacy-preserving, offline-resilient authenticated sync for the signals feeding the
recommendation layer.

**Cloud/DevOps Intern @ LTIMindtree** · Summer 2024
Designed CI/CD pipelines automating VM provisioning and Kubernetes (AKS) deployments on Microsoft Azure using
Docker and YAML, replacing manual setup. Documented pipelines and authored deployment guides for consistent
provisioning across development teams.

**Intern @ ATION Studios** · Spring 2022
Directed a cross-functional team of 5 (writers, artists, animators) producing animated sequences in Blender,
managed production timelines, and led the final client presentation.

---

## 🚀 Featured Projects

### [Hallucination-Resistant Multi-Hop QA](https://github.com/kabrashrey/hallucination_resistant_multihop_qna) · March 2026
[![Repo](https://img.shields.io/badge/View_Code-181717?style=flat&logo=github&logoColor=white)](https://github.com/kabrashrey/hallucination_resistant_multihop_qna)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

Evidence-grounded RAG pipeline for multi-hop QA on HotpotQA. Hybrid **BM25 + FAISS** retrieval with reciprocal
rank fusion, **BGE-reranker-v2-m3** cross-encoder reranking, complexity-based model routing, and strict
citation enforcement with abstention. Inference runs locally via **Ollama** (gemma4:31b) with no cloud APIs and
no task-specific training.

**Results** (zero-shot, full HotpotQA distractor dev set, n=7,405):
Joint F1 improved from **19.6% to 43.2%** · 46.8% EM · 59.5% Token F1 · **94.3% BERTScore F1**
Retrieval architecture contributed **5x more gain** than model upgrades alone.

> *CSCI 566 course project, team of 7.* I contributed to the pipeline infrastructure and owned the final
> evaluation runs.

---

### [Wine Explorer](https://github.com/ishanc2003/wine-explorer) · April 2026
[![Repo](https://img.shields.io/badge/View_Code-181717?style=flat&logo=github&logoColor=white)](https://github.com/ishanc2003/wine-explorer)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

Voice-enabled wine discovery app using **Whisper** speech-to-text, streaming LLM responses via **Ollama**
(Qwen 2.5:7B), and browser-native TTS. Dual-path query engine combining LLM-generated pandas code for
analytical questions (with self-correcting retry) and hybrid RAG for exploratory ones. Runs entirely locally
with **zero cloud APIs**.

---

### N.O.V.A, Narrative & Observational Virtual Assistant · January 2024
![Patent](https://img.shields.io/badge/Patent_Filed-202641027824-B8860B?style=flat)

Local-first AI writing assistant (Python 3.11, Flask, Vue.js, Electron) with offline inference, resource-aware
context management, and response streaming achieving sub-5-second latency versus roughly 30 seconds without.
SHA-256 encrypted local storage.

> *Patent application filed with the Indian Patent Office (No. 202641027824). Source not public.*

---

## 🛠️ Additional Work

*Coursework and personal projects. Happy to walk through any of these in detail.*

| Project | Description | Date |
|---|---|---|
| **Go Player** | Minimax agent for 5x5 Go with alpha-beta pruning and heuristic evaluation (liberties, eyes/connectivity, captures). Roughly 80% win rate against random, greedy, and Q-learning opponents. | Oct 2025 |
| **GA Map** | Genetic algorithm for low-cost routing on weighted maps using path-as-chromosome encoding, selection, crossover, and mutation. **Ranked 17/240** in a class-wide competition. | Sep 2025 |
| **Handwritten Text Generator** | DDPM diffusion model trained on MNIST (85k examples), with a menu-driven inference interface generating in under 7 seconds. | Jul 2025 |
| **OmniWatch** | WearOS watch face app (Jetpack Compose, Kotlin) with 1,000+ visual and interaction configurations. Google Play Closed Testing with **140+ beta testers**. | Mar 2023 |

---

## 🧰 Technical Skills

**AI / ML**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)

*RAG · Diffusion Models · FAISS · BM25 · Llama.cpp · Whisper · NLI Verification*

**Cloud & DevOps**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)

*Certified: AWS AI Practitioner · AWS Cloud Practitioner · Google Cloud Digital Leader*

**Languages & Frameworks**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vuedotjs&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white)
