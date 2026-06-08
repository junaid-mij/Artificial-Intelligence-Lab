# Python Programming Lab Reports

## Overview

This repository contains three Python Programming Lab Reports developed using Google Colab. The labs cover:

1. Basic Python Programming
2. NumPy Operations
3. Data Visualization using Matplotlib and Seaborn

These reports are designed for beginners and demonstrate fundamental programming, numerical computing, and visualization concepts in Python.

---

# Requirements

The following tools are required:

- Google Account
- Google Colab
- Internet Connection

The required Python libraries are already pre-installed in Google Colab:

```python
import numpy
import matplotlib
import seaborn
```

No additional installation is required.

---

# Lab Report 01: Basic Python Programming

## Objective

To learn the fundamental concepts of Python programming including:

- Variables
- Arithmetic Operations
- Loops
- Functions

## Concepts Covered

### Variable Declaration

```python
num1 = 12
num2 = 8
```

Stores values in variables.

### Arithmetic Operation

```python
product = num1 * num2
```

Performs multiplication between two numbers.

### Loop

```python
for number in range(1, 6):
    print(number)
```

Prints numbers from 1 to 5.

### Function

```python
def cube(n):
    return n ** 3
```

Creates a reusable function that calculates the cube of a number.

## Expected Output

```text
Product: 96
Count: 1
Count: 2
Count: 3
Count: 4
Count: 5
Cube of 3: 27
```

## Learning Outcome

After completing this lab, students will understand:

- Python syntax
- Variables
- Loops
- Functions
- Basic arithmetic operations

---

# Lab Report 02: NumPy in Google Colab

## Objective

To learn numerical computing using the NumPy library.

## Concepts Covered

### Import NumPy

```python
import numpy as np
```

Imports the NumPy library.

### Array Creation

```python
numbers = np.array([10, 20, 30, 40, 50])
```

Creates a NumPy array.

### Statistical Operations

```python
np.max(numbers)
np.min(numbers)
np.mean(numbers)
```

Used to find:

- Maximum value
- Minimum value
- Average value

### Matrix Creation

```python
matrix = np.array([
    [1, 2, 3],
    [4, 5, 6]
])
```

Creates a two-dimensional matrix.

## Expected Output

```text
Array: [10 20 30 40 50]
Maximum Value: 50
Minimum Value: 10
Average: 30.0
Matrix:
[[1 2 3]
 [4 5 6]]
```

## Learning Outcome

After completing this lab, students will understand:

- NumPy arrays
- Matrix operations
- Statistical calculations
- Numerical computing basics

---

# Lab Report 03: 7 Figures Generation Using Matplotlib and Seaborn

## Objective

To learn data visualization techniques using Matplotlib and Seaborn.

## Libraries Used

### Matplotlib

Used for:

- Line Plot
- Bar Chart
- Histogram
- Scatter Plot
- Pie Chart

### Seaborn

Used for:

- Box Plot
- Heatmap

---

## Figures Generated

### 1. Line Plot

Shows trends and changes in data over time.

### 2. Bar Chart

Compares values among categories.

### 3. Histogram

Displays frequency distribution of data.

### 4. Scatter Plot

Shows relationships between variables.

### 5. Box Plot

Displays data distribution and outliers.

### 6. Heatmap

Represents matrix values using colors.

### 7. Pie Chart

Shows percentage distribution of data.

## Expected Output

The notebook generates:

- Line Plot
- Bar Chart
- Histogram
- Scatter Plot
- Box Plot
- Heatmap
- Pie Chart

Each graph is displayed directly below its corresponding code cell.

## Learning Outcome

After completing this lab, students will understand:

- Data visualization
- Graph generation
- Plot customization
- Matplotlib basics
- Seaborn basics

---

# How to Run the Lab Reports

## Using Google Colab

### Step 1

Open Google Colab:

https://colab.research.google.com

### Step 2

Upload the desired notebook (.ipynb).

### Step 3

Run the notebook cells sequentially from top to bottom.

### Step 4

Verify that the outputs and graphs are displayed correctly.

### Step 5

Save the notebook if any modifications are made.

---

# Repository Structure

```text
.
├── Lab01_Basic_Python.ipynb
├── Lab02_NumPy.ipynb
├── Lab03_7_Figures_Generation.ipynb
└── README.md
```

---

# Student Information

**Name:** Marajul Islam

**Roll:** 28

**Course:** Python Programming Lab

---

# Conclusion

These three lab reports provide a strong foundation in Python programming, numerical computing, and data visualization. Together, they introduce essential concepts that are widely used in data science, machine learning, software development, and scientific computing.