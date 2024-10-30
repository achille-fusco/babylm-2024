# BabyLM 2024 shared task @ NeTS 

This repository contains the data related to our participation to the [BabyLM 2024](https://babylm.github.io/) competition.

### 01-preprocess
This folder contains our data preprocessing procedures. We performed minimal cleaning on the data source, focusing on removing metalinguistic elements.

### 02-tokenization
In this directory, you will find our original tokenizer, MorPiece (MoP), which is freely inspired by the [Tolerance Principle](https://lingbuzz.net/lingbuzz/004146) proposed by Charles Yang. The current version (v.0.0.1) will be updated soon. Although we did not utilize this tokenizer in the English experiments due to time constraints, we believe it offers a valuable contribution, particularly for languages with rich morphological structures.

### 03-model_training
This section includes our original implementations of standard Recurrent Neural Network architectures, specifically GRU and LSTM models. These models are loosely inspired by alternative processing interpretations of Minimalist Grammars ([e-MGs](https://github.com/cristianochesi/e-MGs)). They aim to model various training biases through specific gate combinations that mimic standard constraints in structure building, such as [C-command](http://www.glottopedia.org/index.php/C-command) and [locality](http://glottopedia.org/index.php/Locality).

### 04-evaluation
Here, you will find the results of our models on the [BLiMP task](https://aclanthology.org/2020.tacl-1.25/) of the lm-eval campaign for BabyLM 2024 challenge, presented in .json format.
