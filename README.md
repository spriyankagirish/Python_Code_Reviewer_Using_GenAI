
```markdown
# 🧠 Python Code Reviewer using Gemini Pro + Streamlit

This is a Streamlit web app that leverages Google's **Gemini 1.5 Pro** (via `google.generativeai`) to provide automated Python code reviews.

It analyzes your code for:
- 🐞 Bugs & Syntax Errors  
- 🧠 Logical Mistakes  
- 🧹 Inefficiencies & Bad Practices  
- 💡 Suggestions for Optimization

---

## 🚀 Features

- Uses **Google Gemini Pro** API for deep AI-based code analysis  
- Interactive web UI powered by **Streamlit**  
- Real-time feedback and actionable recommendations  

---

## 🔧 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/python-code-reviewer.git
cd python-code-reviewer
```

2. **Create a virtual environment (optional but recommended):**

```bash
python -m venv venv
source venv/bin/activate  # on Windows: venv\Scripts\activate
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

---

## 📦 Dependencies

Make sure your `requirements.txt` includes:

```
streamlit
google-generativeai
```

---

## 🔑 API Key Setup

To use Gemini Pro, you need a Google AI Studio API key.

1. Go to [https://aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)
2. Copy your API key
3. Replace the placeholder in `app.py`:

```python
ai.configure(api_key="YOUR_API_KEY_HERE")
```

Or use environment variables for security.

---

## 💻 Run the App

```bash
streamlit run app.py
```

Then open `http://localhost:8501` in your browser.

---

## 🖼️ Screenshot

![App Screenshot](![image](https://github.com/user-attachments/assets/168082e9-b5cf-47e3-bc7e-9f1a3400251c)
)

