# Ecommerce Purchase Data Analysis

This project analyzes ecommerce transaction data to uncover patterns and insights related to customer purchases. The dataset contains detailed information such as purchase price, job titles, credit card details, and browsing data.

## 📁 Project Structure

- `Ecommerce_Purchase_Project.ipynb` – Main Jupyter Notebook with code for data loading, exploration, cleaning, querying, and analysis.

## 📊 Dataset

The dataset includes the following features:

- Address  
- Lot  
- AM or PM (time of purchase)  
- Browser Info  
- Company  
- Credit Card Number  
- Credit Card Expiration Date  
- Security Code  
- Credit Card Provider  
- Email  
- Job  
- IP Address  
- Language  
- Purchase Price  

## ⚙️ Steps Performed

1. **Data Loading** – Load CSV data into a pandas DataFrame.  
2. **Data Inspection** – Check for missing values and data types.  
3. **Exploratory Data Analysis (EDA)** – Analyze purchase distributions, job titles, credit card providers, and languages.  
4. **Querying** – Extract specific information, such as emails by IP address or credit card details.  

## 📈 Results

- 1,097 purchases by French-speaking users.  
- 984 engineers identified in the dataset.  
- 405 Mastercard users made purchases over $50.  
- Nearly equal distribution between AM and PM purchases.  
- 988 credit cards expiring in 2020.  
- Most common email domains: hotmail.com, yahoo.com, and gmail.com.

## 🧰 Technologies Used

- Python  
- Pandas  
- NumPy  
- Jupyter Notebook  

## 🚀 How to Run

1. Clone the repository or download the notebook.  
2. Install dependencies (if any).  
3. Open the notebook:  
   ```bash  
   jupyter notebook Ecommerce_Purchase_Project.ipynb  

