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
def max_marks(array):
    array.sort()
    return array[-1]



```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(array):
    return max(array)



```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1



```



## Output:
![py3](https://github.com/DariusRijin07/FindMaximum/assets/138849120/0c54bb44-c235-4902-b9ef-1324018efb5a)
![py 1](https://github.com/DariusRijin07/FindMaximum/assets/138849120/8b7ad058-218b-46a9-a387-f7c831b2c66c)
![py2](https://github.com/DariusRijin07/FindMaximum/assets/138849120/24357f67-bc14-4211-b74c-e81bfa0d838f)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
