# Air_Quality_Analysis
Air Quality Prediction using RNN A web app that forecasts PM1 levels across Indian regions using IMD, CPCB, and SNDTW UMIT data. It uses Linear Regression and RNN (76%+ accuracy) to provide real-time AQI, health advice, and a chatbot for pollution-related queries. Scalable for advanced data integration

# 🌫️ Air Quality Forecasting and Health Recommendation System

This project presents a data-driven web application for forecasting **PM1 (Particulate Matter)** concentrations across Indian regions using meteorological data from **IMD, CPCB, and SNDTW UMIT**. Leveraging **Linear Regression** and **Recurrent Neural Network (RNN)** models, the system delivers real-time air quality predictions, personalized health recommendations, and an intelligent chatbot assistant.

---

## 🎥 Project Demonstration

<video width="100%" controls>
  <source src="https://github.com/IqraMiyaji/Air_Quality_Analysis/blob/main/prototype_aqi.mp4?raw=true" type="video/mp4">
  Your browser does not support the video tag.
</video>

📎 **[Access full report and project resources on Google Drive →](https://drive.google.com/drive/folders/1NvrZ3rHPXfbF43-JT4elk-dBGKWYRu_q)**

---

## ✨ Key Features

- 🔍 Real-time AQI and PM1 prediction using live meteorological data
- 📈 RNN model accuracy: 76% (Mumbai), 76.11% (Odisha-Cuttack)
- 💬 Interactive chatbot for pollution-related health guidance
- 🧠 Personalized health recommendations by population risk groups
- 🌐 User-friendly web interface for immediate predictions

---

## 📊 Results and Observations

### 📍 Mumbai

- **PM₂.₅** = 0.0000 × INDEX + 3.3150 × MAX − 4.6039 × MIN − 2.5933 × AW + 48.1042  
- **PM₁₀** = 0.0000 × INDEX + 7.6420 × MAX − 6.9687 × MIN − 4.1669 × AW + 15.7419  
- **R² Score:** 0.7611

> Maximum temperature shows a positive correlation with PM levels. Minimum temperature and wind speed (AW) have a negative effect, especially on PM₁₀.

### 📍 Odisha

- **PM₂.₅** = 0.0000 × INDEX − 0.1707 × MAX − 3.0020 × MIN + 97.5438  
- **PM₁₀** = 0.0000 × INDEX + 0.2133 × MAX − 10.1975 × MIN + 295.3829  
- **R² Score:** 0.7569

> Minimum temperature has a stronger negative influence on PM₁₀. INDEX showed negligible statistical significance in both states.

---

## 🧰 Tech Stack

- **Languages & Frameworks:** Python, Flask / Django
- **ML Libraries:** TensorFlow, Keras, Scikit-learn
- **Frontend:** HTML, CSS, JavaScript
- **Deployment:** GitHub, Google Drive (Docs + Demo)

---

## 🔭 Future Enhancements

- Integration of real-world emission sources (e.g., traffic, industry)
- Improved accuracy using hybrid and ensemble ML models
- Advanced multilingual chatbot capabilities
- Mobile app development for accessibility

---

## 🤝 Contribution

Contributions are welcome! Feel free to fork the repository, open issues, or submit pull requests.

> Built with a focus on environmental health, public awareness, and real-world impact.
