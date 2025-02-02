# Basic-Information-of-chip-design-lecture-3
Lecture 3:- Chip Design for High School
Recall:-
1.	 Ohm’s law  ( V = I * R )
2.	 Battery should never be connected without a load else high current due to short will    damage the battery.
3.	 Addition of voltages.
•	How to find net voltage.

![Screenshot 2025-02-02 112229](https://github.com/user-attachments/assets/05fc315b-17d5-478e-9f28-abdb5bcae338)

•	Under what condition the load will tun on
![image](https://github.com/user-attachments/assets/92b159b5-cf43-4b5a-a40c-f5d86852ce0d)

Fundamentals of logical design:-
The term “logical” means decision making.
Let’s take an example of playing games.

![image](https://github.com/user-attachments/assets/e125b1b2-e28b-4f39-9700-d6918c71b803)

Binary logic is utilized in computers because the answer is always either yes or no; there is no maybe. This makes it clear and understandable. This makes it ideal for creating modules with decision-making capabilities, which is the first step toward automation.

Introduction to Boolean arithmetic:
The Boolean arithmetic only use 0s and 1s to represent number. In Boolean arithmetic the digits are weighted according to their power of the base.

For example, let’s take 25 
5*100 = 5*1 = 5
2*101 = 2*10 =20

Boolean Algebra:
This is a truths table of “OR” Operation. It is used to representation of all possibilities inputs combinations which are evaluated and output is obtained.

![image](https://github.com/user-attachments/assets/d6916793-71b3-4d34-a1cf-894fbf964f8f)

Z = X + Y this the symbol for “OR” Operator.


This the truth table for “AND” Operator.

![image](https://github.com/user-attachments/assets/01048ef8-d8a5-4651-aea9-075ed474c339)

 Z = X AND Y this is the symbol for “AND” Operation.


This is the truth table for “NOT” Operation.  

![image](https://github.com/user-attachments/assets/96bb60ce-856e-4936-961f-5d1ed225d1bf)

We have also learned few important Boolean Relationships.

![image](https://github.com/user-attachments/assets/6ab76171-b4ad-4417-8289-8dd182670125)

Introduction to Redundancy theorem:

The Redundancy Theorem is a concept in Boolean algebra that helps simplify logic expressions by eliminating redundant terms.

2 Boolean operations are said to be equal if they give the same output for the applied  inputs if 2 output columns the truth table match, then these 2 Boolean operations are equal.

![image](https://github.com/user-attachments/assets/c36274cf-40dc-4300-9916-fdf34b60054e)

Introduction of De-Morgans Theorem:

![image](https://github.com/user-attachments/assets/058b4b6b-b9dd-40cc-b216-a7dbec1264f8)

![image](https://github.com/user-attachments/assets/cabd4ea1-84a2-43c9-8466-939af987a567)

These two are examples of De – Morgans theorem. So, we conclude that De – Morgans theorem turns “OR” and “AND” operation into “NOT” Operation. 

(X OR Y) = inverted to form = NOR 
(X AND Y) = inverted to form = NAND

NAND gates, you can construct the equivalent of any other logic gate, similar to how you can with NOR gates. This is why both NAND and NOR gates are considered universal gates in chip designing.

Example is here:

![image](https://github.com/user-attachments/assets/d29a8126-2fb0-45fe-8f40-cb961c8c4f9a)
