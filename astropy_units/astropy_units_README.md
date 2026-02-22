# AstroPy Units & Constants – Physical Consistency in Computation

This folder documents structured practice using `astropy.units` 
and `astropy.constants`, developed as part of my preparation 
for computational astrophysics and cosmology workflows.

## Topics Covered

### 1. Attaching Physical Units
- Creating Quantity objects (e.g., `10 * u.Mpc`)
- Working with velocities (`km/s`)
- Preventing unit inconsistencies in calculations

### 2. Unit Conversion
- Converting between compatible units
- Using `.to()` for controlled physical transformations

### 3. Hubble Law with Units
- Implementing \( v = H_0 d \)
- Ensuring dimensional correctness in cosmological calculations

### 4. Using Physical Constants
- Speed of light (`const.c`)
- Gravitational constant (`const.G`)
- Incorporating constants directly into physics equations

### 5. Arrays with Units
- Applying units to NumPy arrays
- Performing vectorized cosmological computations safely

### 6. Estimating the Age of the Universe
- Using the approximation \( t \approx 1/H_0 \)
- Converting time scales to years

---

## Why This Matters for Cosmology

Unit-aware computation is critical in astrophysics to:

- Avoid dimensional errors
- Maintain physical consistency
- Improve reproducibility
- Write research-grade scientific code

AstroPy’s unit system enforces correctness and mirrors 
professional astrophysics workflows used in research.

---

## Transparency Note

This README file was drafted with the assistance of AI 
for clarity and structure. All coding, execution, 
and conceptual work were carried out by me as part of 
my astrophysics training and workshop preparation.