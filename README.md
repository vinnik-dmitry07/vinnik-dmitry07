# Dmitry Vinnik

**Machine Learning Research Engineer**

I build ML experiments and the systems around them: training code, evaluation harnesses, and tools for inspecting results. My recent work focuses on LLM agents that search for better programs, and how to decide which changes are worth keeping.

## Agents, search, and evaluation

### [Autoresearch](https://github.com/vinnik-dmitry07/autoresearch) · Learning when to remove a rule

An LLM evolves a memoryless Durak strategy against fixed opponents in a C++ simulator. In a recorded June 2026 run, its score against a card-counting baseline rose from **0.645 to 0.689 points per game**, evaluated over 5 million deals played from both seats (win = 1, draw = ½).

Part of the gain came from **removing two heuristics**: a new defense rule had made them harmful. The repository includes the search loop, ablations, evaluation gates, and a browser interface for playing against the strategy. [Experiment and results →](https://github.com/vinnik-dmitry07/autoresearch#results)

### [ASHES-ML](https://github.com/vinnik-dmitry07/ashes-ml) · Specifying what an evolving agent may change

An executable reference for an agent-harness language, with separate evaluation and admission, explicit budgets, and checks that candidate programs preserve required guarantees. The repository contains the specification, Python implementation, mutation checks, and audit reports. Its current reference covers bounded experiments; the documented limits are part of the contract.

### [Super-convergence revisited](https://github.com/vinnik-dmitry07/full-batch) · Checking which training methods help

ResNet-18 experiments on CIFAR-10 comparing optimizers, learning-rate schedules, gradient accumulation, stochastic weight averaging, and sharpness-aware minimization. In the recorded comparisons, SAM improved validation accuracy consistently; SWA added little. Training code, CSV results, and plotting scripts make the comparisons inspectable.

## Tools for reading and reasoning

**[Favorite papers](https://github.com/vinnik-dmitry07/favorite-papers)** connects my reading list through citations extracted from the papers. The [interactive map](https://vinnik-dmitry07.github.io/favorite-papers/) lets you follow connections across topics and publication dates. Automated reviewer scores link to their underlying reviews, with disagreement and limitations documented.

**[Consensus AI](https://github.com/vinnik-dmitry07/consensus-ai)** makes the steps behind a council answer visible: individual responses, anonymous peer rankings, disputed claims, a red-team pass, and final synthesis. Built on Karpathy's LLM Council, with review controls, streaming progress, and cost estimates.

## Earlier experiments

<details>
<summary>Computer vision, neural fields, retrieval, and language models</summary>

- [Neural fields](https://github.com/vinnik-dmitry07/sdf): meta-learning for ShapeNet signed distance fields and hypernetworks for MNIST.
- [Furniture generation](https://github.com/vinnik-dmitry07/furniture-generation): Stable Diffusion 2.1 fine-tuning with DreamBooth, generated variations, and links to model checkpoints.
- [Webcam hand capture](https://github.com/vinnik-dmitry07/minimal-hand): a Unity and virtual-camera integration of Minimal Hand for motion capture from a single RGB camera.
- [Synthetic-image detection](https://github.com/vinnik-dmitry07/fake-image-detection): a classifier on frozen BEiT-3 features, with a training notebook, report, and predictions.
- [Interaction tracking](https://github.com/vinnik-dmitry07/reid-corona-hackathon): person detection and re-identification with a web interface for prolonged interactions.
- [Doc Bot](https://github.com/vinnik-dmitry07/doc-hack): a symptom-search and specialty-classification prototype comparing BERT and XLM-RoBERTa.
- [PDF question answering](https://github.com/vinnik-dmitry07/llm-odqa): a retrieval notebook using E5 embeddings and MPT-7B-Instruct.
- [Telegram chatbot](https://github.com/vinnik-dmitry07/chatbot): notebooks for turning chat exports into dialogue data and training a transformer with ParlAI.
- [Email-open prediction](https://github.com/vinnik-dmitry07/predict-email-opened): BERT classification experiments with evaluation metrics and a write-up of the approach's limitations.

</details>

## Theses

- [Associative metamemory](https://github.com/vinnik-dmitry07/research/blob/main/masters/thesis_eng.pdf) — master's thesis on associative retrieval.
- [Intellectual trading strategy using reinforcement learning](https://github.com/vinnik-dmitry07/research/blob/main/bachelors/thesis_eng.pdf) — bachelor's thesis.

[English and Ukrainian versions, figures, and related contributions →](https://github.com/vinnik-dmitry07/research)
