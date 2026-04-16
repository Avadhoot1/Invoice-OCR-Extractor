# Invoice-OCR-Extractor
OCR-based Invoice Data Extraction System using Python, OpenCV, and Tesseract to extract invoice number, date, and total amount from images and PDFs with a Streamlit UI.

# 📄 Invoice OCR Extraction System

## 🚀 Overview

This project is an OCR-based document processing system that extracts key information such as invoice number, date, and total amount from invoice images and PDFs.

## 🧠 Features

* Extract text using Tesseract OCR
* Image preprocessing using OpenCV (grayscale, thresholding)
* Regex-based data extraction
* Supports images and PDFs
* Export structured data to CSV/JSON
* Interactive Streamlit UI for uploading invoices

## 🛠️ Tech Stack

* Python
* OpenCV
* Tesseract OCR
* Pandas
* Streamlit

## 📂 Project Structure

```
InvoiceOCR/
│── data/
│── output/
│── main.py
│── preprocess.py
│── extractor.py
│── utils.py
│── pdf_handler.py
│── app.py
```

## ▶️ How to Run

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Run OCR script

```bash
python main.py
```

### 3. Run Streamlit UI

```bash
streamlit run app.py
```

## 📊 Output Example

Extracted fields:

* Invoice Number
* Date
* Total Amount

Saved as CSV for further analysis.

## 🎯 Use Case

Reduces manual data entry effort and automates invoice processing workflows.

---

⭐ If you like this project, give it a star!
