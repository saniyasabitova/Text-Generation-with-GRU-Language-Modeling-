# Text-Generation-with-GRU-Language-Modeling-

Description
This project focuses on building a  Word-Level Language Model using Gated Recurrent Units (GRU). The goal is to predict the next word in a sequence based on the previous context. The model was trained on a text dataset to capture linguistic patterns and generate coherent sentences.

 Tech Stack
Framework: PyTorch

Architecture: GRU (Gated Recurrent Units)

Optimization: Adam Optimizer, CrossEntropyLoss

Task: Next-Word Prediction / Text Generation

Key Features
Custom GRU Implementation: Optimized for sequence processing to avoid the vanishing gradient problem (better than standard RNN).

Sampling Strategies: Includes a text generation function with adjustable sequence length.

Efficient Preprocessing: Implemented vocabulary mapping (word2ind, ind2word) and tokenization.

 Results & Visualizations
You can find the training metrics and generation examples in the /results folder:

Training Loss: The model shows smooth convergence, indicating effective learning of the language distribution. *

Text Generation Example:

Starting prompt: "I feel"

Result:

Observation: The model generates grammatically structured (though sometimes surreal) sentences, showing it has learned basic English syntax.
