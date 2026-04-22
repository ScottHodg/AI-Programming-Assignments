Project Gutenberg Text Generator
This project implements an English text generator using a Recurrent Neural Network (RNN) architecture. The model is trained on a combined corpus of classic literature to learn syntax, morphology, and punctuation from scratch.

Project Overview

The objective is to train an RNN-based model (Simple RNN, LSTM, or GRU) on three of the top 25 most downloaded books from Project Gutenberg. This project specifically uses a character-level LSTM architecture.

Dataset

The training data consists of the following books from Project Gutenberg:

Crime and Punishment by Fyodor Dostoevsky (Crime.txt)


Frankenstein by Mary Wollstonecraft Shelley (Frankenstein.txt)


The Great Gatsby by F. Scott Fitzgerald (Gatsby.txt)


The combined dataset contains approximately 1,883,383 characters with a unique vocabulary of 78 characters.

Model Architecture

The model is built using TensorFlow/Keras and consists of the following layers:

LSTM Layer: 256 units with return_sequences=True.


Dropout: 20% to prevent overfitting.


LSTM Layer: 256 units.


Dropout: 20%.





