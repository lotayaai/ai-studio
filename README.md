# Lotaya AI Design Studio

[![Build Status](https://github.com/lotayaai/ai-studio/actions/workflows/deploy.yml/badge.svg)](https://github.com/lotayaai/ai-studio/actions) 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/lotayaai/ai-studio/blob/main/LICENSE)
[![Made with Firebase](https://img.shields.io/badge/Made%20with-Firebase-orange)](https://firebase.google.com/) 
[![Powered by Vertex AI](https://img.shields.io/badge/Powered%20by-Vertex%20AI-blue)](https://cloud.google.com/vertex-ai)

An AI-powered design platform built with **Next.js**, **Firebase**, and **Google Cloud Vertex AI**.  
It enables creators to:

- 🎨 Generate logos with AI  
- 🎥 Create short-form videos for TikTok, Instagram, and YouTube Shorts  
- ✍️ Collaborate in real time using intelligent design tools  
- 🔄 Manage content and assets with Firebase and Vertex AI  

---

## 🔗 Repository
[https://github.com/lotayaai/ai-studio](https://github.com/lotayaai/ai-studio)

---

## 🚀 Tech Stack

- **Frontend**: Next.js 14, Tailwind CSS  
- **Backend**: Firebase Functions, Node.js, Python Microservices  
- **AI**: Google Vertex AI (Gemini, Imagen, PaLM APIs)  
- **CI/CD**: Google Cloud Build, GitHub Actions  

---

## 📁 Project Structure

```
lotaya-ai-studio/
├── frontend/
│   ├── src/
│   │   ├── app/
│   │   │   ├── dashboard/
│   │   │   │   ├── logo-generator/
│   │   │   │   └── video-tool/
│   │   │   ├── api/
│   │   │   └── layout.tsx
│   │   ├── components/
│   │   ├── lib/
│   ├── public/
│   └── next.config.js
├── backend/
│   ├── firebase/
│   │   └── functions/
│   └── ai-microservices/
├── devops/
│   └── cloudbuild.yaml
├── docs/
│   ├── API_REFERENCE.md
│   └── SETUP.md
├── .github/
│   ├── workflows/
│   └── ISSUE_TEMPLATE/
├── .env.example
├── docker-compose.yml
├── firebase.json
├── LICENSE
└── README.md
```

---

## 📦 Installation

Clone the repository:
```bash
git clone https://github.com/lotayaai/ai-studio.git
cd ai-studio
```

Install dependencies:
```bash
cd frontend && npm install
cd ../backend/firebase/functions && npm install
```

Setup environment:
```bash
cp .env.example .env
```

Run locally:
```bash
npm run dev   # From /frontend directory
```

---

## 📬 Contact
info@lotaya.io
