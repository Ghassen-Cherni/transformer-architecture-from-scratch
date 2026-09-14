## Work in progress

This is my implementation of a Transformer from scratch with PyTorch, for learning purposes. I started with a simple attention layer, then added multi-head attention and built the encoder and decoder around it.

### Currently implemented:

- Byte Pair Encoding (BPE) tokenization
- Token embedding layer
- Sinusoidal positional encoding
- Single-head scaled dot-product attention
- Multi-head attention
- Attention masking (padding and causal)
- Cross-attention between the decoder and encoder
- Feed-forward network (FFN)
- Layer normalization and residual connections
- Stacked encoder / decoder blocks
- Training loop for French-to-English translation
- Validation loss and token accuracy after each epoch
- Greedy decoding to generate a translation one token at a time
- Generated validation examples alongside reference translations

The model components are written with PyTorch

### Remarks:
This is an implementation for learning purposes and is not meant to be optimized. For example, it does not include dropout, caching... 
