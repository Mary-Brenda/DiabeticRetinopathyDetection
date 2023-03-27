# Advancing Health Equity: Deep Neural Networks for Preventing Vision Loss in Underrepresented Populations

This repository contains code for a multiclassification deep convolutional neural network (DNN) that classifies Diabetic Retinopathy (DR) severity into No DR, Mild DR, and Referable DR (Moderate/Severe/Proliferative) from retinal images, with a focus on underrepresented populations in AI research. The train and validation datasets for the DNN were obtained from the APTOS 2019 Blindness Detection dataset on Kaggle. 

The importance of this project lies in the fact that DR is a leading cause of blindness among individuals aged 20-79 years, and all people living with diabetes are at risk of developing the condition. However, in developing countries that account for about 80% of the world's diabetes burden, a shortage of resources makes it difficult to effectively diagnose and treat DR.

The project's objectives were successfully achieved, as the resulting DNN model showed high performance in detecting DR, achieving a Quadratic Weighted Kappa (QWK) score of 88.9% and sensitivity score of 87%. The model can be further enhanced by exploring a combination of different preprocessing techniques, incorporating more data from diverse populations and optimising the model's hyperparameters.

The model was deployed and can be freely accessed via the following link: https://huggingface.co/spaces/MBA98/DiabeticRetinopathyDetection. 
