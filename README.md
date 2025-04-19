

# 📊 EMI Calculator (Java)

This is a simple command-line Java application that calculates the **Equated Monthly Installment (EMI)** for a loan based on user inputs. The program takes the loan amount, annual interest rate, and loan tenure (in years), and then calculates the monthly EMI using a standard formula.

---

## 💡 Features

- Accepts user input for:
  - Loan amount (USD)
  - Annual interest rate (%)
  - Loan tenure (in years)
- Calculates:
  - Monthly interest rate
  - Loan tenure in months
  - EMI (Equated Monthly Installment)
- Displays the monthly EMI to the user

---

## 🧮 Formula Used

\[
\text{EMI} = \frac{P \times r \times (1 + r)^n}{(1 + r)^n - 1}
\]

Where:

- `P` = Principal loan amount  
- `r` = Monthly interest rate (Annual Rate / 12 / 100)  
- `n` = Total number of monthly installments (Years × 12)

---

## 🛠️ How to Run

1. Make sure you have **Java** installed (JDK 11+ recommended).
2. Save the code in a file named `EMICalculator.java`.
3. Compile and run the code:

```bash
javac EMICalculator.java
java day4.EMICalculator
```

> Ensure your file is within a folder named `day4` as per the package declaration.

---

## 🧑‍💻 Example

```
Enter loan amount in USD:
10000
Enter annual interest rate (in %):
7.5
Enter loan tenure in years:
2
Your monthly EMI is: 450.53
```

---

## 📂 Project Structure

```
EMICalculator/
│
└───day4/
    │   EMICalculator.java
```

---

## 📌 Notes

- The interest is assumed to be compounded monthly.
- This is a basic version meant for educational/demo purposes.

---
