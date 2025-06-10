# Home Assignment 2 –


## Student Info

* **Name:** *Thota Praneeth Babu*
* **Student ID:** *\[700777380]*
* **Course:** CS5720 Neural Networks and Deep Learning
* Home Assignment 2,

---

## Question 1: Convolution Operations with Different Parameters

### Overview

This part of the assignment demonstrates how 2D convolution behaves with different stride and padding settings. I used both **NumPy** (for basic understanding) and **TensorFlow/Keras** (for real-world, modern DL frameworks).

### Task Summary

* Define a **5x5 input matrix** and a **3x3 kernel** as specified.
* Perform 2D convolution with the following combinations:

  * Stride = 1, Padding = ‘VALID’
  * Stride = 1, Padding = ‘SAME’
  * Stride = 2, Padding = ‘VALID’
  * Stride = 2, Padding = ‘SAME’
* Print out all four output feature maps.
* Keep the code clean, clear, and well-commented.

### Files

* `convolution_operations.py` – Contains the code to run all experiments.
* *Add any utility/image files if necessary.*

### How to Run

1. Make sure you have Python 3.x installed.
2. Install dependencies (preferably in a virtual environment):

   ```bash
   pip install numpy tensorflow
   ```
3. Run the script:

   ```bash
   python convolution_operations.py
   ```

   All outputs for each parameter setting will be printed to the console.

### Expected Output

The script will print the output feature maps for each configuration:

* **Stride = 1, Padding = ‘VALID’**
* **Stride = 1, Padding = ‘SAME’**
* **Stride = 2, Padding = ‘VALID’**
* **Stride = 2, Padding = ‘SAME’**

* Code Explanation
The code is straightforward, using both NumPy for manual convolution and TensorFlow/Keras’s built-in layers for the actual operations. Comments are added for every step, so you know what is happening and why. No “black box” magic here.
