![Lexicon Logo](https://lexicongruppen.se/media/wi5hphtd/lexicon-logo.svg)

# Workshop: Algorithm and Flowchart

For each question in this workshop, you must complete **two** things:

1.  **Write the pseudocode**
2.  **Draw the flowchart** using either
    - **Option 1:** Draw.io (recommended) → export image → upload to
      your repository → link it in this file
    - **Option 2 (optional):** Write a Mermaid flowchart directly in
      Markdown
    - **Option 3 (optional):** Any other valid method

👉 **IMPORTANT:** At the **bottom of each question**, add the
following sections:

### ✔ Pseudocode

### ✔ Flowchart

---

## 1. Check Even or Odd Number

Design an algorithm and flowchart that take a number as input and
determine whether it is even or odd.

### ✔ Pseudocode

```text
START
    INPUT number
    IF number % 2 == 0 THEN
        PRINT Even
    ELSE
        PRINT Odd
    ENDIF
END
```

### ✔ Flowchart

```mermaid
flowchart TD
    A([Start]) --> I[/Get input N/]
    I --> B{N % 2 == 0 ?}
    B -->|Yes| C[/Print Even/]
    B -->|No| D[/Print Odd/]
    C --> E([End])
    D --> E([End])
```

---

## 2. Calculate Total and Average Marks

Write the algorithm and draw the flowchart for a program that inputs
marks for 3 subjects, calculates the total and average, and displays
both.

###  Pseudocode

```text
START
    set total = 0
    FOR i FROM 1 to 3
        Input marks
        SET total = total + marks
    ENDFOR
    SET average = total / 3
    OUTPUT total
    OUTPUT average    
END
```     

###  Flowchart
![Flowchart](flowchart1.drawio.svg)
---

## 3. Display Multiplication Table

Create an algorithm and flowchart that input a number and display its
multiplication table from 1 to 10 using a loop.

###  Pseudocode

```text
START
    INPUT number
    FOR i FROM 1 to 10
        SET result = number * i
        OUTPUT result
    ENDFOR  
END
```     

###  Flowchart
![Flowchart](flowchart2.drawio.svg)
---

## 4. Positive, Negative, or Zero Check

Write the algorithm and flowchart to input a number and display whether
it is positive, negative, or zero.

###  Pseudocode

```text
START
    INPUT number
    IF number == 0 THEN
        OUTPUT zero
    ELSE IF number > 0 THEN
        OUTPUT positive    
    ELSE
        OUTPUT negative
    ENDIF
     
END
```     
###  Flowchart
![Flowchart](flowchart3.drawio.svg)
---

## 5. Simple Interest Calculator

Create an algorithm and flowchart for a program that calculates simple
interest using the formula:

**SI = (P × R × T) / 100**

- **P = Principal** → original amount of money
- **R = Rate of Interest** → percentage per year
- **T = Time** → number of years

###  Pseudocode

```text
START
    INPUT Principal
    INPUT InterestRate
    INPUT Time
    SET SimpleInterest=(Principal*InterestRate*Time )/100                                     
    OUTPUT SimpleInterest
END
```   

###  Flowchart
![Flowchart](flowchart4.drawio.svg)
---

## 6. Average Temperature Calculation

Write the algorithm and draw the flowchart for a program that takes the
temperature of 7 days, finds the average temperature, and displays it.

###  Pseudocode

```text
START
    set total = 0
    For i FROM 1 to 7
    INPUT Temperature
    SET total = total + Temperature
    End For
    SET average = total / 7
    OUTPUT average
END
```   

###  Flowchart
![Flowchart](flowchart5.drawio.svg)
---

## 7. Calculate Area of a Rectangle

Create an algorithm and flowchart to input length and width, calculate
the area (**Area = Length × Width**), and display the result.

###  Pseudocode

```text
START
    INPUT length
    INPUT width
    SET area = length * width
    OUTPUT area
END
```   

###  Flowchart
![Flowchart](flowchart6.drawio.svg)

---

## 8. Determine Pass or Fail

Write the algorithm and draw the flowchart for a program that takes a
student's average marks and displays **"Pass"** if average ≥ 50,
otherwise **"Fail"**.

###  Pseudocode

```text
START
    INPUT average
    IF average > = 50  THEN
        OUTPUT Pass
    ELSE
        OUTPUT Fail
    ENDIF
END
```
###  Flowchart
![Flowchart](flowchart7.drawio.svg)
---

## 9. Calculate Factorial of a Number

Write the algorithm and draw the flowchart that input a number and
calculate its factorial using a loop.

###  Pseudocode

```text
START
    INPUT number
    IF number < 0
       OUTPUT Not defined
    ELSE   
       SET factorial = 1
       FOR i FROM 1 to number
          SET factorial = factorial*i
       END FOR
    OUTPUT factorial
    END IF
END
```
###  Flowchart
![Flowchart](flowchart8.drawio.svg)

---

## 10. Calculate Discount on Purchase

Write the algorithm and draw the flowchart for a program that inputs the
purchase amount and gives a **10% discount** if the amount is greater
than 1000.

###  Pseudocode

```text
START
    INPUT Purchase
    IF Purchase > 1000
       SET discount = 0.10
    ELSE   
       SET discount = 0
    END IF
    SET discountAmount=Purchase*discount
    SET total = Purchase - discountamount
    OUTPUT total
END
```
###  Flowchart
![Flowchart](flowchart9.drawio.svg)


---


## Optional Exercises (11–16)

## 11. Online Shopping Delivery Eligibility

Write the algorithm and draw the flowchart for a program that inputs a
customer's purchase amount and displays **"Free Delivery"** if the
amount is 500 SEK or more; otherwise display **"Delivery Charge
Applies"**.

###  Pseudocode

```text
START
    INPUT Purchase
    IF Purchase >=500
       OUTPUT Free Delivery
    ELSE   
       OUTPUT Delivery Charge Applies
    END IF

    END
```
###  Flowchart
![Flowchart](flowchart10.drawio.svg)



---

## 12. Employee Salary and Bonus Calculator

Write the algorithm and draw the flowchart for a program that inputs an
employee's monthly salary and years of service, calculates a bonus of
**10%** for employees with 5 or more years of service and **5%** for
others, then displays the bonus and total salary.

###  Pseudocode

```text
START
    INPUT salary
    INPUT years
    IF salary < 0 OR years < 0
       OUTPUT Invalid Input
    ELSE
        IF years > = 5
          SET bonus = salary * 0.10
        ELSE   
          SET bonus = salary * 0.05
        END IF
      SET totalSalary = salary + bonus
      OUTPUT bonus
      OUTPUT totalSalary
    END if

    END
```
###  Flowchart
![Flowchart](flowchart11.drawio.svg)

---

## 13. Mobile Data Usage Monitor

Write the algorithm and draw the flowchart for a program that inputs a
user's monthly data limit and data usage, then displays whether the user
has exceeded the limit or how much data remains.

---

## 14. Login System (Maximum 3 Attempts)

Create an algorithm and flowchart for a login system that allows a user
up to 3 attempts to enter the correct password. Display **"Access
Granted"** if the password is correct; otherwise display **"Account
Locked"** after 3 failed attempts.

---

## 15. Store Checkout with Multiple Items

Write the algorithm and draw the flowchart for a program that inputs the
number of items purchased, calculates the total purchase amount using a
loop, and applies a **15% discount** if the total exceeds 5000 SEK.

---

## 16. Electricity Bill Calculator

Write the algorithm and draw the flowchart for a program that inputs the
number of electricity units consumed and calculates the total bill using
the following rates: first 100 units at 1.5 SEK per unit, next 200
units at 2.0 SEK per unit, and all remaining units at 3.0 SEK per unit.

---
