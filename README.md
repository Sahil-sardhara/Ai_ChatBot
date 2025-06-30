# 🤖 AI ChatBot using Gemini API (Flutter)

An AI-powered chatbot built in Flutter using **Google's Gemini API** (Generative AI). This chatbot can respond to natural language queries, helping users with intelligent and context-aware answers.

---

## 🖼️ UI Screenshots & Demo

### 🧾 ChatScreen UI

This is the initial screen of the chatbot, where users can enter prompts and interact with the AI:

<div align="center">
  <img src="https://github.com/user-attachments/assets/5aa545f8-9cb6-4cc2-ad77-7ff7c6206d7e" alt="ChatScreen UI">
</div>

---

### 💬 Response of User Text

The chatbot responds in real-time using the Gemini API:

<div align="center">
  <img src="https://github.com/user-attachments/assets/75846812-014b-407f-a6e0-5b5922a7efb6" alt="Response of User Text">
</div>

---

### 📽️ Full Demonstration of APK

A complete walkthrough of the AI Chatbot in action:

<div align="center">

[https://github.com/user-attachments/assets/0c38a946-3e9c-4e0c-b305-688e5c473376](https://github.com/user-attachments/assets/0c38a946-3e9c-4e0c-b305-688e5c473376)

</div>



---

## ✨ Features

* 🔗 Integration with Google Gemini API
* 💬 Chat interface with instant responses
* 🌙 Dark-themed, mobile-friendly design
* 📜 Context-aware chat history
* 🧠 Uses Gemini Pro for intelligent text generation
* 🗂️ Clean folder structure with modular design
* 🔒 API key securely handled via local file

---

## 🚀 Getting Started

### 📋 Prerequisites (Tech Before Installation)

* ✅ Flutter SDK (3.x recommended)
* ✅ Dart
* ✅ Android/iOS emulator or real device
* ✅ Google Gemini API Key
* ✅ VSCode or Android Studio with Flutter plugin

---

### 🔧 Installation

```bash
git clone https://github.com/Sahil-Sardhara/Ai-ChatBot.git
cd Ai-ChatBot
flutter pub get
```

---

### 🔐 Set up your Gemini API Key

Create a file at `lib/secret.dart`:

```dart
const String GEMINI_API_KEY = "your-api-key-here";
```

Make sure it's ignored by Git:

```gitignore
lib/secret.dart
```

---

## 🧪 Usage

Run the app using:

```bash
flutter run
```

Try prompts like:

* “Who developed Flutter?”
* “Write a poem about the night sky.”
* “Explain machine learning in simple terms.”

---

## 🛠 Tech Stack

* **Flutter** – Mobile UI Framework
* **Dart** – Programming Language
* **HTTP** – For Gemini API communication
* **Gemini Pro** – Google Generative AI
* **GetX / Provider** – Optional state management

---

## 📁 Folder Structure

```
lib/
├── screens/
│   └── chat_screen.dart
├── services/
│   └── gemini_api.dart
├── widgets/
│   └── message_bubble.dart
├── secret.dart
└── main.dart

assets/
├── chatscreen.png
├── response.png
└── flutter_viedo.mp4
```

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🙋‍♂️ Author

**Sahil Sardhara**
Flutter Developer | Tech Support | Passionate about AI & UI/UX
[GitHub](https://github.com/Sahil-Sardhara) • [LinkedIn](https://linkedin.com/in/sahil-sardhara)
