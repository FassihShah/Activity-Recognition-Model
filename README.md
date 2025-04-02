# Activity Recognition Model  

This project classifies activities using accelerometer and gyroscope data. It focuses on distinguishing between **"Open Door"** and **"Rub Hands"** activities.  

## 📂 Dataset  

The dataset is originally part of the **BBH dataset**, from which data for two sensors (**Accelerometer** and **Gyroscope**) and two activities (**"Open Door"** and **"Rub Hands"**) were extracted.  

### Processed Dataset Files:  
- `trainJinsAccelerometer.npy` – Training accelerometer data  
- `trainJinsGyroscope.npy` – Training gyroscope data  
- `trainLabels.npy` – Labels for training data  
- `testJinsAccelerometer.npy` – Testing accelerometer data  
- `testJinsGyroscope.npy` – Testing gyroscope data  
- `testLabels.npy` – Labels for testing data  

## 🚀 How It Works  

### 1️⃣ Data Extraction (`Data_Extraction.ipynb`)  
- Loads raw sensor data from the BBH dataset  
- Filters it to keep only **"Open Door"** (20) and **"Rub Hands"** (36) activities  
- Extracts data from **accelerometer** and **gyroscope** sensors  
- Saves the filtered dataset  

### 2️⃣ Model Training (`Activity_Monitoring.ipynb`)  
- Extracts statistical features (mean, max, min, etc.)  
- Trains a **Neural Network** and **Logistic Regression model**  
- Evaluates performance using accuracy and classification reports  

### 3️⃣ Project Report (`Project Report.pdf`)  
- Provides an overview of data processing, feature extraction, and model evaluation
