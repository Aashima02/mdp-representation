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
* {0} Moving Up
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
        0 : [(0.34, 0, 0.0, False)],
        1 : [(0.88, 1, 0.0, False)],
        2 : [(0.76, 2, 0.0, False)],
        3 : [(0.12, 0, 0.0, False)]
    },

    1 : {
        0 : [(0.34, 1, 0.0, False)],
        1 : [(0.27, 1, 0.0, False)],
        2 : [(0.96, 3, 0.0, False)],
        3 : [(0.45, 0, 0.0, False)]
    },

    2 : {
        0 : [(0.12, 0, 0.0, False)],
        1 : [(0.98, 3, 0.0, False)],
        2 : [(0.23, 2, 0.0, False)],
        3 : [(0.12, 2, 0.0, False)]
    },

    3 : {
        0 : [(0.36, 1, 0.0, False)],
        1 : [(0.10, 3, 0.0, False)],
        2 : [(0.97, 4, 0.0, False)],
        3 : [(0.36, 2, 0.0, False)]
    },

    4 : {
        0 : [(0.67, 3, 0.0, False)],
        1 : [(0.87, 5, 0.0, False)],
        2 : [(0.99, 6, 0.0, False)],
        3 : [(0.11, 4, 0.0, False)]
    },

    5 : {
        0 : [(0.23, 5, 0.0, False)],
        1 : [(0.11, 5, 0.0, False)],
        2 : [(0.99, 7, 1.0, True)],
        3 : [(0.63, 4, 0.0, False)]
    },

    6 : {
        0 : [(0.77, 4, 0.0, False)],
        1 : [(0.99, 7, 1.0, True)],
        2 : [(0.34, 6, 0.0, False)],
        3 : [(0.11, 6, 0.0, False)]
    },

    7 : {
        0 : [(0.81, 7, 1.0, True)],
        1 : [(0.45, 7, 1.0, True)],
        2 : [(0.77, 7, 1.0, True)],
        3 : [(0.32, 7, 1.0, True)]
    }
}
```

## OUTPUT:
![image](https://github.com/Aashima02/mdp-representation/assets/93427086/48964b76-62a2-439c-a926-4c4f023322e0)




## RESULT:
Thus a real world problem is represented as Markov Decision Problem in the following ways successfully:

1. Text Representation
2. Graphical Representation
3. Python Representation

