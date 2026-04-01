# 🎬 Movie Data Analysis Project

## 📌 Overview

This project focuses on analyzing a dataset of approximately **3000 movies** to understand different aspects of movie performance.

The main purpose is to find insights such as **profit, ROI, popular actors, and top producers** using Python.

The analysis is done using **Pandas library in Python**.

---

## 📂 Dataset Description

The dataset includes the following details:

- Movie Title  
- Budget  
- Revenue  
- Cast Information  
- Crew Details  
- Genres  
- Original Language  

---

## 🛠️ Tools & Technologies

- Python 
- Pandas  
- NumPy  
- AST module (to handle JSON-like data)  
- Google Colab  

---

## 🧹 Data Preprocessing

Before analysis, the data was cleaned and transformed:

- Columns like `cast` and `crew` were in string format  
  → Converted using `ast.literal_eval()`  

- Extracted important information:
  - Actors from `cast`  
  - Director from `crew`  
  - Producers from `crew`  

- Removed movies where budget was 0  

- Created new columns:
  - **Profit = Revenue − Budget**  
  - **ROI = (Profit / Budget) × 100**  

---

## 📊 Tasks Performed

### 1. 💰 Movie with Highest Profit
- Identified the movie earning maximum profit  
- Retrieved its director, actors, and producers  

---

### 2. 🌍 Language with Best ROI
- Grouped movies based on language  
- Calculated average ROI for each language  

---

### 3. 🎭 Unique Genres
- Extracted all genres from dataset  
- Found list of distinct genres  

---

### 4. 🏆 Top 3 Producers
- Used `explode()` to separate producer names  
- Calculated average ROI for each producer  
- Selected top 3 performers  

---

### 5. 🎬 Actor with Maximum Movies
- Counted how many times each actor appeared  
- Found the most frequent actor  
- Analyzed their movies and profit trends  

---

### 6. 🎥 Top Directors & Their Actors
- Identified top 3 directors  
- Checked which actors they collaborate with most  

---

## ▶️ How to Run the Project

1. Install required libraries
2. Run the Python script or notebook


---

## 📈 Key Learnings / Conclusion

- Data analysis helps in understanding movie success  
- ROI is a very important metric for profitability  
- Some actors and producers consistently perform better  
- Data cleaning is a very important step before analysis  

---

## 👨‍💻 Author

**Satyam Sharma**
