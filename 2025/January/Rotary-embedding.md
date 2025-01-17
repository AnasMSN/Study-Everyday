# Rotary Embedding
---------------------------------

## Positional Embedding

### What is positional embedding?
Positional embedding in context of transformer is one of the step which token will be added embed based on its position in the sentence. This is important because order of token will have an impact of the output of the result and the semantic meaning of sentence itself.

### Type of positional embedding

1. Sinusoidal Positional embedding
    This one is the common encoding used in transformer which use sine and cosine function to encode the position of the token in the sentence.
2. Absolute Positional embedding
   This one will use the absolute position of token in the sentence which is very simple and straightforward. There is maximum length of the sentence that can be used in this encoding that is 512.
3. Relative Positional embedding (T5)
    This one will use a matrix to encode the relative position of the token in the sentence. This is used in T5 model which is a variant of transformer model.

### What is Rotary embedding?
Rotary embedding is embedding type which combine techniques using absolute positional embedding and relative positional embedding. The techniques will use rotation based on the token before it which will add more correlation to the word before it. The absolute value will show based if there is no token before it which will show the same value without the positional embedding techniques. 

