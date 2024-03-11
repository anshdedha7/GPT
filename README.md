# GPT - Transformer Language Model

This is my implementation and training of a character-level Transformer language model, inspired by the architecture introduced in the paper "Attention is All You Need." I implemented this with the help of [Andrej Karpathy's GPT tutorial on YouTube](https://www.youtube.com/watch?v=kCc8FmEb1nY&ab_channel=AndrejKarpathy). The goal of this project is to train a model capable of generating text in the style of Shakespeare's writings, utilizing the Tiny Shakespeare dataset.

## Installation

Before running the project, ensure you have Python 3.8 or later installed. You can install the necessary dependencies by running:

```bash
pip install -r requirements.txt
```

## Dataset

The Tiny Shakespeare dataset (input.txt) comprises selections from Shakespeare's works, concatenated into a single text file. It serves as a compact yet representative sample of Shakespeare's style, making it an ideal training set for this project.

## Overview

The core of the project is the Transformer model, a type of deep learning model that relies on self-attention mechanisms instead of traditional recurrent layers. This model can process input sequences in parallel, leading to more efficient training. In this implementation, we focus on character-level predictions to capture the linguistic style and nuances of Shakespeare's writing.
