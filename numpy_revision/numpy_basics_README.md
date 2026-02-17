# NumPy Arrays – Fundamentals (Up to Array Properties)

This folder contains structured revision of NumPy array fundamentals, 
prepared as part of my computational training for astronomy and cosmology.

## Topics Covered

- Importing NumPy (`import numpy as np`)
- Difference between Python lists and NumPy arrays
- Creating arrays using:
  - `np.array()`
  - `np.zeros()`
  - `np.ones()`
  - `np.linspace()`
  - `np.arange()`
- Understanding array properties:
  - `shape`
  - `size`
  - `dtype`

## Why NumPy?

NumPy is the foundation of scientific computing in Python.  
Unlike Python lists, NumPy arrays support:

- Element-wise mathematical operations
- Efficient numerical computation
- Structured multi-dimensional data handling

These capabilities are essential for:

- Handling astronomical datasets
- Performing vectorized calculations
- Preparing for data analysis using AstroPy and Matplotlib

## Key Concepts Learned

### 1. List vs Array Behavior
NumPy arrays perform mathematical operations element-wise, 
while Python lists do not behave numerically by default.

### 2. Array Creation
Different array creation functions allow structured data generation 
for numerical simulations and scientific workflows.

### 3. Array Properties
Understanding `shape`, `size`, and `dtype` is crucial for:

- Working with multi-dimensional datasets
- Preparing data for plotting
- Performing numerical operations correctly

### 4. indexing and slicing 
understanding  how to access elements from array and how to add elements

This revision forms the computational foundation required 
for further work in numerical methods and astrophysics data analysis.

# NumPy Arrays – Scientific Computing Foundations

This folder contains structured revision of NumPy fundamentals,
prepared as part of my computational training for astronomy and cosmology.

---

## Topics Covered

### 1. Importing NumPy
- `import numpy as np`

NumPy is the foundation of numerical and scientific computing in Python.

---

### 2. Lists vs NumPy Arrays

NumPy arrays differ from Python lists in that they:

- Support element-wise mathematical operations
- Enable efficient numerical computation
- Work naturally with multi-dimensional data

Example:
- Python list: `[1,2,3] * 2` repeats elements
- NumPy array: `np.array([1,2,3]) * 2` multiplies each element

---

### 3. Array Creation

Arrays were created using:

- `np.array()`
- `np.zeros()`
- `np.ones()`
- `np.linspace(start, stop, points)`
- `np.arange(start, stop, step)`

`linspace` is especially important in physics and cosmology for generating evenly spaced numerical grids.

---

### 4. Array Properties

Understanding array structure is essential:

- `shape` → dimensions of array
- `size` → total number of elements
- `dtype` → data type of elements

These properties are critical when handling astronomical datasets and numerical simulations.

---

### 5. Indexing & Slicing

NumPy arrays allow:

- Element access using index notation
- Slicing to extract subarrays
- Multi-dimensional indexing for 2D arrays

This is foundational for:

- Working with image data (FITS files)
- Extracting columns from observational tables
- Manipulating numerical grids

---

### 6. 2D Arrays (Matrices)

Multi-dimensional arrays were introduced to simulate structured datasets.

Applications include:

- Image data processing
- Covariance matrices
- Parameter grids in cosmology

---

### 7. Vectorized Operations

NumPy allows element-wise mathematical operations without explicit loops:

- Addition
- Multiplication
- Power operations
- Square root
- Mean
- Standard deviation

Vectorization improves:

- Code clarity
- Performance
- Scientific readability

---

### 8. Broadcasting

Broadcasting enables automatic expansion of smaller arrays during arithmetic operations.

This feature allows:

- Adding constants to entire datasets
- Applying transformations efficiently
- Writing compact scientific code

Broadcasting is a core concept in scientific Python workflows.

---

## Why This Matters for Astronomy

NumPy arrays form the backbone of:

- Cosmological calculations
- Supernova data analysis
- Redshift–velocity transformations
- Numerical integration
- Statistical analysis of observational data

This revision establishes the computational foundation required
for advanced numerical methods and astrophysical data analysis.


NOTE: This README.md made by AI based on my work that I Done.
