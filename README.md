# Semantic_Textual_Similarity
Creating models to predict the similarity of two texts, trained on the SemEval Dataset

(downloaded from https://alt.qcri.org/semeval2016/task1/index.php?id=data-and-tools)

Two different models were trained.
1) Bidirectional Encoder + DistilBert Transformer + Cosine Loss  
2) Cross Encoder + DistilBert Transformer + Cross Entropy Loss

The python library used for this is sentence-transformers (based on pytorch)
(https://www.sbert.net/index.html)

The folder contents are as below.

1) SemEval_Data - raw data, as obtained from the above link
2) input_data - processed/organized data for training
3) output_model - trained STS prediction models structure 
(actual model bin files cannot be added due to size)

The scripts used for processing the data, training, and prediction are given.
