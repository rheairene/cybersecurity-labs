# AI-Generated Phishing Email Detector

An intelligent email classification system designed to identify and distinguish between 
**legitimate emails, traditional phishing attempts, and AI-generated phishing attacks**.
The project combines a publicly available phishing email dataset with a custom-built collection of 
AI-generated phishing samples to address the emerging threat of large language model (LLM)-assisted cyberattacks.

The model uses **TF-IDF vectorization** to transform email text into numerical features and 
a **Logistic Regression classifier** with balanced class weighting to handle class imbalance. 
Text preprocessing techniques such as URL normalization, email masking, and punctuation removal
help the model focus on meaningful linguistic patterns rather than formatting noise.

Trained on over **18,000 real-world email samples** and evaluated using classification metrics and 
confusion matrices, the detector achieved approximately **97% accuracy** on the test set. 
The project also exports reusable model artifacts, including the trained classifier, vectorizer, and
label encoder, enabling future deployment in applications such as email filtering systems, browser extensions, or cybersecurity awareness tools.

### Key Features

* Detects **Safe Emails**, **Traditional Phishing Emails**, and **AI-Generated Phishing Emails**
* Incorporates a custom dataset of AI-crafted phishing examples to simulate modern attack techniques
* Uses **TF-IDF (unigrams and bigrams)** for feature extraction
* Employs **Logistic Regression with class balancing** for robust classification
* Achieves **97% test accuracy**
* Generates evaluation reports and confusion matrix visualizations
* Saves trained model components for deployment and future use

This project highlights how machine learning can be leveraged to combat evolving cybersecurity threats in the age of generative AI.
