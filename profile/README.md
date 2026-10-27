<p align="center"><a href="https://ml0x.com"><img src="banner.svg" alt="ml0x. Guardrails around Claude Code agents. Every stage passes a gate or the run stops." width="100%"></a></p>

ml0x puts guardrails around coding agents.
An agent run moves through four stages. Analyze, implement, test and review. Each stage has a gate. If a gate fails, the run stops and says why.
Budgets are capped per run, so an agent cannot spend more than you allowed.

### Pipeline

| Repository | What it does |
| --- | --- |
| [100xagenticdev](https://github.com/theluckystrike/100xagenticdev) | The four-stage pipeline for Claude Code with quality gates and budget caps. |
| [gate-contract-rs](https://github.com/ml0x-com/gate-contract-rs) | Fail-closed gate contracts for staged build pipelines, in Rust. |
| [hermes-flash-kit](https://github.com/ml0x-com/hermes-flash-kit) | Harness, cost control and measurement for an agent on a low-cost model. |
| [claude-code-playbook](https://github.com/ml0x-com/claude-code-playbook) | Templates, prompts and configs for Claude Code in production. MIT. |

### Inference arithmetic

Small libraries that answer one sizing question exactly, with the formula in the code.

| Repository | Language | What it answers |
| --- | --- | --- |
| [kv-cache-size-go](https://github.com/theluckystrike/kv-cache-size-go) | Go | How much memory the KV cache and weights need. GQA aware. |
| [KVCacheEstimator](https://github.com/ml0x-com/KVCacheEstimator) | Swift | The same question from a model's config.json. |
| [lora-plan](https://github.com/ml0x-com/lora-plan) | Python | How many parameters a LoRA trains and how much VRAM it needs. |

### Repositories

| Repository | What it does |
| --- | --- |
| [ml0x.com](https://github.com/ml0x-com/ml0x.com) | Machine Learning Cheat Sheet Generator -- free printable reference cards for CNN, RNN, Transformers, SVM, Decision Trees, and more. Key formulas, hyperparameters, and Python code snippets. Client-side, no sign-up. |
| [kv-cache-size](https://github.com/ml0x-com/kv-cache-size) | Exact KV-cache arithmetic for transformer inference: bytes per token, total cache bytes, and the context length that fits a memory budget. |
| [llmcost-d](https://github.com/ml0x-com/llmcost-d) | Compute per-call and monthly LLM API cost from token counts and per-million-token pricing |
| [lstm-shapecalc](https://github.com/ml0x-com/lstm-shapecalc) | Rust crate lstm-shapecalc |
| [token-estimate](https://github.com/ml0x-com/token-estimate) | Estimate LLM token counts without loading a tokenizer |

### Maintainer

Built and maintained by [Michael Lip](https://github.com/theluckystrike) in Warsaw, Poland.
He also fixes bugs in projects he uses. He has 300+ merged pull requests in 200+ outside repositories, including [urllib3](https://github.com/urllib3/urllib3/pull/5330), [Appium](https://github.com/appium/appium/pull/22911), [Prefect](https://github.com/PrefectHQ/prefect/pull/21916) and [Google Chrome extension samples](https://github.com/GoogleChrome/chrome-extensions-samples/pull/1629).
Need an engineer for your own product or AI agent? Send a written brief at [axdale.com](https://www.axdale.com/?utm_source=github&utm_medium=org&utm_campaign=hire&utm_content=ml0x-com).
