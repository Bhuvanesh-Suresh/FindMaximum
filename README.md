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
#Program to mark the maximum of marks using the list method sort
#Developed by:Bhuvanesh.S.R
#RegisterNumber: 23013380
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
``` 
#Program to find the maximum marks using the list method max().
#Developed by: Bhuvanesh.S.R
#RegisterNumber: 23013380
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```
#Program to the maximum marks without using builtin functions.
#Developed by: Bhuvanesh.S.R
#RegisterNumber: 23013380
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```
## Output:
i)To find the maximum of marks using the list method sort.
![Maximmum of marks using list maths SS](https://github.com/Bhuvanesh-Suresh/FindMaximum/assets/145742661/92b94693-e586-452d-8a59-cadf8a4286df)

ii)To find the maximum marks using the list method max().
![find the maximum marks using the list method max()](https://github.com/Bhuvanesh-Suresh/FindMaximum/assets/145742661/3fa7dc6a-4add-4e1e-ad38-d3a2fc0307af)

iii)To find the maximum marks without using builtin functions.
![maximum marks without using builtin functions](https://github.com/Bhuvanesh-Suresh/FindMaximum/assets/145742661/d124bb59-ba86-409f-aa11-bc0b8e445743)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
