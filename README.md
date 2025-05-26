# 🎓 Educational Chatbot

An interactive chatbot built with Streamlit and powered by the `deepseek-ai/DeepSeek-R1` model from Hugging Face. This assistant is designed for educational purposes, providing answers and explanations based on natural language input.

## 🚀 Features

- Conversational interface with chat history
- Uses Hugging Face's hosted inference API
- Real-time response from `deepseek-ai/DeepSeek-R1`
- Automatically removes irrelevant `<think>` tags from responses
- Clean, responsive UI with Streamlit

## 📁 Project Structure

```bash
.
├── app.py              # Streamlit application
├── .env                # Environment variables (Hugging Face API key)
├── requirements.txt    # Dependencies
└── README.md           # Project documentation
```

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone <repo-url>
   cd educational-chatbot
   ```

2. **Create a virtual environment (optional)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Create `.env` file**
   Add your Hugging Face API key to a `.env` file in the project root:
   ```
   HUGGINGFACEHUB_API_TOKEN=your_token_here
   ```

5. **Run the app**
   ```bash
   streamlit run app.py
   ```

## 🧠 Model

The chatbot uses the `deepseek-ai/DeepSeek-R1` model hosted via Hugging Face Inference API for generating responses.

## 📜 Dependencies

- streamlit
- huggingface_hub
- python-dotenv
- re
- os

Install with:
```bash
pip install streamlit huggingface_hub python-dotenv
```

## 📄 License

MIT License
