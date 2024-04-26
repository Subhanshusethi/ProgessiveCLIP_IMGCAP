# Image Captioning with Contrastive Learning

## Overview

This project is a work-in-progress exploring the potential of contrastive learning to improve image captioning. The model utilizes several key components:

### Model Components

- **Image Encoder:** A pre-trained ResNet-101 architecture efficiently extracts visual features from input images. [Learn more](https://arxiv.org/abs/1512.03385)
  
- **Text Encoder:** A pre-trained BERT model encodes captions into meaningful text representations. [Learn more](https://arxiv.org/abs/1810.04805)
  
- **Contrastive Learning Objective:** The model incorporates a contrastive learning objective that encourages the encoders to learn similar representations for semantically related images and captions.

### Data Processing

- **Caption Preprocessing:** Captions are preprocessed to limit them to a specific word limit, ensuring consistency in input data for training.
  
- **Image Augmentation:** Images are augmented using the Albumentations library, enhancing the dataset's diversity and robustness.

### Evaluation Metrics

The project employs several standard metrics for image captioning evaluation:

- **BLEU (Bi-Lingual Evaluation Understudy):** Measures n-gram precision between generated captions and reference captions. [More info](https://www.aclweb.org/anthology/P02-1040.pdf)
  
- **METEOR (Metric for Evaluation of Translation with Ordering):** Considers word order and unigram precision when evaluating captions. [More info](https://www.aclweb.org/anthology/W05-0908.pdf)
  
- **ROUGE (Recall-Oriented Understudy for Gisting Evaluation):** Measures recall between generated captions and reference captions based on n-grams. [More info](https://www.aclweb.org/anthology/W04-1013.pdf)

## Expected Benefits

This model aims to enhance the efficiency and accuracy of image captioning tasks by leveraging contrastive learning for improved representation learning.

**Note:** This is a work-in-progress project.
