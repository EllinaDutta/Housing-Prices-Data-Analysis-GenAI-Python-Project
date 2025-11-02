# 🏠 Housing Prices Data Analysis — *GenAI + Python Project*
![Python](https://img.shields.io/badge/Python-3.10-blue)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-orange)
![AI](https://img.shields.io/badge/GenAI-Powered-lightgreen)
![Visualization](https://img.shields.io/badge/Data%20Viz-Matplotlib%20%7C%20Seaborn-yellow)


---

## 📌 Overview
This project explores a **real estate dataset** to identify key factors influencing property sale prices using **Python (Pandas, Matplotlib, Seaborn)** in **Google Colab**, with active assistance from **ChatGPT (GenAI)**.

It demonstrates how **Generative AI can act as a coding mentor** — guiding code creation, explaining Python logic, and interpreting analytical insights for beginners and analysts alike.

---

## 🎯 Objective
Analyze housing price data to:
- Understand which factors most influence sale prices.
- Perform descriptive, univariate, and bivariate analyses.
- Use **GenAI-driven prompts** to enhance learning and accelerate coding in Python.

---

## 🗂 Dataset
**File:** `HousingPrices_New.csv`

| Feature | Description |
|----------|--------------|
| Flat Area (in Sqft) | Total usable area |
| No of Bedrooms | Number of bedrooms |
| No of Bathrooms | Number of bathrooms |
| Overall Grade | Quality rating |
| Basement Area (in Sqft) | Basement space |
| Sale Price | Target variable |

---

## ⚙️ Project Workflow

### **1. Data Loading**
- Loaded dataset into Colab using Pandas.
- Code generated and explained by ChatGPT.

### **2. Descriptive Statistics**
Calculated:
- Mean, Median, Mode  
- Standard Deviation, Minimum, Maximum  

🧩 *Insights:*  
- `Flat Area` and `Basement Area` show high variability.  
- `Overall Grade` strongly influences `Sale Price`.  
- Bedrooms/Bathrooms have modal values of 3–4.

### **3. Data Cleaning**
Used the **IQR method** to detect and handle:
- Missing values (filled with median)
- Outliers (removed beyond 1.5×IQR)

### **4. Univariate Analysis**
Visualized the distribution of `Flat Area (in Sqft)` using:
- Histogram + KDE  
- Boxplot  

*Why these plots?* They help detect skewness and outliers effectively.

### **5. Bivariate Analysis**
Explored the relationship between `No of Bedrooms` and `Sale Price` using:
- Boxplot  
- Scatterplot with Regression Line  
- Pearson Correlation Coefficient  

📈 *Finding:* The correlation is **weak to moderate** — bedrooms alone aren’t a strong predictor of price.

---

---

## 📊 Project Preview
<img width="690" height="663" alt="image" src="https://github.com/user-attachments/assets/0fe0c56d-a9d3-47b8-b88e-b67ec4ca3862" />


*Sample Visualization: Sale Price vs. Number of Bedrooms (Bivariate Analysis)*


## 💡 Key Insights

| Factor | Influence Strength | Observation |
|---------|--------------------|--------------|
| Flat Area (in Sqft) | High | Larger homes cost more |
| Basement Area (in Sqft) | Moderate | Adds extra value |
| Overall Grade | High | Better grade = higher price |
| No of Bathrooms | Moderate | Slight increase in price |
| No of Bedrooms | Weak | Not a strong standalone driver |

---

## 🤖 Role of GenAI (ChatGPT)
This project was created as part of a **GenAI learning experiment**, focusing on integrating **ChatGPT in data analysis workflows**.

ChatGPT was used to:
- Generate and explain Python code.
- Recommend visualization techniques.
- Provide detailed insights and statistical interpretations.
- Serve as a **learning companion**, reducing time spent debugging.

> 💬 Example Prompt Used:
> “You are an expert data analyst. Give me the Python code to perform bivariate analysis between number of bedrooms and sale price, including correlation and regression plots.”

---

## 🧾 Repository Structure

| File | Description |
|------|--------------|
| `Project_GenAI_Housing_Prices_Ellina_Dutta.ipynb` | Google Colab notebook with all Python code & visualizations |
| `Project-GenAI with Python-Housing Prices- Ellina Dutta.pdf` | PDF version with prompts, code, and output screenshots |
| `Final Report.docx` | Final analytical summary and key insights |

---

## 🧩 Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy  
- **Environment:** Google Colab  
- **AI Assistant:** ChatGPT  
- **Data Type:** Structured CSV (Real Estate Data)

---

## 🚀 Learning Outcomes
- Performing **descriptive & bivariate analysis** using Python.  
- Handling **missing data and outliers** using IQR.  
- Creating **data visualizations** with Seaborn & Matplotlib.  
- Understanding how **GenAI can complement data analytics** learning.

---

## 📈 Future Enhancements
- Add **multivariate regression modeling** to predict prices.  
- Explore **feature importance** using machine learning.  
- Automate **EDA reports** using AI-driven notebooks.

---

## 👩‍💻 Author
**Ellina Dutta**  
📍 Data Analytics Enthusiast | Skilled in Python, SQL, Power BI  
🔗 [LinkedIn](linkedin.com/in/ellinna-duta-94043b5a) | [GitHub](https://github.com/EllinaDutta)

---

⭐ *If you found this project interesting, consider giving it a star on GitHub!*
