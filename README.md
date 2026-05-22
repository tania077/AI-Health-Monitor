# 🫀 AI Health Monitor

An AI-powered health monitoring dashboard that analyzes patient vitals in real-time using the Claude AI API. Built as a beginner-friendly project demonstrating AI API integration, health data visualization, and modern web UI design.

![AI Health Monitor](https://img.shields.io/badge/Status-Active-00f5c4) ![HTML](https://img.shields.io/badge/HTML5-orange) ![JavaScript](https://img.shields.io/badge/JavaScript-yellow) ![Claude AI](https://img.shields.io/badge/Claude_AI-purple)

---

## ✨ Features

- **Real-time Vitals Dashboard** — Displays Heart Rate, Blood Pressure, Temperature, and Blood Oxygen with mini trend charts
- **AI Health Analysis** — Sends vitals to Claude AI and displays a personalized health assessment
- **Risk Level Detection** — Automatically flags Low / Medium / High risk based on vital ranges
- **Alert System** — Visual banners when readings are outside normal ranges
- **Reading History** — Tracks the last 5 patient readings in the session
- **Typing Animation** — AI responses appear with a live typing effect

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 / CSS3 | Structure & styling |
| Vanilla JavaScript | Logic, DOM manipulation |
| Claude AI API | Health analysis & recommendations |
| Google Fonts | Typography (Syne + Space Mono) |

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/ai-health-monitor.git
cd ai-health-monitor
```

### 2. Open in browser
Just open `index.html` in any modern browser — no build tools or server needed!

```bash
# On Mac
open index.html

# On Linux
xdg-open index.html

# Or simply drag and drop into Chrome/Firefox
```

### 3. API Key Setup
The app uses the Anthropic Claude API. To use the AI analysis feature, you need an API key.

> **Note:** In a production app, the API key should be stored securely on a backend server. For this demo/portfolio project, the key is handled by the Claude.ai artifact environment.

---

## 📊 Normal Vital Ranges Used

| Vital | Normal Range |
|---|---|
| Heart Rate | 60 – 100 bpm |
| Systolic BP | 90 – 140 mmHg |
| Diastolic BP | 60 – 90 mmHg |
| Temperature | 97 – 99.5 °F |
| Blood Oxygen | 95 – 100 % |

---

## 🎯 How to Demo in an Interview

1. **Enter patient vitals** in the left panel (try normal values first)
2. Click **"Analyze with AI"** — watch the AI generate a health summary
3. Try **abnormal values** (e.g., HR: 130, BP: 160/100) to trigger alerts
4. Show the **risk badge** changing from Low → Medium → High
5. Point out the **reading history** tracking entries over time

### Key talking points:
- "I used the Claude AI API to send structured medical prompts and parse the response"
- "I implemented a rule-based risk scoring system before sending to AI"
- "The UI updates reactively using vanilla JS DOM manipulation"
- "I used CSS custom properties and animations for a polished look without any framework"

---

## 📁 Project Structure

```
ai-health-monitor/
│
├── index.html          # Single-file app (HTML + CSS + JS)
└── README.md           # This file
```

---

## ⚠️ Disclaimer

This project is for **educational and portfolio purposes only**. It is **not a medical device** and should not be used for real medical decisions. Always consult a qualified healthcare professional for medical advice.

---

## 🙋 Author

**Your Name**  
[LinkedIn](https://linkedin.com/in/yourprofile) · [GitHub](https://github.com/yourusername)

---

## 📄 License

MIT License — feel free to use and modify for your own portfolio!
