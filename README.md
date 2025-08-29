# 🧾 PAN Number Validation Project  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)  
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)  
![pandas](https://img.shields.io/badge/Library-pandas-green)  
![Excel](https://img.shields.io/badge/Data-Excel-lightgrey)  
![License](https://img.shields.io/badge/License-MIT-yellow)  

## 📌 Overview
This project validates **PAN (Permanent Account Number)** entries from a dataset using Python and Jupyter Notebook.  
It processes an input Excel file containing PAN numbers, applies validation rules, and generates a result file with validated entries.

---

## 📂 Project Structure
├── PAN_Validation.ipynb # Jupyter Notebook with source code
├── PAN Number Validation Dataset.xlsx # Input dataset (raw PAN numbers)
└── PAN VALIDATION RESULT.xlsx # Output dataset (validated results)
---

## ⚙️ Requirements
Make sure you have the following installed:
- Python 3.8+  
- Jupyter Notebook  
- pandas  
- openpyxl  

Install dependencies with:
```bash
pip install pandas openpyxl

---

## ⚙️ Requirements
Make sure you have the following installed:
- Python 3.8+  
- Jupyter Notebook  
- pandas  
- openpyxl  

Install dependencies with:
```bash
pip install pandas openpyxl

🚀 How to Run

Clone this repository:

git clone https://github.com/your-username/pan-validation.git
cd pan-validation


Launch Jupyter Notebook:

jupyter notebook


Open PAN_Validation.ipynb and run all cells.

The notebook will:

Read PAN numbers from PAN Number Validation Dataset.xlsx

Apply validation rules (format, structure, etc.)

Save results into PAN VALIDATION RESULT.xlsx

📊 Dataset

Input: PAN Number Validation Dataset.xlsx

Output: PAN VALIDATION RESULT.xlsx

Each PAN entry is validated against rules, and the results are stored in the output file.

✅ Results

PAN numbers are classified as Valid or Invalid based on predefined validation logic.

The output file provides a clear record of validation results.

🔮 Future Improvements

Add support for batch validation via command line.

Implement additional error checks (e.g., duplicate PANs).

Build a simple web interface for user-friendly PAN validation.

🙌 Acknowledgments

Developed in Python using pandas.

Jupyter Notebook for interactive development and testing.
