# Positional Encoding
Positional encoding is a technique used in machine learning, particularly in transformer models, to provide information about the position of tokens in a sequence. Since transformers do not have a built-in notion of order like recurrent neural networks (RNNs), positional encodings are added to the input embeddings to give the model a sense of the order of the tokens.

### Example
In natural language processing tasks, such as language translation or text generation, the order of words is crucial for understanding context. Positional encoding helps the model to differentiate between words based on their positions in a sentence. For instance, in the sentences "The cat sat on the mat" and "On the mat sat the cat," the words are the same, but their meanings differ due to their positions. Positional encoding allows the transformer model to capture this difference effectively.

