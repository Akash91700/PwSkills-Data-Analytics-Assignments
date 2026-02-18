# Assignment 05 - Student Performance Analysis (NumPy & Pandas)

## Dataset: Student Evaluation Dataset

### Columns:
- Student_ID
- Name
- Subject
- Score
- Hours_Studied
- Gender
- Region

---

## Task 1: Data Cleaning

1. Identify missing values in the dataset.
2. Replace missing "Score" values with subject-wise average.
3. Replace missing "Hours_Studied" with overall mean.
4. Drop rows where both "Score" and "Hours_Studied" are missing.

---

## Task 2: Subject-wise Analysis

1. Calculate average score per subject.
2. Identify subject with highest average score.
3. Find subject with highest average study hours.
4. Identify top performer in each subject.

---

## Task 3: Regional Analysis

1. Calculate region-wise average score.
2. Identify region with highest average study hours.
3. Identify region with lowest performance.

---

## Task 4: Gender-Based Analysis

1. Compare average scores of male vs female.
2. Compare average study hours of male vs female.
3. Identify top 3 highest-scoring female students.
4. Identify lowest 2 scoring male students.

---

## Task 5: Performance Categorization

1. Create new column "Performance":
   - High → Score ≥ 80
   - Low → Score < 80
2. Count number of students in each category.
3. Compare performance distribution across subjects.

---

## Task 6: Insights & Trends

1. Does more study time always mean higher score?
2. Identify one student who scored > 80 with < 10 hours study.
3. Identify one student who studied > 12 hours but scored < 70.
