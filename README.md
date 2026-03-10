# ♻️ Multi-Garbage Detection and Recycling Recommendation System

An AI-powered waste detection system that identifies multiple types of garbage from an uploaded image and provides intelligent recycling guidance using Retrieval-Augmented Generation (RAG).

The system combines **YOLOv8 object detection** with a **knowledge-based retrieval system** and **LLM formatting** to generate practical recycling instructions for detected waste materials.

---

# 🚀 Project Overview

Waste management and recycling awareness are major environmental challenges. Manual sorting of waste is inefficient and often leads to improper disposal.

This project proposes an **AI-based solution** that:

• Detects multiple waste objects in an image  
• Identifies their categories (plastic, paper, glass, etc.)  
• Retrieves recycling knowledge from a local knowledge base  
• Generates step-by-step recycling instructions  

The system is deployed as an interactive **web application using Streamlit**.

---

# 🧠 Technologies Used

| Component | Technology |
|--------|--------|
| Object Detection | YOLOv8 (Ultralytics) |
| Retrieval System | FAISS |
| Knowledge Embeddings | Sentence Transformers |
| LLM Formatting | Gemini API |
| Web Interface | Streamlit |
| Programming Language | Python |

---

# 🗂 Project Architecture
