# detecting_online_polarization
To classify if online text is polarized or not polarized, and more with the type of polarization and characteristics



This repository contains my source code and datasets for the **SemEval Shared Task 9: Detecting Multilingual, multicultural, multievent Online Polarization**.

Our approach focuses on **English** and **Swahili** languages, utilizing multilingual architectures (XLM-R, mDeBERTa) combined with data augmentation and robust optimization techniques to handle low-resource settings and class imbalance.

##  Repository Structure

The repository is organized as follows:

- **`dev.zip`**: This archive contains all the datasets across all three subtasks.
- **`subtask1.ipynb`**: Binary Classification (Polarized vs. Non-Polarized). 
- **`subtask2.ipynb`**: Multi-label Classification (e.g., Political, Religious, ethnic, gender, ...). 
- **`subtask3.ipynb`**: Fine-grained Multi-label Classification (e.g., Vilification, Stereotyping). 

##  Getting Started

### 1. Prerequisites
To run the notebooks, you will need Python installed along with the following major libraries:
* `torch` (PyTorch)
* `transformers` (Hugging Face)
* `scikit-learn`
* `pandas`
* `numpy`

You can install them via pip:
```bash
pip install torch transformers scikit-learn pandas numpy 
```


Before running the notebooks, please unzip the dataset **dev.zip**