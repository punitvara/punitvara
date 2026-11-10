### Hi, I'm Punit Vara

**Staff ML Engineer at Visa.** I build the infrastructure that trains and serves ML models: GPU clusters, training platforms, and LLM inference. 9+ years across Visa, MoneyView, Levi's and Intel.

I like understanding systems from first principles instead of treating frameworks as black boxes. That started in kernel and driver code and now covers LLM serving and distributed ML.

#### Open source (merged upstream)

| Project | What I shipped |
|---|---|
| **[vLLM Production Stack](https://github.com/vllm-project/production-stack/pull/996)** | Priority-aware request routing for the K8s-native vLLM router. I wrote the design proposal, `PriorityRouter`, CLI flags, tests, docs and live reconfiguration (+679 lines, 9 files). High-priority requests go to the least-loaded engine, and the resolved priority is passed to vLLM's scheduler for preemption. |
| **[Zephyr RTOS](https://github.com/zephyrproject-rtos/zephyr/pulls?q=is%3Apr+author%3Apunitvara+is%3Amerged)** | 50+ merged PRs (2017–18): POSIX APIs (mutex, semaphore), sensor drivers (APDS9960, BMM150) and kernel cleanups. I also migrated the legacy kernel and network test suite to ztest. |
| **[vLLM](https://github.com/vllm-project/vllm/pull/25058)** | Docs fixes. |
| **[spaCy](https://github.com/explosion/spaCy/pull/5355)** | Added Gujarati language support. |
| **[pandas](https://github.com/pandas-dev/pandas/pull/40031)**, **[Kedro](https://github.com/kedro-org/kedro/pull/1178)** | Style and docs fixes. |
| **RTEMS (GSoC 2016)** | I2C drivers for BeagleBone Black. Later a GSoC mentor (2017–18). |

#### Production work (private, so I describe it here)

- **Visa:** AWS and on-prem K8s GPU training platform, Terraform GitOps, Claude-based agents for code review and ML workflows.
- **MoneyView:** first ML hire. Real-time inference at 200K+ requests/day. Latency cut from 1.7s to 400ms (99%). Call-scoring accuracy 33% → 70% with an in-house STT + LLM pipeline.
- **Levi's:** RAG assistant over internal docs (LangChain, FAISS, OpenAI).

#### Focus areas

LLM inference and serving · GPU systems and collectives (NCCL) · Distributed data systems · ML infrastructure and MLOps (Kubernetes, Terraform, SageMaker)

#### Projects

- [PVKeyboardCleaner](https://github.com/punitvara/PVKeyboardCleaner-): macOS utility that blocks all input so you can clean your keyboard (Swift)
- [TensorTonic-Solutions](https://github.com/punitvara/TensorTonic-Solutions): ML-from-scratch problem solutions

#### Elsewhere

[LinkedIn](https://www.linkedin.com/in/punitvara) · [YouTube](https://www.youtube.com/@punitvara.) · [X](https://twitter.com/punitvara)

*Open to Staff/Principal ML infrastructure and LLM systems roles, remote or relocation.*
