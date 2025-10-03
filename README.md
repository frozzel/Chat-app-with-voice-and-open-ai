# Create a Voice Assistant with OpenAI's GPT-3 and IBM Watson  
![cognitiveclass.ai logo](https://cognitiveclass.ai/images/logo.png)
 

---

## 📖 Introduction  

Welcome to this guided project on **creating a voice assistant** using **OpenAI's GPT-3** and **IBM Watson Speech Libraries for Embed**.  

In this project, you’ll build a virtual assistant that:  
1. Takes **voice input**.  
2. Converts it to text using **speech-to-text**.  
3. Sends the text to **OpenAI’s GPT-3 model**.  
4. Receives a response and converts it back to **speech**.  
5. Plays it to the user via the web interface.  

The assistant features a **responsive frontend** built with **HTML, CSS, and JavaScript**, and a **Flask backend** in Python 3.10.12.  
 

By the end of this project, you will:  
- Understand how voice assistants work.  
- Be able to create an **AI-powered assistant** with speech input/output.  
- Gain experience in **Python, Flask, HTML, CSS, and JavaScript**.  
- Have a finished **full-stack application** to showcase!  

---

## 🧠 Background  

### 🔹 OpenAI (GPT-3)  
[OpenAI](https://openai.com) develops advanced AI systems. GPT-3 is a cutting-edge **natural language processing (NLP)** model that allows your assistant to understand and generate human-like responses.  

### 🔹 IBM Watson Speech Libraries for Embed  
[IBM Watson Speech Libraries](https://www.ibm.com/watson) provide **speech-to-text** and **text-to-speech** technology, enabling real-time voice transcription and synthesis. This allows your assistant to communicate naturally with users.  

### 🔹 Voice Assistants  
A **virtual assistant** simulates conversation with humans via natural speech. They are widely used in **customer service, e-commerce, education**, and more.  

### 🔹 Python & Flask  
[Python](https://www.python.org) is one of the most popular programming languages.  
[Flask](https://flask.palletsprojects.com/) is a lightweight **web framework** used to build the backend of your assistant.  

### 🔹 HTML, CSS, JavaScript  
- **HTML** → structures the web interface.  
- **CSS** → styles the interface.  
- **JavaScript** → adds interactivity for the assistant’s frontend.  

---

## 🎯 Learning Objectives  

By the end of this project, you will be able to:  
- ✅ Explain the basics of **voice assistants** and their applications.  
- ✅ Set up a **Python/Flask** development environment.  
- ✅ Implement **speech-to-text** functionality.  
- ✅ Integrate with **OpenAI’s GPT-3** for intelligent responses.  
- ✅ Implement **text-to-speech** functionality.  
- ✅ Build a **full-stack assistant** with web-based interaction.  
- ✅ (Optional) Deploy your assistant to a web server.  

---

## 🛠️ Prerequisites  

- Basic understanding of **HTML, CSS, JavaScript, and Python** is helpful but not required.  
- Python **3.10.12** must be installed on your system.  
- An **OpenAI API key** and **IBM Watson Speech credentials** are required to run the project.  

---

## 🚀 Getting Started  

### 1. Clone the Repository  
```bash
git clone https://github.com/your-username/voice-assistant-gpt3-watson.git
cd voice-assistant-gpt3-watson
```

### 2. Create a Virtual Environment

```bash
python3.10 -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```
### 4. Set Environment Variables

```bash
OPENAI_API_KEY=your_openai_api_key
IBM_WATSON_API_KEY=your_ibm_api_key
IBM_WATSON_URL=your_ibm_url
```

### 5. Run the Flask App
```bash
flask run
```

App will be available at: http://127.0.0.1:8000


### 📂 Project Structure

voice-assistant-gpt3-watson/
│── app.py                # Flask backend
│── static/               # CSS, JavaScript, images
│── templates/            # HTML frontend
│── requirements.txt      # Python dependencies
│── .env                  # API keys and configs
│── README.md             # Documentation


### 📦 Requirements

Flask
Flask_Cors
openai
requests


### Install

```bash
pip install -r requirements.txt
```

