# Named Entity Recognition with ELMo and Bidirectional LSTMs
Performing Named Entity Recognition using an ELMo layer and Bidirectional LSTMs. The notebook can be viewed [here](https://colab.research.google.com/drive/1Y2PpscubWynMJJVr8-GIyqFQ0Cmpe1wj?usp=sharing).

## Table of Contents
- Introduction
- Dataset & Preprocessing
- Model
- Results

## Introduction
<p align="justify">This repository contains the implementation of a Named Entity Recognition (NER) model. The goal of this project was to identify and classify entities within a corpus of sentences. ELMo (Embeddings from Language Models) was used to generate contextual embeddings for words, and these embeddings were subsequently fed into Bidirectional Long Short-Term Memory networks (BiLSTMs) to perform the NER task. This approach ensures high accuracy and efficiency in recognizing and classifying entities, making it suitable for applications such as information retrieval, question answering, and text summarization.</p>

## Dataset & Preprocessing
