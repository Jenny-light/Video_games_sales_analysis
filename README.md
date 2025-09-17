# 🎮 Video Game Sales Data Analysis  

## 📌 Project Overview  
This project explores the **VGChartz video game sales dataset**, focusing on sales trends, regional performance, critic influence, and overall market patterns. The notebook demonstrates data exploration, cleaning, basic analysis, and visualization using **Python, Pandas,  Matplotlib, and Seaborn**.  
The dataset was gotten from Maven Analytics.
---

## 🗂️ Project Structure  
- `week7assignment.ipynb` → Jupyter Notebook containing the full workflow  
- `vgchartz-2024.csv` → Dataset used for the analysis 
- `requirement.txt` →   Python libraries

---

## 🚀 Steps Performed  

### 1. Data Loading & Exploration  
- Loaded the dataset using **Pandas**  
- Displayed first few rows (`.head()`), dataset info, and checked for missing values  
- Cleaned dataset by dropping/filling missing data  

### 2. Basic Data Analysis  
- Generated descriptive statistics with `.describe()`  
- Grouped data by **platform/genre/region** to compute averages  
- Looked at correlations between **critic scores and sales**  

### 3. Data Visualization  
Created **4 visualizations** using Matplotlib & Seaborn:  
1. 📈 **Line Chart** – Sales trend over time  
2. 📊 **Bar Chart** – Average sales per genre/platform  
3. 📉 **Histogram** – Distribution of game sales  
4. 🔵 **Scatter Plot** – Relationship between critic scores and sales  

### 4. Findings & Key Insights  
- **Market Dominance**: A few franchises (e.g., GTA, Call of Duty) and genres (Sports, Action, Shooter) dominate sales.  
- **Console Legacy**: PS2, Xbox 360, and PS3 era saw the peak of physical video game sales.  
- **Critics vs. Consumers**: Weak correlation (~0.16) between critic scores and sales → commercial success is not driven by critic ratings.  
- **Regional Trends**: North America and Europe dominate sales; Japan contributes less for these genres.  
- **Modern Blockbusters**: Physical sales decline after 2008 (due to digital distribution), but AAA releases still achieve massive success.  

---

## 🛠️ Technologies Used  
- Python 🐍  
- Pandas (Data Analysis)  
- Matplotlib & Seaborn (Visualization)  
- Jupyter Notebook  

---

## 📊 Example Visualization  
 <img width="1101" height="645" alt="barchart vg" src="https://github.com/user-attachments/assets/d66d5f67-c1c4-4b96-8523-44c3fa65c309" />
<img width="1080" height="678" alt="piechart vg" src="https://github.com/user-attachments/assets/b72a6d5a-4967-4d3a-8b93-2077639ea00f" />

## 📌 How to Run

1.Clone this repository:

git clone https://github.com/Jenny-light/Video_games_sales_analysis.git


2.Navigate into the folder:

cd DA_PLP_PROJECT


3.Install required libraries:

pip install -r requirements.txt


4.Open the Jupyter Notebook:

jupyter notebook week7assignment.ipynb

## 📈 Future Improvements

Include digital sales data for modern titles

Add sentiment analysis of reviews

Expand dataset with Nintendo Switch & next-gen console data

## 👩‍💻 Author

Jennifer Omoregie

Data Analyst | Python | SQL | Visualization
