This project is a work-in-progress exploring the potential of contrastive learning to improve image captioning.

Model Overview

The model utilizes several key components:

Image Encoder: A pre-trained ResNet-101 architecture efficiently extracts visual features from input images. (You can find the original ResNet paper here: A Deep Residual Learning for Image Recognition: [invalid URL removed])
Text Encoder: A pre-trained BERT model encodes captions into meaningful text representations. (Learn more about BERT here: BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding: https://arxiv.org/abs/1810.04805)
Contrastive Learning Objective: The model incorporates a contrastive learning objective that encourages the encoders to learn similar representations for semantically related images and captions.
Evaluation Metrics

The project employs several standard metrics for image captioning evaluation:

BLEU (Bi-Lingual Evaluation Understudy): Measures n-gram precision between generated captions and reference captions. (More info: BLEU: a Method for automatic evaluation of machine translation: [invalid URL removed])
METEOR (Metric for Evaluation of Translation with Ordering): Considers word order and unigram precision when evaluating captions. (More info: METEOR: Automatic Metric for MT Onward: https://www.aclweb.org/anthology/W05-0908.pdf)
ROUGE (Recall-Oriented Understudy for Gisting Evaluation): Measures recall between generated captions and reference captions based on n-grams. (More info: ROUGE: A Package for Automatic Evaluation of Summaries: [invalid URL removed])
Expected Benefits

This model aims to enhance the efficiency and accuracy of image captioning tasks by leveraging contrastive learning for improved representation learning.

Note:

This is a work-in-progress project.
