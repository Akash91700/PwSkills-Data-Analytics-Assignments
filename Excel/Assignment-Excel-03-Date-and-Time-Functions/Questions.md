# Assignment Excel 03 - Date and Time Functions

---

## Section 1: Understanding TODAY() and NOW()

1. What is the difference between `TODAY()` and `NOW()` in Excel? Provide an example of when you would use each function.

2. If cell A1 contains the date **2025-06-10**, write a formula using `TODAY()` to determine how many days are left until that date.

3. Write an Excel formula using `NOW()` to display the current date and time in the format **MM/DD/YYYY HH:MM AM/PM**.

4. If a cell contains `=TODAY()`, what will happen when the worksheet is reopened the next day? Explain.

5. You want to store a **static date** (today’s date) in a cell without it changing every day.  
   What keyboard shortcut should you use?

---

## Section 2: Practical Applications of TODAY()

6. Suppose you are managing project deadlines, and column B contains task due dates.  
   Write a formula that checks if a task is overdue by comparing the due date (column B) with today’s date.

7. A company wants to calculate the years of service for employees based on their joining date in column C.  
   Write a formula using `TODAY()` that calculates the number of complete years worked.

8. Write a conditional formatting rule formula that highlights all due dates (column B) that have already passed.

---

## Section 3: Practical Applications of NOW()

9. You want to create a timestamp that records the exact time when a user enters data in column D.  
   What formula should you use, and what potential issue might occur if the worksheet is recalculated?

10. Write an Excel formula to determine the number of hours that have passed between a given timestamp in cell A1 and the current time using `NOW()`.

---

## Section 4: Using DATEDIF for Date Calculations

11. If cell A2 contains **01/01/2010** and cell B2 contains **08/15/2025**, write a formula using `DATEDIF()` to calculate the number of complete years between these dates.

12. Modify the formula from question 11 to calculate only the number of full months between the two dates.

13. You need to calculate the number of days between two dates (ignoring the years).  
    Write a `DATEDIF()` formula that finds the number of days between **03/10/2022** and **06/25/2025**, ignoring years.

14. Write an Excel formula using `DATEDIF()` to determine a person’s exact age in years, months, and days if their birthdate is in cell A1.

---

## Section 5: Advanced Usage

15. Write a formula that displays a message like:  
   **"Today is Monday, January 22, 2025, and the current time is 02:45 PM"**  
   *(Hint: Use `TEXT()`, `TODAY()`, and `NOW()` together).*
