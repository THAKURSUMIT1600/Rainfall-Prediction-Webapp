
# 🌧️ RainVision (Rainfall Prediction Web App)

A web-based application for predicting rainfall using a trained machine learning model. Built with **Flask** for the backend and **HTML, CSS, JavaScript** for the frontend, this app provides real-time predictions based on user-input weather parameters.

## 🚀 Live Demo

👉 [Access the Web App](https://flask-92z9.onrender.com/)

---

## 📌 Features

🌧️ Rainfall Prediction: Provides accurate predictions based on user-provided weather parameters such as temperature, humidity, and pressure.

⚙️ Flask Backend: Seamlessly integrates a pre-trained machine learning model to process inputs and generate predictions.

🎨 User-Friendly Interface: A clean, intuitive, and responsive design for an enhanced user experience across all devices.

🌐 Cloud-Hosted: Deployed on Render, ensuring reliable, fast, and scalable performance.

---

## 🧠 How It Works

1. User Input: Users provide key weather parameters such as temperature, humidity, and pressure through an intuitive form.

2. Data Submission: The input data is securely sent to the Flask server for processing.

3. Model Prediction: The pre-trained machine learning model analyzes the data and generates a rainfall prediction based on the inputs.

4. Dynamic Results: The predicted rainfall is displayed in real-time on the webpage, offering immediate feedback to the user.

---

## 🛠️ Tech Stack

| Layer        | Technology             |
|--------------|------------------------|
| Frontend     | HTML, CSS, JavaScript  |
| Backend      | Flask (Python)         |
| Deployment   | Render                 |

---

## 📁 Project Structure

```
rainfall-prediction-webapp/
│
├── static/                 # CSS and JavaScript files
├── templates/              # HTML templates
├── xgb.pkl and scaler.pkl  # Pre-trained ML model (e.g., model.pkl)
├── app.py                  # Flask application entry point
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/THAKURSUMIT1600/rainfall-prediction-webapp.git
cd rainfall-prediction-webapp
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Application

```bash
python app.py
```

Visit `http://127.0.0.1:5000/` in your browser to use the app locally.

---

## 📷 Screenshots

<!-- Screenshot 1 -->
<div style="background-color: #f0f8ff; padding: 15px; margin-bottom: 20px;">
    <img src="https://github.com/user-attachments/assets/9de7e2a9-38d3-4ab0-9b7a-5fbdfecd422c" alt="Screenshot 1" width="100%" />
</div>

<br> <!-- Line gap -->

<!-- Screenshot 2 -->
<div style="background-color: #e6f7ff; padding: 15px; margin-bottom: 20px;">
    <img src="https://github.com/user-attachments/assets/4f038315-ed9b-4fcc-a295-964b92df7f08" alt="Screenshot 2" width="100%" />
</div>

<br> <!-- Line gap -->

<!-- Screenshot 3 -->
<div style="background-color: #d9f7ff; padding: 15px; margin-bottom: 20px;">
    <img src="https://github.com/user-attachments/assets/de84fb98-ea91-402b-8cd1-f9e68841d7dc" alt="Screenshot 3" width="100%" />
</div>


## ✅ Future Enhancements

- 🌩️ **Integrate real-time weather APIs**: Enhance the app by fetching real-time weather data for more accurate predictions.
- 📊 **Improve model accuracy**: Incorporate additional weather-related parameters and optimize the model for better performance.
- 🔐 **User authentication & data logging**: Implement user authentication for personalized experiences and store user input for analysis.
- 🌍 **Deploy to multiple platforms**: Expand deployment options by hosting the app on other platforms like **AWS** or **Vercel** for better scalability.

## 🤝 Contributing

I am always looking for **improvements** and **ideas** to enhance the project. If you have any suggestions, features you'd like to see, or ideas for optimization, please open an issue, and I’ll try to implement them as soon as possible.

---

**Developed with ❤️ by Sumit**
