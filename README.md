# Chatbot_CstmPrompt

A lightweight and customizable chatbot powered by the **Groq API**, designed for fast, efficient, and high-quality text generation using Large Language Models (LLMs) such as GPT-OSS-20B.

This project demonstrates how to build a minimal yet flexible chatbot system with support for custom system prompts, enabling developers to control behavior, tone, and personality with ease.

---

## 🚀 Features

- Custom system prompts to define chatbot personality and behavior  
- High-speed inference using Groq API  
- Support for advanced LLMs (e.g., GPT-OSS-20B)  
- Minimal and easy-to-understand codebase  
- Quick setup with limited dependencies  

---

## 🛠️ Installation

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/your-username/Chatbot_CstmPrompt.git
cd Chatbot_CstmPrompt
```

Install the required dependencies (Python 3.8 or higher recommended):

```bash
pip install -r requirements.txt
```

Set up your Groq API key:

**Option 1: Using a `.env` file**
```env
GROQ_API_KEY=your_api_key_here
```

**Option 2: Export via terminal**
```bash
export GROQ_API_KEY="your_api_key_here"
```

*For Windows PowerShell:*
```bash
setx GROQ_API_KEY "your_api_key_here"
```

---

## 💻 Usage

Run the chatbot application:

```bash
python app.py
```

Once started, the chatbot will process user inputs based on the configured system prompt and selected language model.

---

## 📂 Project Structure

```
Chatbot_CstmPrompt/
│
├── app.py              # Core chatbot logic and API interaction
├── requirements.txt   # Project dependencies
├── .gitignore         # Ignored files and folders
└── README.md          # Project documentation
```

---

## ⚙️ Configuration

You can customize the chatbot by modifying:

- **System prompts** in `app.py` to control responses  
- **Model parameters** such as temperature and max tokens  
- **LLM selection** depending on your performance and quality needs  

---

## 🚧 Potential Improvements

The current implementation is intentionally minimal. The following enhancements can improve scalability, usability, and production readiness:

- Add a web-based interface (Flask, FastAPI, or Streamlit)  
- Implement conversational memory for context-aware responses  
- Support multiple LLM providers (OpenAI, Anthropic, etc.)  
- Introduce structured logging and robust error handling  
- Containerize the application using Docker  
- Add unit and integration testing  
- Enable token streaming for real-time responses  
- Implement configuration via environment-based settings  

---

## 🤝 Contributing

Contributions are welcome and encouraged.

To contribute:
1. Fork the repository  
2. Create a feature branch (`feature/your-feature`)  
3. Commit your changes  
4. Push to your fork  
5. Open a Pull Request  

For major changes, please open an issue first to discuss your ideas.

---

## ⭐ Support

If you find this project useful, consider giving it a star on GitHub. It helps improve visibility and encourages further development.
