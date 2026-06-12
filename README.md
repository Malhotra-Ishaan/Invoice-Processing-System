> 📌 **Note:** This repository was re-uploaded due to loss of access to the original repo's linked Git email account.


# 🧾 Automated Invoice Processing System

An end-to-end web application that automates extraction and processing of data from multiple PDF invoices. Combining **OCR**, **PyPDF2/PyMuPDF**, and **Google Generative AI**, it converts unstructured invoice PDFs (text-based or scanned) into clean, structured, editable, and exportable data — built for enterprises handling large volumes of invoices.

---

## ✨ Features
- 📂 Upload multiple PDF invoices at once
- 🔍 Extract text from both text-based and image-based (scanned) PDFs via OCR
- 🤖 Use Google Generative AI to accurately capture key invoice fields
- 📊 Organize extracted data into a structured tabular format
- ✏️ Edit and preview extracted data in-browser before finalizing
- 📥 Download processed results as an Excel (.xlsx) file

---

## 🛠️ Tech Stack
- **Backend:** Python 3.10, Flask
- **PDF Processing:** PyPDF2, PyMuPDF (fitz)
- **OCR:** pytesseract, Pillow (PIL)
- **AI Extraction:** Google Generative AI
- **Data Handling:** pandas

---

## 📋 Requirements
- Python 3.10
- Flask
- PyPDF2
- pytesseract
- Pillow (PIL)
- fitz (PyMuPDF)
- google.generativeai
- pandas

---

## 🚀 Usage

### 1. Run the Application
```bash
python app.py
```
Open your browser and navigate to `http://127.0.0.1:5000/`

### 2. Upload Invoices
- Click **"Choose Files"** and select the PDF invoices you want to process
- Click **"Upload"**

### 3. Review & Edit
- View extracted fields such as Scan ID, Country, Bill To Name, Currency, Invoice Date, etc.
- Edit any field directly in the browser if needed

### 4. Download Results
- Click **"Submit"** after reviewing
- Click the download link to get `invoices_summary_edited.xlsx`

---

## 📸 Screenshots

**File Upload Page**
![Upload Page](https://github.com/user-attachments/assets/c8e82e16-a439-470b-8a8c-49e3168f7e35)

**Preview & Edit Page**
![Preview & Edit](https://github.com/user-attachments/assets/563f2c11-23df-4cbb-94fc-82f38b3156e1)

**Summary Sheet**
![Summary Sheet](https://github.com/user-attachments/assets/4833d70e-82f1-44bc-a5f1-0a32b88e7799)
