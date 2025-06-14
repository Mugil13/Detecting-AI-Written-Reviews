# Detecting AI-Written Reviews in Dravidian Languages

[![Paper](https://img.shields.io/badge/ACL_Anthology-View_Paper-blue)](https://aclanthology.org/2025.dravidianlangtech-1.65.pdf)  
*10th Place (Tamil) & 28th Place (Malayalam) @ DravidianLangTech-NAACL 2025 Shared Task*

---

## Overview  

This repository contains our code in a colab file for detecting AI-generated product reviews in Tamil and Malayalam using fine-tuned **mBERT** and **XLM-R** models. The system we developed achieved:  
- **Macro F1-score of 0.90** for Tamil  
- **Macro F1-score of 0.68** for Malayalam  

Some of the key challenges addressed:  
	- Low-resource language processing  
	- Linguistic complexity in Dravidian languages  
	- Misclassification of human-like AI text  

---

## Pre-requisites

Make sure you install all the requirements from the requirements.txt file provided  
```
pip install -r requirements.txt
```

## Usage

Download the colab notebook file given above and the datasets

## Results

| Model    | Language   | Precision (AI) | Recall (AI) | F1 (AI) |
|----------|------------|----------------|-------------|---------|
| mBERT    | Tamil      | 0.94           | 0.95        | 0.94    |
| XLM-R    | Tamil      | 0.95           | 0.96        | 0.92    |
| mBERT    | Malayalam  | 0.91           | 0.93        | 0.68    |
| XLM-R    | Malayalam  | 0.93           | 0.94        | 0.75    |

## Citation

```bibtex
@inproceedings{srihari2025detecting,
  title={Detecting AI-Written Reviews for Consumer Trust},
  author={Srihari V K, Vijay Karthick Vaidyanathan, Mugilkrishna D U and Durairaj Thenmozhi},
  booktitle={Proceedings of DravidianLangTech@NAACL 2025},
  year={2025}
}
```

## License

This project is under an MIT License, which can be viewed in the repo
