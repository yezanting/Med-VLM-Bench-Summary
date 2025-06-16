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

## 📊 Dataset Summary Table

| Dataset Name       | Paper Title                                                                                     | Year / Venue            | Data Modality              | Task Type                      | Size                          | Download Link                                                                                      |
|--------------------|--------------------------------------------------------------------------------------------------|--------------------------|----------------------------|--------------------------------|-------------------------------|-----------------------------------------------------------------------------------------------------|
| ReasonMed| [ReasonMed: A 370K Multi-Agent Generated Dataset for Advancing Medical Reasoning](https://arxiv.org/abs/2506.09513) | 2025.06.11 | Text (Multi-agent CoT, Summary, QA) | Medical Reasoning, QA, CoT Fine-tuning | 370K high-quality samples distilled from 1.75M CoT paths, based on 195K questions from 4 benchmarks | [HF](https://huggingface.co/datasets/lingshu-medical-mllm/ReasonMed) |
| Lingshu (Train) | [Lingshu: A Generalist Foundation Model for Unified Multimodal Medical Understanding and Reasoning](https://arxiv.org/pdf/2506.07044) | 2025.06.08 | Text + Image (Multimodal Instruction, VQA, Report) | Multimodal Medical QA, Reasoning, Consultation, Report Generation | ~9.3M training samples from 60+ datasets | [Project Page](https://alibaba-damo-academy.github.io/lingshu/) |
| MedEvalKit (Linshu Test) | [Lingshu: A Generalist Foundation Model for Unified Multimodal Medical Understanding and Reasoning](https://arxiv.org/pdf/2506.07044) | 2025.06.08 | Text + Image (Multimodal Benchmarks) | Benchmarking: VQA, Report Generation, Medical Text QA | 152,066 evaluation samples from 16 benchmarks | [Github](https://github.com/alibaba-damo-academy/MedEvalKit) |
| MIRIAD | [MIRIAD: Augmenting LLMs with millions of medical query-response pairs](https://arxiv.org/abs/2506.06091) | 2025.06.09 | Text (Instruction-Response) | Medical QA, Retrieval-Augmented Generation (RAG), Hallucination Detection | 5.8M / 4.4M QA pairs | [HF](https://huggingface.co/datasets/miriad/miriad-5.8M) |
| SurgVLM-DB         |SurgVLM-DB: A Large-scale Multimodal Surgical Database Comprising Over 1.81 Million Frames with 7.79 Million Conversations                                                        | 2025.06                 | Video + Text               | Multimodal QA                  | 1.81M frames, 7.79M QAs       | [GitHub](https://github.com/jinlab-imvr/SurgVLM)                                                   |
| MedXpertQA | MedXpertQA: Benchmarking Expert-Level Medical Reasoning and Understanding | ICML2025 | Text + Image (Multimodal MCQs) | Expert-level Medical QA, Clinical Reasoning, Multimodal Understanding | 4,460 questions (2,455 text / 2,005 image) | [HF](https://huggingface.co/datasets/TsinghuaC3I/MedXpertQA) |
| MedCaseReasoning   | MedCaseReasoning: Evaluating and Learning Diagnostic Reasoning from Clinical Case Reports                         | 2025.05.20              | Text                       | Diagnostic Reasoning           | 14,489 QA cases               | [GitHub](https://github.com/kevinwu23/Stanford-MedCaseReasoning)                                   |
| vlm-project-with-images-with-bbox-images-with-tree-of-thoughts | - | 2025.06                 | MRI Image + BBox + Multilingual QA (Including 7 languages: vi, en, fr, de, zh, ko, ja) | VQA, Lesion Detection, Clinical Reasoning (Tree-of-Thought) | 12.3k samples | [HF](https://huggingface.co/datasets/tungvu3196/vlm-project-with-images-with-bbox-images-with-tree-of-thoughts) | N/A |
| DrVD-Bench         | DrVD-Bench: Do Vision-Language Models Reason Like Human Doctors in Medical Image Diagnosis?                | 2025.05.30              | Medical Images + Text      | VQA, Reasoning, Report Gen.    | 7,789 image–QA pairs          | [GitHub](https://github.com/Jerry-Boss/DrVD-Bench), [HF](https://huggingface.co/datasets/jerry1565/DrVD-Bench) |
| MedS-Ins           | Towards Evaluating and Building Versatile LLMs for Medicine                                     | 2025.05                 | Text                       | Instruction Tuning             | 5M instances, 19K instructions| [HF](https://huggingface.co/datasets/Henrychur/MedS-Ins)                                            |
| MedS-Bench         | -                                                                                                | 2025.05                 | Text                       | Clinical Task Benchmark        | 11 task types                 | [HF](https://huggingface.co/datasets/Henrychur/MedS-Bench)                                          |
| MM-Skin            | MM-Skin:Enhancing Dermatology VLM with an Image-Text Dataset Derived from Textbooks                    | 2025.05.09              | Image + Text               | Open-ended VQA (no reasoning)  | -                             | [GitHub](https://github.com/ZwQ803/MM-Skin)                                                        |
| AlphaMed19K        | Beyond Distillation: Pushing the Limits of Medical LLM Reasoning with Minimalist Rule-Based RL                                                     | 2025.05.23              | Text                       | QA Reasoning                   | 19K QAs                       | [HF](https://huggingface.co/datasets/che111/AlphaMed19K)                                           |
| PMC-VQA            | PMC-VQA: Visual Instruction Tuning for Medical VQA                                                       | 2024.08.08              | Image + Text               | VQA                            | 226,946 QA pairs              | [HF](https://huggingface.co/datasets/RadGenome/PMC-VQA)                                            |
| VQARad             | - | 2023.08.07              | Radiography                | VQA                            | 315 images, 3,515 QAs         | [OSF](https://osf.io/89kps/)                                                                         |
| GMAI-MMBench       | GMAI-MMBench: A Comprehensive Multimodal Evaluation Benchmark Towards General Medical AI                     | NeurIPS 2024            | Multi-modal (38 types)     | VQA                            | 26K QA pairs                  | [HF](https://huggingface.co/datasets/OpenGVLab/GMAI-MMBench)                                       |
| PathMMU            | PathMMU: A Massive Multimodal Expert-Level Benchmark for Understanding and Reasoning in Pathology       | 2024.03.20              | Pathology Image + Text     | Multi-choice, Reasoning        | 33,428 QAs, 24,067 images     | [HF](https://huggingface.co/datasets/jamessyx/PathMMU)                                             |
| OmniMedVQA         | OmniMedVQA: A New Large-Scale Comprehensive Evaluation Benchmark for Medical LVLM                          | CVPR 2024               | Multi-modal (12 types)     | VQA                            | 118,010 images, 127,995 QA    | [OpenXLab](https://openxlab.org.cn/datasets/GMAI/OmniMedVQA)                                       |
| CARES              | A Comprehensive Benchmark of Trustworthiness in Medical Vision Language Models                 | NeurIPS 2024            | Medical Images + QA        | Open/Closed QA                 | 41K QA pairs                  | [GitHub](https://github.com/richard-peng-xia/CARES)                                                |
| MultiMedEval       | MultiMedEval: A Benchmark and a Toolkit for Evaluating Medical Vision-Language Models                        | 2024.02.16              | Image + Text               | Multi-task Evaluation          | 6 tasks, 23 datasets          | [GitHub](https://github.com/corentin-ryr/MultiMedEval)                                             |

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
| ReasonMed | [ReasonMed: A 370K Multi-Agent Generated Dataset for Advancing Medical Reasoning](https://arxiv.org/abs/2506.09513) | 2025.06.11 | 文本（多代理推理、多步总结、医学问答） | 医学推理、问答、链式思维微调 | 从 175 万条 CoT 路径中精炼出的 37 万高质量样本，覆盖来自 4 个基准的 19.5 万问题 | [HF](https://huggingface.co/datasets/lingshu-medical-mllm/ReasonMed) |
| Lingshu（Train） | [Lingshu: A Generalist Foundation Model for Unified Multimodal Medical Understanding and Reasoning](https://arxiv.org/pdf/2506.07044) | 2025.06.08 | 文本 + 图像（多模态指令、VQA、报告） | 多模态医学问答、推理、问诊、报告生成 | 约 930 万训练样本，来自 60+ 数据集 | [Project Page](https://alibaba-damo-academy.github.io/lingshu/) |
| MedEvalKit（Linshu test） | [Lingshu: A Generalist Foundation Model for Unified Multimodal Medical Understanding and Reasoning](https://arxiv.org/pdf/2506.07044) | 2025.06.08 | 文本 + 图像（多模态评测基准） | 基准评测：VQA、报告生成、医学文本问答 | 共 152,066 个评估样本，来自 16 个基准数据集 | [Github](https://github.com/alibaba-damo-academy/MedEvalKit) |
| MIRIAD | [MIRIAD: Augmenting LLMs with millions of medical query-response pairs](https://arxiv.org/abs/2506.06091) | 2025.06.09 | 文本（指令-回答对） | 医学问答、RAG 检索增强、幻觉检测 |  582 万 / 448 万 | [HF](https://huggingface.co/datasets/miriad/miriad-5.8M) |
| SurgVLM-DB         |SurgVLM-DB: A Large-Scale Multimodal Surgical Database                               | 2025.06                   | 视频 + 文本               | 多模态问答                      | 1.81M帧, 7.79M对话             | [GitHub](https://github.com/jinlab-imvr/SurgVLM)                                                 |
| MedXpertQA | MedXpertQA: Benchmarking Expert-Level Medical Reasoning and Understanding | ICML2025 | 文本 + 图像（多模态选择题） | 专家级医学问答、临床推理、多模态理解 | 共 4,460 题（文本 2,455 / 图像 2,005） | [HF](https://huggingface.co/datasets/TsinghuaC3I/MedXpertQA) |
| MedCaseReasoning   |MedCaseReasoning: Evaluating and Learning Diagnostic Reasoning from Clinical Case Reports  | 2025.05.20                | 文本                      | 诊断推理                        | 14,489问答对                   | [GitHub](https://github.com/kevinwu23/Stanford-MedCaseReasoning)                                 |
| vlm-project-with-images-with-bbox-images-with-tree-of-thoughts | - | 2025.06 | MRI 图像 + BBox + 多语种问答（vi, en, fr, de, zh, ko, ja） | 医学VQA、病灶检测、临床推理（Tree-of-Thought） | 12,325 条样本 | [HF](https://huggingface.co/datasets/tungvu3196/vlm-project-with-images-with-bbox-images-with-tree-of-thoughts) | 未注明 |
| DrVD-Bench         | DrVD-Bench: Do Vision-Language Models Reason Like Human Doctors in Medical Image Diagnosis? | 2025.05.30          | 医学图像 + 文本           | 医学VQA、推理、报告生成         | 7,789图文QA对                  | [GitHub](https://github.com/Jerry-Boss/DrVD-Bench), [HF](https://huggingface.co/datasets/jerry1565/DrVD-Bench) |
| MedS-Ins           | Towards Evaluating and Building Versatile LLMs for Medicine              | 2025.05                   | 文本                      | 指令微调                        | 5M样本, 19K指令                | [HF](https://huggingface.co/datasets/Henrychur/MedS-Ins)                                         |
| MedS-Bench         | -                                                                         | 2025.05                   | 文本                      | 临床任务评估                    | 11大类任务                     | [HF](https://huggingface.co/datasets/Henrychur/MedS-Bench)                                       |
| MM-Skin            | MM-Skin:Enhancing Dermatology VLM with an Image-Text Dataset Derived from Textbooks | 2025.05.09          | 图像 + 文本               | 开放式VQA（无推理）             | -                             | [GitHub](https://github.com/ZwQ803/MM-Skin)                                                      |
| AlphaMed19K        | Beyond Distillation: Pushing the Limits of Medical LLM Reasoning with Minimalist Rule-Based RL                              | 2025.05.23                | 文本                      | 推理问答                        | 19K问答对                      | [HF](https://huggingface.co/datasets/che111/AlphaMed19K)                                         |
| PMC-VQA            | PMC-VQA: Visual Instruction Tuning for Medical VQA                                 | 2024.08.08                | 图像 + 文本               | 医学VQA                         | 226,946问答对                  | [HF](https://huggingface.co/datasets/RadGenome/PMC-VQA)                                          |
| VQARad             |-| 2023.08.07                | 放射图像                  | VQA                             | 315图像, 3515问答              | [OSF](https://osf.io/89kps/)                                                                       |
| GMAI-MMBench       | GMAI-MMBench: A Comprehensive Multimodal Evaluation Benchmark Towards General Medical AI | NeurIPS 2024          | 多模态（38种）            | 医学VQA                         | 26K问答对                      | [HF](https://huggingface.co/datasets/OpenGVLab/GMAI-MMBench)                                     |
| PathMMU            | PathMMU: A Massive Multimodal Expert-Level Benchmark for Understanding and Reasoning in Patholog | 2024.03.20      | 病理图像 + 文本           | 选择题+推理                     | 33,428问答, 24,067图像         | [HF](https://huggingface.co/datasets/jamessyx/PathMMU)                                           |
| OmniMedVQA         | OmniMedVQA: A New Large-Scale Comprehensive Evaluation Benchmark for Medical LVLM    | CVPR 2024                 | 多模态（12种）            | 医学VQA                         | 118,010图像, 127,995问答       | [OpenXLab](https://openxlab.org.cn/datasets/GMAI/OmniMedVQA)                                     |
| CARES              | A Comprehensive Benchmark of Trustworthiness in Medical Vision Language Models | NeurIPS 2024         | 医学图像+问答             | 开放与封闭问答                   | 41K问答对                      | [GitHub](https://github.com/richard-peng-xia/CARES)                                              |
| MultiMedEval       | MultiMedEval: A Benchmark and a Toolkit for Evaluating Medical Vision-Language Models  | 2024.02.16                | 图文多模态                | 多任务评估                      | 6任务, 23数据集                | [GitHub](https://github.com/corentin-ryr/MultiMedEval)                                           |

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
        <sub><b>叶赞挺</b></sub><br />
        <a href="mailto:yzt2861252880@gmail.com">📧</a>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/lailainan">
        <img src="https://github.com/lailainan.png" width="80px;" alt="lailainan"/><br />
        <sub><b>韩绪</b></sub><br />
        <a href="mailto:hanxv8826@gmail.com">📧</a>
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
