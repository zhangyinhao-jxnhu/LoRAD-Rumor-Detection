# LoRAD: Logic-Reasoning Augmented DeBERTa for Rumor Detection

This repository contains the newly constructed **Twitter26-Mini** dataset and the instructions for acquiring the public datasets used in the paper: *"Logic-Reasoning Augmented DeBERTa (LoRAD) for Real-Time Rumor Detection"*.

## 📊 Datasets

To evaluate our LoRAD model, we utilized three public benchmark datasets and introduced a new out-of-distribution dataset. 

### 1. Twitter26-Mini (Proposed in this paper)
- **Description:** A newly constructed dataset containing 200 samples of emerging events from late 2024 to early 2026. 
- **Annotation:** Data was collected from real-world claims and manually cross-referenced with professional fact-checking websites (Snopes, Reuters Fact Check, and AFP Fact Check) to ensure rigorous logical evidence and factual accuracy.
- **Access:** You can find the dataset directly in this repository under the `/dataset` folder.

### 2. Public Benchmark Datasets (Twitter15, Twitter16, Weibo)
Due to copyright and licensing restrictions of the original authors, we do not directly redistribute the raw text of Twitter15, Twitter16, and Weibo datasets here. You can obtain them through their official academic release channels:
- **Twitter15 & Twitter16:** Please request/download from the original repository: [Rumor_RvNN](https://github.com/majingCUHK/Rumor_RvNN) or refer to Ma et al. (2017).
- **Weibo:** Available from the official repository: [Weibo Dataset](https://github.com/majingCUHK/Rumor_RvNN).

*(Note: If you have obtained the original datasets, you can use the LLM-augmented logic prompts described in our paper to generate the *E*<sub>logic</sub> features.)*

## 🚀 Model & Code
The source code for the LoRAD framework (Logic Augmentation, Disentangled Attention, and Adversarial Training via FGM) will be fully released here upon the acceptance of the paper.

## 📝 License
This project and the Twitter26-Mini dataset are licensed under the [MIT License](LICENSE). The use of Twitter15, Twitter16, and Weibo datasets is subject to their respective original academic licenses.

## 🔗 Citation
If you find our dataset or work useful, please consider citing our paper:
```bibtex
@article{zhang2026lorad,
  title={LoRAD: Logic-Reasoning Augmented DeBERTa with Adversarial Training for Robust Rumor Detection},
  author={Zhang, Yinhao and Muchtar, Farkhana and Mohd Sidik, Mohd Kufaisal and Mohamad Sharif, Johan},
  journal={Electronics},
  volume={15},
  number={5},
  pages={1021},
  year={2026},
  publisher={MDPI}
}
