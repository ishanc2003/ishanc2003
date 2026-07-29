<div align="center">

<a href="https://github.com/ishanc2003"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a2980,100:26d0ce&height=180&section=header&text=Ishan%20Chakrabarti&fontSize=44&fontColor=ffffff&fontAlignY=32&desc=Local-first%20AI%20Systems%20%7C%20Retrieval%20%7C%20On-device%20Inference&descAlignY=53&descSize=16" width="100%" alt="Ishan Chakrabarti" /></a>

**M.S. Computer Science (Artificial Intelligence)** · University of Southern California<br>
Software Engineering Intern @ CrossRoads · Graduating **May 2027**

<a href="https://linkedin.com/in/ishan-chakrabarti-42445422b"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:ishanc3002@gmail.com"><img src="https://img.shields.io/badge/ishanc3002%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://github.com/ishanc2003"><img src="https://img.shields.io/badge/Los_Angeles,_CA-2b3137?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Los Angeles" /></a>

<br>

`Open to part-time roles for Fall 2026 · full-time roles from Summer 2027 onwards`

</div>

---

I build **local-first AI systems** that run without cloud APIs:

- **Retrieval** — hybrid BM25 + FAISS, cross-encoder reranking
- **Inference** — on-device via Ollama, zero cloud APIs
- **Evaluation** — citation enforcement, NLI verification

Most of my recent work centers on making LLMs verifiable: grounding answers in retrieved evidence, and measuring when models are wrong.

---

## 🧰 Toolbox

<div align="center">
<a href="https://github.com/ishanc2003"><img src="https://raw.githubusercontent.com/ishanc2003/ishanc2003/main/assets/card-toolbox.svg" width="100%" alt="Technical toolbox" /></a>
</div>

<sub>Python · PyTorch · TensorFlow · Keras · scikit-learn · Hugging Face · Ollama · Llama.cpp · RAG · FAISS · BM25 · Whisper · Diffusion Models · NLI Verification · AWS · Azure · GCP · Docker · Kubernetes · FastAPI · Flask · Auth0 · C/C++ · Java · Dart · Flutter · React · Vue.js · Django · Node.js · PostgreSQL · Git</sub>

<sub>**Certified:** AWS AI Practitioner · AWS Cloud Practitioner · Google Cloud Digital Leader</sub>

---

## 🔬 Publications & Reports

<div align="center">
<img src="https://raw.githubusercontent.com/ishanc2003/ishanc2003/main/assets/card-publications.svg" width="100%" alt="Publications and reports" />
</div>

<details open>
<summary><b>Unveiling Blockchain's Role in Cultivating Responsible Food Supply Chains</b> · <i>IJEMH, April 2025</i></summary>
<br>
Blockchain-based transparency and traceability mechanisms for agricultural supply chains, focusing on accountability and sustainability across multiple supply stages.
</details>

<details open>
<summary><b>Diabetic Retinopathy Classification using Transfer Learning and CBAM-enhanced MobileNetV2</b> · <i>Under review, IEEE</i></summary>
<br>
Transfer learning with MobileNetV2 and CBAM attention for five-stage diabetic retinopathy classification on Messidor-2, improving classification accuracy from 80% to 85%.
</details>

<details open>
<summary><b>Evidence-Based RAG for Hallucination-Resistant Multi-Hop Q&A</b> · <i>Under review, IEEE</i></summary>
<br>
Evidence-grounded RAG pipeline combining hybrid BM25 and FAISS retrieval, fuzzy title matching for iterative two-hop retrieval, cross-encoder reranking, citation selection from pre-enumerated facts, and an NLI-based verifier with a confidence-blending decider. Evaluated zero-shot on the full HotpotQA distractor development set (7,405 examples).
</details>

---

## 💼 Experience

<div align="center">
<img src="https://raw.githubusercontent.com/ishanc2003/ishanc2003/main/assets/card-experience.svg" width="100%" alt="Experience timeline: ATION Studios Spring 2022, LTIMindtree Summer 2024, CrossRoads Summer 2026" />
</div>

<details open>
<summary><b>Software Engineering Intern @ CrossRoads</b> · <i>Summer 2026</i></summary>
<br>

Launch stabilization and platform hardening for a Flutter/Dart and AWS social platform, spanning release engineering, realtime infrastructure, and backend preference signals. Delivered 8 tracked issues across two release phases.

&nbsp;&nbsp;<sub><b>RELEASE ENGINEERING & CONFIGURATION</b></sub>

- Established a release-time configuration boundary separating public mobile config from server-side configuration, so release-bound builds provably carry only their intended public surface
- Extended secret scanning to cover Flutter asset manifests and generated build inputs, with a documented public-config contract for mobile

&nbsp;&nbsp;<sub><b>REALTIME INFRASTRUCTURE (SPACETIMEDB)</b></sub>

- Authored realtime release gates covering reconnect health, message ordering, stream lag, unread and read-state correctness, and generated-binding drift
- Certified SpacetimeDB as the single source of truth for messaging, presence, and group threads, with no production read or write path depending on RDS/Lambda fallback
- Reviewed runtime ownership across connection services and scoped group and project thread subscriptions

&nbsp;&nbsp;<sub><b>BACKEND PREFERENCE SIGNALS</b></sub>

- Designed an authenticated sync path carrying saved and recent search signals into backend preference profiles, making device-local intent usable as a recommendation input
- Kept local storage as the immediate UI source with retry and idempotency handling, so sync failure degrades silently rather than breaking search
- Applied redaction and minimization to raw queries under the event privacy contract

&nbsp;&nbsp;<sub><b>MEDIA PIPELINE & CLIENT CORRECTNESS</b></sub>

- Hardened video upload and quota enforcement with failure-boundary-specific handling across quota, duration, upload, processing, moderation, auth, and network states
- Specified clip reuse across content flows with a quota model keyed on unique referenced media, removing repeated re-uploads
- Resolved realtime and rendering correctness in direct messaging, including typing-indicator attribution and consolidating avatar rendering into a single intentional component

<br>
</details>

<br>

<details open>
<summary><b>Cloud/DevOps Intern @ LTIMindtree</b> · <i>Summer 2024</i></summary>
<br>

- Designed CI/CD pipelines automating VM provisioning and Kubernetes (AKS) deployments on Microsoft Azure using Docker and YAML, replacing manual setup
- Resolved SSH authentication and image pull failures during testing
- Documented pipelines and authored deployment guides for consistent provisioning across development teams

<br>
</details>

<br>

<details open>
<summary><b>Intern @ ATION Studios</b> · <i>Spring 2022</i></summary>
<br>

- Directed a cross-functional team of 5 (writers, artists, animators) producing animated sequences in Blender
- Managed production timelines and integrated assets
- Led the final client presentation, explaining behind-the-scenes process and creative decisions

<br>
</details>

---

## 🚀 Featured Projects

### <a href="https://github.com/kabrashrey/hallucination_resistant_multihop_qna">Hallucination-Resistant Multi-Hop QA</a> · March 2026

<a href="https://github.com/kabrashrey/hallucination_resistant_multihop_qna"><img src="https://img.shields.io/badge/View_Code-181717?style=flat-square&logo=github&logoColor=white" alt="View code" /></a>
<a href="https://github.com/kabrashrey/hallucination_resistant_multihop_qna"><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /></a>
<a href="https://hotpotqa.github.io/"><img src="https://img.shields.io/badge/HotpotQA-4b8bbe?style=flat-square" alt="HotpotQA" /></a>

Evidence-grounded RAG pipeline for multi-hop QA on HotpotQA. Hybrid **BM25 + FAISS** retrieval with reciprocal rank fusion, **BGE-reranker-v2-m3** cross-encoder reranking, complexity-based model routing, and strict citation enforcement with abstention. Inference runs locally via **Ollama** (gemma4:31b) with no cloud APIs and no task-specific training.

<a href="https://github.com/kabrashrey/hallucination_resistant_multihop_qna"><img src="https://raw.githubusercontent.com/ishanc2003/ishanc2003/main/assets/card-metrics.svg" width="100%" alt="Evaluation results: Joint F1 19.6 to 43.2 percent, BERTScore F1 94.3 percent, Exact Match 46.8 percent, Token F1 59.5 percent, 5x retrieval gain" /></a>

<sub>Joint F1 19.6% → 43.2% · BERTScore F1 94.3% · Exact Match 46.8% · Token F1 59.5% · retrieval architecture contributed 5x more gain than model upgrades. Zero-shot, full HotpotQA distractor dev set (n=7,405).</sub>

> *CSCI 566 course project, team of 7.* I contributed to the pipeline infrastructure and owned the final evaluation runs.

---

### <a href="https://github.com/ishanc2003/wine-explorer">Wine Explorer</a> · April 2026

<a href="https://github.com/ishanc2003/wine-explorer"><img src="https://img.shields.io/badge/View_Code-181717?style=flat-square&logo=github&logoColor=white" alt="View code" /></a>
<a href="https://github.com/ishanc2003/wine-explorer"><img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" /></a>
<a href="https://github.com/ishanc2003/wine-explorer"><img src="https://img.shields.io/badge/Whisper-412991?style=flat-square&logo=openai&logoColor=white" alt="Whisper" /></a>
<a href="https://ollama.com"><img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama" /></a>

Voice-enabled wine discovery app using **Whisper** speech-to-text, streaming LLM responses via **Ollama** (Qwen 2.5:7B), and browser-native TTS. Dual-path query engine combining LLM-generated pandas code for analytical questions (with self-correcting retry) and hybrid RAG for exploratory ones. Runs entirely locally with **zero cloud APIs**.

---

### N.O.V.A, Narrative & Observational Virtual Assistant · January 2024

<a href="https://github.com/ishanc2003"><img src="https://img.shields.io/badge/Patent_Filed-202641027824-B8860B?style=flat-square" alt="Patent filed" /></a>
<a href="https://github.com/ishanc2003"><img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" alt="Electron" /></a>
<a href="https://ollama.com"><img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama" /></a>

Local-first AI writing assistant (Python 3.11, Flask, Vue.js, Electron) with offline inference via **Ollama**, resource-aware context management, and response streaming achieving sub-5-second latency versus roughly 30 seconds without. SHA-256 encrypted local storage.

> *Patent application filed with the Indian Patent Office (No. 202641027824).*

---

## 🛠️ Additional Work

<sub>*Coursework and personal projects. Happy to walk through any of these in detail.*</sub>

| Project | Description | Date |
|---|---|---|
| **Go Player** | Minimax agent for 5x5 Go with alpha-beta pruning and heuristic evaluation (liberties, eyes/connectivity, captures). Roughly 80% win rate against random, greedy, and Q-learning opponents. | Oct 2025 |
| **GA Map** | Genetic algorithm for low-cost routing on weighted maps using path-as-chromosome encoding, selection, crossover, and mutation. **Ranked 17/240** in a class-wide competition. | Sep 2025 |
| **Handwritten Text Generator** | DDPM diffusion model trained on MNIST (85k examples), with a menu-driven inference interface generating in under 7 seconds. | Jul 2025 |
| **OmniWatch** | WearOS watch face app (Jetpack Compose, Kotlin) with 1,000+ visual and interaction configurations. Google Play Closed Testing with **140+ beta testers**. | Mar 2023 |

---

<div align="center">

<sub>Currently building local-first retrieval and evaluation tooling. Always happy to talk about RAG, on-device inference, and making models say when they do not know.</sub>

<a href="https://github.com/ishanc2003"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:26d0ce,100:1a2980&height=100&section=footer" width="100%" alt="" /></a>

</div>
