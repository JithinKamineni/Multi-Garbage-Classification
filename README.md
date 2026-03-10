# ♻️ Multi-Garbage Detection and Recycling Recommendation System

An AI-powered system that detects multiple types of garbage from an image and provides step-wise recycling recommendations using Retrieval-Augmented Generation (RAG).

This project combines **computer vision**, **information retrieval**, and **LLM-based formatting** to create an intelligent waste management assistant.

The system detects waste items using **YOLOv8**, retrieves recycling knowledge from a **local knowledge base**, and formats the results into clear recycling instructions using an **LLM**.

---

# 🚀 Features

• Detect multiple waste objects in a single image  
• Identify waste categories with confidence scores  
• Display bounding boxes around detected objects  
• Retrieve recycling knowledge using RAG  
• Generate step-wise recycling instructions  
• Interactive web interface using Streamlit  

---

# 🧠 Technologies Used

| Component | Technology |
|--------|--------|
| Object Detection | YOLOv8 (Ultralytics) |
| Retrieval System | FAISS |
| Text Embeddings | Sentence Transformers |
| LLM Formatting | Gemini API |
| Web Interface | Streamlit |
| Programming Language | Python |

---

# 🗑 Waste Categories Detected

The model detects the following waste categories:

• Paper  
• Plastic  
• Glass  
• Metal  
• Cardboard  
• Biodegradable  

Multiple objects can be detected within the same image.

---

# 🏗 System Architecture

Image Upload
↓
YOLOv8 Object Detection
↓
Detected Waste Classes
↓
RAG Retrieval (knowledge_base)
↓
LLM Formatting (Gemini API)
↓
Recycling Recommendations

---

# ⚙️ Installation Guide

## 1️⃣ Clone the Repository


git clone https://github.com/YOUR_USERNAME/Multi-Garbage-Classification.git

cd Multi-Garbage-Classification


---

## 2️⃣ Install Dependencies


pip install -r requirements.txt


---

# 🔑 Setting Up the API Key

This project requires a **Gemini API key** to format the recycling recommendations.

## Step 1 — Generate an API Key

Go to:


https://aistudio.google.com/app/apikey


Create a new Gemini API key.

---

## Step 2 — Create a `.env` File

Inside the project folder, create a file named:


.env


Add your API key to the file like this:


GEMINI_API_KEY=your_api_key_here


Example:


GEMINI_API_KEY=AIzaSyXXXXXXXXXXXXXXX


⚠️ Important:

• Do **not upload `.env` to GitHub**  
• `.env` should remain only on your local machine  
• The repository already includes `.gitignore` to prevent this file from being pushed  

---

# ▶️ Running the Application

Start the Streamlit app with:


streamlit run app.py


The application will start in your browser at:
---

# ⚙️ Installation Guide

## 1️⃣ Clone the Repository


git clone https://github.com/YOUR_USERNAME/Multi-Garbage-Classification.git

cd Multi-Garbage-Classification


---

## 2️⃣ Install Dependencies


pip install -r requirements.txt


---

# 🔑 Setting Up the API Key

This project requires a **Gemini API key** to format the recycling recommendations.

## Step 1 — Generate an API Key

Go to:


https://aistudio.google.com/app/apikey


Create a new Gemini API key.

---

## Step 2 — Create a `.env` File

Inside the project folder, create a file named:


.env


Add your API key to the file like this:


GEMINI_API_KEY=your_api_key_here


Example:


GEMINI_API_KEY=AIzaSyXXXXXXXXXXXXXXX


⚠️ Important:

• Do **not upload `.env` to GitHub**  
• `.env` should remain only on your local machine  
• The repository already includes `.gitignore` to prevent this file from being pushed  

---

# ▶️ Running the Application

Start the Streamlit app with:


streamlit run app.py


The application will start in your browser at:
http://localhost:8501


---

# 🌐 Web Application Usage

1. Upload an image containing waste items  
2. The YOLOv8 model detects garbage objects  
3. Detected classes and bounding boxes are displayed  
4. The system retrieves recycling knowledge  
5. Step-wise recycling instructions are generated  





