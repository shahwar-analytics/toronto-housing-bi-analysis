# 🏠 Toronto Housing Market Analysis using Business Intelligence

## 📌 Overview
This project presents an end-to-end Business Intelligence (BI) solution to analyze the Toronto housing market. The goal is to transform raw real estate data into actionable insights that help buyers, sellers, and real estate professionals make informed decisions.

---

## 🎯 Problem Statement
Housing prices in Toronto vary significantly based on:
- Location
- Property type
- Bedrooms and bathrooms
- Market conditions

Due to large volumes of listings and fragmented data sources, it is difficult to determine fair property pricing and identify market trends.

---

## ⚙️ Tools & Technologies
- **Python** (Pandas, Matplotlib, Seaborn)
- **SQL** (SQLite)
- **Power BI**
- **API Integration** (Bank of Canada - Interest Rates)

---

## 🔄 Business Intelligence Pipeline
1. **Data Acquisition**
   - Kaggle housing dataset (MLS listings)
   - Bank of Canada interest rate API

2. **Data Cleaning**
   - Removed duplicates
   - Handled missing values
   - Filtered extreme outliers (e.g., incorrect property tax values)

3. **Data Storage**
   - Cleaned dataset stored in SQLite database

4. **Data Analysis**
   - Location-based pricing (FSA regions)
   - Market composition (property types)
   - Property configuration (bedrooms vs bathrooms)
   - Feature correlation analysis

5. **Visualization**
   - Interactive Power BI dashboard with filters and insights

---

## 📊 Key Insights
- 📍 Location (FSA) is the strongest factor affecting housing prices  
- 🏢 Condos represent the majority of listings  
- 🏠 Detached homes have the highest median prices  
- 🚿 Bathroom count has a stronger impact on price than bedroom count  

---

## 📈 Dashboard
The project includes an interactive Power BI dashboard with:
- Market overview  
- Location analysis  
- Property configuration insights  
- Feature relationship analysis  

<img width="356" height="195" alt="Picture1" src="https://github.com/user-attachments/assets/a8e77f10-d1d6-4392-aaff-5f759f62e72c" />

---

## 💡 Business Impact
- Enables buyers to identify fair market prices  
- Helps sellers price properties competitively  
- Improves transparency in the housing market  
- Supports data-driven decision-making  



## 📁 Project Structure

toronto-housing-bi-analysis/
│
├── data/ # Dataset (sample included)
├── notebooks/ # Python analysis
├── report/ # Project report
├── presentation/ # Project slides
├── dashboard/ # Dashboard screenshots
└── README.md

## ⚠️ Note on Dataset
The original dataset is large (~50MB).  
A sample dataset is included in this repository.


## 🚀 Future Improvements
- Real-time data pipeline (ETL)
- Predictive pricing model using machine learning
- Integration with live MLS data
- Deployment as a web-based dashboard

 ## 👨‍💻 Author
Mohammed Shahwar Ahmed  
Data Analyst | SQL | Python | Power BI
