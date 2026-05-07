# 🧠 Affective Focus Tracker

An emotion-aware task management prototype designed to mitigate cognitive overload and prevent user burnout. This project extends a standard to-do list by integrating **Affective Computing** through a lightweight, client-side Natural Language Processing (NLP) heuristic.

## ✨ Key Features

* **Lexicon-Based Emotion Detection:** Automatically analyzes the text of your tasks to determine if they are high-stress (negative valence) or low-stress (positive valence).
* **Burnout Intervention:** Actively monitors your cognitive load. If you accumulate too many incomplete high-stress tasks, the app triggers a "High Cognitive Load" visual warning to encourage breaks or reprioritization.
* **Human-in-the-Loop (HITL) Machine Learning:** The AI learns your personal stressors. Click on any task's emotion tag to correct the system's prediction; the app will update its localized dictionary and remember your specific vocabulary for future tasks.
* **100% Privacy Preserving:** No external API calls or databases. All emotion detection happens locally, and your custom vocabulary is saved securely in your browser's `localStorage`.

## 🛠️ Technology Stack

* **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
* **Data Storage:** Browser LocalStorage
* **AI/Logic:** Custom Lexicon-based Sentiment Analysis with Stop-Word filtering

## 🚀 How to Run Locally

Because this project is built entirely with vanilla web technologies, there are no dependencies, build steps, or servers required.

1. Clone this repository:
   ```bash
   git clone [https://github.com/kyrariii/affective-focus-tracker.git](https://github.com/kyrariii/affective-focus-tracker.git)