---

# **AI-Powered Screen Time & Well-Being Analysis**  

## **Overview**  
This project is part of the **main repository** and focuses on **AI-driven screen time management** using **Recurrent Neural Networks (RNNs) and GRUs**. It provides insights into **screen usage trends, cognitive overload, and emotional well-being**. **Gemini AI** is integrated for **app categorization and trend analysis**, helping users manage their time effectively.  

## **Key Features**  

### **1. Screen Time Prediction (RNN-Based)**  
- **Predicts future screen time** using an RNN model trained on historical data.  
- **Detects peak usage periods** and alerts users to potential overuse.  
- **Outperforms traditional models** in efficiency and adaptability.  

### **2. App Categorization & Trend Analysis (Gemini AI)**  
- **Classifies apps** into **General, Social Media, or Other**.  
- **Analyzes trends** (increasing, stable, or declining) using AI insights.  
- **Enhances self-awareness** of addictive or excessive usage patterns.  

### **3. Cognitive Overload Prediction (GRU-Based)**  
- **Detects stress & fatigue levels** from user behavior patterns.  
- **Recommends breaks & work-rest balance** based on AI predictions.  
- **Uses GRUs for superior sequential analysis over standard RNNs.**  

### **4. Social & Emotional Analysis**  
- **Extracts sentiment trends** from user interactions (text, voice, behavior).  
- **Suggests social engagement or self-care activities** based on AI-driven emotional insights.  

## **Screenshots** 

![Screenshot 1](img/Screenshot%202025-02-24%20034920.png)

![Screenshot 2](img/Screenshot%202025-02-23%20172404.png)

![Screenshot 3](img/Screenshot%202025-02-23%20182109.png)

![Screenshot 4](img/a7789d0a-b2e4-47f9-8fb9-f653ebd77a37.jfif)

## **Technical Implementation**  

### **📌 Data Processing:**  
- **Datasets:** `screentime_analysis.csv` + Kaggle Lifestyle & Wellbeing Data.  
- **Preprocessing:** Normalization, datetime conversion, missing value handling.  

### **📌 RNN-Based Model (Screen Time Prediction):**  
- **Architecture:** Two SimpleRNN layers, Dropout (20%), Dense output layer.  
- **Optimizer:** Adam, **Learning Rate:** 0.001.  
- **Peak Usage Detection:** 90th percentile threshold for alerts.  

### **📌 GRU-Based Model (Cognitive Overload Analysis):**  
- **Sequential behavioral modeling** with multiple GRU layers.  
- **Evaluation Metrics:** Accuracy, Precision, Recall, MSE.  

### **📌 Gemini AI Integration:**  
- **App Categorization Query:** AI classifies apps as **General, Social Media, or Other**.  
- **Trend Analysis Query:** AI summarizes increasing/stable/declining usage patterns.  
- **Caching enabled** to optimize performance.  

## **Why This Model?**  

| Feature                  | AI-Powered (RNN + Gemini AI) | Traditional Methods |
|--------------------------|----------------------------|---------------------|
| **Future Usage Prediction** | ✅ Yes | ❌ No |
| **Peak Usage Alerts** | ✅ Yes | ❌ No |
| **App Categorization** | ✅ AI-driven | ❌ Manual |
| **Trend Analysis** | ✅ AI-generated | ❌ Raw Data |
| **Cognitive Overload Detection** | ✅ GRU-based | ❌ No |
| **Social & Emotional Insights** | ✅ AI-Powered | ❌ No Analysis |

## **Future Enhancements**  
- **Fine-tune hyperparameters** for improved accuracy.  
- **Explore hybrid models** (RNN + Attention Mechanisms).  
- **Personalized recommendations** for optimized screen time management.  

---  
This module is a crucial part of the **main repository**, enhancing AI-driven digital well-being and productivity insights. 🚀