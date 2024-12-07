# **ELM for Emotion Recognition**  
_This project implements an extreme learning machine (ELM) to analyze the relationship between latent space embeddings and emotional classes. The embeddings are generated from facial expression data using a vector quantized variational autoencoder (VQ-VAE)._

---

## **Description**  
This project explores the use of an extreme learning machine for classifying emotions based on latent space embeddings. Key features include:  
- Utilizes the **Facial Expression Recognition Challenge** dataset available at [Kaggle](https://www.kaggle.com/datasets/debanga/facial-expression-recognition-challenge).  
- Embeddings are derived from a VQ-VAE, which maps images to indices in a latent space.  
- Investigates correlations between the embedding indices and the emotion classes.  

The approach combines unsupervised learning (VQ-VAE) with supervised classification (ELM) to analyze emotional recognition patterns.

---

## **Main Features**  
- Integration of VQ-VAE embeddings for emotion analysis.  
- Classification using an extreme learning machine (ELM).  
- Analysis of the relationship between latent space embeddings and emotional categories.  

---

## **Prerequisites**  
- Python >= 3.8.  
- Required libraries:  
  - `numpy`  
  - `scikit-learn`  
  - `matplotlib`
  - `tensorflow`  

---

## **Installation**  
Steps to set up and run this project:  
1. Clone this repository:  
   ```bash
   git clone https://github.com/angelmdezhdez/elm-emotions.git  
