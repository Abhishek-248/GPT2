# Task 1

## Implementing GPT2
### Overview
Generative Pre-trained Transformer 2 (GPT-2) is a natural language processing model developed by OpenAI. It belongs to the 
Transformer-based model family, which has revolutionized the field of deep learning for sequence-to-sequence tasks.

## Model Description

The model consists of the following components:

- Token and positional embeddings: The model uses byte-pair encoding (BPE) to tokenize the input text into subword units, and assigns each token an embedding vector. The model also uses learned positional embeddings to encode the relative position of each token in the input sequence.
- Transformer layers: The model uses 12 transformer layers, each consisting of a multi-head self-attention layer and a feed-forward network. The multi-head self-attention layer allows the model to attend to different parts of the input sequence, while the feed-forward network applies a non-linear transformation to the hidden state. The model also uses layer normalization and residual connections to facilitate the information flow and gradient propagation.
- Output layer: The model uses a linear layer with a softmax activation to produce the probability distribution over the vocabulary for each token. The model ties the weights of the output layer and the token embeddings to reduce the number of parameters.
#### Key Features
    1. Max length of a sequence = 1024
    2. Word Embedding Dimensions = 768
    3. Vocabulary size = 50257
    3. No. of Decoders = 12
    4. No. of Attention heads = 8
    5. Total No. of Parameters = 124439808

## References

- Radford, A., Wu, J., Child, R., Luan, D., Amodei, D., & Sutskever, I. (2019). Language models are unsupervised multitask learners. *OpenAI Blog*, 1(8), 9.
- Karpathy, A. (2020). nanoGPT. https://github.com/karpathy/nanoGPT
- makemore. (2020). How to build GPT-2 from scratch. https://youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&feature=shared
- Microsoft BING
- https://jalammar.github.io/illustrated-gpt2/

