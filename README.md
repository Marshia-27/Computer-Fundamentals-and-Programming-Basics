### 🔍Problem No: 1(Write a C program to find the greatest amongst three numbers)
**## Code Explanation**
1️⃣ Taking Input**
- The program starts by declaring three integer variables: `a`, `b`, and `c`.
- It prompts the user to enter three numbers using `printf()`.
- `scanf("%d%d%d", &a, &b, &c);` is used to read three integer values.
2️⃣ Checking the Largest Number**
- The program uses **nested `if-else` statements** to compare the numbers:
  - If `a > b`, check if `a > c`. If true, `a` is the largest.
  - Otherwise, `c` is the largest.
  - If `b > c`, then `b` is the largest.
  - Otherwise, `c` is the largest.
3️⃣ Displaying the Result**
- The program prints the **largest number** using `printf()`.
**Expected Result:
  Input: 10000  0.14  5
  Output: Year:  1  Amount: Rs 10014.00
          Year:  2  Amount: Rs 10028.02
          Year:  3  Amount: Rs 10042.06
          Year:  4  Amount: Rs 10056.12
          Year:  5  Amount: Rs 10070.20

### 🔍Problem No: 2(Write a C program to calculate Interest.)
**## Code Explanation**
1️⃣ Taking Input**
- The program declares variables:
  - `amount` (Principal amount)
  - `inrate` (Annual interest rate in percentage)
  - `period` (Number of years)
- It prompts the user to enter these values using `printf()` and reads them using `scanf()`.
2️⃣ Interest Rate Conversion**
- Since interest rates are usually given as a percentage, the program converts it into decimal form:
  ```c
  inrate = inrate / 100.0;
3️⃣ Compound Interest Calculation
- amount = amount * (1 + inrate);
4️⃣ Displaying the Result
- printf("Year: %2d  Amount: Rs %8.2f\n", year, amount);
