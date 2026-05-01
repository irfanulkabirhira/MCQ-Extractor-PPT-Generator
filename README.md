# 📄 PDF2MCQ Generator

An automated Python-based tool that extracts Multiple Choice Questions (MCQs) from PDF files, processes and cleans the data, and exports it into structured formats (CSV/XLSX) along with PowerPoint presentations (PPTX).

---

## 🚀 Features

* 📥 Upload PDF (DOCX-exported or content-based)
* 🔍 Extract text using PyMuPDF
* 🧠 Automatically detect and clean MCQs
* 📊 Export to:

  * CSV
  * Excel (XLSX)
* 🎞️ Generate PowerPoint slides using a template
* 🌐 Works in Google Colab

---

## 🛠️ Technologies Used

* Python
* PyMuPDF (fitz)
* Pandas
* python-pptx
* OpenPyXL

---

## 📂 Workflow

1. Upload PDF file
2. Extract text from PDF
3. Process and clean MCQs
4. Save output as CSV/XLSX
5. Generate PPT slides from template

---

## ▶️ How to Use

### Step 1: Install Dependencies

```bash
pip install pymupdf python-pptx pandas openpyxl
```

### Step 2: Run the Notebook

* Open `Assessment_2.ipynb` in Google Colab or Jupyter
* Upload your PDF file when prompted

### Step 3: Get Output

* Download generated:

  * `mcq_output.csv`
  * `mcq_output.xlsx`
  * PPT presentation file

---

## 📌 Use Cases

* Teachers creating quizzes
* Students preparing study materials
* Educational content automation
* Exam preparation tools

---

## ⚠️ Notes

* Works best with structured PDFs (clear MCQ format)
* Some PDFs may require manual cleaning due to formatting issues

---

## 📜 License

This project is open-source and free to use.

---

## 🙌 Contributions

Feel free to fork, improve, and submit pull requests!
