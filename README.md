# 🚀 Awesome-Graph-Generation-LLM
A collection of AWESOME things about Graph Generation with LLMs.

🤗 Contributions to update new resources and articles are very welcome!

## ❖ Contents 
- [Molecular Graph](#Molecular-Graph)
    - [LLM-centric Approaches](#Model-centric-Approaches)
    - [Graph-centric Approaches](#Graph-centric-Approaches)
- [Knowledge Graph](#Knowledge-Graph)
    - [LLM-centric Approaches](#Model-centric-Approaches-1)
    - [Graph-centric Approaches](#Graph-centric-Approaches-1)
- [Program Graph](#Knowledge-Graph)
    - [LLM-centric Approaches](#Model-centric-Approaches-2)
    - [Graph-centric Approaches](#Graph-centric-Approaches-2)
- [Social Networks](#Knowledge-Graph)
    - [LLM-centric Approaches](#Model-centric-Approaches-3)
    - [Graph-centric Approaches](#Graph-centric-Approaches-3)
 
## ❖ Molecule Graph

### LLM-centric Approaches
|Name|Year|Category|Paper|Code|
| :------------ |:---------------: |:---------------:| :---------------| :---------------| 
| **G2T-LLM** | arXiv 2024.10 | Text-to-Graph Generation  | [G2T-LLM: Graph-to-Tree Text Encoding for Molecule Generation with Fine-Tuned Large Language Models](https://arxiv.org/pdf/2410.02198) | [N/A] |
| **DrugLLM** | arXiv 2024.05 | Text-to-Graph Generation  | [DrugLLM: Open Large Language Model for Few-shot Molecule Generation](https://arxiv.org/pdf/2405.06690) | [N/A] |
| **ICMA** | arXiv 2024.04 | Text-to-Graph Generation  | [Large Language Models are In-Context Molecule Learners](https://arxiv.org/pdf/2403.04197) | [N/A] |
| **MolGen** | ICLR 2024 | Text-to-Graph Generation  | [Domain-Agnostic Molecular Generation with Chemical Feedback](https://openreview.net/pdf?id=9rPyHyjfwP) | [Code](https://github.com/zjunlp/MolGen) |
| **Molgin** | JCIM 2024 | Text-to-Graph Generation  | [Large Language Models as Molecular Design Engines](https://pubs.acs.org/doi/pdf/10.1021/acs.jcim.4c01396?casa_token=-3YNUoig924AAAAA:BBIgPG7N7qZrgsJprH4Xv_WRptbEUeP6eWpKpKshRCfG2wxMYiMjuXYEFnMAhDwqP5uDDT9RYC5NjZ515A) | [N/A] |
| **LICO** | arXiv 2024.06 | Text-to-Graph Generation  | [LICO: Large Language Models for In-Context Molecular Optimization](https://arxiv.org/pdf/2406.18851) | [N/A] |
| **MolGPT** | JCIM | Text-to-Graph Generation  | [MolGPT: Molecular Generation Using a Transformer-Decoder Model](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00600) | [Code](https://github.com/devalab/molgpt) |
| **MSG** | Science Report | Text-to-Graph Generation  | [Transformer neural network for protein‑specifc de novo drug generation as a machine translation problem](https://www.nature.com/articles/s41598-020-79682-4.pdf) | [Code](https://github.com/dariagrechishnikova/molecule_structure_generation) |
| **MolReGPT** | TKDE | ChatGPT  | [MolReGPT: Empowering Molecule Discovery for Molecule-Caption Translation with Large Language Models: A ChatGPT Perspective](https://arxiv.org/pdf/2306.06615) | [Code](https://github.com/phenixace/MolReGPT?tab=readme-ov-file) |
| **ChatDrug** | ICLR 2024 | ChatGPT  | [Conversational Drug Editing Using Retrieval and Domain Feedback](https://openreview.net/pdf?id=yRrPfKyJQ2) | [Code](https://github.com/chao1224/ChatDrug) |
| **Graph DiT** | arXiv 2024.08 | Graph DiT  | [Graph Diffusion Transformers for Multi-Conditional Molecular Generation](https://openreview.net/pdf?id=cfrDLD1wfO) | [Code](https://github.com/liugangcode/Graph-DiT) |
| **UTGDiff** | arXiv 2024.08 | Graph DiT  | [Instruction-Based Molecular Graph Generation with Unified Text-Graph Diffusion Model](https://arxiv.org/pdf/2408.09896) | [Code](https://github.com/ran1812/UTGDiff) |
| **DrugChat** | arXiv 2023.05 | Multi-modal  | [DrugChat: Towards Enabling ChatGPT-Like Capabilities on Drug Molecule Graphs](https://arxiv.org/abs/2309.03907) | [N/A] |
| **DrugChat** | bioRxiv 2024.10 | Multi-modal  | [Multi-Modal Large Language Model Enables All-Purpose Prediction of Drug Mechanisms and Properties](https://www.biorxiv.org/content/10.1101/2024.09.29.615524v1.full.pdf) | [Code](https://github.com/youweiliang/drugchat) |
| **Llamole** | ICLR 2025 | Multi-modal  | [Multimodal Large Language Models for Inverse Molecular Design with Retrosynthetic Planning](https://openreview.net/pdf?id=rQ7fz9NO7f) | [Code](https://github.com/liugangcode/Llamole) |
| **GIT-Mol** | CIBM | Multi-modal  | [GIT-Mol: A Multi-modal Large Language Model for Molecular Science with Graph, Image, and Text](https://www.sciencedirect.com/science/article/pii/S0010482524001574?casa_token=1mNkF3-T30QAAAAA:yLOqN6SuJOKrfwYohhbbGnhUdFjw6Qy8f7_QFMWRsnghwRu4g7gDYhbP8jF-fwnZOqJQZlHGsqMp) | [Code](https://github.com/AI-HPC-Research-Team/GIT-Mol) |
| **MolX** | arXiv 2023.07 | Multi-modal  | [MolX: Enhancing Large Language Models for Molecular Learning with A Multi-Modal Extension](https://arxiv.org/abs/2406.06777) | [N/A] |
| **MolFM** | arXiv 2023.07 | Multi-modal  | [MolFM: A Multimodal Molecular Foundation Model](https://arxiv.org/pdf/2307.09484) | [Code](https://github.com/PharMolix/OpenBioMed) |
| **MoMu** | arXiv 2022.09 | Multi-modal  | [A Molecular Multimodal Foundation Model Associating Molecule Graphs with Natural Language](https://arxiv.org/pdf/2209.05481) | [N/A] |
| **MoleculeSTM** | NMI | Multi-modal  | [Multi-modal molecule structure–text model for text-based retrieval and editing](https://www.nature.com/articles/s42256-023-00759-6) | [Code](https://github.com/chao1224/MoleculeSTM) |




### GNN-centric Approaches
|Name|Category|Paper|Code|
| :------------ |:---------------:| :---------------| :---------------| 
| **DIR** | Invariant Representation Learning    | [[ICLR 2022] Discovering invariant rationales for graph neural networks](https://arxiv.org/pdf/2410.02198) | [Code](https://github.com/Wuyxin/DIR-GNN) |
