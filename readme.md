# Explain Transformer Internals

The idea is to understand its inner workings by explaining the matrices. In ideal case, we should be able to better train them, control, reduce size, and directly update weights to achieve desired properties.

Transformer embedding is tighly coupled with its token vocabulary. It can be loaded directly from HuggingFace Torch model.
