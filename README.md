# ECE2112PA2
Name: Supnet Joshua
Section: 2ECE-D
Date Submitted: September 2, 2024

# II. Instructions:
Write a Python script/code in the Jupyter Notebook to solve the problems. You may submit your Jupyter
notebook in the dedicated submission bin.

# NORMALIZATION PROBLEM: 

Normalization is one of the most basic preprocessing techniques in
data analytics. This involves a centering and scaling process. Centering means subtracting the data from the
Mean, and scaling means dividing by its standard deviation. Mathematically, normalization can be expressed as:
- 𝑍 = (𝑋 − 𝑥̅)/𝜎

In Python, element-wise mean and standard deviation can be obtained using .mean() and .std() calls.
In this problem, create a random 5 x 5 array and store it to variable X. Normalize X. Save your normalized ndarray as X_normalized.npy

- For this problem, I created an array X with random numbers. To do that, I used 'np.random.random'. This allows the entry of random numbers that are in float. Next is the size of the array, which is a 5x5 square. So this becomes X = np.random.random(5,5).
-
