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
Developed by: HariPrasath S
RegisterNumber: 212222240034
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: HariPrasath S
RegisterNumber: 212222240034
'''
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: HariPrasath S
RegisterNumber: 212222240034
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```

## Output:
[i]-To find the maximum of marks using the list method sort.
![3 1](https://github.com/hariprasath5106/FindMaximum/assets/111515488/080d7585-50b7-435d-9247-b221b9b33df2)


[ii]- To find the maximum marks using the list method max().
![3 2](https://github.com/hariprasath5106/FindMaximum/assets/111515488/7039ca76-6fa1-4cb0-a4f9-dff1a20f0b19)


[iii]-To find the maximum marks without using builtin functions.
![3 3](https://github.com/hariprasath5106/FindMaximum/assets/111515488/16140132-ffc9-455d-9a9c-547a2df161f3)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
