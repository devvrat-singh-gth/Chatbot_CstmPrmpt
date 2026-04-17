# Groq AI Chatbot Studio

A lightweight and customizable chatbot powered by the **Groq API**, designed for fast, efficient, and high-quality text generation using Large Language Models (LLMs) such as GPT-OSS-20B.

This project demonstrates how to build a minimal yet flexible chatbot system with support for custom system prompts, enabling developers to control behavior, tone, and personality with ease.

---

## 🚀 Features

- Custom system prompts to define chatbot personality and behavior  
- High-speed inference using Groq API  
- Support for advanced LLMs (e.g., GPT-OSS-20B)  
- Minimal and clean codebase for easy understanding  
- Quick setup with limited dependencies  
- Extensible architecture for future upgrades  

---

## 🛠️ Installation

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/devvrat-singh-gth/Chatbot_CstmPrompt.git
cd Chatbot_CstmPrompt
```

Install the required dependencies (Python 3.8 or higher recommended):

```bash
pip install -r requirements.txt
```

Set up your Groq API key:

**Using a `.env` file**
```env
GROQ_API_KEY=your_api_key_here
```

---

## 💻 Usage

Run the chatbot application:

```bash
python app.py
```

Once started, the chatbot will respond based on the configured system prompt and selected language model.

---

## 📂 Project Structure

```
Chatbot_CstmPrompt/
│
├── __pycache__/        # Auto-generated compiled Python files
├── .gitignore          # Specifies files/folders Git should ignore
├── README.md           # Project documentation
├── app.py              # Main chatbot application logic
└── requirements.txt    # Python dependencies
```

---

## ⚙️ Configuration

You can customize the chatbot by modifying:

- System prompts in `app.py` to control response style and personality  
- Model parameters such as temperature, max tokens, etc.  
- LLM selection depending on performance, cost, and quality requirements  

---

## 🚧 Potential Improvements

This project is intentionally minimal but has strong scalability potential:

- Add a web-based UI using FastAPI, Flask, or Streamlit  
- Implement conversational memory for context-aware responses  
- Integrate multiple LLM providers (OpenAI, Anthropic, etc.)  
- Introduce structured logging and error handling  
- Enable streaming responses for real-time chat experience  
- Containerize the application using Docker for deployment  
- Add unit and integration testing for reliability  
- Move configuration fully to environment-based settings  

---

## 🤝 Contributing

Contributions are welcome.

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
