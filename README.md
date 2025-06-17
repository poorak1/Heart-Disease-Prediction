#  Heart Disease Prediction using ANN

This project aims to predict the likelihood of heart disease in patients using a neural network model trained on health-related features. The goal is to demonstrate how Artificial Neural Networks (ANNs) can be applied to real-world biomedical data for classification tasks.

## 📊 Dataset

The dataset contains patient medical records, including features such as:

- `age`: Age of the patient
- `sex`: Gender (1 = male; 0 = female)
- `cp`: Chest pain type (0-3)
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol (mg/dl)
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- `restecg`: Resting electrocardiographic results
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina (1 = yes; 0 = no)
- `oldpeak`: ST depression induced by exercise relative to rest
- `slope`: The slope of the peak exercise ST segment
- `ca`: Number of major vessels colored by fluoroscopy (0-3)
- `thal`: Thalassemia (0 = normal; 1 = fixed defect; 2 = reversible defect)
- `target`: Diagnosis of heart disease (1 = disease; 0 = no disease)

## 🧠 Model

The core of the project is an **Artificial Neural Network (ANN)** built using:

- **TensorFlow / Keras** for model building and training
- **Matplotlib** and **Seaborn** for exploratory data analysis and visualization

The model is trained to classify whether a patient is likely to have heart disease (`target = 1`) or not (`target = 0`).

## 📈 Visualizations

The project includes feature-target visualizations such as:

- Count plots for categorical variables (e.g., sex, chest pain type)
- Box plots for continuous variables (e.g., age, cholesterol) grouped by target

These visualizations help understand the relationship between features and heart disease likelihood.

## 🧪 Evaluation

Metrics used:

- **Accuracy**
- **Confusion Matrix**
- **Precision, Recall, F1-score**


