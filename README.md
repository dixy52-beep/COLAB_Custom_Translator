# Neural Machine Translation with TensorFlow

This repository contains code for a neural machine translation (NMT) system implemented using TensorFlow. The NMT model translates sentences from one language to another using a sequence-to-sequence architecture with attention mechanisms.

## Features

- Tokenization of input and target texts
- Sequence padding
- LSTM-based encoder-decoder architecture
- Inference mode for translation
- Example usage with provided input and target texts

## Getting Started

To use this NMT system, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the provided Python script to train the model and perform translations.
4. Customize the input and target texts for your specific translation task.
5. Experiment with different hyperparameters and architectures to improve performance.

## Dependencies

- TensorFlow
- NumPy

## Usage

### Training the Model

To train the NMT model, run the following command:

```bash
python train.py
