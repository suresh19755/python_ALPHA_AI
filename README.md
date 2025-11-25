# python_ALPHA_AI
A context-aware AI chatbot built using Python, Streamlit, and Google's Gemini API. Features multi-model selection (Pro/Flash) and persistent chat history.

# 🤖 ALPHA AI - Streamlit & Gemini Chatbot

**ALPHA AI** is a conversational AI interface built with Python. It integrates the power of **Google Gemini's Generative AI** into a clean, responsive **Streamlit** web application. 

## 🚀 Project Overview

The goal of this project was to create ALPHA AI(A chatbot) serves as a dashboard where users can interact with Large Language Models (LLMs) while maintaining conversational context.

### ✨ Key Features

* **🧠 Multi-Model Support:** Users can toggle between different Gemini models (e.g., `gemini-pro`, `gemini-1.5-flash`) via the sidebar to test different capabilities.
* **🔐 Secure API Handling:** The app includes a sidebar input for the Google API Key, ensuring keys aren't hardcoded for security.
* **💬 Context Awareness:** Utilizes `st.session_state` to store chat history, allowing the AI to remember previous inputs for a natural conversation flow.
* **⚡ Real-Time Interaction:** Leverages Streamlit's chat elements for a smooth, instant messaging experience.

## 🛠️ Tech Stack

* **Language:** Python
* **Frontend/UI:** [Streamlit](https://streamlit.io/)
* **AI Model:** [Google Generative AI (Gemini)](https://ai.google.dev/)

## ⚙️ Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/ALPHA-AI.git](https://github.com/your-username/ALPHA-AI.git)
    cd ALPHA-AI
    ```

2.  **Install dependencies:**
    ```bash
    pip install streamlit google-generativeai
    ```

3.  **Run the application:**
    ```bash
    streamlit run AI_chat.py
    ```

4.  **Enter your Credentials:**
    * The app will launch in your default browser.
    * Enter your **Google API Key** in the sidebar (Get one from [Google AI Studio](https://aistudio.google.com/)).
    * Start chatting!

## 📸 Demo
*(
<img width="1920" height="1200" alt="Screenshot (97)" src="https://github.com/user-attachments/assets/f96ea9f8-49a2-40e0-9f58-69148c855cb7" />
<img width="1920" height="1200" alt="Screenshot (98)" src="https://github.com/user-attachments/assets/885a73bc-89be-4a20-855e-9a7928400426" />
)*

---
*Made with ❤️ and 🧠 by [Suresh seervi]
