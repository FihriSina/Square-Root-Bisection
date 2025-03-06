# Square Root Bisection Method in Python

This project implements the **Square Root Calculation using the Bisection Method** in Python. It uses an iterative approach to approximate the square root of a given number.

## Problem Description

The program calculates the square root of a non-negative number using the **Bisection Method**. This method works by iteratively narrowing the range (low and high values) until the approximate square root is found within a specified tolerance.

## Features
- Calculates the square root of non-negative numbers.
- Uses a bisection approach to find the square root.
- Handles edge cases for `0` and `1` directly.
- Provides an option to set the tolerance for precision.
- Limits the number of iterations to avoid infinite loops.

## Function: `square_root_bisection(square_target, tolerance=1e-7, max_iterations=100)`

### Parameters:
- `square_target`: The number whose square root needs to be calculated.
- `tolerance`: The acceptable error range for the result. The default is `1e-7`.
- `max_iterations`: The maximum number of iterations to attempt. The default is `100`.

### Return:
- The function returns the approximate square root of the input number.

### Example Usage:
```python
N = 16
square_root_bisection(N)
```

This will output:
```
The square root of 16 is approximately 4.0
```

### Error Handling:
- If the `square_target` is negative, a `ValueError` is raised because the square root of negative numbers is undefined in the real number system.
- The program will stop if it converges to a result within the tolerance or if it exceeds the maximum number of iterations.

## Installation

To use this script, just clone the repository and run the Python file.

1. Clone the repository:
    ```bash
    git clone https://github.com/FihriSina/Square-Root-Bisection.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Square-Root-Bisection
    ```
3. Run the script:
    ```bash
    python square_root_bisection.py
    ```

## Contributing

This project was completed as part of my learning journey with **FreeCodeCamp**. Contributions, suggestions, and improvements are always welcome!

## License

This project is open-source and available under the MIT License.
