# MDP REPRESENTATION

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.

1. Text representation
2. Graphical representation
3. Python - Dictonary representation

## PROBLEM STATEMENT:

### Problem Description
To develop an environment consisting of a mobile tower as the start and the house as the goal. The aim is to make sure the network signals reaches the house.

### State Space
{0,1,2,3,4,5,6,7}

### Sample State
4

### Action Space
* {0) Moving Up
* {1} Moving Right
* {2} Moving Down
* {3} Moving Left

### Sample Action
{1} Moving Right

### Reward Function
* +1 - If the goal is reached
* 0 - Otherwise

## GRAPHICAL REPRESENTATION:
![WhatsApp Image 2023-09-03 at 19 53 05](https://github.com/Aashima02/mdp-representation/assets/93427086/f9975da2-4262-4564-a57e-0402007880f6)


## PYTHON REPRESENTATION:
```python
P = {
    0 : {
        0 : [(1.0, 0, 0.0, False)],
        1 : [(1.0, 1, 0.0, False)],
        2 : [(1.0, 2, 0.0, False)],
        3 : [(1.0, 0, 0.0, False)]
    },

    1 : {
        0 : [(1.0, 1, 0.0, False)],
        1 : [(1.0, 1, 0.0, False)],
        2 : [(1.0, 3, 0.0, False)],
        3 : [(1.0, 0, 0.0, False)]
    },

    2 : {
        0 : [(1.0, 0, 0.0, False)],
        1 : [(1.0, 3, 0.0, False)],
        2 : [(1.0, 2, 0.0, False)],
        3 : [(1.0, 2, 0.0, False)]
    },

    3 : {
        0 : [(1.0, 1, 0.0, False)],
        1 : [(1.0, 3, 0.0, False)],
        2 : [(1.0, 4, 0.0, False)],
        3 : [(1.0, 2, 0.0, False)]
    },

    4 : {
        0 : [(1.0, 3, 0.0, False)],
        1 : [(1.0, 5, 0.0, False)],
        2 : [(1.0, 6, 0.0, False)],
        3 : [(1.0, 4, 0.0, False)]
    },

    5 : {
        0 : [(1.0, 5, 0.0, False)],
        1 : [(1.0, 5, 0.0, False)],
        2 : [(1.0, 7, 1.0, True)],
        3 : [(1.0, 4, 0.0, False)]
    },

    6 : {
        0 : [(1.0, 4, 0.0, False)],
        1 : [(1.0, 7, 1.0, True)],
        2 : [(1.0, 6, 0.0, False)],
        3 : [(1.0, 6, 0.0, False)]
    },

    7 : {
        0 : [(1.0, 7, 1.0, True)],
        1 : [(1.0, 7, 1.0, True)],
        2 : [(1.0, 7, 1.0, True)],
        3 : [(1.0, 7, 1.0, True)]
    }
}
```

## OUTPUT:
![image](https://github.com/Aashima02/mdp-representation/assets/93427086/20ef6215-f394-4aa0-9c3a-ac15494e6d09)



## RESULT:
Thus a real world problem is represented as Markov Decision Problem in the following ways successfully:

1. Text Representation
2. Graphical Representation
3. Python Representation

