# Air_Quality_Analysis

## 🌫️ Air Quality Prediction using RNN

A data-driven website to forecast PM1, PM2.5, and PM10 levels across Indian cities using meteorological data from **IMD, CPCB, and SNDTW UMIT**.  
It implements **Linear Regression** and **Recurrent Neural Networks (RNN)** to deliver:

- 📈 Real-time AQI forecasting  
- 🩺 Health recommendations  
- 🤖 Chatbot to answer queries on pollution & risks  
- 🌍 Scalable design for multi-city deployment  

Achieved **76%+ accuracy** in both Mumbai and Cuttack using RNN models.

---

## 🎥 Demo

[![thumbnail](https://github.com/user-attachments/assets/3564b325-ec72-4d31-a53d-93920f1621c3)](https://drive.google.com/file/d/1O4g1La0qRpUpgUQJGbr07JhDZUv8PkMX/view?usp=sharing)

📁 **Google Drive Backup:**  
[Click to open Drive folder](https://drive.google.com/drive/folders/1NvrZ3rHPXfbF43-JT4elk-dBGKWYRu_q)

---

## 📊 Results & Observations

### 🏙️ Mumbai

**PM2.5 Equation:**
```
PM2.5 = 0.0000 * INDEX + 3.3150 * MAX - 4.6039 * MIN - 2.5933 * AW + 48.1042
```

**PM10 Equation:**
```
PM10 = 0.0000 * INDEX + 7.6420 * MAX - 6.9687 * MIN - 4.1669 * AW + 15.7419
```

**📈 R² Score:** **0.7611**

✔️ Positive impact of MAX temperature  
❌ Negative impact of MIN temperature and wind speed (AW)

---

### 🌾 Odisha - Cuttack

**PM2.5 Equation:**
```
PM2.5 = 0.0000 * INDEX - 0.1707 * MAX - 3.0020 * MIN + 97.5438
```

**PM10 Equation:**
```
PM10 = 0.0000 * INDEX + 0.2133 * MAX - 10.1975 * MIN + 295.3829
```

**📈 R² Score:** **0.7569**

❌ Strong negative correlation with MIN temperature  
➕ Slight positive correlation with MAX  
🚫 INDEX was found statistically insignificant

---

## ⚙️ Features

- 🔍 AQI predictions for PM1, PM2.5, PM10  
- 👥 Personalized health-based feedback  
- 🤖 Chatbot for environmental awareness  
- 📊 Linear Regression & RNN models  
- 📱 Clean UI & mobile-friendly experience  

---

