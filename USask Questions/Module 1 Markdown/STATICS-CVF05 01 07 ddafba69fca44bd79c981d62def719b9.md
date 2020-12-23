# STATICS-CVF05.01.07

Automatic Grading: Yes
Keywords: 3D, Cartesian, Direction
Last Edit: Oct 30, 2020 11:22 AM
Last Edited By: Nicholas Betancourt
Learning Outcome: Determine the coordinate direction angles alpha, beta, and gamma of a 3D vector, given its Cartesian components
Module: Module 1: Identify and solve statics problems for particles (P)
Needs Calculator: Yes
On Mobius: Yes
Origin/Author: Caelia
Question Format: Numerical fill in the blank
Question Type: A
Randomizable Parameters: Yes
Sean Reviewed: Yes
Shaobo Reviewed: No
Sig Fig: 3 sig figs
Status: Approved
Sub-Outcome: 1. The Cartesian components of the vector are all positive
Sub-Outcome Code: https://www.notion.so/STATICS-CVF05-01-eda8129b4dc04065a1293acff312fbb1

# Question:

Consider the following three-dimensional vector represented in Cartesian form: 

$$\overrightarrow{v}=\left([A]\hat{i}+[B]\hat{j}+[C]\hat{k}\right) \mathrm{N}$$

Find the three coordinate direction angles that characterize the direction of the vector: $\alpha$, $\beta$, and $\gamma$.

### Variable Parameters

$[A]:$ Range (1, 10), 0 decimal places

$[B]:$ Range (-1, -10), 0 decimal places

$[C]:$ Range (1, 10), 0 decimal places

# Answer:

$$\alpha=\arccos\left(\frac{[A]}{|\overrightarrow{v}|}\right)$$

$$\beta=\arccos\left(\frac{[B]}{|\overrightarrow{v}|}\right)$$

$$\gamma=\arccos\left(\frac{[C]}{|\overrightarrow{v}|}\right)$$

# Feedback:

To find each coordinate direction angle of the three-dimensional vector $\overrightarrow{v}$, you will first need to find the magnitude, $|\overrightarrow{v}|$. This can be calculated by squaring each of the scalar Cartesian components, adding them together, and finding the square root of the sum. 

Once you have the magnitude, you can find each angle by taking the **inverse cosine** (written as $\cos^{-1}$ or $\arccos$) of the ratio of the corresponding component and the magnitude of the vector. 

$$\alpha=\arccos\left(\frac{v_x}{|\overrightarrow{v}|}\right)$$

$$\beta=\arccos\left(\frac{v_y}{|\overrightarrow{v}|}\right)$$

$$\gamma=\arccos\left(\frac{v_z}{|\overrightarrow{v}|}\right)$$