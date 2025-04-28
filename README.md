# LokaGPT

A minimal, educational implementation of a character-level GPT model.
Trained on a simple, tiny question/answer dataset to demonstrate end-to-end model training and text generation.

Inspired by nanoGPT by Andrej Karpathy.
## Features

 * Tiny Trivial Q&A dataset (six questions and answers)

 * Character-level vocabulary encoding and decoding

 * Custom GPT architecture including:

     * Self-attention mechanism

     * Multi-layer perceptron (MLP)

     * Layer normalization (LN)

 * Training loop with hyperparameter controls

 * Text sampling from the trained model

## Project Structure
|Part |	Description|
| --- | --- |
|Data Preparation |	Downloads and loads a small text dataset.|
|Vocabulary Setup	|Builds a character-level vocabulary.|
|Model Definition	|Defines GPT components like attention, MLP, and transformer blocks.|
|Training Script	|Fine-tunes the model on the dataset.|
|Sampling Script	|Generates text from the trained model.|
## How to Run

 1. Clone or download this repository.

 2. Install the required libraries:

          pip install torch numpy

 3. Open and run the LokaGPT.ipynb notebook step-by-step:
   
      *  It will automatically download the dataset.
   
      *  Build and train the model.
   
      *  Sample generated answers.

## Acknowledgements

* Core components and ideas adapted from nanoGPT by Andrej Karpathy.
