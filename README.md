# CAPM Analysis – Apple vs S&P 500

## Table of Contents
- [Project Overview](#project-overview)
- [Tools & Technologies](#tools--technologies)
- [Dataset Details](#dataset-details)
- [Key Steps Performed](#key-steps-performed)
- [Key Outcomes](#key-outcomes)
- [Project Structure](#project-structure)
- [Author](#author)

---

## Project Overview
This project demonstrates a practical implementation of the **Capital Asset Pricing Model (CAPM)** using real market data.  

The analysis focuses on **Apple Inc. (AAPL)** stock and compares its performance against the **S&P 500 index**.

**Goal:** Showcase practical data analysis skills including:
- Data cleaning  
- Merging datasets  
- Return calculation  
- Basic financial analysis using Python  

---

## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

## Dataset Details
- `HistoricalQuotes.csv` – Apple stock historical prices  
- `sp500_index.csv` – S&P 500 index historical data  

**Preprocessing performed:**  
- Aligned dates across datasets  
- Removed missing values  

---

## Key Steps Performed
1. Loaded and cleaned stock market datasets  
2. Converted price columns to numeric format  
3. Merged Apple stock data with S&P 500 index data  
4. Calculated daily returns for Apple and the market  
5. Computed **Beta** using covariance and variance  
6. Visualized stock vs market movement  

---

## Key Outcomes
- Estimated **Apple stock Beta** relative to the S&P 500  
- Clear comparison of Apple’s performance against the market  
- Practical demonstration of financial data analysis concepts  

---

## Project Structure
- `CAPM_Analysis.ipynb` – Main Jupyter Notebook  
- `HistoricalQuotes.csv` – Apple stock data  
- `sp500_index.csv` – S&P 500 index data  
- `README.md` – Project documentation  

---

## Author
**Yashka Johari**  
MCA Student | Aspiring Data Analyst  

*This project is created for learning and portfolio demonstration purposes.*
