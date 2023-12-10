# Meta Natural Language Understanding Benchmark 200 (MetaNLLB-200)

This repository contains the Meta Natural Language Understanding Benchmark 200 (MetaNLLB-200). The dataset is curated for evaluating and benchmarking natural language understanding models on a diverse set of tasks.

## Dataset

The MetaNLLB-200 dataset in this repository consists of two files:

- **English.txt:** Text data in the English language.
- **Hindi.txt:** Corresponding translations of the English text in the Hindi language.

The dataset is designed to support various NLU tasks, providing parallel samples in English and Hindi.

## Usage

To leverage the MetaNLLB-200 dataset, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### 2. Dataset Information
Explore the dataset files:

* English.txt: Use this file for English language text data.
* Hindi.txt: Use this file for Hindi translations corresponding to the English text.

### 3. Data Exploration
Explore the dataset to understand the structure and content:

```bash
with open('English.txt', 'r', encoding='utf-8') as english_file, open('Hindi.txt', 'r', encoding='utf-8') as hindi_file:
    english_data = english_file.readlines()
    hindi_data = hindi_file.readlines()

print("English Text Example:", english_data[0])
print("Hindi Translation Example:", hindi_data[0])
```

### 4. Task-Specific Usage
Depending on your NLU task, load and preprocess the data accordingly. The MetaNLLB-200 dataset is suitable for tasks such as sentiment analysis, named entity recognition, and more.

## Additional Information
For additional details, refer to any analysis or documentation provided in the repository.

## Citation
If you use the MetaNLLB-200 dataset in your research or work, please cite the source or authors as appropriate.


