# 🛒 Online Retail Predictive Analytics Project

📎 [Open in Google Colab](https://colab.research.google.com/drive/1-5AEkwyca4i1PJzL-lwIiOhrLLKJ4j15?usp=sharing)

## 📌 Project Overview
This project applies predictive analytics to identify whether a customer is likely to become a repeat buyer, using a real-world dataset from a UK-based online retailer. It simulates a common business scenario where early customer segmentation is critical for driving retention and revenue.

This project was completed as part of the ISOM 835 – *Predictive Analytics and Machine Learning* course.

## 🎯 Objectives
- Clean and explore transactional data from an e-commerce business.
- Engineer meaningful customer-level features.
- Build predictive models to classify repeat vs. non-repeat buyers.
- Generate business insights and reflect on ethical implications.

## 📊 Dataset
- **Source**: [UCI Machine Learning Repository – Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)
- **Period**: December 2010 – December 2011
- **Size**: ~541,000 transactions (after cleaning: ~397,000)
- **Features**: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

## ⚙️ Tools & Libraries
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Google Colab
- GitHub for version control and documentation

## 🚀 How to Run
1. Open the [Colab Notebook](https://colab.research.google.com/drive/1-5AEkwyca4i1PJzL-lwIiOhrLLKJ4j15?usp=sharing)
2. Upload the `Online Retail.xlsx` dataset when prompted.
3. Run each cell in sequence to view:
   - Data Cleaning
   - Feature Engineering
   - Modeling Results (Logistic Regression & Random Forest)
   - Insights and Ethical Reflection

## 📈 Results Summary
- **100% accuracy** achieved using both Logistic Regression and Random Forest models.
- Key predictive features: Total Quantity, Total Revenue, Number of Invoices.
- Repeat buyers display consistent high-volume purchase behavior.

## 💡 Business Insights
- Customers with larger order quantities and higher revenue tend to return.
- Identifying them early helps optimize loyalty campaigns and increase ROI.
- Customers from certain countries also showed higher repeat behavior patterns.

## ⚖️ Ethical Considerations
- Ensure customer privacy by anonymizing data.
- Avoid reinforcing geographic or economic bias in marketing decisions.
- Maintain fairness in how model results are used in customer segmentation.

## 👤 Author
- Crystal Vu Ngoc Bao Chau  
- MSBA Candidate – Suffolk University  

---
