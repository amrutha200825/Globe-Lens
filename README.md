# 🌍 Globe Lens

### AI-Powered Travel Assistance Platform

> **Explore Smarter. Travel Better.**

Globe Lens is an AI-powered travel assistance platform designed to make travel more convenient, accessible, and informed. It brings essential travel capabilities such as trip planning, budget management, translation, navigation, local discovery, cultural guidance, and emergency information together in one unified platform.

---

## 📌 Problem Statement

Travelers exploring unfamiliar destinations often face difficulties with language barriers, navigation, discovering local attractions and food, understanding cultural practices, managing travel expenses, and accessing emergency information.

Although different applications provide solutions for these individual problems, travelers often need to switch between multiple platforms. This fragmented experience can make travel planning and assistance complicated and time-consuming.

Globe Lens addresses this problem by providing multiple essential travel-assistance capabilities through a single AI-powered platform.

---

## 💡 Our Solution

Globe Lens acts as a unified digital travel assistant that helps users before and during their journey.

The platform combines **Artificial Intelligence, Machine Learning, Natural Language Processing, Computer Vision, Speech Processing, Translation, and Location-Based Services** to provide practical travel assistance.

### Core capabilities:

* 🗺️ AI Trip Planning
* 💰 Budget-Aware Planning
* 📷 Camera Translation
* 🎙️ Voice Translation
* 🧭 Camera-Based Route Guidance
* 🍜 Local Food Guide
* 🏛️ Attraction Discovery
* 🌏 Cultural Guidelines
* 🚨 Local Emergency Information

---

## ✨ Features

### 🧳 Plan

#### AI Trip Planner

Helps users organize their travel plans based on their destination and travel requirements.

#### Budget-Aware Planning

Helps travelers consider their available budget while planning travel-related expenses.

---

### 🗣️ Communicate

#### Camera Translation

Allows users to capture text such as signboards, menus, notices, and other travel-related information and obtain translated results.

#### Voice Translation

Supports communication between travelers and local people by processing spoken input and providing translated output.

---

### 🧭 Navigate

#### Camera-Based Route Guidance

Uses camera-based visual assistance and location information to help travelers understand their surroundings and navigate unfamiliar places.

---

### 🔎 Discover

#### Local Food Guide

Helps travelers discover local food and culinary experiences.

#### Attraction Discovery

Helps users find places of interest and attractions around their destination.

#### Cultural Guidelines

Provides information about local customs, practices, and appropriate cultural behavior.

---

### 🛡️ Safety

#### Local Emergency Information

Provides access to relevant emergency information and important local services when travelers need assistance.

---

## 🔄 How Globe Lens Works

```text
             ┌─────────────────────┐
             │      Traveler       │
             └──────────┬──────────┘
                        │
                        ▼
             ┌─────────────────────┐
             │     Globe Lens      │
             │   AI Travel System  │
             └──────────┬──────────┘
                        │
       ┌────────────────┼────────────────┐
       │                │                │
       ▼                ▼                ▼
    PLAN           COMMUNICATE       NAVIGATE
       │                │                │
       ▼                ▼                ▼
 AI Trip Planner   Translation     Camera Route
 Budget Planning   Voice Support    Guidance
       │                │                │
       └────────────────┼────────────────┘
                        │
                        ▼
                  ┌─────────────┐
                  │  DISCOVER   │
                  └──────┬──────┘
                         │
             ┌───────────┼───────────┐
             ▼           ▼           ▼
         Attractions   Local Food   Culture
                         │
                         ▼
                  ┌─────────────┐
                  │    SAFETY   │
                  └──────┬──────┘
                         │
                         ▼
                Emergency Information
```

---

## 🏗️ System Architecture

```text
                    ┌───────────────────┐
                    │     User /        │
                    │     Traveler      │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │   React Frontend  │
                    │   HTML / CSS / JS │
                    └─────────┬─────────┘
                              │
                         REST APIs
                              │
                              ▼
                    ┌───────────────────┐
                    │   FastAPI Backend │
                    │      Python       │
                    └─────────┬─────────┘
                              │
          ┌───────────────────┼───────────────────┐
          │                   │                   │
          ▼                   ▼                   ▼
     AI / ML / NLP      Computer Vision      Location Services
          │                   │                   │
          ▼                   ▼                   ▼
    Generative AI       OpenCV / OCR       Maps / Geolocation
    Recommendations                         Places / Weather
          │
          ▼
     ┌───────────────┐
     │ MySQL Database│
     └───────────────┘
```

---

## 🛠️ Technology Stack

### Frontend

* React.js
* HTML5
* CSS3
* JavaScript

### Backend

* Python
* FastAPI
* REST APIs

### AI & Machine Learning

* Machine Learning
* Natural Language Processing (NLP)
* Generative AI
* Recommendation Systems

### Computer Vision

* OpenCV
* Tesseract OCR

### Speech Processing

* Speech-to-Text (STT)
* Text-to-Speech (TTS)
* Voice Processing

### Translation

* AI/NLP-based Translation APIs

### Maps & Location

* Maps APIs
* Geolocation APIs
* Location-Based Services
* Places/Attractions APIs
* Weather APIs

### Database

* MySQL

### Development Tools

* VS Code
* Git
* GitHub

---

## 🎯 Objectives

* Provide a unified travel assistance platform.
* Reduce dependence on multiple separate travel applications.
* Help travelers overcome language and communication barriers.
* Improve navigation in unfamiliar environments.
* Assist travelers in discovering local attractions and food.
* Promote awareness of local cultural practices.
* Support budget-conscious travel planning.
* Provide easy access to local emergency information.
* Make travel assistance more accessible and convenient through AI.

---

## 🌟 Key Advantages

* **Unified Platform** – Multiple travel-assistance capabilities in one system.
* **AI-Powered Assistance** – Uses AI and ML to provide intelligent travel support.
* **Visual Assistance** – Uses camera-based technologies for translation and navigation.
* **Budget Awareness** – Helps users plan according to their available budget.
* **Local Discovery** – Supports exploration of attractions and local food.
* **Cultural Awareness** – Helps travelers understand local customs and practices.
* **Safety Support** – Provides important local emergency information.
* **User-Friendly Experience** – Designed to keep travel assistance simple and accessible.

---

## 🚀 Future Scope

Future versions of Globe Lens can be extended with:

* Advanced multilingual conversational assistance
* Augmented Reality-based navigation
* Personalized travel recommendations
* Offline travel assistance
* Real-time transportation information
* Advanced voice-based travel interaction
* More comprehensive destination intelligence
* Integration with travel booking services
* Enhanced visual recognition for landmarks and surroundings

---

## 📂 Project Structure

```text
Globe-Lens/
│
├── frontend/
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── services/
│       └── App.jsx
│
├── backend/
│   ├── app/
│   ├── routes/
│   ├── services/
│   ├── models/
│   └── main.py
│
├── database/
│   └── schema.sql
│
├── docs/
│
├── README.md
└── LICENSE
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/globe-lens.git
cd globe-lens
```

### 2. Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### 3. Backend Setup

Create and activate a Python virtual environment:

```bash
cd backend
python -m venv venv
```

Windows:

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Start the FastAPI server:

```bash
uvicorn main:app --reload
```

---

## 🔐 Environment Variables

Create a `.env` file in the backend directory and add the required API credentials.

```env
DATABASE_URL=your_mysql_database_url
MAPS_API_KEY=your_maps_api_key
TRANSLATION_API_KEY=your_translation_api_key
WEATHER_API_KEY=your_weather_api_key
AI_API_KEY=your_ai_api_key
```

> **Note:** Never commit API keys, passwords, or other sensitive credentials to GitHub.

---

## 📸 Application Modules

Globe Lens can be organized into the following major modules:

```text
Globe Lens
│
├── AI Trip Planner
├── Budget-Aware Planning
├── Camera Translation
├── Voice Translation
├── Camera-Based Route Guidance
├── Local Food Guide
├── Attraction Discovery
├── Cultural Guidelines
└── Local Emergency Information
```

---

## 🎓 Use Cases

### Tourist

A traveler can use Globe Lens to plan a trip, estimate expenses, translate signs or menus, navigate unfamiliar areas, discover attractions and local food, understand cultural practices, and access emergency information.

### International Traveler

A traveler visiting a destination where they do not know the local language can use camera and voice translation to communicate and understand written information.

### Budget Traveler

A traveler with a limited budget can use budget-aware planning to organize their travel expenses.

### First-Time Visitor

A first-time visitor can use attraction discovery, local food guidance, cultural guidelines, and route assistance to explore an unfamiliar destination more comfortably.

---

## 🔮 Vision

> **Globe Lens aims to make travel assistance simpler by bringing essential planning, communication, navigation, discovery, cultural, and safety support into one intelligent platform.**

---

## 👥 Team

### QYRA

Globe Lens is developed by **Team QYRA**, with a focus on building an AI-powered travel assistance platform that makes exploring unfamiliar destinations more convenient, accessible, and informed.

---


## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

**Globe Lens — Explore Smarter. Travel Better.**
