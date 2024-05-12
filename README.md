# Undergraduate Research Papers

This repository contains two research papers that I completed in the fourth year of my undergraduate degree. Below are the details including the titles and abstracts of each paper.

---

## Machine Learning for Parenting
### Abstract
Predicting and classifying Responsive Interactions for Learning (RIFL) scores in
parent-child interactions pose significant potential for advancements in developmental psychology. This paper explores the efficacy of various supervised machine
learning approaches to predict or classify RIFL scores using text transcripts and audio data. Utilizing a small dataset of 253 labeled samples of parent-child interactions,
we implemented and compared a range of techniques including linear regression,
XGBoost, Recurrent Neural Networks (RNN) with Gated Recurrent Units (GRU),
transformers, and the novel ROCKET (RandOm Convolutional KErnel Transform)
method. Despite rigorous experimentation with state-of-the-art machine learning
algorithms, our findings indicate that the current volume and distribution of data do
not permit the development of a model that generalizes sufficiently to unseen data
for accurate RIFL score prediction. A transformer model trained on transcript data
showed relative promise, achieving up to 70% validation accuracy while showing
clear signs of overfitting. This result suggests a larger, more balanced dataset might
yield improvements. The study highlights the complexity of capturing nuanced
parent-child interactions and sets a foundation for future work which could include
leveraging video data, larger datasets, and novel language models for enhanced prediction and classification of RIFL scores.


---

## Combinatorics with Model Compression
### Abstract
This study investigates the effects of several compression techniques on machine learning models.
Namely, Knowledge Distillation, Iterative Magnitude Pruning, Low-Rank Tensor Factorization, and
Quantization in an attempt to preserve model accuracy while minimizing model size on a DenseNet.
After sweeping over all possible combinations, we find that using Iterative Magnitude Pruning and
Quantization reduces the storage footprint by 99.84% while only sacrificing 1.24% of the original
model accuracy. We make a justification for why these two methods may have a synergy with
compression. We also analyze several poor-performing techniques, highlighting which combinations
to avoid to preserve accuracy during model compression.

---

## Contact Information
For more information, you can reach me at christopher dot mountain @ mail dot utoronto dot ca.
