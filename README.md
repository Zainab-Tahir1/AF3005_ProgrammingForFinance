# **AF3005 Programming for Finance - Assignment 1**

## **Smart Financial Management System**

This repository contains the implementation of a **Smart Financial Management System** developed for SecureBank. The system is designed to automate various financial operations using Python and `ipywidgets` for interactive user input. The implementation is divided into five parts, each addressing a specific financial task.

---

## **Features**

The system includes the following features:

1. **Loan Eligibility & Interest Rate Calculation**  
   - Checks if a customer is eligible for a loan based on employment status, income, and credit score.
   - Calculates the applicable interest rate or rejects the loan application.

2. **Investment Risk Assessment**  
   - Evaluates a portfolio of stocks and classifies the risk level based on stock returns.

3. **Loan Repayment Tracker**  
   - Tracks the remaining loan balance as monthly payments are made until the loan is fully repaid.

4. **Stock Price Monitoring and Trading Strategy**  
   - Monitors stock prices daily and triggers an alert when the price reaches a target value.

5. **Currency Exchange Rate Tracker**  
   - Tracks the PKR/USD exchange rate daily and stops when the rate reaches a target value.

---

## **Requirements**

To run the code, you need the following:

- **Python 3.x**
- **Jupyter Notebook**
- **ipywidgets** library (install using `pip install ipywidgets`)

---

## **How to Use**

1. **Clone the Repository**  
   Clone this repository to your local machine using the following command:
   ```bash
   git clone https://github.com/Zainab-Tahir1/AF3005_ProgrammingForFinance.git
   ```

2. **Open the Jupyter Notebook**  
   Navigate to the repository directory and open the Jupyter Notebook file:
   ```bash
   cd AF3005_ProgrammingForFinance
   jupyter notebook i229848_Zainab_Tahir_AF3005_Assignment1.ipynb
   ```

3. **Run the Code**  
   - Execute each cell in the notebook to load the interactive widgets.
   - Input the required values using the widgets and click the buttons to see the results.

---

## **Repository Structure**

The repository is structured as follows:

```
AF3005_ProgrammingForFinance/
├── 22i-9848_AF3005_Assignment1.ipynb  # Jupyter Notebook file
├── README.md                              # This file
```

---

## **Implementation Details**

### **Part 1: Loan Eligibility & Interest Rate Calculation**
- Uses `ipywidgets` to collect user input for employment status, income, and credit score.
- Implements conditional logic to determine loan eligibility and interest rates.

### **Part 2: Investment Risk Assessment**
- Takes a list of stock returns as input and classifies the portfolio risk level.
- Uses loops and conditional statements to evaluate the returns.

### **Part 3: Loan Repayment Tracker**
- Simulates loan repayment by deducting monthly payments from the loan balance.
- Displays the remaining balance after each payment.

### **Part 4: Stock Price Monitoring and Trading Strategy**
- Iterates through a list of stock prices and skips missing data (`None` values).
- Triggers an alert when the stock price reaches the target value.

### **Part 5: Currency Exchange Rate Tracker**
- Tracks the PKR/USD exchange rate daily and stops when the rate reaches the target value.

---

## **Contributing**

If you would like to contribute to this project, feel free to fork the repository and submit a pull request. Please ensure your code follows the same structure and style.

## **Contact**

For any questions or feedback, please contact:  
- **Name**: Zainab Tahir 
- **Email**: zainabbtahirxiif@gmail.com 
- **GitHub**: Zainab-Tahir1

---

Enjoy using the Smart Financial Management System! 🚀


