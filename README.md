# Optimization
## Lagrangian minimization problem
### Symbolic and Numerical Optimization with SymPy and NumPy

This project involves symbolic computation using SymPy and numerical computation using NumPy to solve an optimization problem. The primary goal is to find the unit vector that maximizes the dot product with a given input vector under a specified constraint.

## Requirements

- Python 3.x
- SymPy
- NumPy

You can install the necessary packages using pip:

```bash
pip install sympy numpy
```

## Usage

1. Clone the repository or download the script.
2. Run the script using Python:

```bash
python optimization_script.py
```

3. Follow the prompts to input the dimensions, coefficients, and variables of your vector.
4. The script will compute the optimized unit vector and print the results, including the Lagrangian equation, Jacobian matrix, Hessian matrix, and the maximized dot product.

## Output

- **Primary function**: The function representing the dot product of the input vector and the symbolic vector.
- **Constraint**: The sum of the squared variables minus 1, representing the unit vector condition.
- **Lagrangian equation**: The equation combining the primary function and the constraint with a Lagrange multiplier.
- **Jacobian matrix**: The matrix of first derivatives of the Lagrangian equation with respect to the variables.
- **Hessian matrix**: The matrix of second derivatives of the Lagrangian equation.
- **Unit vector**: The vector that maximizes the dot product under the given constraint.
- **Maximized dot product**: The final optimized dot product value.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
