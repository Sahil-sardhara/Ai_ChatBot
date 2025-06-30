# 🤖 AI ChatBot using Gemini API (Flutter)

An AI-powered chatbot built in Flutter using **Google's Gemini API** (Generative AI). This chatbot can respond to natural language queries, helping users with intelligent and context-aware answers.

---

## 🖼️ UI Screenshots & Demo

### 🧾 ChatScreen UI

This is the initial screen of the chatbot, where users can enter prompts and interact with the AI:

![ChatScreen UI](assets/chatscreen.png)

---

### 💬 Response of User Text

The chatbot responds in real-time using the Gemini API:

![Response of User Text](assets/response.png)

---

### 📽️ Full Demonstration of APK

A complete walkthrough of the AI Chatbot in action:

<video src="assets/flutter_viedo.mp4" width="700" controls></video>

---

## ✨ Features

- 🔗 Integration with Google Gemini API
- 💬 Chat interface with instant responses
- 🌙 Dark-themed, mobile-friendly design
- 📜 Context-aware chat history
- 🧠 Uses Gemini Pro for intelligent text generation
- 🗂️ Clean folder structure with modular design
- 🔒 API key securely handled via local file

---

## 🚀 Getting Started

### 📋 Prerequisites

- Flutter SDK (3.x recommended)
- Dart
- Android/iOS emulator or device
- Google Gemini API Key

### 🔧 Installation

```bash
git clone https://github.com/your-username/ai-chatbot-gemini.git
cd ai-chatbot-gemini
flutter pub get
🔐 Set up your Gemini API Key
Create a lib/secret.dart file:

dart
Copy
Edit
const String GEMINI_API_KEY = "your-api-key-here";
Make sure secret.dart is in .gitignore:

gitignore
Copy
Edit
lib/secret.dart
🧪 Usage
Run the app using:

bash
Copy
Edit
flutter run
Start interacting with your AI ChatBot using prompts like:

“Who developed Flutter?”

“Write a poem about the night sky.”

“Explain machine learning in simple terms.”

🛠 Tech Stack
Flutter – Mobile framework

Dart – Programming language

HTTP – For Gemini API requests

Gemini Pro – Google Generative AI

GetX/Provider – (Optional) State management

📁 Folder Structure
css
Copy
Edit
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
📬 Contact
💼 LinkedIn

💻 GitHub

📄 License
This project is licensed under the MIT License.
