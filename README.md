# Linear Search and Binary search
## Aim:
To write a program to perform linear search and binary search using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Get the list of marks as input
Use the sort()function or max()function or use the for loop to find the maximum mark
Return the maximum value
## Linear Search:
1.	Start from the leftmost element of array[] and compare k with each element of array[] one by one.
2.	If k matches with an element in array[] , return the index.
3.	If k doesn’t match with any of elements in array[], return -1 or element not found.
## Binary Search:
1.	Set two pointers low and high at the lowest and the highest positions respectively.
2.	Find the middle element mid of the array ie. arr[(low + high)/2]
3.	If x == mid, then return mid.Else, compare the element to be searched with m.
4.	If x > mid, compare x with the middle element of the elements on the right side of mid. This is done by setting low to low = mid + 1.
5.	Else, compare x with the middle element of the elements on the left side of mid. This is done by setting high to high = mid - 1.
6.	Repeat steps 2 to 5 until low meets high
## Program:
i)	#Use a linear search method to match the item in a list.
```python
Program to mark the maximum of marks using the list method sort
Developed by:S.Suriya prakash 
RegisterNumber:23013599 
def max_marks(marks):
    large=max(marks)
    return large
```
ii)	# Find the element in a list using Binary Search(Iterative Method).
```python
Program to find the maximum marks using the list method max().
Developed by: S.Suriya prakash
RegisterNumber: 23013599
def max_marks(marks):
    large=max(marks)
    return large
```
iii)	# Find the element in a list using Binary Search (recursive Method).
```python
Program to the maximum marks without using builtin functions.
Developed by: Suriya prakash
RegisterNumber:23013599 
def max_marks(marks):
    large=max(marks)
    return large
```
## Sample Input and Output
i)	#Use a linear search method to match the item in a list.
![image](https://github.com/arulsuriyalokeshy/Search-Algorithm/assets/149130151/0702d380-e184-4a0e-8666-3ebf84c61f66)

ii)	# Find the element in a list using Binary Search(Iterative Method).
![image](https://github.com/arulsuriyalokeshy/Search-Algorithm/assets/149130151/6abee2ea-2267-46e2-b73c-e1c66954ae8a)

iii)	# Find the element in a list using Binary Search (recursive Method).
![image](https://github.com/arulsuriyalokeshy/Search-Algorithm/assets/149130151/77223a19-59c6-4918-9b8c-1a6391e23eb9)

## Result
Thus the linear search and binary search algorithm is implemented using python programming.
