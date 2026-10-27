# Hi, I'm Kartik Anagawadi

**AI/ML Engineer | LLM systems · Computer vision · Retrieval · Efficient inference**

Building ML systems professionally since **March 2023**. I work across model development, data pipelines, APIs, and deployment, with a particular interest in making useful AI run on constrained hardware.

My projects explore local GraphRAG, speculative decoding, detection and segmentation, reinforcement learning, and low-VRAM model workflows. I publish implementations, experiments, and limitations so the engineering decisions can be inspected.

[LinkedIn](https://www.linkedin.com/in/kartik-anagawadi-4b33a81b6/) · [Email](mailto:anagawadi.kartik@gmail.com)

## Featured repositories

### [Qwen-GraphRAG](https://github.com/Kartik-A-1820/Qwen-GraphRAG) — Local document intelligence

A local document question-answering platform combining **dense retrieval, BM25, and a Kuzu knowledge graph**.

- Typed entity/relation extraction with a rule-based fallback, reciprocal-rank fusion, and optional reranking.
- FastAPI backend, Streamlit graph/monitoring dashboard, multi-format ingestion, and retrieval evaluation utilities.
- Configurable small-model and 4-bit inference paths for laptop-class hardware.

**Explore:** [Retrieval implementation](https://github.com/Kartik-A-1820/Qwen-GraphRAG/tree/main/backend/retrieval) · [Tests](https://github.com/Kartik-A-1820/Qwen-GraphRAG/blob/main/tests/test_retrieval.py)

### [specbench](https://github.com/Kartik-A-1820/specbench) — Speculative decoding on a 4 GB GPU

An inference experiment with paired benchmarks, correctness tests, KV-cache rollback, and a trained EAGLE-style draft head.

- Published sampling result: **1.321× speedup** with a **95% bootstrap CI of 1.235–1.406**, over 29 scored prompts on a GTX 1650 Ti.
- Reports the negative result too: the trained draft head reached **0.938×**, with diagnosis and limitations.

**Explore:** [Results](https://github.com/Kartik-A-1820/specbench/blob/main/docs/results.md) · [Methodology](https://github.com/Kartik-A-1820/specbench/blob/main/docs/methodology.md) · [Correctness tests](https://github.com/Kartik-A-1820/specbench/tree/main/tests)

### [detektor](https://github.com/Kartik-A-1820/detektor) — Detection and segmentation framework

A lightweight custom model framework covering training, validation, export, serving, and a web console.

- Hardware-aware training, EMA/AMP, ONNX parity checks, reproducible model packaging, and benchmark tooling.
- Serving includes API-key authentication, upload validation, bounded concurrency, readiness checks, and metrics.
- **Current focus:** improving real-image model quality. Published CPU/synthetic benchmarks are labeled separately from real-data accuracy.

**Explore:** [Architecture](https://github.com/Kartik-A-1820/detektor/blob/main/docs/ARCHITECTURE.md) · [Benchmarks](https://github.com/Kartik-A-1820/detektor/blob/main/docs/BENCHMARKS.md) · [Project status](https://github.com/Kartik-A-1820/detektor/blob/main/docs/status/PROJECT_STATUS.md)

### [snake-rl-from-scratch](https://github.com/Kartik-A-1820/snake-rl-from-scratch) — Reinforcement learning with a browser demo

A hands-on comparison of tabular Q-learning, DQN variants, masked PPO, and a Hamiltonian planning baseline.

- Includes training code, pretrained agents, browser inference, parity tests, and experiment notes.
- Publishes multi-seed ablations where available, failed approaches, hardware profiling, and checkpoint-selection details.
- Separates learned policies from planning baselines and identifies single-seed results.

**Explore:** [Browser demo](https://kartik-a-1820.github.io/snake-rl-from-scratch/) · [Training and evaluation code](https://github.com/Kartik-A-1820/snake-rl-from-scratch/tree/main/python)

## More tools and ongoing work

| Repository | What it explores | Scope |
| --- | --- | --- |
| [VizGen](https://github.com/Kartik-A-1820/VizGen) | Local image generation/editing through React, FastAPI, a SQLite queue, and ComfyUI; staged model loading for low VRAM | Windows/local workflow with published hardware-specific benchmarks |
| [Nano-LLM Studio](https://github.com/Kartik-A-1820/Nano-LLM-studio) | Small language-model training: corpus collection, tokenizer preparation, architecture selection, training, and checkpoint inference | Local experimental workbench |
| [ATEAM-NEXT](https://github.com/Kartik-A-1820/ATEAM-NEXT) | TypeScript/Ink agent workspace with event-driven state, persistence, provider adapters, and permission-policy components | In development; simulation and live integration status are documented in the roadmap |

## Engineering labs

[**Projects-ML**](https://github.com/Kartik-A-1820/Projects-ML) contains my AI/ML engineering and data-science labs, alongside earlier notebooks.

- [Weekly AI/ML projects](https://github.com/Kartik-A-1820/Projects-ML/tree/main/weekly-projects) — implementations, tests, and architecture discussions.
- [Data-science labs](https://github.com/Kartik-A-1820/Projects-ML/tree/main/data-science-labs) — calibration, uncertainty, causal uplift, survival analysis, and other experiments.
- [ContractTrace: verified agent tool transactions](https://github.com/Kartik-A-1820/Projects-ML/tree/main/weekly-projects/week-37-contracttrace-agent-transactions) — strict action contracts, SQLite transactions, idempotency, fault injection, and final-state verification. The core uses a deterministic planner; local SLM integration is optional.

Lab scope varies: synthetic smoke tests, measured model experiments, and proposed production extensions are distinguished in each project's documentation.

## Technical toolkit

| Area | Technologies |
| --- | --- |
| Languages and APIs | Python, SQL, TypeScript, FastAPI, Django |
| ML and vision | PyTorch, TensorFlow/Keras, scikit-learn, OpenCV, YOLO, Segment Anything |
| LLMs and retrieval | Hugging Face Transformers, PEFT/LoRA, LangChain, Qwen, Gemma, Chroma, FAISS, BM25, Kuzu |
| Inference and deployment | Quantization, OpenVINO, ONNX Runtime, Docker, Streamlit, React, AWS |

## Professional background

- ML pipelines for seafood freshness classification and image-based inference.
- Intel OpenVINO inference optimization and model deployment.
- Dataset annotation, segmentation tooling, and multimodal retrieval.
- Backend integration using FastAPI/Django, Docker, and cloud infrastructure.

## Education and certifications

**B.E., Electronics & Communication Engineering** — Basaveshwar Engineering College, Karnataka  
2018–2022 · CGPA: 8.6

- Machine Learning & Deep Learning Masters — iNeuron
- Python for Data Science — NPTEL

---

*Profile refreshed: October 2026. Benchmark figures describe the published repository experiments and their stated hardware/scope.*
