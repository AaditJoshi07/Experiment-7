

Aim:-

To understand and implement the control flow of while loops in Python through various mathematical and logical programming exercises including factorials, Fibonacci series, and string manipulation.

---

Theory:-

A while loop in Python repeatedly executes a target statement as long as a given condition is true. It is generally used when the number of iterations is not known beforehand.

Initialization: Setting a starting value for a counter or variable.

Condition: A logical expression checked before each iteration.

Body: The block of code that runs if the condition is true.

Update: Modifying the variable (increment/decrement) to eventually make the condition false and avoid an infinite loop.

Control Statements: break is used to exit the loop prematurely, while continue skips the current iteration and jumps to the next cycle.

---

Algorithms:-

1. Basic Counting (1 to N)
   
Initialize a variable i = 1.

Input the limit N.

While i <= N, print i and increment i by 1.

---

2. Factorial of a Number
   
Input a number n and initialize fact = 1.

While n > 0:

Multiply fact by n.

Decrement n by 1.

Print the final value of fact.

---

3. Fibonacci Series

Initialize a = 0, b = 1, and a counter i = 1.

While i <= N:

Print the current value of a.

Calculate the next term c = a + b.

Update a = b and b = c.

Increment i.

---

4. Reverse a Number
   
Input a number num and set rev = 0.

While num > 0:

Extract the last digit: digit = num % 10.

Append to reverse: rev = (rev * 10) + digit.

Remove the last digit: num //= 10.

Print rev.

---

5. Palindrome Check (Number/String)
   
Store the original input in a temp variable and reverse it using a loop or slicing.

Compare the original value with the reversed value.

If equal, print "Palindrome"; otherwise, "Not Palindrome".

---

6. Count Digits
   
Input num and set count = 0.

While num > 0:

Increment count.

Perform integer division num //= 10.

Print the count.

---

7. Linear Search (with Break)
   
Initialize a list and a found flag as False.

Iterate through the list using an index i.

If list[i] matches the search element, set found = True and break the loop.

After the loop, check the found flag to print the result.

---

8. Odd Numbers (with Continue)
   
Initialize i = 0.

While i < 10:

Increment i.

If i % 2 == 0 (even), use continue to skip the print statement.

Otherwise, print i.

---

Conclusion:-

We have successfully demonstrated the utility of while loops for repetitive tasks and mastered the use of jump statements to effectively control program execution.

---
