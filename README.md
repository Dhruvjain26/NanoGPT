# NanoGPT
I trained a language model based on GPT (Generative Pretrained Transformer) called "NanoGPT" on a dataset containing more than 11 Lakh characters. Built-in PyTorch, this model is a transformer-based language model based on the paper "Attention is All You Need". However, this model is simply a character-level language model.

Implementation - 
1) I trained and made a Bigram model that predicted the next character based on only the previous character. Adamw Optimizer was used.
2) To improve the loss of the function I built a Dot-Product Single-Head Self Attention model using the Softmax activation function for normalization.

Cross entropy loss function (negative log-likelihood loss) was used to estimate performance and a loss of 2.382 was achieved.

What next?

The model performance could be optimized and improved using Batched Multi-head Self Attention. 
Further optimization could be achieved using a feed-forward type function and residual connections.
