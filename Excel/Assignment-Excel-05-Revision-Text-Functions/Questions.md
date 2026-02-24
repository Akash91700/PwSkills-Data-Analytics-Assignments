# Assignment Excel 05 - Revision of TEXT Functions

---

## Dataset Link  
**Practice Data**

---

### 1. Clean and Standardize Names  
Use a combination of `TRIM` + `PROPER` to remove extra spaces and convert names to proper case.

---

### 2. First Name Extraction  
Extract the first name from the Name column.

---

### 3. Last Name Extraction  
Extract the last name in a new column.

---

### 4. Clean Emails  
Emails contain inconsistencies (spaces, uppercase, and misplaced dots).  
Using `TRIM`, `LOWER`, and `SUBSTITUTE`, create a standard email column named **Clean_Email** that:
- Removes spaces before/after @  
- Replaces double spaces  
- Converts all text to lowercase

---

### 5. Extract Email Domain  
From the cleaned email, extract the domain such as `gmail.com`, `yahoo.com`, etc.

---

### 6. Convert Product Names  
Create a new column and convert all product names to **uppercase**.

---

### 7. Standardize Product Codes  
Clean and standardize all product codes using text functions so that every code follows a uniform format: `P-0XX`  
Examples: `"P-001"`, `"P-005"`, `"P-008"`

---

### 8. Numeric Code Extraction  
From the Code column, extract only the **numeric part** using the `TEXT` function.

---

### 9. Find Keyword  
Find entries containing the word **"road"** in the address column.

---

### 10. Create Unique Identifier  
Create a **unique customer identifier** by combining:
- First Name
- Last 3 digits of product code

