# 📘 Legal Document Simplifier

An interactive web application that simplifies complex legal documents like contracts, policies, and acts using a transformer-based abstractive summarization model from Hugging Face. Built using Streamlit, this tool enables users to upload `.txt`, `.pdf`, or `.docx` files and get readable, condensed summaries instantly.

---

## 🎯 Objective

Legal language is often long, repetitive, and hard to interpret. This app automates the summarization of such documents, helping:
- 📚 Law students & educators
- 🧑‍⚖️ Legal professionals
- 🧠 General users needing simplified legal content

---

## 🚀 Features

- 📂 Upload legal documents in `.txt`, `.pdf`, or `.docx`
- 🔍 Automatic chunking for long texts
- 🤖 BART-based summarization (`facebook/bart-large-cnn`)
- 🎛 Select between *Concise* and *Detailed* summaries
- 📥 Download the final summary as a `.txt` file
- 🧾 PDF and DOCX parsing support

---

## 🛠️ Tech Stack

| Tool        | Purpose                        |
|-------------|--------------------------------|
| Streamlit   | Frontend interface             |
| Hugging Face Transformers | Abstractive summarization |
| NLTK        | Sentence tokenization          |
| PyMuPDF     | PDF text extraction            |
| python-docx | DOCX text extraction           |

---

## 🤖 Model Used

- **Model**: `facebook/bart-large-cnn`
- **Type**: Abstractive summarization
- **Token Limit**: Up to 1024 tokens per chunk
- **Trained On**: CNN/DailyMail dataset

---

## 🧪 Results

The app was tested on various legal documents including the **Indian Patents Act, 1970**.

- **Original Length**: ~14,000 words  
- **Final Summary**: ~300–500 words  
- **Performance**:
  - ✅ Preserved key definitions and clauses
  - ✅ Reduced redundant legal text
  - ✅ Made procedural language easier to interpret

> *Example:*  
> “Patent means a patent for any invention granted under this Act...”  
> ⟶ Retained due to legal significance and accuracy

---

## 🧾 Sample Output

📄 [Click to View Full Summary PDF](https://github.com/adithyanum/legal_document_simplifier/blob/81f1dfebd1b104728ac35c06f4eb7b5d2035562e/Legal_Document_Simplifier.pdf)
