# Hi, I'm Kartik Anagawadi

**AI/ML Engineer · Generative AI · Deep Learning · Computer Vision**

I build machine-learning systems from data preparation and model training through evaluation, inference, and APIs. I have worked professionally in AI/ML since **March 2023**, including image-based freshness assessment and inference optimization.

My public work spans retrieval, language-model adaptation, agent orchestration, generative models, and computer vision. The projects below show both the implementation and the experiments used to assess it.

[LinkedIn](https://www.linkedin.com/in/kartik-anagawadi-4b33a81b6/) · [Email](mailto:anagawadi.kartik@gmail.com)

## Generative AI and agent systems

| Project | What I built | Where to look |
| --- | --- | --- |
| [**Qwen-GraphRAG**](https://github.com/Kartik-A-1820/Qwen-GraphRAG) | Local document Q&A combining dense, BM25, and graph retrieval, with rank fusion and optional reranking. | Retrieval code, API, and evaluation utilities. A real-corpus quality benchmark remains to be established. |
| [**LLM Fine-Tuning**](https://github.com/Kartik-A-1820/LLM-finetune) | A Pythia LoRA training pipeline with response-only loss, disjoint data splits, generation, and held-out code-evaluation tools. | Split manifests, training scripts, and evaluation tests. Historical ROUGE results are documented separately from held-out evaluation. |
| [**AI-AGENT**](https://github.com/Kartik-A-1820/AI-AGENT) | An asynchronous assistant with tool orchestration, persistent memory, Google integrations, and opt-in container execution. | Execution controls, API, and offline tests. Generated-code execution is disabled by default. |
| [**Medical Chatbot**](https://github.com/Kartik-A-1820/medical_chatbot) | An educational medical-document Q&A prototype with PDF retrieval, source references, and browser interfaces. | Retrieval and provider integration. This is an application prototype with no clinical validation. |

## Model training and computer vision

| Project | What I built | Where to look |
| --- | --- | --- |
| [**Conditional Diffusion**](https://github.com/Kartik-A-1820/2025/blob/main/controlled-diffusion.ipynb) | A class-conditioned DDPM for MNIST, including the noise schedule, time-conditioned U-Net, attention, training loop, and reverse sampling. | The training notebook and generated samples. Its conditioning uses digit classes; quantitative image-quality evaluation is still needed. |
| [**detektor**](https://github.com/Kartik-A-1820/detektor) | A detection and segmentation framework covering dataset checks, training, evaluation, ONNX export, and an authenticated inference API. | Architecture, tests, and benchmarks. Real-image model quality remains an improvement area. |
| [**Nano-LLM Studio**](https://github.com/Kartik-A-1820/Nano-LLM-studio) | A local workbench for corpus preparation, tokenizer and small-model training, checkpoint selection, and inference. | Training implementation and CPU regression tests, including checkpoint resume behavior. |

## Inference and experimental engineering

- [**specbench**](https://github.com/Kartik-A-1820/specbench): speculative-decoding implementations and paired benchmarks under a small GPU memory budget. The published sampling result is **1.321× speedup** (95% CI **1.235–1.406**) on one GTX 1650 Ti; the results also document configurations that slowed inference down.
- [**Snake RL from scratch**](https://github.com/Kartik-A-1820/snake-rl-from-scratch): tabular and deep reinforcement learning, masked PPO, planning baselines, environment parity checks, and a [browser demo](https://kartik-a-1820.github.io/snake-rl-from-scratch/).
- [**Projects-ML**](https://github.com/Kartik-A-1820/Projects-ML): AI engineering and data-science labs covering retrieval, model evaluation, uncertainty, causal modeling, and model lifecycle tooling. The source inventory identifies incomplete migrations.

Also: [VizGen](https://github.com/Kartik-A-1820/VizGen), a local image-generation workbench built around ComfyUI; and [ATEAM-NEXT](https://github.com/Kartik-A-1820/ATEAM-NEXT), an agent terminal with event-driven state and SQLite persistence.

## Explore and contribute

Start with a repository's README for its available setup, tests, results, and limitations. Reproduction reports, focused bug fixes, documentation improvements, and measured experiments on other hardware are welcome. For larger changes, open an issue with the problem and proposed approach first.

## Technical focus

- **Models:** PyTorch, TensorFlow/Keras, scikit-learn, Hugging Face Transformers, PEFT/LoRA.
- **Retrieval and vision:** LangChain, Chroma, FAISS, Kuzu, OpenCV.
- **Serving and integration:** Python, SQL, FastAPI, Django, Docker, ONNX Runtime, OpenVINO, React, TypeScript.

## Education

**B.E., Electronics & Communication Engineering** — Basaveshwar Engineering College, Karnataka  
2018–2022 · CGPA: 8.6

Certifications: Machine Learning & Deep Learning Masters — iNeuron; Python for Data Science — NPTEL.
