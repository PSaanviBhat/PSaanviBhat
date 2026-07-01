<div align="center">

# P Saanvi

**AI/ML Engineer | Computer Science Student | Explainable AI & Quantitative ML**

Bengaluru, India | [Email](mailto:psaanvibhat@outlook.com) | [GitHub](https://github.com/PSaanviBhat) | [LinkedIn](https://linkedin.com/in/psaanvi)

---

### Profile Summary
I am an undergraduate Computer Science student at PES University specializing in Artificial Intelligence and Machine Learning. I design and build high-performance, data-driven AI systems and quantitative pipelines that solve real-world problems. My experience spans **sensor telemetry, time-series anomaly detection, explainable AI (XAI), and private permissioned ledger integration**. I focus on constructing production-grade ML architectures, robust ETL systems, and low-latency inference modules.

</div>

---

## Technical Stack

<table>
  <tr>
    <td valign="top" width="50%">
      <h3>Languages & Core Fundamentals</h3>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="C" />
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
        <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
        <img src="https://img.shields.io/badge/Assembly-009639?style=flat-square&logo=assemblyscript&logoColor=white" alt="Assembly" />
        <img src="https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white" alt="MATLAB" />
      </p>
      <h3>Quantitative Finance & Machine Learning</h3>
      <ul>
        <li><b>Frameworks:</b> PyTorch, TensorFlow, XGBoost, Scikit-learn, NumPy, SciPy</li>
        <li><b>Quantitative Modeling:</b> Monte Carlo Simulation, Black-Scholes-Merton Pricing, Greeks Sensitivity Analysis</li>
        <li><b>Deep Learning:</b> LSTMs, CNNs, Autoencoders, Reinforcement Learning (PPO)</li>
        <li><b>Telemetry & Analytics:</b> Extreme Value Theory (SPOT/DSPOT), Anomaly Detection, Time-Series Forecasting, Adaptive Thresholding</li>
      </ul>
    </td>
    <td valign="top" width="50%">
      <h3>Systems, Cryptography & Blockchain</h3>
      <ul>
        <li><b>Distributed Ledgers:</b> Smart Contracts (Solidity), Consensus Mechanisms (PoA/DPoS)</li>
        <li><b>Security & Privacy:</b> AES-256-GCM Encryption, Cryptographic Hashing (SHA-256), GDPR- & HIPAA-Compliant Architectures</li>
        <li><b>Data Engineering:</b> ETL Pipelines, REST API Integration, Pandas Vectorization, Chunked I/O, Pytest Mocking, Exponential Backoff</li>
        <li><b>Business Intelligence:</b> Power BI Integration</li>
      </ul>
      <h3>Computer Vision & Web Tools</h3>
      <p>
        <img src="https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square&logo=yolo&logoColor=black" alt="YOLOv8" />
        <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV" />
        <img src="https://img.shields.io/badge/Zero--DCE-8A2BE2?style=flat-square" alt="Zero-DCE" />
        <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit" />
        <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask" />
        <img src="https://img.shields.io/badge/MERN_Stack-61DAFB?style=flat-square&logo=react&logoColor=black" alt="MERN" />
        <img src="https://img.shields.io/badge/ChromaDB-4B0082?style=flat-square" alt="Vector DB" />
        <img src="https://img.shields.io/badge/Arduino_IoT-00979D?style=flat-square&logo=arduino&logoColor=white" alt="Arduino" />
      </p>
    </td>
  </tr>
</table>

---

## Projects Portfolio

### Deep Learning, RAG & Explainable AI (XAI)

#### Explainable VAE-EVT-XGBoost Framework for Smart Grid Fault Detection
**Publication-Ready** | Hybrid Deep Learning + Explainability | [GitHub Repository](https://github.com/PSaanviBhat/-SmartGridAnomalyDetection)
* Engineered an anomaly detection pipeline achieving an **F1 score of 0.9959** and improving precision from **0.924 (static) to 0.992 (DSPOT)** using Variational Autoencoders + DSPOT adaptive thresholding (16x improvement over Isolation Forest & One-Class SVM).
* Developed a latent-space-augmented XGBoost multi-class fault classifier yielding **96.85% test accuracy** and a **0.9676 F1 score**.
<details>
<summary><b>View Technical Implementation Details</b></summary>

* Applied SHAP-based explainability to isolate fault-driving process parameters across 7 sensor telemetry dimensions.
* Proposed a novel interpretability metric, the **XAI Coherence Score (XCS)**, to quantify cross-stage attribution agreement between VAE reconstruction signals and XGBoost SHAP values, enabling reproducible evaluation of explainability pipelines.
* **Tech:** Variational Autoencoders (VAEs), XGBoost, SHAP/TreeSHAP, Extreme Value Theory (SPOT/DSPOT), Multivariate Sensor Telemetry.
</details>

---

#### Multi-Branch Spatio-Temporal Respiration Classifier & Joint MTL Framework
* Engineered a 3-branch time-frequency feature extraction pipeline (Mel Spectrogram, CQT, CWT) on the ICBHI 2017 database (6,898 cycles) using a PyTorch-based Cross-Attention Late Fusion and CNN-Conformer sequence classifier.
* Integrated patient-invariant contrastive regularization (InfoNCE Loss) over patient IDs to align latent features, resolving validation calibration overfitting and achieving a record **47.25% official ICBHI score** under strict patient-wise partitions.
<details>
<summary><b>View Technical Implementation Details</b></summary>

* Developed a joint multi-task learning (MTL) framework classifying 4-class respiratory cycles and 3-class disease pathologies (COPD, URTI, Healthy) over 6,311 cycles.
* Implemented learnable homoscedastic uncertainty loss balancing alongside class-weighted Focal Loss and Mixup augmentation to achieve a **93.03% disease classification accuracy** and push cycle anomaly sensitivity to **45.08%** at a real-time inference latency of **4.36ms/cycle**.
* **Tech:** PyTorch, Signal Processing (Mel Spectrogram, CQT, CWT), CNN-Conformer, Cross-Attention Late Fusion, InfoNCE Loss, Multi-Task Learning, Homoscedastic Uncertainty.
</details>

---

#### Memora: Multimodal Cognitive Assistive Platform for Alzheimer's Patients
Production-Grade Assistive AI System | [GitHub Repository](https://github.com/PSaanviBhat/Memora-AR-Based-Cognitive-Assistive-Platform)
* Architected an end-to-end multimodal AI system integrating biometric identity recognition (face via ArcFace + voice via ECAPA-TDNN) with a Retrieval-Augmented Generation (RAG) pipeline.
* Designed the complete STT → LLM → TTS inference pipeline for real-time conversational assistive prompts using Whisper, Qwen LLM, and Coqui TTS.
<details>
<summary><b>View Technical Implementation Details</b></summary>

* Achieved sub-second memory retrieval latency using a ChromaDB-backed vector database with embedding-indexed knowledge retrieval, enabling LLM inference over personalized structured memory at scale.
* Deployed as a robust local system designed for low-latency cognitive aid.
* **Tech:** ArcFace, ECAPA-TDNN, ChromaDB Vector DB, RAG, Qwen LLM, Whisper STT, Coqui TTS.
</details>

---

### Cryptography & Systems Engineering

#### Private Permissioned Blockchain Network for Clinical Trial Data Management
* Designed and deployed a 12-step private permissioned blockchain network for clinical trial data management using hybrid PoA + DPoS consensus and SHA-256 cryptographic hashing.
* Ensured GDPR/HIPAA-compliant immutability across 2,000 trial records with ~23% injected anomalies, achieving near-zero unauthorized data commits via a pre-chain ML fraud gate benchmarking 8 classifiers.
<details>
<summary><b>View Technical Implementation Details</b></summary>

* Architected 6 Solidity smart contract functions enforcing role-based access control (RBAC), phase-sequence validation (Phase I→IV), and tamper-evident audit trails across distributed nodes.
* Achieved $O(1)$ hash-chain validation per transaction with AES-256-GCM encryption for IPFS-pinned record storage.
* Deployed XGBoost as the primary fraud gate achieving **86.82% accuracy** and **100% precision** at 16.4ms inference latency.
* **Tech:** Solidity, Blockchain (PoA/DPoS), AES-256-GCM, SHA-256, IPFS, Role-Based Access Control, XGBoost.
</details>

---

#### Fault-Tolerant Backend ETL Pipeline & Workforce Analytics Dashboard
* Engineered a production-grade Python ETL pipeline ingesting 1,000+ employee records from external REST APIs through automated format detection and schema normalization, eliminating manual ingestion.
* Improved pipeline fault tolerance by implementing a retry decorator with three-attempt exponential backoff and SSL-verified session management, reducing transient API failure impact to 0%.
<details>
<summary><b>View Technical Implementation Details</b></summary>

* Accelerated data normalization throughput by optimizing Pandas transformation chains using vectorized operations and memory-efficient chunked I/O.
* Established reliability through 20+ automated Pytest unit tests mocking network latency, file corruption, and schema mismatches.
* Extended the system with Power BI-integrated dashboards to surface real-time workforce analytics for cross-functional stakeholders.
* **Tech:** Python, Pandas, REST APIs, Pytest, ETL, Power BI, Exponential Backoff.
</details>

---

### Quantitative Finance & Optimization

#### Option Pricing & Sensitivity Analysis Suite
Quantitative Finance Tool | [New Project]
* Implemented a quantitative finance suite featuring an analytical Black-Scholes-Merton pricing engine and a Geometric Brownian Motion Monte Carlo simulator with discounted expected payoff and 95% confidence intervals.
* Designed a dual-method Implied Volatility Solver using Newton-Raphson with analytical Vega gradient and Bisection fallback for convergence robustness.
<details>
<summary><b>View Technical Implementation Details</b></summary>

* Extended the suite with a multi-leg Option Strategy Payoff Visualizer computing portfolio Greeks (Delta, Gamma, Theta, Vega, Rho) as weighted linear combinations across legs.
* Enabled real-time sensitivity analysis of complex option strategies (e.g., spreads, straddles, iron condors).
* **Tech:** Python, NumPy, SciPy, Streamlit.
</details>

---

#### Reinforcement Learning-Based Traffic Signal Optimization
Adaptive Deep RL Agent | [GitHub Repository](https://github.com/PSaanviBhat/Reinforcement-Learning-Intelligent-Traffic-Light-Controller)
* Trained a Proximal Policy Optimization (PPO)-based deep RL agent in a custom Gymnasium environment to minimize vehicle wait times dynamically under variable traffic loads.
* Engineered custom reward shaping functions balancing waiting time, congestion, and emergency vehicle prioritization.
<details>
<summary><b>View Technical Implementation Details</b></summary>

* Implemented learning-rate annealing for stable generalization to unseen traffic distributions.
* Demonstrated adaptability to multi-intersection scenarios.
* **Tech:** Gymnasium, Proximal Policy Optimization (PPO), Stable Baselines3, Custom Simulation Environment.
</details>

---

### Full Stack Web & Internet of Things (IoT)

#### Civic-Spark: Gamified Civic Engagement Platform for Bengaluru
Mobile-First Web Platform | [Live App](https://civic-spark-nine.vercel.app) | [GitHub Repository](https://github.com/PSaanviBhat/civic-spark)
* Architected a mobile-first web platform with modular React 18 + TypeScript components; integrated real-time geolocation mapping (OpenStreetMap) with status-based visualization for civic issue tracking.
* Engineered a custom priority ranking algorithm: `(Upvotes × Trust Score) + Time Decay + Category Weight` for data-driven issue prioritization.
<details>
<summary><b>View Technical Implementation Details</b></summary>

* Implemented XP/badge gamification with dynamic leaderboard state management and optimized API caching via Vite.
* Implemented a trust & verification system featuring photo evidence, GPS timestamping, and spam prevention.
* **Tech:** React 18, TypeScript, Vite, Tailwind CSS, Framer Motion, React Leaflet, Radix UI.
</details>

---



## GitHub Statistics

<div align="center">

| **Core Developer Metrics** | **Streaks & Language Breakdown** |
| :---: | :---: |
| ![GitHub Stats](https://github-readme-stats.vercel.app/api?username=PSaanviBhat&show_icons=true&theme=transparent&hide_border=true&rank_icon=github) | ![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=PSaanviBhat&theme=transparent&hide_border=true) <br><br> [![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=PSaanviBhat&layout=compact&theme=transparent&hide_border=true)](https://github.com/PSaanviBhat) |

</div>

---

## Research Interests & Focus

* **Explainable AI (XAI)** – Restoring interpretability in deep black-box models.
* **Quantitative Machine Learning** – Appling statistical modeling and ML to financial markets and telemetry data.
* **Reinforcement Learning** – Sequential decision-making, game theory, and adaptive control systems.
* **Intelligent Edge Systems** – Deploying low-latency ML and cryptographic verification to edge nodes/IoT devices.

---

## Open to Collaboration

I am keen to collaborate on **AI research, open-source ML systems, and quantitative modeling projects**. If you are building in the ML/AI, Quant, or Decentralized Systems spaces, let's connect!

<div align="center">

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:psaanvibhat@outlook.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/psaanvi)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PSaanviBhat)

*Last updated: July 2026*

</div>
