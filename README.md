# Multilingual-question-answering
Predicting answers to questions is a common NLU task, but not for Hindi and Tamil. Current progress on multilingual modeling requires a concentrated effort to generate high-quality datasets and modelling improvements.
Additionally, for languages that are typically underrepresented in public datasets, it can be difficult to build trustworthy evaluations. The goal is to predict answers to real questions about Wikipedia articles. <br>

### Technical Details:
- A transformer-based masked language model (XLM-RoBERTa) trained on a limited set of data, which resulted in significant performance gains for underrepresented languages like Hindi and Tamil.
- Incorporated K-Fold Cross-Validation and ensemble techniques to improve accuracy.

For Kaggle competition: https://www.kaggle.com/c/chaii-hindi-and-tamil-question-answering
