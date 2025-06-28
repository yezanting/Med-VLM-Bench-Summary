# 🧠 Med-VLM-Bench: A Curated Benchmark Repository for Medical Vision-Language Models

📚 A comprehensive summary of recent benchmarks for evaluating and training Medical Vision-Language Models (Med-VLMs)

---

## 👨‍💻 Contributors

- 🧑‍🔬 **Zanting Ye**  
  Southern Medical University  
  📧 yzt2861252880@gmail.com

- 🧑‍🔬 **Xu Han**  
  Shanghai Jiao Tong University  
  📧 hanxv8826@gmail.com

- 🧑‍🔬 **Xiaolong Niu**  
  Southern Medical University

- 🧑‍🔬 **Zian Wang**  
  Shanghai Jiao Tong University
  
- 🧑‍🔬 **Shengyuan Liu**  
  The Chinese University of Hong Kong   
  📧 liushengyuan@link.cuhk.edu.hk
- 👨‍🏫 **Lijun Lu**  
  Southern Medical University
  


---

## 📊 GitHub Stats

![Stars](https://img.shields.io/github/stars/yezanting/Med-VLM-Bench-Summary?style=social)
![Forks](https://img.shields.io/github/forks/yezanting/Med-VLM-Bench-Summary?style=social)
![License](https://img.shields.io/github/license/yezanting/Med-VLM-Bench-Summary)
![Last Commit](https://img.shields.io/github/last-commit/yezanting/Med-VLM-Bench-Summary)

---

## 🔍 Project Overview

With the continuous advancement of research on Medical Vision-Language Models (Med-VLMs) and their reasoning capabilities, a number of high-quality, publicly available datasets focusing on medical reasoning have been released between March and May 2025. These datasets provide a solid foundation for the development of multimodal medical AI systems.

**Med-VLM-Bench** is a curated, continuously updated repository of the latest and most important datasets for training and evaluating medical LLMs and VLMs. This project focuses on:

- ✅ Reasoning-centric multimodal benchmarks
- 📅 Latest datasets published in Mar–May 2025
- 🧠 Foundational datasets from 2023–2024
- 🔗 Direct access to dataset links or HuggingFace/GitHub repositories

💡 Our knowledge is limited to public sources. We welcome community contributions — feel free to open an issue to share new datasets, and we will update promptly. 

📌Note: The annotation time of the dataset is based on the publication time of the corresponding article.

---

### 📢 News

#### 🌟 Latest Updates
- **2025-06-29**: 🎉 Added new datasets/benchmarks AbdomenAtlas 3.0 (ICCV2025), Derm1M(ICCV2025), MedTVT-R1, , GEMeX(ICCV2025) and HIE-Reasoning(ICML2025). Check it out for detailed information and download links!
- **2025-06-18**: 🎉 Added new datasets/benchmarks Lingshu, ReasonMed. Check it out for detailed information and download links!
- **2025-06-11**: 🎉 Added some recent datasets and benchmarks!
- **2025-06-11**: 🎉 Create our github project!
## 📊 Dataset Summary Table

| Dataset Name       | Paper Title                                                                                     | Year / Venue            | Data Modality              | Task Type                      | Size                          | Download Link                                                                                      |
|--------------------|--------------------------------------------------------------------------------------------------|--------------------------|----------------------------|--------------------------------|-------------------------------|-----------------------------------------------------------------------------------------------------|
| MedTVT-QA | [MedTVT-R1: A Multimodal LLM Empowering Medical Reasoning and Diagnosis](https://arxiv.org/pdf/2506.18512) | 2025.06.23 | Text + Time Series (ECG) + Image (CXR) + Tabular (Lab Test) | Multimodal Medical Reasoning, Multi-disease Diagnosis, Report Generation | 8,706 multimodal data combinations used to generate QA pairs | [Github](https://github.com/keke-nice/MedTVT-R1) |
| HIE-Reasoning | [Visual and Domain Knowledge for Professional-level Graph-of-Thought Medical Reasoning](https://openreview.net/pdf?id=tnyxtaSve5) | 2025.06.18(ICML2025) | Text + Image (MRI) + Clinical Data | Professional-level Medical Reasoning, Neurocognitive Outcome Prediction, Lesion Analysis | 133 unique MRIs, 749 professional QA pairs, 133 interpretation summaries | [Github](https://github.com/i3-research/HIE-Reasoning) |
| ReasonMed| [ReasonMed: A 370K Multi-Agent Generated Dataset for Advancing Medical Reasoning](https://arxiv.org/abs/2506.09513) | 2025.06.11 | Text (Multi-agent CoT, Summary, QA) | Medical Reasoning, QA, CoT Fine-tuning | 370K high-quality samples distilled from 1.75M CoT paths, based on 195K questions from 4 benchmarks | [HF](https://huggingface.co/datasets/lingshu-medical-mllm/ReasonMed) |
| Lingshu (Train) | [Lingshu: A Generalist Foundation Model for Unified Multimodal Medical Understanding and Reasoning](https://arxiv.org/pdf/2506.07044) | 2025.06.08 | Text + Image (Multimodal Instruction, VQA, Report) | Multimodal Medical QA, Reasoning, Consultation, Report Generation | ~9.3M training samples from 60+ datasets | [Project Page](https://alibaba-damo-academy.github.io/lingshu/) |
| MedEvalKit (Linshu Test) | [Lingshu: A Generalist Foundation Model for Unified Multimodal Medical Understanding and Reasoning](https://arxiv.org/pdf/2506.07044) | 2025.06.08 | Text + Image (Multimodal Benchmarks) | Benchmarking: VQA, Report Generation, Medical Text QA | 152,066 evaluation samples from 16 benchmarks | [Github](https://github.com/alibaba-damo-academy/MedEvalKit) |
| MIRIAD | [MIRIAD: Augmenting LLMs with millions of medical query-response pairs](https://arxiv.org/abs/2506.06091) | 2025.06.09 | Text (Instruction-Response) | Medical QA, Retrieval-Augmented Generation (RAG), Hallucination Detection | 5.8M / 4.4M QA pairs | [HF](https://huggingface.co/datasets/miriad/miriad-5.8M) |
| ClinBench-HPB | [ClinBench-HPB: A Clinical Benchmark for Evaluating LLMs in Hepato-Pancreato-Biliary Diseases](https://arxiv.org/abs/2506.00095) | 2025.06.04 | Text (Multiple-choice Questions, Clinical Cases) | Medical Question Answering, Hepato-Pancreato-Biliary Clinical Case Diagnosis | 3,535 MCQs & 337 clinical cases, covering 465+ Hepato-Pancreato-Biliary diseases | [Project Page](https://clinbench-hpb.github.io), [HF](https://huggingface.co/datasets/ASD9987/ClinBench-HPB) |
| SurgVLM-DB         |SurgVLM-DB: A Large-scale Multimodal Surgical Database Comprising Over 1.81 Million Frames with 7.79 Million Conversations                                                        | 2025.06                 | Video + Text               | Multimodal QA                  | 1.81M frames, 7.79M QAs       | [GitHub](https://github.com/jinlab-imvr/SurgVLM)                                                   |
| EndoBench    | [EndoBench: A Comprehensive Evaluation of Multi-Modal Large Language Models for Endoscopy Analysis](https://arxiv.org/abs/2505.23601v1) | 2025.05.29   | Image + Text (Visual QA, Multimodal Tasks, Multi-level Visual Prompts) | Endoscopy Analysis, Medical Imaging, Multimodal Model Evaluation | Covers 4 endoscopy scenarios (Gastroscopy, Colonoscopy, Capsule Endoscopy, Surgical Endoscopy); includes 12 clinical tasks and 12 subtasks; 5 levels of visual prompt granularity; 6832 clinically validated VQA samples | [HF](https://huggingface.co/datasets/Saint-lsy/EndoBench) |
| MedXpertQA | MedXpertQA: Benchmarking Expert-Level Medical Reasoning and Understanding | ICML2025 | Text + Image (Multimodal MCQs) | Expert-level Medical QA, Clinical Reasoning, Multimodal Understanding | 4,460 questions (2,455 text / 2,005 image) | [HF](https://huggingface.co/datasets/TsinghuaC3I/MedXpertQA) |
| MedCaseReasoning   | MedCaseReasoning: Evaluating and Learning Diagnostic Reasoning from Clinical Case Reports                         | 2025.05.20              | Text                       | Diagnostic Reasoning           | 14,489 QA cases               | [GitHub](https://github.com/kevinwu23/Stanford-MedCaseReasoning)                                   |
| vlm-project-with-images-with-bbox-images-with-tree-of-thoughts | - | 2025.06                 | MRI Image + BBox + Multilingual QA (Including 7 languages: vi, en, fr, de, zh, ko, ja) | VQA, Lesion Detection, Clinical Reasoning (Tree-of-Thought) | 12.3k samples | [HF](https://huggingface.co/datasets/tungvu3196/vlm-project-with-images-with-bbox-images-with-tree-of-thoughts) | N/A |
| DrVD-Bench         | DrVD-Bench: Do Vision-Language Models Reason Like Human Doctors in Medical Image Diagnosis?                | 2025.05.30              | Medical Images + Text      | VQA, Reasoning, Report Gen.    | 7,789 image–QA pairs          | [GitHub](https://github.com/Jerry-Boss/DrVD-Bench), [HF](https://huggingface.co/datasets/jerry1565/DrVD-Bench) |
| MedS-Ins           | Towards Evaluating and Building Versatile LLMs for Medicine                                     | 2025.05                 | Text                       | Instruction Tuning             | 5M instances, 19K instructions| [HF](https://huggingface.co/datasets/Henrychur/MedS-Ins)                                            |
| MedS-Bench         | -                                                                                                | 2025.05                 | Text                       | Clinical Task Benchmark        | 11 task types                 | [HF](https://huggingface.co/datasets/Henrychur/MedS-Bench)                                          |
| MM-Skin            | MM-Skin:Enhancing Dermatology VLM with an Image-Text Dataset Derived from Textbooks                    | 2025.05.09              | Image + Text               | Open-ended VQA (no reasoning)  | -                             | [GitHub](https://github.com/ZwQ803/MM-Skin)                                                        |
| AlphaMed19K        | Beyond Distillation: Pushing the Limits of Medical LLM Reasoning with Minimalist Rule-Based RL                                                     | 2025.05.23              | Text                       | QA Reasoning                   | 19K QAs                       | [HF](https://huggingface.co/datasets/che111/AlphaMed19K)                                           |
| Derm1M | [Derm1M: A Million-scale Vision-Language Dataset Aligned with Clinical Ontology Knowledge for Dermatology](https://arxiv.org/pdf/2503.14911) | 2025.04.13(ICCV2025) | Text + Image (Dermatology) | Skin Disease Classification, Concept Identification, Cross-modal Retrieval | 1,029,761 image-text pairs | [Github](https://github.com/SiyuanYan1/Derm1M) |
| GEMeX | [GEMeX: A Large-Scale, Groundable, and Explainable Medical VQA Benchmark for Chest X-ray Diagnosis](https://arxiv.org/pdf/2411.16778) | 2025.03.23 (ICCV2025) | Text + Image (Chest X-ray) | Medical Visual Question Answering (VQA) for Chest X-ray Diagnosis | 151,025 images and 1,605,575 QA pairs | [HF](https://huggingface.co/datasets/BoKelvin/GEMeX-VQA), [Github](https://github.com/Awenbocc/GEMeX-Project) |
| Surg-396K | [EndoChat: Grounded Multimodal Large Language Model for Endoscopic Surgery](https://arxiv.org/abs/2501.11347) | 2025.03.15 | Image + Text (Multimodal Instruction, VQA, Grounding, Description) | Endoscopic Surgery, Surgical Scene Understanding, Visual QA, Grounded Dialogue | 396K instruction-image pairs from 41.4K images across 3 datasets (EndoVis, CoPESD, Cholec80) with 5 conversation types and 7 scene understanding tasks | [GitHub](https://github.com/gkw0010/EndoChat), [Data Link](https://mycuhk-my.sharepoint.com/personal/1155180074_link_cuhk_edu_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2F1155180074%5Flink%5Fcuhk%5Fedu%5Fhk%2FDocuments%2FRENLAB%20AI%20Data%2FSurg%2D396k&ga=1) |
| AbdomenAtlas 3.0 | [RadGPT: Constructing 3D Image-Text Tumor Datasets](https://arxiv.org/pdf/2501.04678) | 2025.01.08(ICCV2025) | Text + 3D Image (Abdominal CT) | 3D Abdominal CT Report Generation, Tumor Segmentation, Staging, and Analysis | 9,262 3D CT scans with paired reports, detailing 8,562 tumor instances | [Github](https://github.com/MrGiovanni/RadGPT), [HF](https://huggingface.co/datasets/SpamYdob/AbdomenAtlas3.0Report)|
| HuatuoGPT-o1 Dataset | [HuatuoGPT-o1，Towards Medical Complex Reasoning with LLMs](https://arxiv.org/pdf/2412.18925) | 2024.12.25 | Text (Complex CoT, Medical Verifiable Problems, Multi-Step Reasoning) | Medical Complex Reasoning, CoT Fine-tuning, Reinforcement Learning | Contains 40K high-quality medical complex reasoning problems filtered by a medical verifier, based on MedQA-USMLE and MedMCQA medical exam training sets | [GitHub](https://github.com/FreedomIntelligence/HuatuoGPT-o1), [HF](https://huggingface.co/datasets/FreedomIntelligence/medical-o1-reasoning-SFT) |
| PubMedVision        | [HuatuoGPT-Visionn, Towards Injecting Medical Visual Knowledge into Multimodal LLMs at Scale](https://arxiv.org/abs/2406.19280)                         | 2024.09.30 | Image + Text (Multimodal) | Medical VQA (Alignment VQA, Instruction-Tuning VQA), Captioning, Summarization | 1.3M VQA samples from 914,960 filtered PubMed medical images & text (647K + 647K)     | [Hugging Face](https://huggingface.co/datasets/FreedomIntelligence/PubMedVision)|
| PMC-VQA            | PMC-VQA: Visual Instruction Tuning for Medical VQA                                                       | 2024.08.08              | Image + Text               | VQA                            | 226,946 QA pairs              | [HF](https://huggingface.co/datasets/RadGenome/PMC-VQA)                                            |
| VQARad             | - | 2023.08.07              | Radiography                | VQA                            | 315 images, 3,515 QAs         | [OSF](https://osf.io/89kps/)                                                                         |
|  Asclepius | [Asclepius: A Spectrum Evaluation Benchmark for Medical Multi-Modal Large Language Models](https://arxiv.org/abs/2402.11217) | ACL 2025 | Image + Text | VQA | 3232 VQA pairs encompassing 15 medical specialties, stratifying into 3 main categories and 8 sub-categories of clinical tasks | [GitHub](https://github.com/Asclepius-Med/Asclepius) |
|  MedTrinity-25M | [MedTrinity-25M: A Large-scale Multimodal Dataset with Multigranular Annotations for Medicine](https://yunfeixie233.github.io/MedTrinity-25M/) | ICLR 2025 | Image + Text | VQA | 25M VQA pairs, covering over 25 million images across 10 modalities | [HF](https://huggingface.co/datasets/UCSC-VLAA/MedTrinity-25M) |
|  MediConfusion | [MediConfusion: Can you trust your AI radiologist? Probing the reliability of multimodal medical foundation models](https://arxiv.org/abs/2409.15477) | ICLR 2025 | Image + Text | VQA | 176 confusing pairs, a set of two images that share the same question and corresponding answer options, but the correct answer is different for the images. | [HF](https://huggingface.co/datasets/shahab7899/MediConfusion) |
| GMAI-MMBench       | GMAI-MMBench: A Comprehensive Multimodal Evaluation Benchmark Towards General Medical AI                     | NeurIPS 2024            | Multi-modal (38 types)     | VQA                            | 26K QA pairs                  | [HF](https://huggingface.co/datasets/OpenGVLab/GMAI-MMBench)                                       |
| PathMMU            | PathMMU: A Massive Multimodal Expert-Level Benchmark for Understanding and Reasoning in Pathology       | 2024.03.20              | Pathology Image + Text     | Multi-choice, Reasoning        | 33,428 QAs, 24,067 images     | [HF](https://huggingface.co/datasets/jamessyx/PathMMU)                                             |
| OmniMedVQA         | OmniMedVQA: A New Large-Scale Comprehensive Evaluation Benchmark for Medical LVLM                          | CVPR 2024               | Multi-modal (12 types)     | VQA                            | 118,010 images, 127,995 QA    | [OpenXLab](https://openxlab.org.cn/datasets/GMAI/OmniMedVQA)                                       |
| CARES              | A Comprehensive Benchmark of Trustworthiness in Medical Vision Language Models                 | NeurIPS 2024            | Medical Images + QA        | Open/Closed QA                 | 41K QA pairs                  | [GitHub](https://github.com/richard-peng-xia/CARES)                                                |
| MultiMedEval       | MultiMedEval: A Benchmark and a Toolkit for Evaluating Medical Vision-Language Models                        | 2024.02.16              | Image + Text               | Multi-task Evaluation          | 6 tasks, 23 datasets          | [GitHub](https://github.com/corentin-ryr/MultiMedEval)                                             |
| PubMedVision       | HuatuoGPT-Vision, Towards Injecting Medical Visual Knowledge into Multimodal LLMs at Scale | EMNLP 2024          | Medical Images + QA            | Medical VQA                         | 1,294,062 QA pairs                      | [HF](https://huggingface.co/datasets/FreedomIntelligence/PubMedVision)                                     |
| medical-o1-reasoning-SFT       | HuatuoGPT-o1, Towards Medical Complex Reasoning with LLMs | ACL 2025          | Medical VQA、Reasoning            | Medical VQA                         | 19.7k QA pairs                      | [HF](https://huggingface.co/datasets/FreedomIntelligence/medical-o1-reasoning-SFT)                                     |

---

## 🇨🇳 中文版本

### 🔍 项目简介

随着医学视觉语言模型（Med-VLM）及其推理能力研究的持续推进，尤其在 2025 年 3 月至 5 月期间，陆续发布了众多高质量、聚焦于医学推理能力的新型公开数据集，为多模态医疗人工智能的发展提供了坚实的数据基础。为此，我们希望尽可能汇总这一些数据，期待能为该社区提供更便捷的数据访问方式。我们发布了Med-VLM-Bench：

**Med-VLM-Bench** 致力于汇总并整理这些模型训练与评估的关键资源：

- ✅ 聚焦 2025 年 3–6 月发布的新数据集  
- 🧠 重点强调推理能力、多模态理解和问答能力的数据集 
- 🧪 同时覆盖 2023–2024 年的经典Med LLM/VLM benchmark datasets
- 🔗 提供直接可用的下载链接和开源地址

💡 我们的知识来源有限，欢迎大家通过 Issue 或 PR 推荐更多数据集，我们会第一时间更新！

📌Note: 此外我们的数据集标注时间以相应文章发表时间为准

---

### 📊 数据集汇总表

| 数据集名称         | 论文标题                                                                 | 年份 / 会议              | 数据模态                  | 任务类型                        | 数据规模                       | 下载链接                                                                                         |
|--------------------|--------------------------------------------------------------------------|---------------------------|---------------------------|----------------------------------|-------------------------------|--------------------------------------------------------------------------------------------------|
| MedTVT-QA | [MedTVT-R1: A Multimodal LLM Empowering Medical Reasoning and Diagnosis](https://arxiv.org/pdf/2506.18512) | 2025.06.23 | 文本 + 时间序列 (心电图) + 图像 (胸部X光) + 表格 (血液检测) | 多模态医疗推理、多病种诊断、报告生成 | 用于生成QA对的8,706组多模态数据组合 | [Github](https://github.com/keke-nice/MedTVT-R1) |
| HIE-Reasoning | [Visual and Domain Knowledge for Professional-level Graph-of-Thought Medical Reasoning](https://openreview.net/pdf?id=tnyxtaSve5) | 2025.06.18(ICML2025) | 文本 + 图像 (MRI) + 临床数据 | 专业级医疗推理、神经认知结局预测、病灶分析 | 133个独立MRI、749个专业问答对、133份解读摘要 | [Github](https://github.com/i3-research/HIE-Reasoning) |
| ReasonMed | [ReasonMed: A 370K Multi-Agent Generated Dataset for Advancing Medical Reasoning](https://arxiv.org/abs/2506.09513) | 2025.06.11 | 文本（多代理推理、多步总结、医学问答） | 医学推理、问答、链式思维微调 | 从 175 万条 CoT 路径中精炼出的 37 万高质量样本，覆盖来自 4 个基准的 19.5 万问题 | [HF](https://huggingface.co/datasets/lingshu-medical-mllm/ReasonMed) |
| Lingshu（Train） | [Lingshu: A Generalist Foundation Model for Unified Multimodal Medical Understanding and Reasoning](https://arxiv.org/pdf/2506.07044) | 2025.06.08 | 文本 + 图像（多模态指令、VQA、报告） | 多模态医学问答、推理、问诊、报告生成 | 约 930 万训练样本，来自 60+ 数据集 | [Project Page](https://alibaba-damo-academy.github.io/lingshu/) |
| MedEvalKit（Linshu test） | [Lingshu: A Generalist Foundation Model for Unified Multimodal Medical Understanding and Reasoning](https://arxiv.org/pdf/2506.07044) | 2025.06.08 | 文本 + 图像（多模态评测基准） | 基准评测：VQA、报告生成、医学文本问答 | 共 152,066 个评估样本，来自 16 个基准数据集 | [Github](https://github.com/alibaba-damo-academy/MedEvalKit) |
| MIRIAD | [MIRIAD: Augmenting LLMs with millions of medical query-response pairs](https://arxiv.org/abs/2506.06091) | 2025.06.09 | 文本（指令-回答对） | 医学问答、RAG 检索增强、幻觉检测 |  582 万 / 448 万 | [HF](https://huggingface.co/datasets/miriad/miriad-5.8M) |
| ClinBench-HPB | [ClinBench-HPB: A Clinical Benchmark for Evaluating LLMs in Hepato-Pancreato-Biliary Diseases](https://arxiv.org/abs/2506.00095) | 2025.06.04 | 文本 (选择题, 临床病例) | 医学问答, 临床病例诊断 | 3,535道选择题和337个临床病例, 覆盖465+种肝胆胰疾病 | [Project Page](https://clinbench-hpb.github.io), [HF](https://huggingface.co/datasets/ASD9987/ClinBench-HPB) |
| SurgVLM-DB         |SurgVLM-DB: A Large-Scale Multimodal Surgical Database                               | 2025.06                   | 视频 + 文本               | 多模态问答                      | 1.81M帧, 7.79M对话             | [GitHub](https://github.com/jinlab-imvr/SurgVLM)                                                 |
| EndoBench  | [EndoBench: A Comprehensive Evaluation of Multi-Modal Large Language Models for Endoscopy Analysis](https://arxiv.org/abs/2505.23601v1) | 2025.05.29 | 图像+文本（视觉问答、多模态任务、多层次视觉提示） | 内镜分析、医学影像、多模态模型评估 | 覆盖胃镜、结肠镜、胶囊内镜和手术内镜 4 大场景；包含 12 个临床任务及 12 个次任务；5 种视觉提示粒度；6832 个经过临床验证的 VQA 样本 | [HF](https://huggingface.co/datasets/Saint-lsy/EndoBench) |
| MedXpertQA | MedXpertQA: Benchmarking Expert-Level Medical Reasoning and Understanding | ICML2025 | 文本 + 图像（多模态选择题） | 专家级医学问答、临床推理、多模态理解 | 共 4,460 题（文本 2,455 / 图像 2,005） | [HF](https://huggingface.co/datasets/TsinghuaC3I/MedXpertQA) |
| MedCaseReasoning   |MedCaseReasoning: Evaluating and Learning Diagnostic Reasoning from Clinical Case Reports  | 2025.05.20                | 文本                      | 诊断推理                        | 14,489问答对                   | [GitHub](https://github.com/kevinwu23/Stanford-MedCaseReasoning)                                 |
| vlm-project-with-images-with-bbox-images-with-tree-of-thoughts | - | 2025.06 | MRI 图像 + BBox + 多语种问答（vi, en, fr, de, zh, ko, ja） | 医学VQA、病灶检测、临床推理（Tree-of-Thought） | 12,325 条样本 | [HF](https://huggingface.co/datasets/tungvu3196/vlm-project-with-images-with-bbox-images-with-tree-of-thoughts) | 未注明 |
| DrVD-Bench         | DrVD-Bench: Do Vision-Language Models Reason Like Human Doctors in Medical Image Diagnosis? | 2025.05.30          | 医学图像 + 文本           | 医学VQA、推理、报告生成         | 7,789图文QA对                  | [GitHub](https://github.com/Jerry-Boss/DrVD-Bench), [HF](https://huggingface.co/datasets/jerry1565/DrVD-Bench) |
| MedS-Ins           | Towards Evaluating and Building Versatile LLMs for Medicine              | 2025.05                   | 文本                      | 指令微调                        | 5M样本, 19K指令                | [HF](https://huggingface.co/datasets/Henrychur/MedS-Ins)                                         |
| MedS-Bench         | -                                                                         | 2025.05                   | 文本                      | 临床任务评估                    | 11大类任务                     | [HF](https://huggingface.co/datasets/Henrychur/MedS-Bench)                                       |
| MM-Skin            | MM-Skin:Enhancing Dermatology VLM with an Image-Text Dataset Derived from Textbooks | 2025.05.09          | 图像 + 文本               | 开放式VQA（无推理）             | -                             | [GitHub](https://github.com/ZwQ803/MM-Skin)                                                      |
| AlphaMed19K        | Beyond Distillation: Pushing the Limits of Medical LLM Reasoning with Minimalist Rule-Based RL                              | 2025.05.23                | 文本                      | 推理问答                        | 19K问答对                      | [HF](https://huggingface.co/datasets/che111/AlphaMed19K)                                         |
| Derm1M | [Derm1M: A Million-scale Vision-Language Dataset Aligned with Clinical Ontology Knowledge for Dermatology](https://arxiv.org/pdf/2503.14911) | 2025.04.13(ICCV2025) | 文本 + 图像（皮肤病学） | 皮肤病分类、概念识别、跨模态检索 | 1,029,761个图文对 | [Github](https://github.com/SiyuanYan1/Derm1M) |
| GEMeX | [GEMeX: A Large-Scale, Groundable, and Explainable Medical VQA Benchmark for Chest X-ray Diagnosis](https://arxiv.org/pdf/2411.16778) | 2025.03.23 (ICCV2025) | 文本 + 图像（胸部X光片） | 用于胸部X光诊断的医疗视觉问答（VQA） | 151,025张图片和1,605,575个问答 | [HF](https://huggingface.co/datasets/BoKelvin/GEMeX-VQA), [Github](https://github.com/Awenbocc/GEMeX-Project) |
| Surg-396K | [EndoChat: Grounded Multimodal Large Language Model for Endoscopic Surgery](https://arxiv.org/abs/2501.11347) | 2025.03.15 | 图像 + 文本（多模态指令、问答、目标定位、详细描述） | 内窥镜外科、手术场景理解、视觉问答、定位对话 | 来自 EndoVis、CoPESD 和 Cholec80 的 41,400 张图像，生成 396,000 图文对，覆盖 5 种对话类型与 7 类手术理解任务 | [GitHub](https://github.com/gkw0010/EndoChat) [Data link](https://mycuhk-my.sharepoint.com/personal/1155180074_link_cuhk_edu_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2F1155180074%5Flink%5Fcuhk%5Fedu%5Fhk%2FDocuments%2FRENLAB%20AI%20Data%2FSurg%2D396k&ga=1)|
| AbdomenAtlas 3.0 | [RadGPT: Constructing 3D Image-Text Tumor Datasets](https://arxiv.org/pdf/2501.04678) | 2025.01.08 (ICCV2025) | 文本 + 3D图像 (腹部CT) | 3D腹部CT报告生成、肿瘤分割、分期与分析 | 9,262组3D CT扫描及配对报告，包含8,562个肿瘤实例 | [Github](https://github.com/MrGiovanni/RadGPT), [HF](https://huggingface.co/datasets/SpamYdob/AbdomenAtlas3.0Report)|
| HuatuoGPT-o1 Dataset | [HuatuoGPT-o1，Towards Medical Complex Reasoning with LLMs](https://arxiv.org/pdf/2412.18925) | 2024.12.25 | 文本（复杂链式思维、医学验证题、多步推理） | 医学复杂推理、链式思维微调、强化学习 | 包含 40K 经医学验证器筛选的高质量医学复杂推理问题，基于 MedQA-USMLE 和 MedMCQA 医学考试训练集 | [GitHub](https://github.com/FreedomIntelligence/HuatuoGPT-o1), [HF](https://huggingface.co/datasets/FreedomIntelligence/medical-o1-reasoning-SFT) |
| PubMedVision         | [HuatuoGPT-Vision, Towards Injecting Medical Visual Knowledge into Multimodal LLMs at Scale](https://arxiv.org/abs/2406.19280)                         | 2024.09.30 | 图像 + 文本（多模态）     | 医学视觉问答（VQA）、图文对齐、指令微调、描述生成等                         | 130 万 VQA 样本，来自 PubMed 中筛选的 91.5 万医学图像与上下文（647K + 647K）        | [HF](https://huggingface.co/datasets/FreedomIntelligence/PubMedVision)      |
| PMC-VQA            | PMC-VQA: Visual Instruction Tuning for Medical VQA                                 | 2024.08.08                | 图像 + 文本               | 医学VQA                         | 226,946问答对                  | [HF](https://huggingface.co/datasets/RadGenome/PMC-VQA)                                          |
| VQARad             |-| 2023.08.07                | 放射图像                  | VQA                             | 315图像, 3515问答              | [OSF](https://osf.io/89kps/)                                                                       |
|  Asclepius | [Asclepius: A Spectrum Evaluation Benchmark for Medical Multi-Modal Large Language Models](https://arxiv.org/abs/2402.11217) | ACL 2025 | 图像 + 文本 | 医学VQA | 3232条问答对，涵盖 15 个医学专业，分为 3 个主要类别和 8 个子类别的临床任务 | [GitHub](https://github.com/Asclepius-Med/Asclepius) |
|  MedTrinity-25M | [MedTrinity-25M: A Large-scale Multimodal Dataset with Multigranular Annotations for Medicine](https://yunfeixie233.github.io/MedTrinity-25M/) | ICLR 2025 | 图像 + 文本 | 医学VQA | 大规模医学多模态数据集，涵盖 10 种模态的2500万张图像，为65种疾病提供多粒度注释 | [HF](https://huggingface.co/datasets/UCSC-VLAA/MedTrinity-25M) |
|  MediConfusion | [MediConfusion: Can you trust your AI radiologist? Probing the reliability of multimodal medical foundation models](https://arxiv.org/abs/2409.15477) | ICLR 2025 | 图像 + 文本 | 医学VQA | 由 176 个令人困惑的对组成。混淆对是一组两张图像，它们共享相同的问题和相应的答案选项，但图像的正确答案不同。 | [HF](https://huggingface.co/datasets/shahab7899/MediConfusion) |
| GMAI-MMBench       | GMAI-MMBench: A Comprehensive Multimodal Evaluation Benchmark Towards General Medical AI | NeurIPS 2024          | 多模态（38种）            | 医学VQA                         | 26K问答对                      | [HF](https://huggingface.co/datasets/OpenGVLab/GMAI-MMBench)                                     |
| PathMMU            | PathMMU: A Massive Multimodal Expert-Level Benchmark for Understanding and Reasoning in Patholog | 2024.03.20      | 病理图像 + 文本           | 选择题+推理                     | 33,428问答, 24,067图像         | [HF](https://huggingface.co/datasets/jamessyx/PathMMU)                                           |
| OmniMedVQA         | OmniMedVQA: A New Large-Scale Comprehensive Evaluation Benchmark for Medical LVLM    | CVPR 2024                 | 多模态（12种）            | 医学VQA                         | 118,010图像, 127,995问答       | [OpenXLab](https://openxlab.org.cn/datasets/GMAI/OmniMedVQA)                                     |
| CARES              | A Comprehensive Benchmark of Trustworthiness in Medical Vision Language Models | NeurIPS 2024         | 医学图像+问答             | 开放与封闭问答                   | 41K问答对                      | [GitHub](https://github.com/richard-peng-xia/CARES)                                              |
| MultiMedEval       | MultiMedEval: A Benchmark and a Toolkit for Evaluating Medical Vision-Language Models  | 2024.02.16                | 图文多模态                | 多任务评估                      | 6任务, 23数据集                | [GitHub](https://github.com/corentin-ryr/MultiMedEval)                                           |
| PubMedVision       | HuatuoGPT-Vision, Towards Injecting Medical Visual Knowledge into Multimodal LLMs at Scale | EMNLP 2024          | 医学图像 + 文本            | 医学VQA                         | 1,294,062条数据（对齐数据:647,031，指令微调数据:647,031 ）                      | [HF](https://huggingface.co/datasets/FreedomIntelligence/PubMedVision)                                     |
| medical-o1-reasoning-SFT       | HuatuoGPT-o1, Towards Medical Complex Reasoning with LLMs | ACL 2025          | 医学VQA、推理            | 医学VQA                         | 19.7k问答对                      | [HF](https://huggingface.co/datasets/FreedomIntelligence/medical-o1-reasoning-SFT)                                     |

---

## 📬 联系我们 / Issues & Contact

如有任何问题欢迎提交 Issue 或通过邮件联系：

- 📧 **叶赞挺 (Zanting Ye)**: yzt2861252880@gmail.com  
- 📧 **韩绪 (Xu Han)**: hanxv8826@gmail.com

---

## 👥 合作者（Contributors）

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/yezanting">
        <img src="https://github.com/yezanting.png" width="80px;" alt="yezanting"/><br />
        <sub><b>叶赞挺(Zanting Ye)</b></sub><br />
        <a href="mailto:yzt2861252880@gmail.com">📧</a>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/lailainan">
        <img src="https://github.com/lailainan.png" width="80px;" alt="lailainan"/><br />
        <sub><b>韩绪(Xu Han)</b></sub><br />
        <a href="mailto:hanxv8826@gmail.com">📧</a>
      </a>
    </td>
        <td align="center">
          <a href="https://github.com/Long0121">
          <img src="https://github.com/Long0121.png" width="80px;" alt="lailainan"/><br />
          <sub><b>牛小龙(Xiaolong Niu)</b></sub><br />
          <a href="">📧</a>
     </td>
        <td align="center">
          <a href="https://github.com/zianwang1110">
          <img src="https://github.com/zianwang1110.png" width="80px;" alt="lailainan"/><br />
          <sub><b>王梓安(Zian Wang)</b></sub><br />
          <a href="">📧</a>  
      </a>
    </td>
        <td align="center">
          <a href="https://github.com/Saint-lsy">
          <img src="https://github.com/Saint-lsy.png" width="80px;" alt="lailainan"/><br />
          <sub><b>刘圣圆(Shengyuan Liu)</b></sub><br />
          <a href="liushengyuan@link.cuhk.edu.hk">📧</a> 
      </a>
    </td>
  </tr>
</table>

---

## ⭐ Star 趋势图 (Star History)

![Star History Chart](https://api.star-history.com/svg?repos=yezanting/Med-VLM-Bench-Summary&type=Date)

---

---

⭐ Star 本项目支持我们持续更新，欢迎 PR 和建议交流！
