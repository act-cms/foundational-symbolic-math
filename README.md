# Foundations of Symbolic Mathematics in Python

While many chemical problems can be solved by a "longhand" pen-and-paper
approach, several advanced concepts rely on mathematical skills (e.g.,
calculus, linear algebra, differential equations, variational optimization,
etc.) with which not every student may feel comfortable. This module is meant
to help students develop foundational skills in performing symbolic
mathematical operations in Python. These modules are each structured with a few
applications to chemical problem solving at the general chemistry (first-year)
level, and provide any additional conceptual background when necessary.

Current Lessons:
- Symbolic Algebra

Planned Lessons (coming soon!):
- Symbolic Calculus

## Setup

Notes on environment setup for materials hosted on various platforms.

### Local Installation

1. Create a new Conda environment to sandbox software stack
```
~$ conda create -n algwsym python=3.10 jupyter
```
2. Activate new Conda environment
```
~$ conda activate algwsym
```
3. Install required packages with `pip`, because that's all that distributes `algebra_with_sympy`
```
~$ pip install sympy-for-algebra
~$ pip install algebra-with-sympy
~$ pip install numpy matplotlib
~$ pip install jupyterlab_myst
```
4. To ensure you are using the proper version of SymPy, uninstall any bare `sympy` package
```
~$ pip uninstall sympy
```
5. Any time you wish to run the code in the included lessons, 
    1. Activate `algwsym` Conda environment
        ```
        ~$ conda activate algwsym
        ```
    2. Start your Jupyter lab or notebook instance from within the activated `algwsym` Conda environment


