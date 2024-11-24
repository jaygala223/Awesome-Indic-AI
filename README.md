# 🌟 Awesome Indic AI  
A curated collection of **awesome research papers, models, and datasets** in Indic languages. Contributions are welcome!

## 📚 Contents  
- [Models](#-models)  
- [Notable Research](#-notable-research)
- [Datasets](#-datasets)
- [Contributing](#-contributing)
- [Citation](#️-citation)


## 🤖 Models  

| 🗓 Year | 📄 Title                          | 📜 Paper Link       | 💻 Code Repo       |
|:-------:|:---------------------------------:|:-------------------:|:------------------:|
| 2023    | IndicBERT-MLM - A vanilla BERT style model trained on IndicCorp v2 with the MLM objective | - | [Hugging Face](https://huggingface.co/ai4bharat/IndicBERTv2-MLM-only) |
| 2022    | Samanantar - TLM as an additional objective with Samanantar Parallel Corpus | [View Paper](#) | [Hugging Face](https://huggingface.co/ai4bharat/IndicBERTv2-MLM-Sam-TLM) |
| 2023    | Back-Translation - TLM as an additional objective by translating the Indic parts of IndicCorp v2 dataset into English w/ IndicTrans model | - | [Hugging Face](https://huggingface.co/ai4bharat/IndicBERTv2-MLM-Back-TLM) |
| 2023    | IndicBERT-SS - To encourage better lexical sharing among languages we convert the scripts from Indic languages to Devanagari and train a BERT style model with the MLM objective | - | [Hugging Face](https://huggingface.co/ai4bharat/IndicBERTv2-SS) |
| 2023    | Indic-TTS - Towards Building Text-To-Speech Systems for the Next Billion Users | [View Paper](https://arxiv.org/abs/2209.12345) | [Bhashini](https://bhashini.gov.in/ulca/model/explore-models) |
| 2023    | IndicTrans2 - The first open-source transformer-based multilingual NMT model that supports high-quality translations across all the 22 scheduled Indic languages | [View Paper](https://arxiv.org/abs/2305.16307) | [GitHub](https://github.com/AI4Bharat/IndicTrans2) |
| 2024    | Airavata - A Hindi chat model instruction finetuned on SarvamAI's OpenHathi | [View Paper](https://arxiv.org/abs/2401.15006) | [Hugging Face](https://huggingface.co/ai4bharat/airavata) |
| 2023    | Tamil Llama - A New Tamil Language Model Based on Llama 2 | [View Paper](https://arxiv.org/abs/2311.05845) | [GitHub](https://github.com/abhinand5/tamil-llama) |

## 📦 Notable Research  

| 🗓 Year | 📄 Title                          | 📜 Paper Link       | 💻 Code Repo       |
|:-------:|:---------------------------------:|:-------------------:|:------------------:|
| 2023    | Evaluating the Diversity, Equity, and Inclusion of NLP Technology: A Case Study for Indian Languages | [View Paper](https://aclanthology.org/2023.findings-eacl.131/) | - |
| 2023    | Assessing Translation capabilities of Large Language Models involving English and Indian Languages | [View Paper](https://arxiv.org/abs/2311.09216) | - |
| 2024    | RomanSetu: Efficiently unlocking multilingual capabilities of Large Language Models via Romanization | [View Paper](https://arxiv.org/abs/2401.14280) | [GitHub](https://github.com/AI4Bharat/romansetu) |
| 2024    | Decoding the Diversity: A Review of the Indic AI Research Landscape | [View Paper](https://arxiv.org/abs/2406.09559) | - |
| 2024    | IndiText Boost: Text Augmentation for Low Resource India Languages | [View Paper](https://arxiv.org/abs/2401.13085) | - |

## 📦 Datasets  

| 📂 Dataset Name       | 🌐 Languages Covered  | 📜 Description       | 📥 Download Link    | 📄 Paper Link       |
|:---------------------:|:---------------------:|:--------------------:|:-------------------:|:-------------------:|
| IndicCOPA             | 18 Indic Languages    | COPA test set in 18 languages | [Download](https://huggingface.co/datasets/ai4bharat/IndicCOPA) | - |
| MILU                  | 11 Indic Languages    | Evaluation dataset for Large Language Models across 11 Indic languages. | [Download](https://huggingface.co/datasets/ai4bharat/MILU) | - |
| IndicQA               | 11 Indic Languages    | Cloze-style reading comprehension dataset | [Download](https://huggingface.co/datasets/ai4bharat/IndicQA) | - |
| IndicXParaphrase      | 10 Indic Languages    | Multilingual paraphrase detection dataset | [Download](https://huggingface.co/datasets/ai4bharat/IndicXParaphrase) | - |
| IndicSentiment        | 13 Indic Languages    | Multilingual sentiment analysis dataset | [Download](https://huggingface.co/datasets/ai4bharat/IndicSentiment) | - |
| IndicXNLI             | 11 Indic Languages    | Translated XNLI dataset | [Download](https://huggingface.co/datasets/Divyanshu/indicxnli) | [View Paper](https://aclanthology.org/2022.emnlp-main.755/) |
| Naamapadam            | 9 Indic Languages     | NER dataset with testsets | [Download](https://huggingface.co/datasets/ai4bharat/naamapadam) | [View Paper](https://arxiv.org/abs/2212.10168) |
| MASSIVE               | 7 Indic Languages     | Intent classification and slot-filling dataset | [Download](https://github.com/alexa/massive#accessing-and-processing-the-data) | [View Paper](https://arxiv.org/abs/2204.08582) |
| FLORES                | 18 Indic Languages    | Indic parts of the FLORES-101 dataset | [Download](https://huggingface.co/datasets/facebook/flores) | [View Paper](https://arxiv.org/abs/2207.04672) |
| IndicCorp v2          | 24 Indic Languages    | Multilingual dataset for various NLP tasks | [Download](https://github.com/AI4Bharat/IndicBERT?tab=readme-ov-file#indiccorp-v2) | - |
| Indic Instruct v0.1   | Hindi                 | Instruction dataset containing translated English instructions and native Hindi datasets (wikiHow and Anudesh) | [Download](https://huggingface.co/datasets/ai4bharat/indic-instruct-data-v0.1) | - |


## 🤝 Contributing  

We welcome contributions! Here's how you can help:  

1. Fork this repository.  
2. Add research papers, models, or datasets with appropriate links and descriptions.  
3. Create a pull request with your changes.  

**Formatting Guidelines:**  
- Ensure all links are valid.  
- Use the provided table format for consistency.  
- Add a brief description for each entry.  

## ✍️ Citation  

If you find this repository helpful in your research or projects, please consider citing it as follows:  

```
@misc{gala2024awesomeindicai,
  author = {Jay Gala},
  title = {Awesome Indic AI},
  year = {2024},
  publisher = {GitHub},
  journal = {GitHub Repository},
  howpublished = {\url{https://github.com/jaygala223/Awesome-Indic-AI}}
}
```

Feel free to explore, contribute, and build upon this repository. Share this repository to spread awareness and encourage collaboration in Indic AI research
