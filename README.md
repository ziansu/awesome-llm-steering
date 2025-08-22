# Awesome LLM Steering
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ![GitHub stars](https://img.shields.io/github/stars/ziansu/awesome-llm-steering?color=yellow) ![GitHub forks](https://img.shields.io/github/forks/ziansu/awesome-llm-steering?color=9cf) [![GitHub license](https://img.shields.io/github/license/ziansu/awesome-llm-steering)](https://github.com/ziansu/awesome-llm-steering/blob/main/LICENSE)


This list focuses on the *steering of large language models*, which generally refers to techniques to influence and control the model's behavior without retraining it from scratch. There's a bias towards covering more about techniques that leverages LLM internals and interpretability for inference time intervention, as opposed to system prompts or agentic workflow style control.

Some papers in this list do not explicitly mention steering but are intrinsically connected to it, such as certain knowledge editing techniques.

## Table of Contents

- [Papers](#papers)
- [Blogs & Posts](#blogs--posts)
- [Videos](#videos)
- [Other LLM Interpretability Repositories](#other-llm-interpretability-repositories)


## Papers

- [arxiv, Anthropic] [Persona Vectors: Monitoring and Controlling Character Traits in Language Models](https://arxiv.org/abs/2507.21509)

- [arxiv] [KV Cache Steering for Inducing Reasoning in Small Language Models](https://arxiv.org/abs/2507.08799)

- [EMNLP 2025] [AutoSteer: Automating Steering for Safe Multimodal Large Language Models](https://arxiv.org/abs/2507.13255)

- [EMNLP 2025] [Locate-then-Merge: Neuron-Level Parameter Fusion for
 Mitigating Catastrophic Forgetting in Multimodal LLMs](https://arxiv.org/abs/2505.16703)

- [COLM 2025] [μKE: Matryoshka Unstructured Knowledge Editing of Large Language Models](https://arxiv.org/abs/2504.01196)

- [COLM 2025] [One-shot Optimized Steering Vectors Mediate Safety-relevant Behaviors in LLMs](https://arxiv.org/abs/2502.18862)

- [ICML 2025] [AxBENCH: Steering LLMs? Even Simple Baselines Outperform Sparse Autoencoders](https://arxiv.org/abs/2501.17148)

- [NAACL 2025] [Steering Knowledge Selection Behaviours in LLMs via SAE-Based Representation Engineering](https://arxiv.org/abs/2410.15999)

- [ICLR 2025] [NNsight and NDIF: Democratizing Access to Open-Weight Foundation Model Internals](https://arxiv.org/abs/2407.14561)

- [ICLR 2025] [Improving Instruction-Following in Language Models through Activation Steering](https://openreview.net/forum?id=wozhdnRCtw)


- [NeurIPS 2024] [Stealth edits to large language models](https://proceedings.neurips.cc/paper_files/paper/2024/hash/5c8168a8eca2eb23f6b1f5019371043e-Abstract-Conference.html)

- [COLM 2024] [Locating and Editing Factual Associations in Mamba](https://arxiv.org/abs/2404.03646)

- [EMNLP 2024] [Backward Lens: Projecting Language Model Gradients into the Vocabulary Space](https://arxiv.org/abs/2402.12865)

- [ACL 2024] [Understanding and Patching Compositional Reasoning in LLMs](https://arxiv.org/abs/2402.14328)

- [ACL 2024] [Steering Llama 2 via Contrastive Activation Addition](https://arxiv.org/abs/2312.06681)

- [CoRR 2023] [Representation Engineering: A Top-Down Approach to AI Transparency](https://arxiv.org/abs/2310.01405)

- [ICLR 2024] [Towards Best Practices of Activation Patching in Language Models: Metrics and Methods](https://arxiv.org/abs/2309.16042)

- [ICLR 2024] [Function Vectors in Large Language Models](https://arxiv.org/abs/2310.15213)

- [arxiv] [Steering language models with activation engineering](https://arxiv.org/abs/2308.10248)

- [NeurIPS 2023] [Inference-Time Intervention: Eliciting Truthful Answers from a Language Model](https://arxiv.org/abs/2306.03341)

- [EMNLP 2023] [Label Words are Anchors: An Information Flow Perspective for Understanding In-Context Learning](https://arxiv.org/abs/2305.14160)

- [ACL 2024] [Word Embeddings Are Steers for Language Models](https://arxiv.org/abs/2305.12798)

- [ICLR 2023] [Mass-Editing Memory in a Transformer](https://arxiv.org/abs/2210.07229)

- [NeurIPS 2022] [Locating and Editing Factual Associations in GPT](https://arxiv.org/abs/2202.05262)

- [EMNLP 2021] [Transformer Feed-Forward Layers Are Key-Value Memories](https://arxiv.org/abs/2012.14913)

## Blogs & Posts

- [Transformer Circuits Thread](https://transformer-circuits.pub/)
    - [Towards Monosemanticity: Decomposing Language Models With Dictionary Learning](https://transformer-circuits.pub/2023/monosemantic-features)
    - [Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet](https://transformer-circuits.pub/2024/scaling-monosemanticity/index.html)
    - [Circuit Tracing: Revealing Computational Graphs in Language Models](https://transformer-circuits.pub/2025/attribution-graphs/methods.html)
- [Mechanistic Interpretability - Neel Nanda](https://www.neelnanda.io/mechanistic-interpretability)
- [LessWrong](https://www.lesswrong.com/)

## Videos

- [Inside Gemma 3: Modifying the output through activation hacking](https://www.youtube.com/watch?v=JTUsmSHixSc)

## Other LLM Interpretability Repositories

- https://github.com/zepingyu0512/awesome-llm-understanding-mechanism
- https://github.com/ruizheliUOA/Awesome-Interpretability-in-Large-Language-Models
- https://github.com/cooperleong00/Awesome-LLM-Interpretability
- https://github.com/JShollaj/awesome-llm-interpretability
- https://github.com/IAAR-Shanghai/Awesome-Attention-Heads