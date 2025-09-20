# 🦠 COVID-19 Analysis and Visualization using Plotly

## 📌 Project Overview
This project focuses on analyzing and visualizing the **COVID-19 pandemic** using multiple datasets.  
The goal is to provide **clear, interactive, and insightful visualizations** that showcase the spread, trends, and health impacts of COVID-19 across different countries, timelines, and comorbidities.

The project is divided into **3 main parts**:
1. **Country-Level Analysis** (using `covid.csv`)
2. **Time-Series Analysis** (using `covid_grouped.csv`)
3. **Mortality & Comorbidity Analysis** (using `coviddeath.csv`)

---

## 📂 Datasets Used
1. **covid.csv**  
   - Country-wise data on population, cases, deaths, recoveries, and testing rates.  
2. **covid_grouped.csv**  
   - Time-series dataset with daily confirmed, recovered, and death cases across countries.  
3. **coviddeath.csv**  
   - Age-wise and comorbidity-based COVID-19 death statistics.  

---

## ⚡ Technologies Used
- **Python**
- **Pandas** – data manipulation  
- **NumPy** – numerical analysis  
- **Matplotlib & Seaborn** – static visualization  
- **Plotly Express** – interactive visualization  
- **Jupyter/Colab Notebook** – project execution  

---

## 📊 Key Analysis & Visualizations

### 🔹 Part 1: Country-Level Analysis (`covid.csv`)
- Top countries by **Total Cases** and **Deaths**  
- **Cases per Million** and **Deaths per Million**  
- **Testing vs Cases correlation** (impact of testing on detection)  
- **Continent-wise distribution** of cases and deaths  

### 🔹 Part 2: Time-Series Analysis (`covid_grouped.csv`)
- Global **growth of cases, deaths, and recoveries** over time  
- **Daily new cases trend** visualization  
- **Top 10 countries trend comparison**  
- **Case Fatality Rate (CFR) trends** over time  

### 🔹 Part 3: Mortality & Comorbidity Analysis (`coviddeath.csv`)
- **Age-group distribution of deaths**  
- **Young vs Older mortality comparison**  
- **Comorbidities impact** (respiratory, circulatory, diabetes, etc.)  
- **Heatmap of Age × Condition** showing most vulnerable groups  
- **Weekly death trends** and spikes during major waves  

---

## 💡 Insights

### 🌍 Country-Level
- USA, Brazil, and India had the **highest cases**, while Europe & Americas saw **higher cases per million**.  
- **Testing rates strongly correlated with reported cases**, indicating better detection in high-testing countries.  

### 📈 Time-Series
- Clear **waves of infections** across time.  
- **Fatality rate decreased** over time due to improved healthcare and vaccination.  

### 🧑‍⚕️ Mortality & Comorbidities
- **Older age groups (65+)** were the most affected.  
- Patients with **respiratory & circulatory conditions** had higher fatality risks.  
- Weekly deaths aligned with **pandemic waves**, peaking during surges.  

## 📊 Sample Visualizations

### 🌍 Country-Level Cases
![Cases by Country]
<img width="1736" height="593" alt="image" src="https://github.com/user-attachments/assets/bf6af16c-e25a-457a-9d88-41758299ac2f" />


### 🧑‍⚕️ Deaths by Age Group
![Deaths by Age]
<img width="1740" height="595" alt="image" src="https://github.com/user-attachments/assets/bf1486c9-57ce-416a-8427-6d4ca4c24ef3" />

### 🔥 Heatmap of Age × Condition
![Heatmap]
"C:\Users\91897\OneDrive\Pictures\Screenshots\download.png"

---

## ✅ Conclusion
- COVID-19 had a **disproportionate global impact**, with regional and demographic differences.  
- **Testing & healthcare capacity** played key roles in detection and survival rates.  
- Elderly people and those with **pre-existing conditions** were at the highest risk.  
- Over time, improved **medical response and vaccination** reduced fatality rates.  

---

## 🚀 Future Scope
- Add **vaccination datasets** to analyze impact on cases & mortality.  
- Build a **dashboard (Dash/Streamlit/Power BI)** for live interactive exploration.  
- Apply **Machine Learning models** to forecast cases and deaths.  
- Combine with **socio-economic data** (GDP, healthcare spending, mobility trends).  

---

## 📂 Repository Structure
