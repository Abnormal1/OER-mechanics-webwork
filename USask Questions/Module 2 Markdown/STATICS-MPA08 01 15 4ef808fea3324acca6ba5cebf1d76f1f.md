# STATICS-MPA08.01.15

Automatic Grading: Yes
Keywords: 3D, cross product, moment
Last Edit: Oct 30, 2020 11:22 AM
Last Edited By: Nicholas Betancourt
Learning Outcome: Calculate the vector moment of a force about a point in 3D, given a Cartesian force vector and a Cartesian position vector (text and diagram)
Margin of Error: 0
Module: Module 2: Identify and solve introductory level rigid body statics problems
Needs Calculator: No
On Mobius: Yes
Origin/Author: Zoe
Question Format: Numerical fill in the blank
Question Type: A
Randomizable Parameters: No
Sean Reviewed: Yes
Shaobo Reviewed: No
Sig Fig: Exact
Status: Approved
Sub-Outcome: 1. all 8 octants
Sub-Outcome Code: https://www.notion.so/STATICS-MPA08-01-52fdd412aa704056b70ae01ab06250b1
Topic/ Unit: 2. Calculate the moment of a force about a point or an axis in 2D and 3D using vector and scalar formulations (MPA)

# Question:

Given $\overrightarrow{F}_{AC}=(-150\hat{i}-100\hat{j}-300\hat{k})~\text{lb}$, and $\overrightarrow{r}_{EA}=(0\hat{i}+0\hat{j}+30\hat{k})~\text{ft}$, determine the moment produced by the force $\overrightarrow{F}_{AC}$ about **point E**. Express the result as a Cartesian vector.

Enter your answer:     $($___$\hat{i}~~-$___$~\hat{j}~~+~$___$\hat{k})$  $\text{lb}\cdot\text{ft}$

![STATICS-MPA08%2001%2015%204ef808fea3324acca6ba5cebf1d76f1f/Untitled.png](STATICS-MPA08%2001%2015%204ef808fea3324acca6ba5cebf1d76f1f/Untitled.png)

# Answer:

$3000,4500,0$

# Feedback：

The moment of a force $\overrightarrow{F}$ about point O can be expressed using the vector cross product, namely,

$$\overrightarrow{M_O}=\overrightarrow{r}\times\overrightarrow{F}=\begin{vmatrix}\hat{i}&\hat{j}&\hat{k}\\r_x&r_y&r_z\\F_x&F_y&F_z\\\end{vmatrix}$$

$$=(r_yF_z-r_zF_y)\hat{i}-(r_xF_z-r_zF_x)\hat{j}+(r_xF_y-r_yF_x)\hat{k}$$

Thus, for this question:

$$\overrightarrow{M_{E}}=\overrightarrow{r}_{EA}\times\overrightarrow{F}_{AC}=\begin{vmatrix}\hat{i}&\hat{j}&\hat{k}\\ 0&0&30\\ -150&-100&-300\\\end{vmatrix}$$

$$=\{0(-300)-30(-100)\}\hat{i}-\{0(-300)-30(-150)\}\hat{j}+\{0(-100)-0(-150)\}\hat{k}$$

$$=\{3000\hat{i}-4500\hat{j}+0\hat{k}\}~\text{lb}\cdot\text{ft}$$