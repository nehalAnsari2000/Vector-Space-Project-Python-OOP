# Vector Space Python Project

## Overview

This project is an implementation of 2D and 3D vector spaces in Python using object-oriented programming (OOP). It defines an `R2Vector` class for 2D vectors and extends it with an `R3Vector` class for 3D vectors, demonstrating class inheritance. The project was developed as part of the **Scientific Computing with Python** certification on **FreeCodeCamp**, where I explored OOP concepts such as encapsulation, method overriding, and operator overloading.

## Features

- **Object-Oriented Design**: Uses OOP principles, including inheritance and encapsulation.
- **Supports 2D and 3D Vectors**: Implements `R2Vector` (2D) and `R3Vector` (3D) classes.
- **Operator Overloading**:
  - Addition (`+`) and subtraction (`-`) of vectors.
  - Scalar multiplication (`*`) and dot product calculation.
  - Equality (`==`), inequality (`!=`), and comparison operators (`<`, `>`, `<=`, `>=`).
- **Cross Product Calculation**: The `R3Vector` class implements the cross product operation.
- **Vector Norm Calculation**: Computes the magnitude of a vector.
- **Readable String Representation**: `__str__` and `__repr__` methods for better debugging and display.

## Implementation Details

### `R2Vector` Class
- Represents a 2D vector with `x` and `y` coordinates.
- Includes vector addition, subtraction, scalar multiplication, dot product, and comparison operations.
- Uses a `norm` method to calculate vector magnitude.

### `R3Vector` Class (Extends `R2Vector`)
- Adds a `z` coordinate to extend functionality to 3D vectors.
- Implements a `cross` method for cross product calculation.
- Inherits other functionalities from `R2Vector`.

## Usage

### Creating Vectors
```python
v1 = R3Vector(x=2, y=3, z=1)
v2 = R3Vector(x=0.5, y=1.25, z=2)
```

### Performing Operations
```python
v3 = v1 + v2  # Vector Addition
v4 = v1 - v2  # Vector Subtraction
v5 = v1 * v2  # Dot Product
v6 = v1.cross(v2)  # Cross Product
```

### Example Output
```
v1 = (2, 3, 1)
v2 = (0.5, 1.25, 2)
v1 + v2 = (2.5, 4.25, 3)
v1 - v2 = (1.5, 1.75, -1)
v1 * v2 = 8.25
v1 x v2 = (4.25, -3.5, -0.25)
```

## Dependencies
- Python 3.x
- 
## Acknowledgments
This project was developed as part of the **Scientific Computing with Python** certification on **FreeCodeCamp**, where I learned about object-oriented programming, class inheritance, and operator overloading in Python.

