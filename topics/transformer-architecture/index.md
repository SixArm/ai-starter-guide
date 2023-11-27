# Transformer architecture

Transformer architecture is a type of neural network architecture featuring self-attention mechanisms and feed-forward neural networks. The Transformer architecture has been widely adopted in various natural language parsing tasks, including machine translation, question-answering, and sentiment analysis. Its self-attention mechanism has inspired innovations in computer vision, speech recognition, and other areas where capturing long-range dependencies is crucial.

Main concepts…

Self-Attention Mechanism: Self-attention allows the model to weigh the importance of different words (or tokens) in a sequence i.e. how much focus should be given to each word. This enables the model to capture long-range dependencies in the input sequence.

Positional Encoding: Transformers lack an inherent sequential order in their architecture (unlike recurrent neural networks), so add positional encodings to provide information about the relative positions of tokens in the input sequence.

Encoder and Decoder Stacks: Transformers consist of multiple layers of encoders and decoders. In the original Transformer model for machine translation, the encoder processes the input sequence, and the decoder generates the output sequence. Each layer in the encoder and decoder contains a self-attention sub-layer and a feed-forward neural network sub-layer.

Multi-Head Attention: In addition to self-attention, the Transformer employs multi-head attention, which involves performing self-attention multiple times in parallel. This allows the model to capture different types of dependencies and patterns in the data.
