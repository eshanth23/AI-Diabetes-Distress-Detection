<img width="480" height="371" alt="image" src="https://github.com/user-attachments/assets/da7c1043-28e9-4008-b799-e94dec94f9d3" />


# 🧠 AI-Based Diabetes Distress Detection System  
🏆 People’s Choice Winner – Paul English Applied AI Institute Fall Symposium 2025  

![GitHub stars](https://img.shields.io/github/stars/eshanth23/AI-Diabetes-Distress-Detection?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/eshanth23/AI-Diabetes-Distress-Detection?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/eshanth23/AI-Diabetes-Distress-Detection?style=for-the-badge)
![License](https://img.shields.io/github/license/eshanth23/AI-Diabetes-Distress-Detection?style=for-the-badge)
![Last Commit](https://img.shields.io/github/last-commit/eshanth23/AI-Diabetes-Distress-Detection?style=for-the-badge)

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![React](https://img.shields.io/badge/React-TypeScript-blue?style=for-the-badge&logo=react)
![Node.js](https://img.shields.io/badge/Node.js-Backend-green?style=for-the-badge&logo=node.js)
![Gemini API](https://img.shields.io/badge/LLM-Gemini-orange?style=for-the-badge)

🧠 AI-Based Diabetes Distress Detection System

🏆 People’s Choice Winner – Paul English Applied AI Institute Fall Symposium 2025

🚀 Overview

This project presents an AI-powered system that analyzes patient conversations (audio/transcripts) to detect hidden emotional distress in individuals managing chronic diseases like diabetes.

Patients often do not explicitly express feelings like anxiety, frustration, or burnout. Our system identifies these latent emotional cues to support early intervention, improved communication, and better healthcare outcomes.

💡 Problem Statement

Traditional clinical assessments often miss real-time emotional distress, as patients may not openly communicate their struggles.

➡️ This leads to:

Delayed interventions
Poor adherence to treatment
Increased risk of complications
🎯 Our Solution

We built a hybrid AI system that:

Analyzes patient transcripts using LLMs (Gemini API)
Classifies distress into Low / Medium / High
Generates a 0–100 distress score
Extracts evidence spans from text
Provides supportive, non-diagnostic recommendations
🧠 Key Features
🔍 Distress Detection
Identifies emotional cues like fear, frustration, overwhelm
Maps outputs to clinically relevant distress levels
📊 Explainable AI
Highlights exact text evidence behind predictions
Provides high-level reasoning for transparency
⚖️ Hybrid Approach
Combines:
LLM-based predictions
Heuristic (rule-based) scoring
Enables validation and comparison
🏥 Clinical Alignment
Validated against Diabetes Distress Scale (DDS-17)
Collaborated with nursing PhD researchers
🏗️ System Architecture
Patient Transcript
        ↓
   LLM Analysis (Gemini)
        ↓
 Distress Score (0–100)
        ↓
Classification (Low / Medium / High)
        ↓
 Evidence + Recommendations
        ↓
Heuristic Comparison + Evaluation
📈 Evaluation Strategy (Planned)

We evaluate the model using:

Classification Accuracy (Low/Medium/High)
Precision, Recall, F1-score
Mean Absolute Error (MAE) for numeric scores
Comparison with:
Heuristic baseline
Expert-labeled ground truth
🖥️ Tech Stack
AI/ML: LLMs (Gemini API), NLP, Prompt Engineering
Frontend: React, TypeScript
Backend: Node.js / Express (if applicable)
Other: Heuristic Modeling, Data Analysis
👥 Team

Dynamo2Diabetes

Eshanth Kumar
Sankalp Vaish
Clark Ohlenbusch
Musah Abubakari

Faculty Mentors:

Xiaohui Liang
Michelle D. S. Boakye, PhD, MPH, RN
🌍 Impact
Detects hidden emotional distress in patients
Enables early intervention
Improves patient–provider communication
Supports behavioral health referrals
Scalable for real-world healthcare systems
🔮 Future Work
Expand ground truth dataset beyond 18 transcripts
Fine-tune models using expert-labeled data
Implement full evaluation pipeline
Integrate real-time voice analysis
Deploy in telehealth platforms
🏆 Achievement

🏅 People’s Choice Winner – PEAII Fall Symposium 2025

🤝 Contributions

Feel free to fork, contribute, or open issues!
Let’s build AI that makes healthcare more human. 💙

<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/drive/1EeHJOZiVanJP-L-bD2UWewYAJOhZ023o

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`
