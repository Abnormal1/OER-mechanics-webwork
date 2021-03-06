# STATICS-VDP07.01.02

Automatic Grading: Yes
Keywords: 3D, Cartesian, Direction, Dot product
Last Edit: Oct 30, 2020 11:22 AM
Last Edited By: Nicholas Betancourt
Learning Outcome: Calculate the angle between two 2D Cartesian vectors using the dot product
Module: Module 1: Identify and solve statics problems for particles (P)
Needs Calculator: Yes
On Mobius: Yes
Origin/Author: Caelia
Question Format: Numerical fill in the blank
Question Type: A
Randomizable Parameters: Yes
Sean Reviewed: Yes
Shaobo Reviewed: No
Status: Approved
Sub-Outcome: 1. The given vectors are in the same quadrant
Sub-Outcome Code: https://www.notion.so/STATICS-VDP07-01-16d78844520a445ca4b7fd3828e71971

# Question:

Consider the following two-dimensional vectors represented in Cartesian form: 

$$\overrightarrow{A}=[A]\hat{i}+[B]\hat{j}$$

$$\overrightarrow{B}=[C]\hat{i}+[D]\hat{j}$$

Calculate the **angle** between these two vectors using the formula for the dot product.

### Variable Parameters

$[A]:$ Range (-1, -10), 0 decimal places

$[B]:$ Range (1, 10), 0 decimal places

$[C]:$ Range (-1, -10), 0 decimal places

$[D]:$ Range (1, 10), 0 decimal places

# Answer:

$$\overrightarrow{A}\cdot\overrightarrow{B}=[A][C]+[B][D]$$

$$|\overrightarrow{A}|=\sqrt{[A]^2+[B]^2}; \qquad|\overrightarrow{B}|=\sqrt{[C]^2+[D]^2}$$

$$\theta=\arccos\left(\frac{\overrightarrow{A}\cdot\overrightarrow{B}}{|\overrightarrow{A}||\overrightarrow{B}|}\right)=\arccos\left(\frac{[A][C]+[B][D]}{(\sqrt{[A]^2+[B]^2})(\sqrt{[C]^2+[D]^2})}\right)$$

# Feedback:

To find the angle between two Cartesian vectors using the dot product formula, you must first rearrange it to solve for $\theta$. The original formula:

$$\overrightarrow{A}\cdot\overrightarrow{B}=|\overrightarrow{A}||\overrightarrow{B}|\cos\theta$$

Becomes:

$$\theta=\arccos\left(\frac{\overrightarrow{A}\cdot\overrightarrow{B}}{|\overrightarrow{A}||\overrightarrow{B}|}\right)$$

You must first calculate the dot product $\overrightarrow{A}\cdot\overrightarrow{B}$ by multiplying components and summing the products:

$$\overrightarrow{A}\cdot\overrightarrow{B}=A_xB_x+A_yB_y$$

Then the magnitude of each vector can be found by adding the squares of each component and taking the square root:

$$|\overrightarrow{A}|=\sqrt{A_x^2+A_y^2};\qquad|\overrightarrow{B}|=\sqrt{B_x^2+B_y^2}$$

Now the values calculated for the dot product and the magnitudes can be substituted into our equation for $\theta$, where we then take the **inverse cosine** of the result (denoted by $\arccos$ or $\cos^{-1}$):

$$\theta=\arccos\left(\frac{\overrightarrow{A}\cdot\overrightarrow{B}}{|\overrightarrow{A}||\overrightarrow{B}|}\right)$$