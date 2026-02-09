# Experiment-3
## Aim: Study of tuple in python

## Theory:
A tuple in Python is an ordered collection of elements enclosed in parentheses ().It can store different data types and allows duplicate values.
Tuples are immutable, so their elements cannot be changed once created.They hey support indexing, which allows access to individual elements using their position. 
They also support slicing, making it possible to extract a subset of elements from the sequence. In addition, they support iteration, enabling traversal through each element one by one using loops.
Because of immutability, tuples are faster and use less memory than lists. Tuples are mainly used to store **fixed or constant data** because they are **immutable**, meaning their elements cannot
be changed after creation. This makes tuples ideal for representing data that should remain the same throughout a program’s execution, such as coordinates, configuration values, or records that must 
not be modified accidentally. Since tuples do not allow operations like adding, removing, or updating elements, they provide data integrity and help prevent unintended changes. Additionally, tuples are 
more memory-efficient and slightly faster to access than lists, making them suitable for storing constant collections of values.The length of a tuple is determined using the len() function. It returns the total 
number of elements present in the tuple.Elements of a tuple can be accessed using slicing by specifying a range of indices. Slicing allows you to retrieve a portion of the tuple without modifying the original 
tuple. The syntax follows the format tuple[start : end], where the start index is inclusive and the end index is exclusive.

A list uses square brackets [] and is mutable.Lists allow insertion, deletion, and modification of elements.
Tuples can be used as dictionary keys, while lists cannot.


## Tuple Properties Program
1. Create a tuple with different values.
2. Find the length of the tuple.
3. Access elements using slicing.
4. Display the results.


 ## Algorithm:
 1: Create and Print a Tuple
Purpose: Store different data types in a tuple and display it.
Start
Create a tuple tpl with values (2, True, "maahi")
Print the tuple
Stop

 2: Access Tuple Elements Using Index
Purpose: Access elements from a tuple using positive and negative indexing.
Start
Create a tuple tpl2 with elements ("apple", "kiwi", "banana")
Access the element at index -2 and print it
Access the element at index 1 and print it
Stop

 3: Attempt to Modify a Tuple
Purpose: Show that tuples are immutable.
Start
Create a tuple tpl3 with elements ("apple", "banana", "Kiwi")
Try to change the element at index 1
Observe the TypeError because tuples do not allow item assignment
Stop

4: Tuple Repetition Using *

Purpose: Demonstrate tuple repetition and integer multiplication.
Start
Create a tuple tpl5 by repeating (10,) five times
Print tpl5
Multiply integer 10 by 5 and store in tpl6
Print tpl6
Stop

 5: List Repetition
Purpose: Repeat list elements using *.
Start
Create a list containing "symbiosis"
Repeat the list five times using *
Print the list
Stop

 6: Tuple Concatenation and Memory Address Change
Purpose: Show immutability of tuples using id().
Start
Create a tuple tpl7 with three elements
Print the memory address of tpl7
Create a tuple tpl8 with one element
Concatenate tpl8 to tpl7
Print the updated tuple
Print the new memory address
observe that the memory address changes
Stop

 7: List Concatenation and Memory Address
Purpose: Show mutability of lists.
start
Create a list tpl7
Print its memory address
Create another list tpl8
Add tpl8 to tpl7 using +=
Print the updated list
Print the memory address
Observe that the memory address remains the same
Stop

 8: Perform Operations on Tuple of Marks
Purpose: Find maximum, minimum, sum, average, and sorted values.
Start
Create a tuple marks with student scores
Find and print the maximum marks
Find and print the minimum marks
Find and print the total number of subjects
Calculate and print the sum of marks
Calculate and print the average marks
Sort and print the marks
Stop

9: Tuple Unpacking and Distinction Check
Purpose: Extract tuple values and check eligibility for distinction.
Start
Create a tuple result with subject, marks, and grade
Print each value using index
Unpack the tuple into variables
Print unpacked values
Check if marks are greater than or equal to 75
If yes, print "Distinction"
Stop

10: Attendance Analysis Using Tuple
Purpose: Count presence and absence.
Start
Create a tuple attendance with "P" and "A"
Count total present days using count("P")
Count total absent days using count("A")
Check if "A" exists in the tuple
If yes, print absentee message
Stop

## Conclusion:
Therefore we learnt the use of tuple in python as well as the difference between tuple and lists in python.
