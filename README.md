# Project Description

The primary objective of this project is to explore and evaluate various models designed for **Part-of-Speech (POS) Tagging**, a fundamental task in Natural Language Processing (NLP). Specifically, the project compares the performance of **pre-trained Transformer models** (such as CamemBERT and BERT-base-multilingual-cased) with **custom-built Transformer models** developed from scratch.

### Key Objectives:
1. **Model Comparison**: Investigate whether pre-trained models, which have been trained on large multilingual datasets, outperform custom models specifically fine-tuned for POS tagging in French.
2. **Custom Architectures**: Develop and evaluate two types of custom Transformer models:
   - One using **word embeddings**.
   - Another using **character-level convolutional encoding** to handle unknown words more effectively.
3. **Performance Evaluation**: Assess model performance using metrics such as accuracy and F1-score on a French dataset (UD FRENCH Sequoia).
4. **Multi-task Potential**: Briefly explore the potential of multi-task learning by testing the models on a secondary task: **lemmatization**.

### Key Findings:
- Pre-trained models like **CamemBERT** and **BERT-base-multilingual-cased** generally perform well, but their effectiveness depends on the diversity and size of their training corpora.
- Custom models, particularly the **Transformer with convolutional encoding**, achieved competitive results, even surpassing some pre-trained models in specific configurations.
- The **F1-score** was used to account for class imbalances in the dataset, providing a more nuanced evaluation of model performance.

### Dataset:
The project focuses on the **French language**, using the **UD FRENCH Sequoia** dataset, which is part of the Universal Dependencies project. This dataset is rich in morphological and syntactic annotations, making it ideal for POS tagging tasks.

### Future Work:
- Further fine-tuning of custom models.
- Exploration of larger datasets and multi-task learning scenarios.
- Testing models on multiple languages or more complex NLP tasks.

This project provides valuable insights into the strengths and limitations of pre-trained versus custom-built models for POS tagging, offering a foundation for future research in NLP and deep learning.
