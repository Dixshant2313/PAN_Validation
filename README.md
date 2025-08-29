# 🧾 PAN Number Validation Project  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)  
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)  
![pandas](https://img.shields.io/badge/Library-pandas-green)  
![Excel](https://img.shields.io/badge/Data-Excel-lightgrey)  
![Validation](https://img.shields.io/badge/Task-Data%20Cleaning%20%26%20Validation-brightgreen)  

---

## 📌 Overview  
The **PAN Number Validation Project** is a data validation pipeline built using **Python** and **Jupyter Notebook**.  
It automates the process of checking whether **Permanent Account Numbers (PAN)** are valid by applying **format-based rules** and outputs the validation results into a structured Excel file.  

This project demonstrates how Python can be applied in **data preprocessing, cleaning, and rule-based validation**.  
It is especially useful in financial, compliance, and KYC-related workflows where accurate PAN entries are critical.  

---

## 📂 Project Structure  
```
├── PAN_Validation.ipynb                # Jupyter Notebook with source code
├── PAN Number Validation Dataset.xlsx  # Input dataset (raw PAN numbers)
└── PAN VALIDATION RESULT.xlsx          # Output dataset (validated results)
```

---

## ⚙️ Requirements  
- Python 3.8+  
- Jupyter Notebook  
- pandas  
- openpyxl  

Install dependencies with:  
```bash
pip install pandas openpyxl
```

---

## 🛠️ Methodology & Validation Logic  
The notebook follows these steps:  

1. **Load Dataset**  
   - Reads PAN numbers from the Excel file using `pandas.read_excel()`.  

2. **Preprocessing**  
   - Strips leading/trailing spaces.  
   - Converts entries to uppercase for consistency.  
   - Duplicate Detection
   - Handled Missing Data

3. **Validation Rules Applied**  
   - PAN must be **10 characters long**.  
   - The **first 5 characters** must be **alphabets (A–Z)**.  
   - The **next 4 characters** must be **digits (0–9)**.  
   - The **last character** must be an **alphabet (A–Z)**.  
   - Any deviation from this format is marked **Invalid**.  

4. **Result Generation**  
   - A new column `Validation Result` is added to mark each PAN as **Valid** or **Invalid**.  
   - Results are exported to `PAN VALIDATION RESULT.xlsx`.  

---

## 🚀 How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/pan-validation.git
   cd pan-validation
   ```

2. Launch Jupyter Notebook:  
   ```bash
   jupyter notebook
   ```

3. Open **`PAN_Validation.ipynb`** and run all cells.  

4. The notebook will:  
   - Read PAN numbers from **`PAN Number Validation Dataset.xlsx`**  
   - Apply validation rules  
   - Save results into **`PAN VALIDATION RESULT.xlsx`**  

---

## 📊 Dataset  
- **Input File** → `PAN Number Validation Dataset.xlsx`  
  - Contains raw PAN numbers to be validated.  

- **Output File** → `PAN VALIDATION RESULT.xlsx`  
  - Adds a validation column showing whether each PAN is **Valid** or **Invalid**.  

---

## ✅ Results  
- PAN entries are classified as **Valid** or **Invalid** based on rules.  
- Results are stored in Excel for easy review and reporting.  

Example result format:  

| PAN Number | Validation Result |  
|------------|-------------------|  
| ABCDE1234F | Valid             |  
| A1CDE1234X | Invalid           |  

---

## 🔮 Future Improvements  
- Integrate with a **GUI or web app** for user-friendly validation.  
- Extend support for validating other IDs (Aadhaar, GST, etc.).  

---

## 🙌 Acknowledgments  
- Developed using **Python (pandas + openpyxl)**.  
- Designed and tested in **Jupyter Notebook**.  
