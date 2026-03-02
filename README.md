# EXP7
Here is the **rephrased version** of your experiment:

---

# **Experiment 7: Study of Looping Statements in Python**

## **Aim**

To understand and implement different looping statements in Python (while and for loops) to perform repetitive operations such as printing number sequences, calculating factorials, and generating the Fibonacci series.

---

## **Theory**

Loops are control structures that allow a block of code to be executed repeatedly as long as a given condition remains true.

In Python, the main types of loops are:

### **While Loop**

* Executes a set of statements as long as the specified condition evaluates to True.
* Suitable when the number of iterations depends on a condition rather than a fixed range.

### **Working of While Loop**

1. The condition is evaluated.
2. If the condition is True, the statements inside the loop are executed.
3. After execution, the condition is checked again.
4. The process continues until the condition becomes False.
5. Once the condition becomes False, the loop terminates and control moves to the next part of the program.

Loops help in minimizing code repetition, increasing efficiency, and simplifying tasks such as mathematical calculations, sequence generation, and pattern printing.

---

## **Algorithms**

### **1. Print Numbers from 1 to 5**

Start
Set i = 1
While i ≤ 5
 Print i
 Increase i by 1
Stop

---

### **2. Print Numbers from 1 to n**

Start
Input value n
Set i = 1
While i ≤ n
 Print i
 Increase i by 1
Stop

---

### **3. Factorial of a Number**

Start
Input number n
Set fact = 1
While n > 0
 fact = fact × n
 Decrease n by 1
Display factorial
Stop

---

### **4. Fibonacci Series**

Start
Input number of terms n
Initialize a = 0 and b = 1
Print a and b
Repeat from term 3 to n
 Calculate c = a + b
 Print c
 Update a = b and b = c
Stop

---

### **5. Reverse of a Number (Using While Loop)**

Start
Input number n
Set rev = 0
While n > 0
 Find remainder r = n % 10
 Update rev = (rev × 10) + r
 Update n = n // 10
Repeat until n becomes 0
Display rev
Stop

---

### **6. Palindrome Number (Using While Loop)**

Start
Input number n
Store original number in temp
Set rev = 0
While n > 0
 Find remainder r = n % 10
 Update rev = (rev × 10) + r
 Update n = n // 10
After loop, compare rev with temp
If rev equals temp
 Print “Number is Palindrome”
Else
 Print “Number is Not Palindrome”
Stop

---

### **7. Choose a Number from a List**

Start
Create a list (e.g., L = [10, 20, 30, 40, 50])
Input a number n
Set found = False
For each element in the list
 If element equals n
  Set found = True
  Exit loop
After loop
If found is True
 Print “Number found in the list”
Else
 Print “Number not found in the list”
Stop

---

### **8. Sum of First n Natural Numbers**

Start
Input number n
Set sum = 0 and i = 1
While i ≤ n
 Add i to sum
 Increase i by 1
Display sum
Stop

---

## **Overall Conclusion**

The experiment was completed successfully. We explored and implemented looping statements in Python using both while and for loops. Through this study, we understood how loops efficiently handle repetitive tasks such as printing sequences, calculating factorials, computing sums, and generating Fibonacci series. Looping constructs make programs more concise, organized, and efficient by reducing redundant code.

---
