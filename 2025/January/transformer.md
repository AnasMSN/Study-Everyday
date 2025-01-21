# Transformer Architecture

## How many kind of architecture are there in transformer?

1. Encoder Only 
    This architecture is only encode the input. This means, it only understand and cannot create a text. This is good for classification task.
2. Encoder-Decoder (transformer)
   It really starting to popular after the paper "Attention is All you need paper" which introduce attention mechanism to understand sentence and generate it back. This popular for translation task.
3. Decoder-Only
   This only create a text and better for text generation. This model didn't understand the context of the input. But, it can generate a text based on the input.