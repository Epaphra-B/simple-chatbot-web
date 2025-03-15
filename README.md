# AI Chatbot Web Application

This is a simple AI chatbot web application built using Flask for the backend and (optionally) React for the frontend. The chatbot processes user input using Natural Language Processing (NLP) and machine learning.

## Features
✅ NLP-based chatbot with NLTK and TensorFlow  
✅ Flask backend API    
✅ Deployment-ready

---

## **1. Installation & Setup**

### **Clone the Repository**
```bash
git clone https://github.com/yourusername/chatbot-web.git
cd chatbot-web
```

### **Set Up Virtual Environment (Recommended)**
```bash
python -m venv venv
```

**Activate the Virtual Environment:**
- **Windows:**
  ```bash
  venv\Scripts\activate
  ```
- **Mac/Linux:**
  ```bash
  source venv/bin/activate
  ```

### **Install Dependencies**
```bash
pip install -r requirements.txt
```

### **(Optional) Download NLTK Data**
```python
import nltk
nltk.download('punkt')
nltk.download('wordnet')
```

---

## **2. Run the Application Locally**

### **Start the Flask Backend**
```bash
python app.py
```
Backend will be running at: `http://127.0.0.1:5000/`

### **Start the React Frontend (If Applicable)**
```bash
cd frontend
npm install  # Install frontend dependencies
npm start    # Run frontend
```
Frontend will be running at: `http://localhost:3000/`

---


🎉 **Now your AI chatbot is live!** 🚀