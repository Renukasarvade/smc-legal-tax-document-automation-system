# 🏛️ smc-legal-tax-document-automation-system

# AI-Powered Document Analysis & Query Assistant for Solapur Municipal Corporation

> ⚠️ **Note:** This project was developed for the Solapur Municipal Corporation (SMC).  
> Due to confidentiality and organization policies, the **source code cannot be shared publicly**.  
> This repository contains **documentation only**, not the implementation.

---

## 📌 Overview

The **SMC Legal-Tax Document Automation System** is an advanced AI-powered platform designed to support the **Tax Department** and **Legal Department** of the Solapur Municipal Corporation.

SMC officers handle large volumes of:

- Legal notices  
- Tax assessment PDFs  
- Court documents  
- Property case files  
- Government orders  
- Citizen applications  

This system automates the extraction, summarization, and interpretation of long documents, helping officers make faster and more accurate administrative decisions.

---

## 🎯 Core Objectives

- Automate the reading of long legal/tax PDFs  
- Provide instant document summaries  
- Extract important sections, deadlines, and responsibilities  
- Allow officers to ask natural-language questions  
- Support scanned documents using OCR  
- Enable AI reasoning even in offline mode  

---

## ⭐ Key Features

### ✔ 1. **AI-Based Document Understanding**
Understands context, legal references, deadlines, penalties, and action points.

### ✔ 2. **Natural Language Query Answering**
Officers can ask questions like:
- “What action is required as per this notice?”
- “What is the due date mentioned?”
- “Which section applies here?”
- “Who is responsible for compliance?”

### ✔ 3. **Automatic Summaries**
System provides:
- 1-minute quick summary  
- Detailed summary  
- Extracted key points  
- Legal/tax insights  

### ✔ 4. **OCR for Scanned Municipal Documents**
Handles:
- Photocopies  
- Scanned PDFs  
- Low-quality images  

Powered by **Tesseract OCR**.

### ✔ 5. **Speech-to-Text & Text-to-Speech**
Useful for officers who prefer dictation or audio output.

### ✔ 6. **Hybrid AI System**
- **Online Mode:** Gemini 2.5 models  
- **Offline Mode:** Local NLP engine  

System continues working even when internet or API access is limited.

## 🏗️ System Architecture

PDF/Image Upload
➜ OCR / Text Extraction
➜ Preprocessing
➜ AI Engine (Gemini / Offline NLP)
➜ Semantic Understanding
➜ Summaries + Key Points
➜ Q&A Response
➜ Display on Web UI
---

## 🧠 Technology Stack

### **Frontend**
- HTML  
- CSS  
- JavaScript  
- REST API integration  

### **Backend**
- Python  
- Flask (REST API)  
- Session management  

### **AI / NLP**
- Google Gemini 2.x Models (online)  
- Offline fallback NLP engine  
- Embedding models for semantic search  

### **Document Processing**
- PyPDF2  
- pdfplumber  
- Tesseract OCR (bundled with the app)  
- Speech-to-text & text-to-speech support  

### **Storage Layer**
- JSON-based lightweight DB  
- User sessions  
- Logs  
- Document metadata  

---

## 🎥 Demo Video
Click below to watch the system demo:

▶️ **YouTube Link:** https://youtu.be/liR3K9MWwMI






