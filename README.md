# NLP_Taxonomy_Classifier
Repository for the NLP Taxonomy Classifier project using a fine-tuned BERT model.

📄 Paper: Exploring the Landscape of Natural Language Processing Research (RANLP 2023)

🤗 Model: https://huggingface.co/TimSchopf/nlp_taxonomy_classifier

💾 Data: https://huggingface.co/datasets/TimSchopf/nlp_taxonomy_data

# Evaluation Results
The model was evaluated on a manually labeled test set of 828 different EMNLP 2022 papers. The following shows the average evaluation results for classifying papers according to the NLP taxonomy on three different training runs. Since the distribution of classes is very unbalanced, we report micro scores.

F1: 93.21
Recall: 93.99
Precision: 92.46
