# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Chandrasekar S
RegisterNumber: 212222230025
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large





```

ii)	# To find the maximum marks using the list method max().
```''' 
Program to find the maximum marks using the list method max().
Developed by: Chandrasekar S
RegisterNumber: 212222230025
'''
def max_marks(marks):
    large = max(marks)
    return large






```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: Chandrasekar S
RegisterNumber: 212222230025
'''
def max_marks(list1):
    max= list1[0]
    for i in list1:
        if i > max:
            max = i
    return max        




```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
## find the maximum of marks using the list method sort:
![image](https://github.com/ChandrasekarS22008273/FindMaximum/assets/119643845/d372fd17-a79e-40e4-878b-f1be6e766bf5)

## find the maximum marks using the list method max():
![image](https://github.com/ChandrasekarS22008273/FindMaximum/assets/119643845/48e267bf-d7d7-4f23-a86b-a5b967d15fa1)


## find the maximum marks without using builtin functions:
![image](https://github.com/ChandrasekarS22008273/FindMaximum/assets/119643845/2b4ff2c3-e49f-4770-822e-f72028d1d0e5)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
