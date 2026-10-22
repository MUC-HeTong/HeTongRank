# HeTongRank

**HeTongRank: Open Leaderboards for Multilingual, Multimodal, and Low-Resource Foundation Models**

**和同模型能力排行榜**

*和而不同，智联万语。 — Harmony in Diversity, Intelligence Across Languages.*

[中文说明](./README_zh.md) · [HeTong Models](https://github.com/MUC-HeTong/HeTong) · [HeTongEval](https://github.com/MUC-HeTong/HeTongEval) · [HeTongBench](https://github.com/MUC-HeTong/HeTongBench)

> **Project status: Planning / Repository scaffolding.** No verified model rankings, evaluation results, leaderboard website, or ranking code have been published.

## Overview

HeTongRank is the planned leaderboard and model capability monitoring component of the HeTong open-source ecosystem. It aims to support transparent, reproducible comparison of multilingual, multimodal, and low-resource language foundation models.

- **HeTongBench:** Benchmark definitions and dataset documentation.
- **HeTongEval:** Evaluation execution, diagnostics, and monitoring.
- **HeTongRank:** Presentation and historical tracking of verified evaluation results.
- **HeTongReport:** Future analysis and evaluation reports.

The repositories are related but have distinct responsibilities.

## Planned Leaderboard Tracks

| Track | Intended scope | Status |
| --- | --- | --- |
| **HeTongRank-LLM** | Multilingual text foundation models | Planned |
| **HeTongRank-MLLM** | Multimodal language models | Planned |
| **HeTongRank-ASR** | Multilingual automatic speech recognition | Planned |
| **HeTongRank-NMT** | Neural machine translation | Planned |
| **HeTongRank-TTS** | Multilingual speech synthesis | Planned |
| **HeTongRank-Agent** | Agent capability evaluation | Planned |
| **HeTongRank-LowResource** | Low-resource language model capabilities | Planned |

### HeTongRank-LowResource

**HeTongRank-LowResource** is a priority research direction, intended to track model capabilities on Tibetan, Mongolian, Uyghur, and other underrepresented languages where evaluation resources and review processes are available.

Actual coverage will depend on released benchmarks and validated evaluation methods. Different languages, scripts, varieties, and task metrics should remain clearly identified; an overall score will not be assumed by default.

## Evaluation Transparency (Planned)

Future published entries should identify the model and version, language and language variety, task, benchmark version, evaluation protocol, metric and score direction, evaluation date, and reproducibility information. Submission rules, result verification, licensing, and benchmark contamination checks will be defined before accepting public submissions.

## Repository Structure

| Path | Planned purpose |
| --- | --- |
| `README.md`, `README_zh.md` | Project overviews |
| `docs/` | Leaderboard methodology, policies, and documentation |
| `leaderboards/` | Planned leaderboard track directories |
| `submissions/` | Future submission guidelines and records |
| `reports/` | Future verified evaluation summaries |
| `assets/` | Future presentation assets |

All directories currently contain placeholders only. **No leaderboard datasets, rankings, evaluation results, or executable code are included.**

## Roadmap

- [x] Initialize the project documentation and directory layout
- [ ] Publish leaderboard rules and reporting standards
- [ ] Establish compatible benchmark and metric versions with HeTongBench
- [ ] Verify evaluation pipelines and published results with HeTongEval
- [ ] Open the first validated leaderboard tracks
- [ ] Add longitudinal monitoring and model capability reports

## Related Projects

- [HeTong Model Family](https://github.com/MUC-HeTong/HeTong)
- [HeTongEval — Evaluation Platform](https://github.com/MUC-HeTong/HeTongEval)
- [HeTongBench — Benchmark Suite](https://github.com/MUC-HeTong/HeTongBench)

---

**HeTongRank — 和而不同，智联万语。**
