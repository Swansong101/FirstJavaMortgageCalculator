### README

# Java Mortgage Calculator

## Overview
This is a simple **Mortgage Calculator** built in Java, designed to help users calculate monthly mortgage payments based on the loan amount, annual interest rate, and loan term (in years). It’s an excellent introduction to Java programming concepts, including user input, basic math operations, and control structures.

## Features
- Accepts user input for:
  - Loan amount (principal)
  - Annual interest rate (as a percentage)
  - Loan term (in years)
- Calculates and displays:
  - Monthly mortgage payments
  - Total payment over the loan term
- Handles invalid input gracefully (e.g., non-numeric values or negative numbers).

## How It Works
The program uses the **standard mortgage formula**:

\[
M = P \times \frac{r(1 + r)^n}{(1 + r)^n - 1}
\]

Where:
- \(M\) = Monthly payment
- \(P\) = Loan amount (principal)
- \(r\) = Monthly interest rate (annual rate divided by 12 and converted to decimal)
- \(n\) = Total number of payments (years \(\times\) 12)

## Prerequisites
- Java Development Kit (JDK) installed.
- A code editor or IDE such as VS Code, IntelliJ IDEA, or Eclipse.

## Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/Swansong101/FirstJavaMortgageCalculator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd FirstJavaMortgageCalculator
   ```
3. Compile the Java file:
   ```bash
   javac MortgageCalculator.java
   ```
4. Run the program:
   ```bash
   java MortgageCalculator
   ```

## Example Usage
```
Enter the loan amount (e.g., 200000): 300000
Enter the annual interest rate (e.g., 5.5): 4.25
Enter the loan term in years (e.g., 30): 15

Your monthly payment is: $2252.69
Total payment over 15 years: $405,484.20
```

## Future Improvements
- Add a GUI for a more user-friendly interface.
- Allow users to input additional monthly payments to calculate early payoff.
- Include error handling for edge cases like 0% interest or 0-year terms.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Author
Created by **Swansong101** – Feel free to reach out with any suggestions or feedback!

---
