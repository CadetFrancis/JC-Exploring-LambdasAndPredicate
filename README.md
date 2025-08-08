# Name: Francis Aldrin Belmes
# Lab: Introduction to Java Lambdas and Predicates
# Objective:
To understand the purpose of lambda expressions and learn how to write and use simple Predicates to test data.
***
## Exercise 1: The "New Way" - A Simple Lambda Expression
### Prediction:
Output would be:<br>
"Is 'short' long? false"<br>
"Is 'This is a very long string' long? true"<br>
### Observation:
Output is actually:<br>
"Is 'short' long? false"<br>
"Is 'This is a very long string' long? true"<br>
![image_info](./media/ex1.png)

## Exercise 2: Using Predicates to Filter a List
### Prediction:
Output would be:<br>
"--- Call signs starting with 'A' ---"<br>
"Alpha"<br>
"Archangel"<br>
"Avenger"<br>
### Observation:
Output is actually:<br>
"--- Call signs starting with 'A' ---"<br>
"Alpha"<br>
"Archangel"<br>
"Avenger"<br>
![image_info](./media/ex2.png)


## Exercise 3: Chaining Predicates (and, negate)
### Prediction:
Output would be:<br>
"--- Starts with 'A' AND length > 5 ---"<br>
"Archangel"<br>
"Avenger"<br>
<br>
"--- Does NOT start with 'A' ---"<br>
"Bravo"<br>
"Echo"<br>
### Observation:
Output is actually:<br>
"--- Starts with 'A' AND length > 5 ---"<br>
"Archangel"<br>
"Avenger"<br>
<br>
"--- Does NOT start with 'A' ---"<br>
"Bravo"<br>
"Echo"<br>
![image_info](./media/ex3.png)