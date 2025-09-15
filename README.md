## ***IIT Kharagpur Data Science Hackathon 2025 (Semi-Finalist)***

## **Related to Multi-Class Classification for Research Paper Categorization**

### **Objective -** 
This hackathon challenges participants to develop an AI-driven system using the Pathway Framework to streamline the process of conference selection and research paper evaluation. The system will harness advanced language models, comparative analysis techniques, and streaming data frameworks to automate and optimize these tasks.

***Task : Research Paper Publishability Assessment*** 
A dataset of 150 research papers is provided for classification, with 15 labeled papers available for reference to guide the development of the framework. The framework should be designed to accurately classify papers into the appropriate category, ensuring that it can handle a wide range of research topics and maintain consistency across different types of content. The proposed framework must be capable of systematically analyzing these and other aspects of research papers to ensure a reliable and objective evaluation process. The solution should demonstrate high accuracy in detecting such issues, ensuring its applicability across a range of research domains and scalability for future use with larger datasets.

### **Solution (Methodology) :-**

1) Automated Extraction & Organization – Unzipped PDFs, sorted, and assigned labels (Published / Not Published) with subcategories (CVPR, EMNLP, KDD, NeurIPS, TMLR).

2) Smart Label Encoding – Combined metadata into structured labels (e.g., Published_CVPR) for classification.

3) Feature Engineering with BERT – Tokenized text combining PDF names and labels for contextual learning.

4) Fine-Tuned AI Model – Trained a BERT-based classifier with early stopping, achieving F1 Score = 1.0.

5) Robust Evaluation – Used confusion matrix, classification report, and weighted F1 to validate performance.

6) Semi-Deployment Ready – Enabled PDF name-based predictions & recommendations for real-time classification.


### **Evaluating Model Performance: F1 Score, and Confusion Matrix -**

*AI (BERT) model's F1 Score: 1.0*

------------------------------------------------------------------------------------------------------

<img width="600" height="550" alt="image" src="https://github.com/user-attachments/assets/b5e9b7b9-73c5-4f0c-846d-7cdc987fdc14" />

### **Semi-Deployment: PDF Name-Based Prediction and Recommendation**

<img width="600" height="427" alt="Screenshot (16)" src="https://github.com/user-attachments/assets/91721b2d-650b-4eac-baca-571c397f3a58" />



