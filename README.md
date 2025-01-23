# 🧠 Local LLM Chatbot with Ollama

This project demonstrates a simple chatbot built using the [LangChain](https://github.com/hwchase17/langchain) framework and the [Ollama](https://ollama.ai/) Local LLM model. The chatbot leverages conversation context to provide more accurate and coherent responses to user queries.

---

## 🚀 Features
- **Local LLM**: Powered by Ollama's `llama3.2` model for private and efficient AI interactions.
- **Context-Aware**: Retains conversation history for more accurate responses.
- **Simple Interface**: A command-line chatbot that’s easy to use.
- **Customizable Prompt**: Easily modify the prompt template for different tasks.

---

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/local-llm-chatbot.git
   cd local-llm-chatbot
   python3 -m venv venv

2. Set up a virtual environment (recommended):
   ```bash
    source venv/bin/activate  # For Linux/macOS
    venv\Scripts\activate     # For Windows

3. Install dependencies:
  ```bash
  pip install langchain langchain-ollama ollama
  ```

## 🧑‍💻 Usage
1. Run the chatbot:
  ```bash
  python main.py
  ```
2. Interact with the chatbot:

Type your questions, and the chatbot will respond.
Type exit to end the session.

Example:

bash
```
Welcome to the AI chatbot. Type 'exit' to quit
You: What is LangChain?
AI response: LangChain is a framework designed for building applications with LLMs, focusing on composability and usability.
You: How does Ollama work?
AI response: Ollama is a local LLM platform that allows running AI models privately without relying on external APIs.
```

## 📁 Project Structure
bash
```
.
├── main.py           # Main chatbot script
├── README.md         # Project documentation
└── LICENSE           # License file
```

## ⚙️ Customization
Modify the Prompt Template: You can customize the template in the app.py file to change how the AI responds to queries.
Change the LLM Model: Use different models available in Ollama by updating:
python
```
model = OllamaLLM(model="your_model_name")
```

## 📝 Requirements
Python 3.8 or above
Ollama installed and configured
Internet connection (for initial model setup)

## 🤝 Contributing
Contributions are welcome! If you have ideas to enhance the chatbot or encounter issues, feel free to open an issue or a pull request.

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

Enjoy chatting with your private, context-aware AI! 🎉








