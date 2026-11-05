# Hi, I'm Ignacy Małachowski

Second-year **Artificial Intelligence and Cognitive Science** student at the University of Warsaw.
I build and evaluate LLM agents, and I care about measuring AI systems honestly before reporting results.

## Featured project

### [promptloop](https://github.com/imalachowsk-creator/prompt-loop) – continuous prompt improvement for an agentic docs assistant

A RAG agent answers Python documentation questions. The framework evaluates it, turns failures and
human feedback into reusable rules, lets an optimizer LLM rewrite the agent's prompt, and **accepts a
new prompt only if the score improves**.

| | Result |
|---|---|
| Score on train questions | 0.544 → 0.744 |
| Score on held-out test questions | **0.767** (the prompt generalizes, not memorizes) |
| Hallucinated answers to out-of-scope questions | 100% → **0%** |

What I learned along the way: a train/test split exposed an earlier, inflated score of 0.938, and
reading the failures showed the optimizer had never seen the hallucination cases – a sampling bug I fixed.

`Python` · `Ollama (Llama 3.2, Qwen 2.5)` · `BM25 RAG from scratch` · `LLM-as-judge` · `pytest` · `GitHub Actions CI`

## Other projects

- **[gpu-bench](https://github.com/imalachowsk-creator/gpu-bench)** – honest CPU vs GPU benchmarking: NumPy vs PyTorch CPU vs CUDA on an NVIDIA Tesla T4, 104 verified configurations; GPU matmul ~29× (FP32) and ~158× (FP16) faster at n = 4096.

## Currently

- Studying Machine Learning & Neural Networks, NLP, and EEG / eye-tracking data analysis
- Project Manager at ICAN Institute
- Learning C/C++ and CUDA basics

## Tools

Python · PyTorch · NumPy · pandas · Git · GitHub Actions · Ollama · TypeScript / Next.js · SQL basics

## Contact

[LinkedIn](https://www.linkedin.com/in/ignacy-ma%C5%82achowski-8217b8404/) · ignacymalachowski03@gmail.com
