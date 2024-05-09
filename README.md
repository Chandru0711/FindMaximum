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
#Program Developed by: CHANDRU SM
#Register No:212223230034

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
#Program developed by: CHANDRU SM
#Register No: 212223230034

def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
#Program developed by: CHANDRU SM
#Register No: 212223230034

def max_marks(marks):
    max_mark=0
    for i in marks:
        if i>max_mark:
            max_mark=i
    return max_mark


```



## Output:
![Screenshot 2024-05-09 150738](https://github.com/Chandru0711/FindMaximum/assets/144979368/493ffaed-bf11-4e2b-a4a9-d4d3c8e241a7)

![Screenshot 2024-05-09 150757](https://github.com/Chandru0711/FindMaximum/assets/144979368/ef8c2e78-6232-4701-8398-5c8a50215086)

![Screenshot 2024-05-09 150812](https://github.com/Chandru0711/FindMaximum/assets/144979368/52255fbc-3adc-47bc-bdfc-bf5827ce2296)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
