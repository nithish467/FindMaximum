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
## Developed by: NITHISH KUMAR S
## Register Number: 23013506

i)	# To find the maximum of marks using the list method sort.
```Python

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python

def max_marks(marks):
   large=max(marks)
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
## Sample Input and Output

1) ![image](https://github.com/nithish467/FindMaximum/assets/150232274/c3e5000c-9587-4853-835e-17f0d3842450)


2) ![image](https://github.com/nithish467/FindMaximum/assets/150232274/20bbeb91-8dd9-46fd-b82e-ef877984c380)


3) ![image](https://github.com/nithish467/FindMaximum/assets/150232274/2520fd14-d4a6-4f26-8ea1-84dd4e29b0a5)



## Output:

1) ![Screenshot 2023-12-28 122259](https://github.com/nithish467/FindMaximum/assets/150232274/6ddcda17-def7-47df-892b-ee9d95f3a0d9).


2) ![image](https://github.com/nithish467/FindMaximum/assets/150232274/4d3171e1-2792-4d46-a76c-794592fa6ddf)


3) ![image](https://github.com/nithish467/FindMaximum/assets/150232274/c66c6be6-dc39-4269-8793-4dab678fcc1a)






## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
