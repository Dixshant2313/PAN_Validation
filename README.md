# 🧾 PAN Number Validation Project  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)  
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)  
![pandas](https://img.shields.io/badge/Library-pandas-green)  
![Excel](https://img.shields.io/badge/Data-Excel-lightgrey)  
![License](https://img.shields.io/badge/License-MIT-yellow)  

---

## 📌 Overview  
The **PAN Number Validation Project** validates Permanent Account Numbers (PAN) from an Excel dataset using Python and Jupyter Notebook.  
It applies format rules, flags invalid entries, and generates a clean result file, showcasing practical data validation and automation with **pandas**.  

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
```
pip install pandas openpyxl
```

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
   - Validate each entry (format, structure, etc.)  
   - Save results into **`PAN VALIDATION RESULT.xlsx`**  

---

## 📊 Dataset  
- **Input** → `PAN Number Validation Dataset.xlsx`  
- **Output** → `PAN VALIDATION RESULT.xlsx`  

Each PAN entry is validated and labeled as **Valid** or **Invalid**.  

---

## ✅ Results  
- PAN numbers are classified as **Valid** or **Invalid**.  
- Output is stored in a structured Excel file for easy reference.  

---

## 🔮 Future Improvements  
- Extend validation rules for advanced error checks.  
- Add duplicate detection.  
- Create a web-based interface for real-time validation.  

---

## 🙌 Acknowledgments  
- Built with **Python, pandas, and openpyxl**  
- Developed and tested in **Jupyter Notebook**  
