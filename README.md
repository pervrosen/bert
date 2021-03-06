**Note that this repository is no longer maintained. See https://github.com/af-ai-center/SweBERT instead.**

# BERT
Swedish pre-trained models for BERT.

## Introduction

**BERT**, or **B**idirectional **E**ncoder **R**epresentations from
**T**ransformers, is a new method of pre-training language representations which
obtains state-of-the-art results on a wide array of Natural Language Processing
(NLP) tasks.

BERT is based on the Transformer architecture introduced in [Attention is all you need](https://arxiv.org/abs/1706.03762).

Googles academic paper which describes BERT in detail and provides full results on a
number of tasks can be found here:
[https://arxiv.org/abs/1810.04805](https://arxiv.org/abs/1810.04805).

Googles Github repository where the original english models can be found here:
[https://github.com/google-research/bert](https://github.com/google-research/bert).

Included in the downloads below are PyTorch versions of the models based on the work of 
NLP researchers from HuggingFace.
[PyTorch version of BERT available](https://pytorch.org/hub/huggingface_pytorch-pretrained-bert_bert/)

## What is BERT?

BERT is a method of pre-training language representations, meaning that we train
a general-purpose "language understanding" model on a large text corpus (like
Wikipedia), and then use that model for downstream NLP tasks that we care about
(like question answering). BERT outperforms previous methods because it is the
first *unsupervised*, *deeply bidirectional* system for pre-training NLP.

*Unsupervised* means that BERT was trained using only a plain text corpus, which
is important because an enormous amount of plain text data is publicly available
on the web in many languages.

We used Swedish Wikipedia with approximatelly 2 million articles and 300 million words.

The links to the models are here (right-click, 'Save link as...' on the name):

*   **[`Swedish BERT-Base, Uncased`](https://storage.googleapis.com/ai-center/2019_06_15/swe-uncased_L-12_H-768_A-12.zip)**:
    12-layer, 768-hidden, 12-heads, 110M parameters
*   **[`Swedish BERT-Large, Uncased`](https://storage.googleapis.com/ai-center/2019_06_15/swe-uncased_L-24_H-1024_A-16.zip)**:
    24-layer, 1024-hidden, 16-heads, 340M parameters
    
## Disclaimer

This is initial pretrained Swedish versions of BERT models based on a smaller corpus than the original English versions. 

## Contact information

If you find these models useful or if you have suggestions for how they can be improved, please submit a GitHub issue.

For personal communication related to these Swedish versions of BERT, please contact Magnus Bjelkenhed
(`magnus.bjelkenhed@arbetsformedlingen.se`) or Mattias Bielsa (`mattias.bielsa@arbetsformedlingen.se`)

