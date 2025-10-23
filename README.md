# CLIP_Bias  
_Auditing and mitigating social bias in contrastive vision-language models_

Authors: **Zahraa Al Sahili**, **Ioannis Patras**, and **Matthew Purver** 
📄 Paper: [Data Matters Most: Auditing Social Bias in Contrastive Vision–Language Models (TMLR, 2025)](https://openreview.net/forum?id=3vF2fn9owm)

---

## 🔍 Overview  
This repository contains the code and experiments for the paper  
**“Data Matters Most: Auditing Social Bias in Contrastive Vision–Language Models” (TMLR, 2025)**.  

It provides tools to evaluate and mitigate **social bias** in contrastive vision–language models such as **CLIP** and **OpenCLIP**, using datasets like **FairFace** and **PATA**.  
The framework supports auditing across bias dimensions including **agency**, **communion**, and **crime**, and evaluating the effectiveness of **debiasing methods**.

---

## 📁 Repository Structure  

| Notebook | Description |
|-----------|-------------|
| `CLIP_agen_FF.ipynb` | Agency bias on CLIP using FairFace |
| `CLIP_comm_FF.ipynb` | Communion bias on CLIP using FairFace |
| `CLIP_bias_FF.ipynb` | Crime bias on CLIP using FairFace |
| `PATA_Bias_agen.ipynb` | Agency bias on the PATA dataset |
| `oCLIP_*.ipynb` | Same audits using OpenCLIP |
| `debias_oclip.ipynb` | Evaluates and audits debiasing methods |

---

## 📚 Citation
If you use this repository, please cite:

@article{sahili2025data,
  title={Data Matters Most: Auditing Social Bias in Contrastive Vision--Language Models},
  author={Zahraa Al Sahili and Ioannis Patras and Matthew Purver},
  journal={Transactions on Machine Learning Research},
  issn={2835-8856},
  year={2025},
  url={https://openreview.net/forum?id=3vF2fn9owm}
}

