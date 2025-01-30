# sleep-apnea-analysis
A data-driven analysis of sleep apnea using machine learning and statistical methods. This project explores patterns in sleep data, identifies risk factors, and applies predictive modeling to assess apnea severity.

# **Sleep Apnea Detection using Deep Learning**
## Overview
Obstructive Sleep Apnea (OSA) is a prevalent sleep disorder characterized by repeated episodes of partial or complete upper airway obstruction during sleep. This condition disrupts normal sleep patterns, reduces oxygen intake, and can lead to severe health complications if left untreated. Early and accurate detection of OSA is crucial for effective management and intervention.

In this research study, we explore the potential of deep learning techniques for OSA detection, leveraging advanced neural network architectures. Our primary focus is on Convolutional Neural Networks (CNNs), Long Short-Term Memory (LSTM) networks, and a hybrid model that combines the strengths of both approaches. We also analyze how different optimization strategies and activation functions impact the accuracy of OSA detection.

# Architecture
### CNN
![Image](https://github.com/user-attachments/assets/1663a6fd-2d9c-4a7f-a4fa-422b586baebe)

### LSTM
![Image](https://github.com/user-attachments/assets/a7444ec0-5486-415e-8ca4-76bd5995e162)

### Hybrid Model
![Image](https://github.com/user-attachments/assets/bec233ea-a878-4c44-9d9a-410d26f75a43)

## Key Contributions
Deep Learning-Based OSA Detection: We employ CNNs, LSTMs, and a hybrid model for feature extraction and classification of OSA.
Optimization Strategies: We experiment with various optimizers, including Adam, RMSprop, and Nadam, to identify the most effective one.
Activation Function Analysis: We evaluate multiple activation functions to determine their influence on model performance.
Comprehensive Evaluation: Extensive experiments are conducted to benchmark accuracy, efficiency, and robustness of different models.

## Experimental Findings
Our study yields several noteworthy results:

Nadam optimizer delivers the best performance in OSA detection, achieving an impressive test accuracy of 95.22%.
The hybrid CNN-LSTM model outperforms standalone models, reaching a peak accuracy of 95.38%.
The LSTM model, particularly when combined with the sigmoid activation function, achieves a consistent accuracy of 93.80%.
Our findings emphasize the importance of proper model selection and optimization techniques for enhancing OSA detection accuracy.

## Impact and Future Scope
The results of this study contribute to the advancement of more accurate and practical diagnostic tools for OSA detection. By improving early diagnosis, this research has the potential to enhance patient outcomes, treatment strategies, and overall quality of life for individuals suffering from sleep apnea.

## 📄 Publication  
This project is based on our published research paper:  

**Title:** Obstructive Sleep Apnea Syndrome Identification Using CNN-LSTM Hybrid Model  
📌 **Authors:** Prasanna Kulkarni, Deepali Vora,Prajjwal Dewangan,Rohi Bindal,Nilima Zade,Anshita Singh, Aditya Gupte  
📖 **Journal:** Journal of Electrical Systems, Volume 20, Issue 2, 2024  
🔗 **DOI/Link:** [Paper Link](https://doi.org/10.52783/jes.2013)
