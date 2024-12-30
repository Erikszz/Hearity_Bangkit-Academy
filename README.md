# 📅 Daily Hearing Loss Forecasting for Heavy Machinery Workers: Leveraging Machine Learning in Time Series

### **Background: Hearing Loss in Heavy Machinery Workers👂🛠️**

Heavy machinery workers are exposed to noisy environments (85 dB or higher) for up to 8 hours daily, which can lead to gradual hearing loss over time. Despite safety measures like earplugs and earmuffs, workers often neglect to use them due to discomfort, lack of enforcement, or a false sense of security. This gradual hearing loss is hard to detect until it becomes severe, and many workers are unaware of the irreversible nature of noise-induced hearing damage.

### **Problem Statement** :
* **Gradual Hearing Loss 👂** : Hearing deterioration in noisy environments occurs slowly, making it hard to track without continuous monitoring.

* **Infrequent Testing 🗓️** : Hearing tests are done only every six months, leaving gaps in tracking daily noise exposure impacts.
* **Neglected Hearing Protection 🚫🦻** : Workers often neglect hearing protection, contributing to gradual hearing loss.
* **Awareness Gap ⚠️** : Workers lack awareness about the long-term effects of noise exposure and the importance of consistent hearing protection.
* **Absence of Daily Tracking 📉** : While test results provide a snapshot of hearing condition on a specific day (day-0), there’s no system to forecast or predict hearing deterioration on subsequent days (day-1 and beyond), especially with the continuous exposure to harmful noise.

### **📜Data Overview** :
This dataset was obtained through an interview with an audiologist who previously conducted hearing tests for workers in this field. I then combined this information with my own knowledge gained from working in the industry to avoid any potential bias.

#### **Data Interval**:
- **Start Date**: 2022/01/15
- **End Date**: 2023/07/27

The dataset contains hearing test results used to track hearing deterioration over time, specifically for workers exposed to high noise environments.

For more details, you can access the dataset [here](https://github.com/Erikszz/Bangkit-Academy_Hearity/tree/main/ml-forecasting/data/).

Below are the first 5 tables of the dataset:

[![First 5 Tables](img/)](https://github.com/Erikszz/Bangkit-Academy_Hearity/tree/main/img/first_5_rows.png)

### **⚔️Language, Tools, and Depedencies⚔️**
#### **📊Machine Learning** : 
     - 🐍 Python
     - 📚 Pandas
     - 🔢 Numpy
     - 🔮TensorFlow
     - ⚙️ Scikit-learn
     - 📦 Pickle
     - 📈 Matplotlib
     - ⚙️ Flask
     - 🐳 Docker
     - 📒Jupyter Notebook, 📙Google Colab

#### **🔗Data Pipeline** :
     - 🐍 Python, 💻 SQL 
     - 📚 Pandas
     - 🔢 Numpy
     - 🐳 Docker, 🐋 docker-compose
     - 🌬️ Apache Airflow
     - ☁️ Cloud:
          - 🖥️ Google Compute Engine (VM)
          - 🔍 Google BigQuery
          - 🔑 Google Secrets Manager
          - 🚀 Cloud Run

### **📇Data Pipeline View**
[![Data Pipeline](img/)](https://github.com/Erikszz/Bangkit-Academy_Hearity/tree/main/img/data_pipeline.png)

### **🌬️Apache Airflow Webserver** :
[![Airflow Webserver](img/)](https://github.com/Erikszz/Bangkit-Academy_Hearity/tree/main/img/airflow_webserver.png)

### **App overview** :
[![App Overview](img/)](https://github.com/Erikszz/Bangkit-Academy_Hearity/tree/main/img/hearity_app.png)

### **For Further Explanations**:
[!Project Briefing](https://github.com/Erikszz/Bangkit-Academy_Hearity/tree/main/Explanations-Hearity.pdf)