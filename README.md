<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a2980,100:26d0ce&height=180&section=header&text=Ishan%20Chakrabarti&fontSize=44&fontColor=ffffff&fontAlignY=32&desc=Local-first%20AI%20Systems%20%7C%20Retrieval%20%7C%20On-device%20Inference&descAlignY=53&descSize=16" width="100%" alt="Ishan Chakrabarti" />

**M.S. Computer Science (Artificial Intelligence)** · University of Southern California<br>
Software Engineering Intern @ CrossRoads · Graduating **May 2027**

<a href="https://linkedin.com/in/ishan-chakrabarti-42445422b"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:ichakra777@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://github.com/ishanc2003"><img src="https://img.shields.io/badge/Los_Angeles,_CA-2b3137?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Los Angeles" /></a>

<br>

`Open to part-time roles for Fall 2026 · full-time roles from Summer 2027 onwards`

</div>

---

I build **local-first AI systems**: retrieval pipelines, on-device inference, and voice interfaces that run without cloud APIs. Most of my recent work centers on making LLMs verifiable by grounding answers in retrieved evidence, enforcing citations, and measuring when models are wrong.

---

## 🧰 Toolbox

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,flask,fastapi,docker,kubernetes,aws,azure,gcp&theme=dark" alt="AI, ML and cloud tooling" />
<br>
<img src="https://skillicons.dev/icons?i=cpp,java,dart,flutter,react,vue,django,nodejs,postgres,git&theme=dark" alt="Languages and frameworks" />

<sub>**Also:** RAG · FAISS · BM25 · Ollama · Llama.cpp · Whisper · Hugging Face · Diffusion Models · NLI Verification</sub>

<sub>**Certified:** AWS AI Practitioner · AWS Cloud Practitioner · Google Cloud Digital Leader</sub>

</div>

---

## 🔬 Publications & Reports

<details open>
<summary><b>Unveiling Blockchain's Role in Cultivating Responsible Food Supply Chains</b> · <i>IJEMH, April 2025</i></summary>
<br>
Blockchain-based transparency and traceability mechanisms for agricultural supply chains, focusing on accountability and sustainability across multiple supply stages.
</details>

<details open>
<summary><b>Diabetic Retinopathy Classification using Transfer Learning and CBAM-enhanced MobileNetV2</b> · <i>Manuscript in submission</i></summary>
<br>
Transfer learning with MobileNetV2 and CBAM attention for five-stage diabetic retinopathy classification on Messidor-2, improving classification accuracy from 80% to 85%.
</details>

<details open>
<summary><b>Evidence-Based RAG for Hallucination-Resistant Multi-Hop Q&A</b> · <i>CSCI 566 course project report, USC, 2026</i></summary>
<br>
Evidence-grounded RAG pipeline combining hybrid BM25 and FAISS retrieval, fuzzy title matching for iterative two-hop retrieval, cross-encoder reranking, citation selection from pre-enumerated facts, and an NLI-based verifier with a confidence-blending decider. Evaluated zero-shot on the full HotpotQA distractor development set (7,405 examples).
</details>

---

## 💼 Experience

<details open>
<summary><b>Software Engineering Intern @ CrossRoads</b> · <i>Summer 2026</i></summary>
<br>

Hardened a Flutter/Dart and AWS social platform ahead of public launch.

- Strengthened release-build configuration handling
- Authored SpacetimeDB realtime release gates with unit tests and certification runbooks
- Built privacy-preserving, offline-resilient authenticated sync for the signals feeding the recommendation layer

</details>

<details open>
<summary><b>Cloud/DevOps Intern @ LTIMindtree</b> · <i>Summer 2024</i></summary>
<br>

- Designed CI/CD pipelines automating VM provisioning and Kubernetes (AKS) deployments on Microsoft Azure using Docker and YAML, replacing manual setup
- Resolved SSH authentication and image pull failures during testing
- Documented pipelines and authored deployment guides for consistent provisioning across development teams

</details>

<details open>
<summary><b>Intern @ ATION Studios</b> · <i>Spring 2022</i></summary>
<br>

- Directed a cross-functional team of 5 (writers, artists, animators) producing animated sequences in Blender
- Managed production timelines and integrated assets
- Led the final client presentation, explaining behind-the-scenes process and creative decisions

</details>

---

## 🚀 Featured Projects

### <a href="https://github.com/kabrashrey/hallucination_resistant_multihop_qna">Hallucination-Resistant Multi-Hop QA</a> · March 2026

<a href="https://github.com/kabrashrey/hallucination_resistant_multihop_qna"><img src="https://img.shields.io/badge/View_Code-181717?style=flat-square&logo=github&logoColor=white" alt="View code" /></a>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/HotpotQA-4b8bbe?style=flat-square" alt="HotpotQA" />

Evidence-grounded RAG pipeline for multi-hop QA on HotpotQA. Hybrid **BM25 + FAISS** retrieval with reciprocal rank fusion, **BGE-reranker-v2-m3** cross-encoder reranking, complexity-based model routing, and strict citation enforcement with abstention. Inference runs locally via **Ollama** (gemma4:31b) with no cloud APIs and no task-specific training.

<table>
<tr>
<td align="center"><b>19.6% → 43.2%</b><br><sub>Joint F1</sub></td>
<td align="center"><b>94.3%</b><br><sub>BERTScore F1</sub></td>
<td align="center"><b>46.8%</b><br><sub>Exact Match</sub></td>
<td align="center"><b>59.5%</b><br><sub>Token F1</sub></td>
<td align="center"><b>5x</b><br><sub>retrieval gain vs<br>model upgrades</sub></td>
</tr>
</table>

<sub>Zero-shot, full HotpotQA distractor dev set (n=7,405).</sub>

> *CSCI 566 course project, team of 7.* I contributed to the pipeline infrastructure and owned the final evaluation runs.

---

### <a href="https://github.com/ishanc2003/wine-explorer">Wine Explorer</a> · April 2026

<a href="https://github.com/ishanc2003/wine-explorer"><img src="https://img.shields.io/badge/View_Code-181717?style=flat-square&logo=github&logoColor=white" alt="View code" /></a>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/Whisper-412991?style=flat-square&logo=openai&logoColor=white" alt="Whisper" />

Voice-enabled wine discovery app using **Whisper** speech-to-text, streaming LLM responses via **Ollama** (Qwen 2.5:7B), and browser-native TTS. Dual-path query engine combining LLM-generated pandas code for analytical questions (with self-correcting retry) and hybrid RAG for exploratory ones. Runs entirely locally with **zero cloud APIs**.

---

### N.O.V.A, Narrative & Observational Virtual Assistant · January 2024

<img src="https://img.shields.io/badge/Patent_Filed-202641027824-B8860B?style=flat-square" alt="Patent filed" />
<img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" alt="Electron" />

Local-first AI writing assistant (Python 3.11, Flask, Vue.js, Electron) with offline inference, resource-aware context management, and response streaming achieving sub-5-second latency versus roughly 30 seconds without. SHA-256 encrypted local storage.

> *Patent application filed with the Indian Patent Office (No. 202641027824). Source not public.*

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

<img src="https://github-readme-stats.vercel.app/api?username=ishanc2003&show_icons=true&hide_border=true&hide=stars,issues&theme=tokyonight&bg_color=00000000&title_color=26d0ce&icon_color=26d0ce" alt="GitHub stats" height="150" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ishanc2003&layout=compact&hide_border=true&exclude_repo=Programs,FinanceApp&hide=html,css&theme=tokyonight&bg_color=00000000&title_color=26d0ce" alt="Top languages" height="150" />

</div>
