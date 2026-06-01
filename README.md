# 📸 SnapClass — AI Powered Attendance System

## 🌐 Live Links
👉 [Live App](https://snapclass-ai-attendance-0505.streamlit.app/)
👉 [Landing Page](https://snap-class-landing-nine.vercel.app/)

## 📌 Overview
SnapClass is a next-generation AI-powered attendance management system that revolutionizes classroom attendance using computer vision and voice biometrics. 
Teachers can mark attendance via face recognition from a single class photo or through sequential voice identification — eliminating manual roll calls entirely.

## 🎯 Problem Statement
Traditional attendance marking wastes valuable class time and is prone to errors and proxies.
SnapClass automates the entire process using advanced AI — making attendance instant, accurate, secure and completely paperless.

## ✨ Key Features

### 👨‍🏫 For Teachers
- 🔐 Secure login & authentication
- 📊 Unified dashboard for all subjects
- 📷 FaceID attendance — scan entire class 
  from a single photo in milliseconds
- 🎙️ Voice ID attendance — students say 
  "Present" and AI matches voice biometrics
- 📱 QR code generation for instant 
  student enrollment
- 📈 Attendance records with confidence 
  scores & CSV export

### 🎓 For Students
- ⚡ Instant enrollment via QR code
- 🤖 One-time Face & Voice biometric 
  registration
- 📊 Personal dashboard with attendance 
  percentage across all subjects

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Core language |
| Streamlit | Frontend & deployment |
| Flask | Landing page backend |
| OpenCV | Computer vision |
| FaceRecognition + Dlib | Face biometrics |
| Resemblyzer + Librosa | Voice biometrics |
| Supabase (PostgreSQL) | Cloud database & auth |
| Vercel | Landing page hosting |

## 📊 Project Workflow
1. Teacher creates course & QR code generated
2. Students enroll via QR & register FaceID + VoiceID
3. Teacher starts attendance session
4. AI scans class photo OR matches voice inputs
5. Attendance auto-marked with confidence scores
6. Records saved to Supabase cloud database
7. CSV export & analytics available

## 👩‍💻 Author
**Swati Swagatika Sahoo**

B.Tech CSE @SUIIT

GitHub: https://github.com/swati-0505

Live App: https://snapclass-ai-attendance-0505.streamlit.app/

Landing: https://snap-class-landing-nine.vercel.app/
