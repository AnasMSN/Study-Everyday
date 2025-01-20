# Flash Attention
---------------------------------

## Attention mechanism

### What is attention?
Attention in transformer techniques is step to calculate the correlation of a token in entire of sentence given. These step have Query, Key, and Value  as the property to be implemented. These three parameter will get matrix multiplication, softmax, and matrix multiplication again to get the output of the attention. The output of the attention will be used to calculate the output of the transformer.


### What is Flash Attention?
Flash attention help attention mechanism to be more faster with its ability to efficeintly use the gpu memory and input output aware of the attention mechanism. Starndard attention mechanism is doing read and write in each step like matrix multiplication and sofmax which take more time as there is latency in each read and write to the GPU memory. Flash attention is taking advantage of tiling the query, key, and value to do one matrix multiplication, softmax, and matrix multiplication again to then write it back to GPU memory. This will reduce the latency of the read and write to the GPU memory and make the attention mechanism faster.

