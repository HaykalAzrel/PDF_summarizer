# PDF_summarizer

# 📘 GraniteSummarizerApp

A simple Google Colab + Replicate API project to summarize the contents of uploaded PDF files using IBM Granite LLM.

---

## 🎯 Project Overview

This project enables users to upload a PDF document, extract its text, and generate a concise summary using IBM Granite (accessed via Replicate API). The goal is to demonstrate how AI can assist in quickly understanding lengthy academic or professional documents.

---

## 🔗 Dataset

- The dataset is user-uploaded PDF files (e.g., scientific journals, reports, articles).
- No fixed dataset is bundled in this project.

---

## ⚙️ Tech Stack

- Google Colab (Python)
- IBM Granite 3.3 8B via [Replicate](https://replicate.com/)
- PyMuPDF (`fitz`) for extracting text from PDF
- LangChain + Replicate wrapper for inference

---

## 🚀 How It Works

1. User uploads a PDF in Colab
2. The first ~3000 characters are extracted from the text
3. A prompt is constructed to summarize the document
4. The prompt is sent to the Granite model
5. The output is a 4–5 point summary returned to the user

## 📬 Submission

- ✅ Google Colab notebook: [https://colab.research.google.com/drive/1II4m2pFU9GK79LtBoJ5bnf0Wup1XgOI5?usp=sharing]
- ✅ Presentation slide: [https://docs.google.com/presentation/d/1VasZMoxrNCKFWuv0EhDJ9_7weOtNGZk_Y59u2HB0FdI/edit?usp=sharing]
- ✅ README and sample input/output files available in repo (if using GitHub)


---

## 📄 Example Prompt Sent to Granite

