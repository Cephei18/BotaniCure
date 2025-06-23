# BotaniCure
Botanicure
AI-Powered Plant Disease Diagnosis and Remedy Recommendation

Overview
Botanicure is a Machine Learning-based application designed to assist farmers, gardeners, and agricultural professionals in identifying plant diseases through image analysis. By simply uploading a photo of an infected plant, users can receive accurate disease predictions along with appropriate treatment suggestions. This tool aims to enhance crop health, reduce pesticide misuse, and support sustainable agricultural practices.

Features
Upload images of infected plant leaves for analysis

Automatically detect plant diseases using a trained ML model

Receive recommended remedies and preventive measures

Scalable design to support multiple plant types and disease classes

Can be integrated into a web or mobile interface for user accessibility

Tech Stack
Machine Learning Framework: TensorFlow / PyTorch / Scikit-learn (select the appropriate one)

Model Type: Convolutional Neural Network (CNN)

Frontend: React / Streamlit / Flask / HTML-CSS (if applicable)

Backend: Flask / Django / FastAPI (if applicable)

Dataset: Publicly available plant disease datasets such as PlantVillage (mention exact dataset used)

Installation and Setup

How It Works
The user uploads an image of a plant leaf.

The image is preprocessed and passed through a trained CNN model.

The model predicts the disease class.

Based on the prediction, the application retrieves appropriate remedies from a predefined database or rule set.

Future Enhancements
Expand support for more plant species and regional diseases

Integrate real-time mobile camera diagnosis

Integration with agricultural databases or government advisory systems


Acknowledgments
PlantVillage Dataset

