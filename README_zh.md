# HeTongRank | 和同模型能力排行榜

**HeTongRank: Open Leaderboards for Multilingual, Multimodal, and Low-Resource Foundation Models**

**和同多语种、多模态与低资源语言基础模型能力排行榜**

**和而不同，智联万语。**

[English README](./README.md) · [HeTong 模型家族](https://github.com/MUC-HeTong/HeTong) · [HeTongEval 评测平台](https://github.com/MUC-HeTong/HeTongEval) · [HeTongBench 评测基准](https://github.com/MUC-HeTong/HeTongBench)

> **项目状态：规划与仓库框架建设阶段。** 尚未发布经过验证的模型排名、评测结果、排行榜网站或相关代码。

## 项目简介

HeTongRank 是 HeTong（和同）开源生态中规划的模型能力排行榜与动态监测展示项目，旨在逐步建设透明、可复现、可比较的多语种、多模态及低资源语言基础模型能力评价体系。

各项目的定位：

- **HeTongBench：** 评测基准、数据规范与任务定义；
- **HeTongEval：** 统一评测、能力诊断与动态监测；
- **HeTongRank：** 经核验评测结果的展示、对比与历史跟踪；
- **HeTongReport：** 未来的评测分析报告。

## 规划中的排行榜

| 排行榜 | 目标方向 | 状态 |
| --- | --- | --- |
| **HeTongRank-LLM** | 多语种文本大模型 | 规划中 |
| **HeTongRank-MLLM** | 多模态语言模型 | 规划中 |
| **HeTongRank-ASR** | 多语种自动语音识别 | 规划中 |
| **HeTongRank-NMT** | 神经机器翻译 | 规划中 |
| **HeTongRank-TTS** | 多语种语音合成 | 规划中 |
| **HeTongRank-Agent** | 智能体能力评测 | 规划中 |
| **HeTongRank-LowResource** | 低资源语言模型能力 | 规划中 |

### 核心特色：HeTongRank-LowResource

HeTongRank-LowResource 拟作为重点建设方向，持续跟踪国内外模型在藏文、蒙古文、维吾尔文及其他低资源语言上的能力表现。

具体支持的语言、文字体系、语言变体与任务，以未来公开的基准资源和经过审查的评测方法为准。不同任务应明确指标和适用范围，不默认将不具可比性的分数汇总成单一排名。

## 未来排行榜的透明性原则

正式发布结果时，原则上应注明：

- 模型名称、版本及可核验的来源；
- 语言、文字体系、方言或语言变体；
- 评测任务、基准及版本；
- 指标定义、分数及指标方向（越高越好或越低越好）；
- 评测日期、协议、参数设置及复现信息；
- 结果审核、数据许可和基准污染检查情况。

公开提交规则及审核流程会在开放榜单前单独公布。

## 仓库结构

| 路径 | 预留用途 |
| --- | --- |
| `README.md`、`README_zh.md` | 中英文介绍 |
| `docs/` | 排行榜方法学、规则与说明 |
| `leaderboards/` | 规划中的各类榜单目录 |
| `submissions/` | 未来提交规范与记录 |
| `reports/` | 未来经过核验的评测报告 |
| `assets/` | 未来网页或展示素材 |

上述目录目前只含占位文件。**不包含真实评测结果、排行榜数据、模型代码或可执行程序。**

## 项目规划

- [x] 初始化中英文项目说明与目录结构
- [ ] 发布模型排名规则及结果报告标准
- [ ] 与 HeTongBench 明确基准和指标版本
- [ ] 与 HeTongEval 对接可核验的评测流程
- [ ] 开放首批经过验证的能力排行榜
- [ ] 建立历史趋势监测及能力分析报告

## 相关项目

- [HeTong Model Family](https://github.com/MUC-HeTong/HeTong)
- [HeTongEval](https://github.com/MUC-HeTong/HeTongEval)
- [HeTongBench](https://github.com/MUC-HeTong/HeTongBench)

---

**HeTongRank — 和而不同，智联万语。**
