# GPT Model from scratch using Pytorch

## Personal Project

### Year
2024

### Overview
This project implements a GPT (Generative Pre-trained Transformer) model for text generation using PyTorch and a text file as the data source. The model is designed to generate text based on a given starting sequence, and it can be trained on any text corpus. The implementation includes key components such as multi-head attention, feedforward neural networks, and a decoder. The project allows for customization of model parameters and training configurations. This is a foundational project aimed at understanding the architecture and mechanics of transformers.

### Features
- **GPT Model Implementation**: Utilizes multi-head attention and feedforward neural networks to build a transformer-based GPT model.
- **Customizable Training**: Allows for setting various model parameters such as embedding size, number of heads, feedforward dimensions, and dropout rate.
- **Text Data Handling**: Supports reading text data from a txt file, tokenizing the text into words and creating datasets for training and validation.
- **Training and Validation**: Provides functions to train the model and evaluate its performance using cross-entropy loss.
- **Text Generation**: Includes a function to generate text based on a given starting sequence, with customizable generation length and temperature for controlling randomness.

### Functionality
The project uses PyTorch for all aspects of model implementation, training, and evaluation, offering a versatile tool for exploring transformer-based architectures.

### How It Works
Users start by preparing a text corpus and reading it into the system. The text is tokenized, and a vocabulary is created. A PyTorch dataset is then constructed from the tokens, and data loaders are set up for training and validation. The GPT model is initialized with specified parameters, and the training process is carried out using the AdamW optimizer and exponential learning rate scheduler. After training, the model can generate new text sequences based on a starting prompt.
