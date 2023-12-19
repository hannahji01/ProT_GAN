# ProT_GAN
CPSC 488 Final Project

## Introduction
This repository contains the code for the ProT_GAN project, developed as a part of the CPSC 488 Final Project. ProT_GAN is a generative model designed for generating protein sequences. It leverages a Generative Adversarial Network (GAN) architecture to generate protein sequences with desired properties.

## Project Overview
In this project, we implemented ProT_GAN and trained it on protein sequence data. The model's primary goal is to generate novel protein sequences based on the characteristics of the input data. It is particularly useful for generating proteins with specific properties or for various design tasks within the field of bioinformatics.

## Data
Data was downloaded from [UniProt]{https://www.uniprot.org/}. We trained the model on homo sapien transcription and non-transcription protein sequences.

## How to Run
To run this project, we recommend using Google Colab with access to GPUs.

The file, ProT_GAN.ipynb includes the model architecture, training, and evaluation components. 

The following steps outline how to run the code:

1. Install Requirements: All modules are listed at the top of ProT_GAN.ipynb
2. Load pre-trained model weights saved as .pkl files in the repo
3. Generate protein sequences and save to .txt file. Separate each sequence with '>Generated_sequence_i \n'
4. Upload generated sequences to [UniProt Align]{https://www.uniprot.org/blast}
5. Analyze protein sequences
