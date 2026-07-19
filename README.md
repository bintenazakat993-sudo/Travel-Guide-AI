# Travel Guide AI

## Overview

Travel Guide AI is an AI-powered travel assistant built with **Python** and **Streamlit**. It helps users plan trips, discover destinations, estimate budgets, and get personalized travel recommendations through a simple and interactive interface.

---

# Features

* 🌍 AI-powered travel recommendations
* 📍 Destination suggestions based on user preferences
* 🗺️ Day-wise travel itinerary generation
* 💰 Estimated travel budget
* 🏨 Hotel recommendations
* 🍽️ Food and local cuisine suggestions
* 🚕 Transportation guidance
* 🌦️ Travel tips and best time to visit
* 🎒 Packing suggestions
* 📋 Trip summary
* 📄 Download travel plan as PDF
* 💬 Interactive chatbot interface
* ⚡ Fast and user-friendly Streamlit UI

---

# Technologies Used

* Python
* Streamlit
* Groq API (LLM)
* HTML
* CSS
* python-dotenv
* FPDF (for PDF generation)

---

# Project Structure

```text
TravelGuideAI/
│── app.py
│── requirements.txt
│── README.md
│── .env.example
│── assets/
│── utils/
└── generated_pdfs/
```

---

# Installation

1. Clone the repository

```bash
git clone <repository-link>
```

2. Open the project folder

```bash
cd TravelGuideAI
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Create a `.env` file

```env
GROQ_API_KEY=your_api_key_here
```

5. Run the application

```bash
streamlit run app.py
```

---

# How It Works

1. User enters travel details.
2. AI analyzes the request.
3. Personalized travel recommendations are generated.
4. The system creates an itinerary, budget, travel tips, and other suggestions.
5. Users can download the generated travel plan as a PDF.

---

# Future Improvements

* Live weather integration
* Google Maps integration
* Flight price comparison
* Hotel booking integration
* Multi-language support
* Voice assistant
* User login and trip history
* Currency converter

---

# Requirements

* Python 3.10+
* Streamlit
* Groq API Key
* Internet Connection

---

# Author

**Developed by:** Aneesa Nazakat

---

# License

This project is developed for educational and learning purposes.
