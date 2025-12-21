# Computational Theory
This is a Jupyter Notebook testing and implementing algorithms describe in the FIPS PUB 180-4 Secure Hash Standard.

## Project Overview
This notebook covers five main concepts:
1. Logical bitwise functions: 
    - `Parity(x, y, z)`
    - `Ch(x, y, z)`
    - `Maj(x, y, z)`
    - `Sigma0(x)`
    - `Sigma1(x)`
    - `sigma0(x)`
    - `sigma1(x)`
    
    All of which use 32-bit words, to produce a new 32-bit word output.

2. The mathematical calculations necessary to derive the sixty four K constants.

3. Generator function to compute message parsing.

4. Implement hash computation of a message block from the current value.

5. Applying dictionary attacks on passwords using the SHA-256 algorithms.

## Setup Instructions
### Prerequisites
- Python 3.12+
- NumPy
- JupyterLab/Jupyter Notebook (installation below)

### 1. Clone the repository:
```bash
git clone https://github.com/natashazywczyk/Computational-Theory.git
```

### 2. Go into cloned repository:
```bash
cd Computational-Theory
```

### 3. Install required dependencies:
```bash
pip install -r requirements.txt
```

### 4. Start up the Jupyter Notebook:
```bash
jupyter notebook problems.ipynb
```

- If Juypter is not already installed:
    ```bash
    pip install jupyter
    ```

## Running the Code
- All code is provided in `problems.ipynb`
- Either 'Run All' or run each function individually manually
- Run from the top
- No external files necessary 

## Reference
The main reference used throughout this notebook and `problems.ipynb` is the [Secure Hash Standard](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf) (FIBS PUB-180).