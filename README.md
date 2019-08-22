# BCSC0002 - Object-Oriented Programming

## Assignment 1

### Date: 12 August 2019.
### Deadline: 24 August 2019 till midnight.

#### Instructions
1. You are to clone this repository and use this as the template code for your solution.
2. Please do not host code that you did not write. Doing so will be an act of misconduct.
3. You are free to ask for help from me by creating an issue [here](https://github.com/dbc2201/GLAU_BCSC0002/issues/new?assignees=&labels=DOUBT&template=doubt.md&title=DOUBT)
---

#### Problem Statement

Recall, that if an object is released so that it falls,
the speed of the object at time `t` seconds after its release
is calculated to be `gt` and the distance the object has travelled
in those `t` seconds after its release is 
![](https://latex.codecogs.com/gif.latex?$$\frac{1}{2}g{t^2}$$).
Here, `g` is the gravity constant. Its value is approximately `9.8`.  

Write a program in which, the method main performs the following actions:  
1. The program declares the variables `time` for time, `speed` for the speed, and `distance` for the distance travelled.
2. The program assigns value to `time`.
3. The program calculates the speed and the distance.
4. The program prints the calculated values. 

---

#### Input Format
The program will input a single value `t` for the time after its release.

#### Output Format
The program will output the calculated values in the following format:
```
The speed of the object at <t> seconds after its release is <speed> and the distance the object has travelled in the <t> seconds after the relase is <distance>
```
---

#### Sample Input
```
6.0
```

#### Sample Output 
```
The speed of the object at 6.0 seconds after its release is 58.800000000000004 and the distance the object has travelled in the 6.0 seconds after the relase is 176.4
```