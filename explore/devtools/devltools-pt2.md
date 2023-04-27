### Question 1:
The bug was that the values inputed in the input fields needed to be casted to numbers. This is because the values are read as strings, and the **'calculateSum()'** function is expecting numbers. So when the values are added together, they are concatenated instead of added.
### Question 2:
Parase the values to numbers before adding them together.