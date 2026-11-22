# Hi, I'm Jan 👋

Computer Engineering student at **Universitat Politècnica de Catalunya (UPC)** focused on **on-device machine learning and high-performance software systems**.

Currently working in **Machine Learning research at UPC** and preparing for an exchange semester at **Université Paris-Saclay**. Previously worked in **Software Engineering R&D at SEAT S.A.**

## Selected Work

### [Math on the Edge: an offline LLM on an Arduino UNO Q](https://github.com/jan-lozano-dev/math-slm-arduino-uno-q)
Built for the **Qualcomm "Math on the Edge" challenge** at Datathon FME 2026 (UPC). A 4-bit quantised 1.5B-parameter model (Qwen2.5-Coder, **llama.cpp**) runs entirely on a 4-core Cortex-A53 board with 4 GB RAM and no network, under a 60 s per-problem limit.

Instead of asking the model to pick a letter, it writes a short Python program that runs in a sandbox (stdlib only, CPU, memory and time limits) and is matched to the answer options: **23% → 46%** on the organisers' practice set. Includes pinned board setup, a reproducible evaluation harness and an error analysis by language, level and figure.

### [C++ Order Book](https://github.com/jan-lozano-dev/cpp-orderbook)
C++20 matching engine implementing price-time priority, limit/market orders, GTC/IOC/FOK execution, partial fills, cancellation and order amendments.

Designed around ordered price levels, FIFO queues and indexed order lookup, with correctness-focused tests and CMake builds.

### [DevFlight: observability for AI agents on RawTree](https://github.com/jan-lozano-dev/devflight-rawtree) 🏆
**Winner of the Tinybird side challenge** ("Best agentic use of RawTree"), Datathon FME 2026.

Telemetry platform for AI coding agents: OTLP ingestion, a durable local outbox, a FastAPI backend and an AI analyst over RawTree. Python and React, 85 automated tests.

### [Stacked GBM — Bankruptcy Prediction](https://github.com/jan-lozano-dev/Stacked-GBM)
Reproducible stacking pipeline for imbalanced tabular classification using **CatBoost, LightGBM and XGBoost**.

Uses stratified cross-validation and out-of-fold predictions, with a CatBoost meta-learner, automated tests and CI.

## Technologies

**Languages:** C++, Python  
**Edge / Systems:** llama.cpp, GGUF quantisation, Linux, systemd, CMake  
**ML/Data:** PyTorch, scikit-learn, CatBoost, LightGBM, XGBoost, NumPy, pandas  
**Engineering:** Git, CI, automated testing

---

Seeking **Software Engineering and Machine Learning Engineering internships for Summer 2027**, especially in edge AI and systems.

📫 jan.lozano.dev@gmail.com
