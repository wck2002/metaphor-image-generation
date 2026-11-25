# 隐喻图像生成

视觉隐喻（Visual Metaphor）图像**生成、理解与检索**方向的文献库。收录 40 篇论文的结构化笔记（含 CCF 2026 等级、发表渠道、研究任务与可借鉴点），其中 33 篇附本地 PDF。

整理时间：2026 年 11 月。近两年窗口按 2024-11-19 至 2026-11-19 计算。

## 快速导航

| 文件 | 内容 |
| --- | --- |
| [000 视觉隐喻文献总览](000%20视觉隐喻文献总览.md) | 40 篇逐篇摘要、研究内容、与课题的关系、原文链接 |
| [000 推荐阅读顺序](000%20推荐阅读顺序.md) | 按 2026 → 2025 → 2024 的 40 篇阅读路线，标注每篇该看什么 |
| [000 PDF 下载清单](000%20PDF%20下载清单.md) | 缺失 PDF 的补齐清单与获取途径 |

时间有限时，先读 **001 → 002 → 032 → 030**：用 001、002 对比"生成前规划"与"生成后修订"，再用 032、030 判断生成图到底错在喻体角色、跨域关系还是构图。

## 按研究任务定位

- **隐喻文生图**：001 从源域/目标域映射构造提示，002 用视觉语言模型反馈修订，030 细分生成图的结构与语义保真度。037 展示扩散过程中的注意力绑定，038 提供常用数据来源。
- **参考图驱动生成**：028 将参考图的隐喻逻辑迁移给新主体。003、004 适合对比信息图构思与视觉概念融合流程。
- **隐喻图文检索与非字面排序**：005 含隐喻可视化的零样本图文检索实验，006 含习语义与字面义的图像排序。036 是直接相关的早期检索基准，039 提供面向构思的素材探索接口。023–027 提供组合图像检索基线与评测设计。
- **视觉理解与生成评价**：007 适合中英广告与跨文化问题，008 评估图像描述与问答，010 用解释式视觉蕴含检查非字面含义，013 关注同图多解。

## 文献索引

| 编号 | 论文 | 发表渠道 | 任务 | CCF 2026 |
| --- | --- | --- | --- | --- |
| 001 | Conceptual Metaphor Theory-Inspired Framework for Metaphorical Image Generation | 2026 · Findings of ACL | 生成 | 不计入（Findings） |
| 002 | Critiquing and Refining Visual Elaborations for Figurative Language Illustrations | 2026 · Findings of ACL | 生成 | 不计入（Findings） |
| 003 | Unpacking Visual Metaphors in Infographics: A Design Space | 2026 · ACM CHI | 生成与视觉设计 | A 会议 |
| 004 | Creative Blends of Visual Concepts | 2025 · ACM CHI | 生成与交互设计 | A 会议 |
| 005 | Mining Contextualized Visual Associations from Images for Creativity Understanding | 2025 · INLG | 图文检索 | 目录未列 |
| 006 | SemEval-2025 Task 1: AdMIRe | 2025 · SemEval | 非字面图像排序 | 目录未列 |
| 007 | Cultural Bias Matters: Cross-Cultural Benchmark for Multimodal Metaphors | 2025 · ACL | 跨文化视觉理解 | A 会议 |
| 008 | Looking Beyond the Pixels: Evaluating Visual Metaphor Understanding in VLMs | 2025 · Findings of EMNLP | 视觉理解与评估 | 不计入（Findings） |
| 009 | Multimodal metaphor understanding and generation in MLLMs | 2026 · Pattern Recognition | 理解与生成 | B 期刊 |
| 010 | Understanding Figurative Meaning through Explainable Visual Entailment | 2025 · NAACL | 视觉理解与评估 | B 会议 |
| 011 | Vibe Spaces for Creatively Connecting and Expressing Visual Concepts | 2026 · CVPR | 概念融合 | A 会议 |
| 012 | ImaRA: Imaginative Frame Augmented Method for Low-Resource Metaphor Detection | 2025 · Findings of NAACL | 检测与解释 | 不计入（Findings） |
| 013 | Can MLLMs understand visual metaphors? Multi-perspective evaluation | 2026 · Expert Systems with Applications | 视觉理解与多义性 | C 期刊 |
| 014 | The Language of Infographics: Conceptual Metaphor in Scientific Storytelling | 2025 卷期 · IEEE TVCG | 视觉设计 | A 期刊 |
| 015 | T2I-ReasonBench: Benchmarking Reasoning-Informed Text-to-Image Generation | 2026 · Findings of ACL | 非字面生成评估 | 不计入（Findings） |
| 016 | R2I-Bench: Benchmarking Reasoning-Driven Text-to-Image Generation | 2025 · EMNLP | 生成评估 | B 会议 |
| 017 | A Computational Approach to Visual Metonymy | 2026 · EACL | 视觉转喻与评估 | 目录未列 |
| 018 | Reasoning Beyond Literal: Cross-style Multimodal Reasoning | 2026 · Findings of EACL | 非字面理解 | 不计入（Findings） |
| 019 | M2Metaphor: Multi-modal Fusion and Hierarchical Contrastive Learning | 2026 · Expert Systems with Applications | 多模态隐喻识别 | C 期刊 |
| 020 | Visual Metaphor Advertisements: Human-made vs AI-generated Images | 2025 · International Journal of Advertising | 广告隐喻与人工评价 | 目录未列 |
| 021 | Metaphor and multisensoriality in print advertising | 2026 · Language and Cognition | 跨感官隐喻 | 目录未列 |
| 022 | Visual Congruency and Brand Attitudes | 2026 · Journal of Advertising Research | 广告隐喻与人工评价 | 目录未列 |
| 023 | Generative Zero-Shot Composed Image Retrieval | 2025 · CVPR | 可迁移检索方法 | A 会议 |
| 024 | PinPoint: Evaluation of Composed Image Retrieval | 2026 · CVPR | 可迁移检索基准 | A 会议 |
| 025 | WISER: Training-Free Zero-Shot Composed Image Retrieval | 2026 · CVPR | 可迁移检索方法 | A 会议 |
| 026 | A Comprehensive Survey on Composed Image Retrieval | 2026 · ACM TOIS | 检索综述 | A 期刊 |
| 027 | LLM-Enhanced Composed Image Retrieval | 2025 · ACM TOIS | 可迁移检索方法 | A 期刊 |
| 028 | Beyond Pixels: Visual Metaphor Transfer via Schema-Driven Agentic Reasoning | 2026 · SIGGRAPH Asia（作者报告） | 隐喻迁移 | 待核 |
| 029 | The Mind's Eye: Multi-Faceted Reward for Visual Metaphor Generation | 2025 · NeurIPS GenProCC Workshop | 生成与奖励 | 不计入（Workshop） |
| 030 | Blending Concepts: Benchmarking Visual Metaphor Generation in T2I | 2026 · arXiv 预印本 | 生成基准 | 预印本 |
| 031 | MetaphorStar: End-to-End Visual Reinforcement Learning | 2026 · arXiv 预印本 | 视觉理解与推理 | 预印本 |
| 032 | Presence Is Not Faithfulness: Figurative Vehicle Intrusion in T2I | 2026 · arXiv 预印本 | 生成失效与评价 | 预印本 |
| 033 | M³R-Bench: Evidence-Grounded Multimodal Metaphor Understanding | 2026 · arXiv 预印本 | 证据引导理解 | 预印本 |
| 034 | PRISM: Category-Theoretic Framework for Multimodal Analogies | 2026 · arXiv 预印本 | 类比与生成 | 预印本 |
| 035 | Simile Understanding in Text-to-Image Models | 2026 · arXiv 预印本 | 明喻与生成评估 | 预印本 |
| 036 | MetaCLUE: Towards Comprehensive Visual Metaphors Research | 2023 · CVPR（窗口外） | 视觉隐喻基础与检索 | A 会议 |
| 037 | GOME: Grounding-based Metaphor Binding for Figurative Language Illustration | 2024 · EMNLP（窗口外） | 生成基础 | B 会议 |
| 038 | I Spy a Metaphor: LLMs and Diffusion Models Co-Create Visual Metaphors | 2023 · Findings of ACL（窗口外） | 生成基础与数据 | 不计入 |
| 039 | MetaMap: Multi-dimensional Example-based Exploration | 2021 · CHI（窗口外） | 素材检索与构思 | A 会议 |
| 040 | M3UCD | 2026 · AAAI | 多模态隐喻理解与评估 | A 会议 |

## 文件命名

`NNN 简称.md`（笔记）/ `NNN 论文标题.pdf`（原文），两处编号一一对应，可按序号在文件夹内定位。编号不代表优先级，阅读顺序见「000 推荐阅读顺序」。

## 声明

PDF 仅用于个人学术阅读与研究，版权归原作者及出版方所有。如需引用或再分发，请以原文正式出版版本为准。
