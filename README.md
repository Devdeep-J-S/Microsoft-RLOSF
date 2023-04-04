Name : Devdeep Shetranjiwala <br>
Email ID : devdeep0702@gmail.com 

****

# Microsoft Reinforcement Learning Open-Source Fest - 2023
# Testing infrastructure for VowpalWabbit - Screening exercise

---

## Screening exercise
> Let’s say we have just implemented a new training algorithm for regression with the following interface:

class NewTrainer: <br>
    ... <br>
    def train(self, x: List[List[float]], y: List[float]): <br>
        ... <br>

    def predict(self, x: List[float]) -> float: <br>
        ... <br>
        return 0 <br>
> Design and write test suite for it in Python using unittest or pytest frameworks.

## Explanation

Declaring model in training and using it in pytest_file.py to perform simple testing of code.

Tool of my choice : 
```
Pytest
``` 
