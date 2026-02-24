# Assignment Excel 04 - VLOOKUP, HLOOKUP & IF ELSE

---

## Dataset Link

Employee_bonus *(Use this dataset for lookup tasks)*

---

## VLOOKUP Questions

1. Using `VLOOKUP`, find the **Salary** of “Yuvraj Patel”.  
2. Using `VLOOKUP`, return the **Department** of Emp_ID = **1031**.  
3. Use `VLOOKUP` to find the **City** of “Sneha Chakraborty”.  
4. Using `VLOOKUP`, fetch the **Score** for Emp_ID = **1050**.  
5. `VLOOKUP`: Find the **Bonus_Eligible** status of “Tara Chawla”.

---

## HLOOKUP Questions

6. Convert the dataset horizontally and use `HLOOKUP` to return the **Salary** of Emp_ID = **1020**.  
7. Using `HLOOKUP`, retrieve the **Department** value for Emp_ID = **1044**.

---

## IF Questions

### IF Simple
8. IF for Salary Category:  
   - If Salary ≥ 70,000 → “High Salary”  
   - Else → “Regular Salary”

---

### IF + AND

9. Rating:  
   - If Score ≥ 85  
   - And Salary ≥ 60,000  
   then return **“Top Performer”**  
   Else return **“Average Performer”**.

10. Create a formula that returns a **combined designation** based on each employee’s City and Department:  
   - Format: *City* + “ ” + *Department*  
   Example output must be:  
   - *Mumbai Marketing Staff*  
   - *Delhi Finance Staff*  
   - *Bengaluru HR Staff*  
   - *Chennai Operations Staff*  
   - *Pune Sales Staff*

   *(Use IF statements to automatically generate the correct result)*

---

## IF + OR

11. Create a formula that returns an employee’s **zone → designation** based on the city:

### City to Zone mapping:
- Mumbai, Pune → *West Zone*  
- Delhi → *North Zone*  
- Chennai, Bengaluru → *South Zone*

Return text as:
