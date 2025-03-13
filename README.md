# CEFR_listening_classification
This repository is a companion to the paper "Predicting the CEFR level of English listening texts with machine learning methods"

The data is organised in the following files

## Data
### Metadata for the CEFR English Listening Corpus

### Linguistic features and embeddings for the CEFR English Listening Corpus
OpenAI: bc_cam_with_ada_002_embeddings.csv
BERT: bc_cam_bert_embeddings.csv
Linguistic Features: bc_cam_5_taales_etc_variables.csv

## Python_Code
### Embeddings extraction
OpenAI: GPT_bc_cam_get_embeddings.ipynb
BERT: BERT_Embeddings_Extractor.ipynb

### Classification
OpenAI (finetuning SVM): GPT_bc_cam_finetuning_SVM.ipynb
OpenAI (4 methods): GPT_bc_cam_embeddings_classification_B2plus_Bootstrap_500.ipynb
BERT: BERT_bc_cam_embeddings_classification_B2plus_Bootstrap_500.ipynb
Linguistic Features: TAALES_etc_bc_cam_embeddings_classification_B2plus_Bootstrap_500.ipynb

### Final model usage
_Final_Model_and_YT22_Prediction.ipynb

## Final_Model
ADD HERE
