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
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by:A.Sesank 
RegisterNumber: 23009543
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by:A.Sesank 
RegisterNumber:23009543 
'''
def max_marks(marks):
    # write your code here
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by:A.Sesank
RegisterNumber: 23009543
'''
def max_marks(list1):
    # write your code here
    max=list1[0]
    for i in list1:
        if i > max:
            max = i
    return max        


```
## Sample Input and Output
![image](https://github.com/ALLAMSESANK/FindMaximum/assets/147120920/02272dd1-df06-4488-94d9-68fcc80f4221)


## Output:
![image](https://github.com/ALLAMSESANK/FindMaximum/assets/147120920/387c4797-ad1d-4b19-9873-fca57ab5d250)
![image](https://github.com/ALLAMSESANK/FindMaximum/assets/147120920/5c2c3d7d-fe84-41d2-8bd9-e6f10ae9b961)
![image](https://github.com/ALLAMSESANK/FindMaximum/assets/147120920/b7eff5dc-c735-4629-a59c-dad3ef0c22bc)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
