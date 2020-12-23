# STATICS-CMC07.02.01

Automatic Grading: Yes
Keywords: couple, free vector, moment
Last Edit: Oct 30, 2020 11:22 AM
Last Edited By: Nicholas Betancourt
Learning Outcome: Define the concept of a free vector
Module: Module 2: Identify and solve introductory level rigid body statics problems
Needs Calculator: No
On Mobius: Yes
Origin/Author: Caelia
Question Format: Multiple choice
Question Type: A
Randomizable Parameters: No
Sean Reviewed: Yes
Shaobo Reviewed: No
Status: Approved
Sub-Outcome: 2. what is a good definition of a free vector
Sub-Outcome Code: https://www.notion.so/STATICS-CMC07-02-6d58ff914fef41ec82ca5e579b732c8e
Topic/ Unit: 3. Incorporate couples in moment calculations (CMC)

# Question:

From the options below, select the **best definition** for a free vector.

a) A vector that can be applied at any point on a body

b) A vector that has a magnitude of 1

c) A vector whose direction can be reversed without consequence

d) A vector created by a pair of forces of equal magnitude

# Answer:

a) A vector that can be applied at any point on a body

# Feedback:

a) Correct! A **free vector** can act any *any point* on a body. We can demonstrate this using the diagram below:

![STATICS-CMC07%2002%2003%20d3f8626137fa459da79ddd541076ac93/Untitled.png](STATICS-CMC07%2002%2003%20d3f8626137fa459da79ddd541076ac93/Untitled.png)

Assuming that point $B$ is located halfway between points $A$ and $C$, and that point $D$ is a perpendicular distance $d/2$ away from $\overrightarrow{F}$, we can use this diagram to demonstrate that the resultant moment from both forces around each point is the **same**, and therefore that a couple moment vector can be applied anywhere on a body to yield the same moment. 

### **Resultant Moment at Point A:**

Point $A$ lies on one of the force vectors, and therefore has a zero moment arm for one, with a moment arm of $d$ for the other. If $M_1$ is the moment around point $A$ due to the $-\overrightarrow{F}$ vector, and $M_2$ is the moment around point $A$ due to the $\overrightarrow{F}$, then we can calculate them as:

$$M_1=F(0)=0\\
M_2=Fd$$

The resultant moment about point $A$ is the sum of the two moments due to each force vector:

$$\sum M_A=M_1+M_2=Fd$$

### **Resultant Moment at Point B:**

Point $B$ is halfway between points $A$ and $C$, giving it a moment arm of $d/2$ to each force vector. If $M_1$ is the moment around point $B$ due to the $-\overrightarrow{F}$ vector, and $M_2$ is the moment around point $B$ due to the $\overrightarrow{F}$, then we can calculate them as:

$$M_1=F(d/2)\\
M_2=F(d/2)$$

The resultant moment about point $B$ is the sum of the two moments due to each force vector:

$$\sum M_B=M_1+M_2=F(d/2+d/2)=Fd$$

### **Resultant Moment at Point C:**

Point $C$ lies on one of the force vectors, and therefore has a zero moment arm for one, with a moment arm of $d$ for the other. If $M_1$ is the moment around point $C$ due to the $-\overrightarrow{F}$ vector, and $M_2$ is the moment around point $C$ due to the $\overrightarrow{F}$, then we can calculate them as:

$$M_1=Fd\\
M_2=F(0)=0$$

The resultant moment about point $A$ is the sum of the two moments due to each force vector:

$$\sum M_C=M_1+M_2=Fd$$

### **Resultant Moment at Point D:**

Even though point $D$ lies outside the space between the two force vectors, we can still calculate the perpendicular distance to it from each force vector to find the moment arm lengths. If point $D$ is a perpendicular distance away from the $\overrightarrow{F}$ vector of $d/2$, then it is $d+d/2=3d/2$ away from the $-\overrightarrow{F}$ vector. If $M_1$ is the moment around point $D$ due to the $-\overrightarrow{F}$ vector, and $M_2$ is the moment around point $D$ due to the $\overrightarrow{F}$, then we can calculate them as:

$$M_1=F(3d/2)\\
M_2=-F(d/2)$$

Notice the change in sign for $M_2$ since the moment about point $D$ due to $\overrightarrow{F}$ will be clockwise and therefore negative. The resultant moment about point $D$ is the sum of the two moments due to each force vector:

$$\sum M_D=M_1+M_2=F(3d/2-d/2)=Fd$$

### Conclusion

At this point, it should be clear that no matter where the resultant moment is calculated on the body due to both force vectors, the moment vector remains the same. Because the two force vectors are the same magnitude, parallel, and in opposite directions, these two forces create a **couple moment**, which we've demonstrated is a **free vector**. That is, it can be applied anywhere on the body. 

---

b) You might be thinking of a **unit vector**. A free vector does not have to have a magnitude of one - try again!

c) This is not a property exhibited by a free vector. A free vector's direction does matter - try again!

d) While this requirement must be met to generate a couple moment vector, this is not the complete definition of a couple moment or of a free vector - try again!