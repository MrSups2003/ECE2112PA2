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

- Before we start, I have to import numpy first as np. Meaning I have to input 'import numpy as np'
- For this problem, I created an array X with random numbers. To do that, I used 'np.random.random'. This allows the entry of random numbers that are in float. Next is the size of the array, which is a 5x5 square. So this becomes X = np.random.random(5,5).
- Next, I created a variable Z, the formula for normalizing X. I also created a print(z) just for fun
- I then save the normalization of X as 'X_normalized.npy'
- Just type in np.load('X_normalized.npy') and the normalized ndarray will appear
- Here is my coded input:
  ![image](https://github.com/user-attachments/assets/00530939-f4ec-4ae5-9488-d6a66263c1e2)

# DIVISIBLE BY 3 PROBLEM: 
Create the following 10 x 10 ndarray.

![image](https://github.com/user-attachments/assets/056cdcc4-572d-4a48-8d8d-2df4b5852156)

which are the squares of the first 100 positive integers.
From this ndarray, determine all the elements that are divisible by 3. Save the result as div_by_3.npy

- For this problem, I created an array using variable A for np.arange from 1 to 101. Why this range? It's because it will start from 1 and it will end at 100. 101 is just the limit of "less than 101."
- Next, I created another variable called 'B,' which will be A.reshape(10,10). This allows the shape of the array to be a 10x10 square.
- Next is that I created another variable called 'C,' which will be the squared elements from B, which is A that is reshaped to a 10x10 square array and ranges from 1 to 100
- I also wanted to print variable C just to show what the elements inside the array
- Next, I will index C, which will be C[C%3==0]. This will allow us to print the elements that are divisible by 3.
- Now, I save this under the name 'div_by_3.npy'.
- Load this file, and the divisible elements will appear.
- Here is my coded input:
 ![image](https://github.com/user-attachments/assets/afc54e76-8ad9-41c4-b495-ae5701c142c0)


