# AI Chat Assistant (Flutter + OpenAI Integration)

A cross-platform mobile application demonstrating the practical integration of **Large Language Models (LLMs)** into client-facing applications. This project serves as a proof-of-concept for deploying Generative AI solutions in mobile environments.

## 📋 Table of Contents
- [Overview](#-overview)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Architecture & Data Flow](#-architecture--data-flow)
- [Getting Started](#-getting-started)
- [Future Improvements](#-future-improvements)

## 📖 Overview
This project bridges the gap between **Flutter** (Frontend) and **OpenAI's GPT API** (Backend Intelligence). It allows users to interact with an AI assistant in real-time, featuring a responsive UI and robust state management to handle asynchronous data streams.

**Use Case:** This architecture is designed to be scalable for industrial applications such as **Automated Customer Support**, **Field Technician Assistants**, or **Internal Knowledge Retrieval**—aligning with modern IT x OT convergence trends.

## 🚀 Key Features
* **Real-time LLM Integration:** Direct integration with OpenAI's API (GPT-3.5/4 models).
* **Asynchronous Data Handling:** Smooth user experience with loading states and non-blocking API calls.
* **Robust Error Handling:** Manages API timeouts, token limits, and connectivity issues gracefully.
* **Dynamic Chat Interface:** A familiar, user-friendly chat UI inspired by modern messaging platforms.
* **State Management:** Efficient management of chat history and app state.

## 🛠 Tech Stack
* **Framework:** Flutter (Dart)
* **AI Service:** OpenAI API (RESTful Integration)
* **State Management:** Provider / Riverpod (Select one you used)
* **Networking:** `http` package for API requests
* **Environment Management:** `flutter_dotenv` for secure API key storage

## 🏗 Architecture & Data Flow
This application follows a **Clean Architecture** principle to separate the UI from the logic:

1.  **UI Layer:** Handles user input and displays chat bubbles.
2.  **Service Layer:** The `OpenAIService` acts as a middleware, formatting the JSON payload and managing authentication headers.
3.  **API Layer:** Sends the `POST` request to OpenAI and parses the JSON response.

## ⚡ Getting Started

### Prerequisites

* Flutter SDK installed ([Guide](https://docs.flutter.dev/get-started/install))
* An OpenAI API Key ([Get one here](https://platform.openai.com/api-keys))

### Installation

1. **Clone the repository**
```bash
git clone [https://github.com/leductrung0110/Integrating_ChatGPT_with_Flutter.git](https://github.com/leductrung0110/Integrating_ChatGPT_with_Flutter.git)
cd Integrating_ChatGPT_with_Flutter

```


2. **Install dependencies**
```bash
flutter pub get

```


3. **Configure Environment Variables**
* Create a `.env` file in the root directory.
* Add your API key (Do not commit this file to GitHub!):


```env
OPENAI_API_KEY=sk-your-actual-api-key-here

```


4. **Run the App**
```bash
flutter run

```



## 🔮 Future Improvements

* **Voice Integration:** Adding Speech-to-Text (STT) for hands-free industrial use cases.
* **Local LLM Support:** Integrating on-device models (e.g., TensorFlow Lite) for offline capabilities.
* **RAG Implementation:** Connecting the bot to a custom document database for domain-specific knowledge.

## 📬 Contact

**Le Duc Trung**

* **Email:** leductrung2021123@gmail.com
* **GitHub:** [leductrung0110](https://www.google.com/search?q=https://github.com/leductrung0110)
