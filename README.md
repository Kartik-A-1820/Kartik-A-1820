# Hi, I'm Kartik Anagawadi

**AI/ML Engineer · LLM systems · Computer vision · Retrieval · Efficient inference**

I build machine-learning systems from data preparation and modeling through evaluation, APIs, and deployment. My professional experience began in **March 2023**, with work in image-based freshness assessment, inference optimization, and applied AI tooling.

My public projects focus on a practical question: **how can useful AI systems be made measurable, reliable, and affordable to run?** The repositories below include implementation details, experiment results, and the limits of the evidence.

[LinkedIn](https://www.linkedin.com/in/kartik-anagawadi-4b33a81b6/) · [Email](mailto:anagawadi.kartik@gmail.com)

## Selected engineering work

| Project | Problem and implementation | Evidence to explore |
| --- | --- | --- |
| [**specbench**](https://github.com/Kartik-A-1820/specbench) | Accelerating LLM decoding within a small GPU memory budget: draft/verify decoding, KV-cache rollback, paired benchmarking, and acceptance-cost analysis. | Published sampling speedup **1.321×**, 95% CI **1.235–1.406**, on one GTX 1650 Ti. Includes an EAGLE-style draft-head slowdown and its diagnosis. [Results and conditions](https://github.com/Kartik-A-1820/specbench/blob/main/docs/results.md) |
| [**detektor**](https://github.com/Kartik-A-1820/detektor) | A custom detection/segmentation framework covering dataset checks, training, evaluation, ONNX export, packaging, and an authenticated inference API. | [Tests](https://github.com/Kartik-A-1820/detektor/tree/main/tests), [architecture](https://github.com/Kartik-A-1820/detektor/blob/main/docs/ARCHITECTURE.md), and [benchmarks](https://github.com/Kartik-A-1820/detektor/blob/main/docs/BENCHMARKS.md). Real-image model quality remains an improvement area. |
| [**Qwen-GraphRAG**](https://github.com/Kartik-A-1820/Qwen-GraphRAG) | Local document question answering with Chroma dense retrieval, BM25, Kuzu graph retrieval, reciprocal-rank fusion, and optional reranking. | [Retrieval implementation](https://github.com/Kartik-A-1820/Qwen-GraphRAG/tree/main/backend/retrieval), [tests](https://github.com/Kartik-A-1820/Qwen-GraphRAG/blob/main/tests/test_retrieval.py), and evaluation utilities. No real-corpus quality benchmark is claimed by the profile. |
| [**Snake RL from scratch**](https://github.com/Kartik-A-1820/snake-rl-from-scratch) | Comparing tabular Q-learning, DQN variants, masked PPO, and planning baselines with Python/JavaScript environment parity and a browser demo. | [Play or watch trained agents](https://kartik-a-1820.github.io/snake-rl-from-scratch/). Includes multi-seed ablations where available, separately labeled single-run results, and hardware profiling. |

The measured numbers above describe the published model, hardware, and experiment settings. They are not promises for other environments.

## Tools and experiments you can try

| Repository | What you can explore | Current scope |
| --- | --- | --- |
| [VizGen](https://github.com/Kartik-A-1820/VizGen) | A React/FastAPI image-generation interface with a persistent queue, ComfyUI workflows, and staged model loading. | Local image generation/editing; Windows setup and hardware-specific measurements. |
| [Nano-LLM Studio](https://github.com/Kartik-A-1820/Nano-LLM-studio) | Corpus preparation, tokenizer/model training, validation-based checkpoint selection, and inference in a local workbench. | Experimental small-model training, with CPU regression tests. |
| [ATEAM-NEXT](https://github.com/Kartik-A-1820/ATEAM-NEXT) | A TypeScript/Ink agent terminal with event-driven state, SQLite persistence, and simulated failure scenarios. | In development; simulation is the starting point and provider integration has separate requirements. |
| [Projects-ML](https://github.com/Kartik-A-1820/Projects-ML) | AI engineering and data-science labs with per-project setup, tests, and architecture discussions. | Mixed experiment maturity; [source inventory](https://github.com/Kartik-A-1820/Projects-ML/blob/main/PORTFOLIO_STATUS.md) records incomplete migrations. |

Within Projects-ML, [ContractTrace](https://github.com/Kartik-A-1820/Projects-ML/tree/main/weekly-projects/week-37-contracttrace-agent-transactions) explores idempotent agent-tool transactions, fault injection, and final-state verification. Its reproducible core uses a deterministic planner; a local language-model adapter is optional.

Start with a repository's README to choose a demo or lightweight test path. Bug reports with reproduction steps, documentation improvements, and measured experiments on other hardware are welcome. Contribution steps and project scope belong in each repository.

## Professional focus

- **Applied ML and vision:** image classification, object detection, segmentation, and dataset tooling.
- **LLMs and retrieval:** local RAG, hybrid search, graph-assisted retrieval, PEFT/LoRA, and evaluation.
- **Engineering:** FastAPI/Django integration, Docker, model serving, reproducibility, and observability.
- **Efficiency:** constrained-memory inference, quantization, OpenVINO, and ONNX Runtime.

**Core tools:** Python, SQL, PyTorch, TensorFlow/Keras, scikit-learn, OpenCV, Hugging Face Transformers, LangChain, Chroma, FAISS, Kuzu, React, TypeScript, and AWS.

## Education

**B.E., Electronics & Communication Engineering** — Basaveshwar Engineering College, Karnataka  
2018–2022 · CGPA: 8.6

Certifications: Machine Learning & Deep Learning Masters — iNeuron; Python for Data Science — NPTEL.
