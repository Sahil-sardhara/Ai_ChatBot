# 🤖 AI ChatBot using Gemini API (Flutter)

An AI-powered chatbot built in Flutter using **Google's Gemini API** (Generative AI). This chatbot can respond to natural language queries, helping users with intelligent and context-aware answers.

---

## 🖼️ UI Screenshots & Demo

### 🧾 ChatScreen UI

This is the initial screen of the chatbot, where users can enter prompts and interact with the AI:

![ChatScreen UI](https://github.com/user-attachments/assets/19038de6-4394-4aa7-8ea0-960bd2dec3e7)


---

### 💬 Response of User Text

The chatbot responds in real-time using the Gemini API:

![Response of User Text](https://github.com/user-attachments/assets/75846812-014b-407f-a6e0-5b5922a7efb6)


---

### 📽️ Full Demonstration of APK

A complete walkthrough of the AI Chatbot in action:


https://github.com/user-attachments/assets/ff3503e3-aeef-486c-98d3-fd67026a34e3


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
git clone https://github.com/Sahil-Sardhara/Ai-ChatBot.git
cd Ai-ChatBot
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


📄 License
This project is licensed under the MIT License.
