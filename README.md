# 🍽️ MacroSnap – AI Meal Analysis Assistant

MacroSnap is an AI-powered meal analysis application that uses **Google Gemini Vision** to analyze food images and provide useful information about the meal.

## 🚀 Features

* 📸 Upload or capture a meal photo
* 🤖 AI-powered food analysis using Google Gemini
* 🥗 Get estimated nutritional information
* 💬 Ask questions about the meal
* 📊 Get a simple meal summary
* 🖥️ Interactive Streamlit interface
* 🌐 Deployed as a web application

## 🛠️ Technologies Used

* Python
* Streamlit
* Google Gemini API
* Google GenAI SDK
* Pillow (PIL)

## ⚙️ How It Works

1. Upload or capture a photo of your meal.
2. MacroSnap sends the image to the Gemini Vision model.
3. Gemini analyzes the food in the image.
4. The application generates a meal analysis and nutritional summary.
5. Users can interact with the AI through the chat interface.

## 📂 Project Structure

```text
MacroSnap/
│
├── app.py
├── prompts.py
├── requirements.txt
├── README.md
└── .streamlit/
    └── secrets.toml
```

## 🔑 Environment Setup

Create a `.streamlit/secrets.toml` file and add your Gemini API key:

```toml
GEMINI_API_KEY = "your_api_key_here"
```

> ⚠️ Never upload your `secrets.toml` file or expose your API key publicly.

## ▶️ Run Locally

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Go to the project folder:

```bash
cd MacroSnap
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run app.py
```

## 🌐 Live Demo

🔗 **Live Project:** YOUR_DEPLOYED_APP_LINK

## 📌 Project Purpose

MacroSnap was developed to explore how **AI vision and conversational AI** can be used to analyze real-world meal images and provide an interactive user experience.

## 👨‍💻 Developer

**Monal Bansinge**

Electronics and Communication Engineering Student
Priyadarshini College of Engineering, Nagpur

---

⭐ If you find this project useful, consider giving the repository a star!
