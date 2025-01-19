## Text Classification Model: Predicting Authors' Native Languages

This project focuses on developing a text classification model to predict the native language of authors based on textual data. The model utilizes advanced Natural Language Processing (NLP) techniques, leveraging embeddings from state-of-the-art transformer models like BERT and RoBERTa. The goal is to achieve high accuracy in identifying linguistic patterns indicative of an author's native language.  

### Features
- **Contextualized Text Representation:** Uses BERT and RoBERTa embeddings for capturing linguistic nuances.
- **Logistic Regression Classifier:** Implements a lightweight classification layer for prediction.
- **Fine-Tuning:** Applies fine-tuning of transformer models for domain-specific optimization.
- **Comparative Analysis:** Benchmarks performance across models, including baseline methods.

### Models Used
1. **BERT (Bidirectional Encoder Representations from Transformers):**
- Used for generating contextualized embeddings.
- Logistic Regression classifier achieved 77.67% accuracy.

2. **RoBERTa (Robustly Optimized BERT Approach):**
- Fine-tuned for better performance, achieving 82.3% accuracy.
- Offers improved pretraining and optimization compared to BERT.

### Dataset
**Source:**  
The dataset consists of text samples labeled with authors' native languages.

**Structure:**  
- Text: Raw sentences or paragraphs written by authors.
- Label: Native language of the author.
