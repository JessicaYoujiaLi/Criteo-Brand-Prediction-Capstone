# Criteo-Brand-Prediction-Capstone
Capstone Project on zero shot image segmentation sponsored by Criteo, Columbia University Fall 2024.  

This Capstone Project, a collaboration between Columbia University and Criteo, aims to enhance product brand recognition and categorization in Criteo's image catalog by developing a multi-tier embedding and classification framework. This approach combines image and text data, utilizing a pre-trained ResNet for image embeddings and DistilBERT for textual descriptions. These embeddings are concatenated to create a unified product representation, which serves as input for subsequent classification layers.

The framework features a three-tier design: the first tier generates unified embeddings; the second tier employs a neural network to predict product categories; and the third tier consists of category-specific neural networks trained exclusively on products within each category to predict brands. For products with missing brand or category labels, embeddings are processed through this hierarchical system to infer both attributes.  

Link to the Final Report: https://docs.google.com/document/d/1DgYAIO945XX4XblKokCUWvQdzF6yWko_aNkJm4LrlgI/edit?tab=t.0  


![Brand_prediction_poster]([https://github.com/user-attachments/assets/5bc27616-609f-4b24-8f5c-596c8ef8fe41](https://github.com/JessicaYoujiaLi/Criteo-Brand-Prediction-Capstone/blob/main/Brand_prediction_poster.png))
