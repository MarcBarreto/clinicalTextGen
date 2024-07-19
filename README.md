# ClinicalTextGen

## Table of Contents
1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Model](#model)
6. [Dataset](#dataset)
7. [Fine-Tuning](#fine-tuning)
8. [License](#license)

## Introduction
ClinicalTextGen is a project aimed at fine-tuning the Starling-LM-7B-alpha model to answer medical questions. The fine-tuning process utilizes the Llama2-MedTuned-Instructions dataset and employs LoRA (Low-Rank Adaptation) and STTF (Self-Tuning Task Framework) techniques.

## Project Structure
The project is organized as follows:
```sh
clinical-text-gen
┣ 📜 ClinicalTextGen.ipynb
┗ 📜 README.md
┗ 📜 LICENSE
```

## Installation
To run this project, you need to have Google Colab set up. Follow the instructions below to get started:

1. **Open Google Colab**: Go to [Google Colab](https://colab.research.google.com/).

2. **Upload the Notebook**:
   - Click on `File` > `Upload notebook`.
   - Choose the `ClinicalTextGen.ipynb` file from your local machine.

3. **Set Up the Environment**:
   - Ensure you have a Google account to save and execute the notebook.

## Usage
To use the ClinicalTextGen model, follow these steps:

1. **Execute the Notebook**:
   - Run each cell in the `ClinicalTextGen.ipynb` notebook sequentially.
   - The notebook includes the following steps:
     - Data preprocessing
     - Loading Model and Tokenizer
     - Fine-tuning the model
     - Evaluating the model

## Model
### Starling-LM-7B-alpha
- **Source**: The model can be found on HuggingFace at [Starling-LM-7B-alpha](https://huggingface.co/berkeley-nest/Starling-LM-7B-alpha).

## Dataset
### Llama2-MedTuned-Instructions
- **Description**: This dataset is used to fine-tune the model to better handle medical queries.
- **Source**: The dataset can be found on HuggingFace at [Llama2-MedTuned-Instructions](https://huggingface.co/datasets/nlpie/Llama2-MedTuned-Instructions).

## Fine-Tuning
The notebook utilizes LoRA and STTF techniques for fine-tuning the model:

- **LoRA (Low-Rank Adaptation)**: A technique used to efficiently fine-tune large language models.
- **SFTT (Super Fine Tuning Training)**: A framework for enhancing the model's ability to adapt to specific tasks.

## License
This project is licensed under the MIT License. See the [LICENSE](https://opensource.org/licenses/MIT) file for more information.

---

Feel free to explore the notebook and experiment with different configurations to see how the model performs!

