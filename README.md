# MDP REPRESENTATION

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.

Text representation,

Graphical representation,

Python - Dictonary representation.

## PROBLEM STATEMENT:

### Problem Description
To conplete the school admisssion process , the role of the agent is to promote if the student is eligible , if not eligible , no admisssion.
### State Space
{A1,A2,A3}->{0,1,2}
- A1-> Admission Process 1
- A2-> Admission Process 2
- A3-> Final Process of Admission

### Sample State
A1 -> Admission Process 1

### Action Space
{E,NE} -> {0,1}
E  -> Eligible
NE -> Not Eligible

### Sample Action
E-> Eligible

### Reward Function
```
R= {
    +1, if eligible
    +0, otherwise

```
### Graphical Representation

![RL_1](https://github.com/user-attachments/assets/7c52561d-a6ec-42a4-bd41-452cc404ec47)


## PYTHON REPRESENTATION:
```py

T = {
    0: {
        0: [(0.8, 1, 1.0, False), (0.2, 0, 0.0, False)],
        1: [(0.9, 0, 0.0, False), (0.1, 1, 0.5, False)]
    },
    1: {
        0: [(0.7, 2, 1.0, False), (0.3, 0, 0.0, False)],
        1: [(0.85, 0, 0.0, False), (0.15, 2, 0.5, False)]
    },
    2: {
        0: [(0.9, 2, 1.0, True), (0.1, 1, 0.0, False)],
        1: [(0.6, 1, 0.0, False), (0.4, 0, 0.0, False)]
    }
}
T

```

## OUTPUT:

![123](https://github.com/user-attachments/assets/039f4c28-dfee-4f1b-838a-e7beb9c471f3)



## RESULT:
Thus the given Markov Decision Process(MDP) problem is represented in the following ways.

Text representation,
Graphical representation,
Python - Dictonary representation.

