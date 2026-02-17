# CVSpark AI 📄✨

**Smart Resume • Better Jobs**

CVSpark AI is a Flutter-based AI Resume Builder that helps users create ATS-friendly resumes, analyze job descriptions, identify skill gaps, and generate optimized resumes using AI.

---

## 🚀 Features

* 📄 ATS Resume Checker
* 🎯 Resume vs Job Description Match (JD Gap Analysis)
* 🤖 AI Resume Generator
* ✉️ Cover Letter Generator
* 🌍 Multi-language Resume Support
* 📊 Skill Gap Analysis & Suggestions
* 💳 Subscription & Credit System
* 📁 Resume History & Reports
* 👤 User Profile Management

---

## 🏗 Architecture

This project follows **MVVM + Clean Architecture**.

```
UI (Views) → ViewModel → UseCases → Repository → API / Services
```

### Layers

* **Presentation** → Views, ViewModels
* **Domain** → Entities, UseCases
* **Data** → Models, API Services, Repositories

---

## 📁 Project Structure

```
lib/
├── core/            # Theme, utils, constants, common widgets
├── data/            # Models, API services, repositories
├── domain/          # Entities and use cases
├── viewmodels/      # MVVM state management
├── views/           # UI screens
├── navigation/      # Routing
├── main.dart
├── app.dart
```

---

## 🎨 UI

* Gradient Splash Screen
* Modern AI theme (Blue + Purple)
* Clean Card-based UI
* Responsive Layout

---

## ⚙️ Tech Stack

* **Flutter (MVVM)**
* Provider (State Management)
* REST API (Python FastAPI backend)
* MongoDB (Cloud Database)
* AWS S3 (File Storage)
* Stripe (Payments)
* OpenAI / AI Engine

---

## 📦 Setup & Installation

### 1. Clone repository

```bash
git clone https://github.com/your-username/cvspark-ai.git
cd cvspark-ai
```

### 2. Install dependencies

```bash
flutter pub get
```

### 3. Add assets

Create folder:

```
assets/
```

Add logo:

```
assets/logo.png
```

Update `pubspec.yaml`:

```yaml
flutter:
  assets:
    - assets/logo.png
```

### 4. Run app

```bash
flutter run
```

---

## 🔐 Environment (Future Backend)

Create `.env` file for API:

```
API_BASE_URL=https://api.cvspark.ai
STRIPE_KEY=xxxx
```

---

## 📌 Roadmap

* [ ] Google / Apple Login
* [ ] Resume Parser Integration
* [ ] JD Matching AI
* [ ] Resume Generator AI
* [ ] Payment Integration
* [ ] Dark Mode
* [ ] Web Dashboard (React)

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first.

---

## 📄 License

MIT License © CVSpark AI

---

## 👨‍💻 Author

**CVSpark AI**
AI Resume Builder Platform
