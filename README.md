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
```
Developed by: MANOKARTHICK S
Register number:212222230077
```

i)	# To find the maximum of marks using the list method sort.
```Python
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large




```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large = max(marks)
    return large




```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max




```



## Output:
![image](https://github.com/MANOKARTHICK09/FindMaximum/assets/121785458/f3ba91a9-cf72-48fd-9580-b324c6b2a1d9)
![image](https://github.com/MANOKARTHICK09/FindMaximum/assets/121785458/066602ee-8f78-4e94-b100-dafbb40af03c)
![image](https://github.com/MANOKARTHICK09/FindMaximum/assets/121785458/10add0fb-7f2f-4f0f-b9c2-999919e1d780)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
