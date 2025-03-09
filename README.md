# E-Commerce Customer Purchase Analysis

![Interactive Cares Course Project](https://img.shields.io/badge/Interactive-Cares-blue)
![Pandas Analysis](https://img.shields.io/badge/Pandas-1.5.3-blue)
![Matplotlib](https://img.shields.io/badge/Matplot-lib-brightgreen)
![Seaborn](https://img.shields.io/badge/Sea-Born-blue)
![Python](https://img.shields.io/badge/Python-3.9%2B-brightgreen)
![Dataset](https://img.shields.io/badge/Records-30k-orange)

## 📌 Project Overview
This project was completed as part of the **Data Science and Machine Learning Career Path** course on [Interactive Cares](https://interactivecares.com/courseDetails/284?title=Data_Science_and_Machine_Learning_Career_Path/) - Bangladesh's premier skill development platform. It analyzes synthetic E-commerce data from [Cust_Purch_FakeData.csv](Dataset/Cust_Purch_FakeData.csv) containing **30,000 customer records** while protecting user privacy. The analysis focuses on answering key business client questions of using Python and Pandas to derive actionable insights about customer behavior, spending trends, credit card usage as well as purchasing patterns. It involves data exploration, cleaning, and visualization using Python.

## Repository Structure

## 📂 **File Structure**  

- **[Data Cleaning.sql](Data%20Cleaning.sql)**: SQL script for cleaning and preparing the data for analysis.  
- **[Exploratory Data Analysis (EDA).sql](Exploratory%20Data%20Analysis%20(EDA).sql)**: SQL script for performing EDA on the dataset, including analyzing distributions, trends, and correlations.  
- **[RFM Segmentation.sql](RFM%20Segmentation.sql)**: SQL script for performing RFM segmentation analysis.  
- **[README.md](README.md)**: Project documentation.  

### 📁 **[Dataset Folder](Dataset)**  
  - **[Cust_Purch_FakeData.csv](Dataset/Cust_Purch_FakeData.csv)**: The dataset used for analysis.  
  - **[Cust_Purch_Data_Exercise.ipynb](Dataset/Cust_Purch_Data_Exercise.ipynb)**: Jupyter Notebook for initial exploration and analysis.  

### 📁 **[Results & Findings Folder](Results%20&%20Findings)**  
  - **[Client's Questions Answered.md](Results%20&%20Findings/Client's%20Questions%20Answered.md)**: Answers to key business questions based on analysis.  
  - **[EDA Summary.md](Results%20&%20Findings/EDA%20Summary.md)**: Summary of findings from exploratory data analysis.  
  - **[RFM Customer Segmentation.png](Results%20&%20Findings/RFM%20Customer%20Segmentation.png)**: Graphical representation of RFM segmentation results.  
  - **[RFM_Table.csv](Results%20&%20Findings/RFM_Table.csv)**: Final table containing customer segments based on RFM analysis.  

### 📁 **[Visualizations Folder](Results%20&%20Findings/Visuals)**  
  - **![Age Distribution Histogram](Results%20&%20Findings/Visuals/Age%20Distribution%20Histogram.png)**  
  - **![Customer Activity by Day](Results%20&%20Findings/Visuals/Bar%20Chart%20of%20Customer%20Activity%20by%20Day.png)**  
  - **![Top 10 Email Providers](Results%20&%20Findings/Visuals/Bar%20Chart%20of%20the%20Top%2010%20Email%20Providers.png)**  
  - **![Spending vs Age Scatter Plot](Results%20&%20Findings/Visuals/Spending%20vs%20Age%20Scatter%20Plot.png)**  

---





## 📊 Dataset Overview
The dataset, [Cust_Purch_FakeData.csv](Dataset/Cust_Purch_FakeData.csv), contains **30,000 entries** and **20 columns**, including:
- **Customer Information**: Name, Age, Email, Phone, Profession, etc.
- **Transaction Details**: Purchase Amount, Credit Card Type, Expiry Date, etc.
- **Behavioral Data**: Active Shopping Days, Email Providers, etc.

## 🔍 Key Insights
- The most common customer name is **Willie** (130 occurrences), followed by Francis and Eula.
- The most used credit card type is **Visa** (1,721 customers).
- The top spending day is **Saturday (4,376 customers).**
- The most common email provider is **Gmail (1,687 users).**
- Customer age distribution is mostly between **18-65 years**, with an average of **~41.55 years.**
- **87 Structural Engineers** in the dataset, with a gender distribution visualized.
- Highest spending recorded: **100 CAD**, with an average of **49.99 CAD.**
- Common Professions are **Preschool Teachers (112)**, **Distribution Managers (107).**

Check the detailed insights in **[Client's Questions Answered.md](Results%20&%20Findings/Client's%20Questions%20Answered.md).**

## 📈 Visualizations
All visualizations are available in the **[Visuals folder](Results%20&%20Findings/Visuals/)** and were generated using **[E-Commerce Project Visuals.ipynb](E-Commerce%20Project%20Visuals.ipynb).**

## 🛠 Technologies Used
- **Python** (Pandas, Matplotlib, Seaborn, NumPy)
- **Jupyter Notebook** for analysis


## How to Use This Repository
1️⃣ Clone the repository:
```bash
git clone https://github.com/yourusername/Ecommerce-Customer-Purchase-Analysis.git
```
2️⃣ Install dependencies:
```bash
pip install -r requirements.txt
```
3️⃣ Run **Cust_Purch_Data_Solution.ipynb** for analysis.
4️⃣ Run **E-Commerce Project Visuals.ipynb** to generate visualizations.

## Author
**Afridi Jubair** - Data Science Enthusiast | AI Engineer Aspirant

---

✅ **For full findings, check [Client's Questions Answered](./Results%20%26%20Findings/Client's%20Questions%20Answered.md)**

