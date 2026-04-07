# Experiment No. 14: Data Normalization and Data Types

**Name:** Vibhas Shukla 
**PRN:** 25070123164  
**Branch:** F.Y. E&TC (2025–29)  
**Batch:** A1  
**Subject:** Exploratory Data Analysis with Python  

---

## 1. Aim

The aim of this experiment is to study and implement various **data normalization techniques** and understand different **data types**, along with converting categorical data into numerical form so that the dataset becomes suitable for analysis and machine learning.

---

## 2. Objective

- To understand the concept of **data normalization**  
- To apply normalization techniques such as **Min-Max, Z-Score, and Decimal Scaling**  
- To understand the difference between **numerical and categorical data**  
- To convert categorical data into numerical form using encoding techniques  
- To improve data quality and make it suitable for analysis  

---

## 3. Concepts Used

### 3.1 Data Normalization
Data normalization is the process of scaling numerical values into a fixed range so that all features contribute equally during analysis.

### 3.2 Types of Normalization
- Min-Max Normalization  
- Z-Score Normalization  
- Decimal Scaling  

### 3.3 Data Types
- Numerical Data  
- Categorical Data  

### 3.4 Encoding Techniques
- Label Encoding  
- One-Hot Encoding  
- Dummy Encoding  

---

## 4. Theory

### 4.1 Introduction to Data Normalization

In real-world datasets, different features often have values in different ranges. For example, price values may be in thousands while ratings may be in decimals. This difference in scale can negatively affect data analysis and machine learning models.

Data normalization helps in bringing all values to a **common scale** without changing their original relationships.

---

### 4.2 Need for Data Normalization

- Ensures fair comparison between features  
- Prevents bias due to large values  
- Improves model performance  
- Helps in faster and more accurate computations  
- Essential for machine learning algorithms  

---

### 4.3 Types of Normalization Techniques

#### 1. Min-Max Normalization

This method rescales the data into a fixed range (usually between 0 and 1).

**Formula:**

X' = (X - X_min) / (X_max - X_min)

**Explanation:**
- X = Original value  
- X_min = Minimum value in dataset  
- X_max = Maximum value in dataset  
- X' = Normalized value  

**Characteristics:**
- Values always lie between 0 and 1  
- Maintains original data distribution  

---

#### 2. Z-Score Normalization (Standardization)

This method transforms data based on mean and standard deviation.

**Formula:**

Z = (X - Mean) / Standard Deviation

**Explanation:**
- X = Original value  
- Mean = Average of dataset  
- Standard Deviation = Spread of data  
- Z = Standardized value  

**Characteristics:**
- Data is centered around zero  
- Useful when dataset contains outliers  

---

#### 3. Decimal Scaling

This method scales values by dividing them by powers of 10.

**Formula:**

X' = X / (10^j)

**Explanation:**
- X = Original value  
- j = Number of digits in the maximum value  
- X' = Scaled value  

**Characteristics:**
- Simple and easy to apply  
- Keeps data distribution intact  

---

### 4.4 Data Types

#### 1. Numerical Data
- Represents measurable quantities  
- Can be:
  - Continuous (e.g., height, weight, price)  
  - Discrete (e.g., number of students)  

#### 2. Categorical Data
- Represents labels or categories  
- Example: Gender, City, Product Type  
- Cannot be directly used in mathematical models  

---

### 4.5 Encoding of Categorical Data

Since machine learning models require numerical input, categorical data must be converted into numbers.

---

#### 1. Label Encoding

- Assigns a unique number to each category  
- Example: Male = 0, Female = 1  

**Advantages:**
- Simple and fast  
- Memory efficient  

**Disadvantage:**
- Introduces artificial order  

---

#### 2. One-Hot Encoding

- Creates separate columns for each category  
- Uses binary values (0 or 1)  

**Advantages:**
- No order is assumed  
- More accurate representation  

**Disadvantage:**
- Increases number of columns  

---

#### 3. Dummy Encoding

- Similar to one-hot encoding  
- Removes one column to avoid redundancy  

**Advantages:**
- Prevents multicollinearity  
- Reduces dimensionality  

---

### 4.6 Application in Dataset

In this experiment:

- Numerical columns such as **Price, Calories, Ratings, and Units Sold** were normalized using different techniques  
- Categorical columns such as **Gender, City, Product Category, and Payment Method** were encoded into numerical values  
- The dataset was transformed into a structured format suitable for analysis  

---

### 4.7 Importance of Normalization and Encoding

- Improves data consistency  
- Makes data suitable for machine learning  
- Enhances accuracy of results  
- Helps in better visualization and interpretation  
- Reduces errors caused by scale differences  

---

## 5. Conclusion

In this experiment, different data normalization techniques such as **Min-Max Normalization, Z-Score Normalization, and Decimal Scaling** were successfully studied and applied. These techniques helped in scaling numerical data into a uniform range.

Additionally, categorical data was converted into numerical format using encoding techniques such as **Label Encoding, One-Hot Encoding, and Dummy Encoding**.

Overall, this experiment highlights the importance of **data preprocessing** in exploratory data analysis and demonstrates how normalization and encoding play a crucial role in preparing high-quality datasets for analysis and machine learning.

---
