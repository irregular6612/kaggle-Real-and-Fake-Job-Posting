2024 Outta-3rd Competition P2 Notebook
Real and Fake Job Posting Classification


Url : https://www.kaggle.com/competitions/2024-outta-basic-p-2/overview
Dataset : https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction/data

Task-type: sequence classification(NLP)
Model: pretrained BERT (from hugging-face)

Short Summary:
- Classify the job information whether it is true or not.
- Fine tuning pretrained BERT(BertForSequenceClassification, 'bert-base-multilingual-cased')
(use whole structure)

Result:
- train_acc: 1.0
- test_acc: 0.987
- rank: 12/39

Key Point:
- doesn't use freeze
- lr scheduler
- gradient clipping


Last edited: 24/09/06