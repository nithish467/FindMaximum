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

![image](https://github.com/nithish467/FindMaximum/assets/150232274/49553336-2740-4f23-8e8f-ad91771d46c3)


![Screenshot 2023-12-28 093811](https://github.com/nithish467/FindMaximum/assets/150232274/7956e4a1-3069-416c-992e-e01fcafb487a)


![Screenshot 2023-12-28 093732](https://github.com/nithish467/FindMaximum/assets/150232274/792ff3ac-8f31-46aa-a4f2-6d67a1d4d754)



## Output:

![Screenshot 2023-12-28 122259](https://github.com/nithish467/FindMaximum/assets/150232274/6ddcda17-def7-47df-892b-ee9d95f3a0d9


![image](https://github.com/nithish467/FindMaximum/assets/150232274/4d3171e1-2792-4d46-a76c-794592fa6ddf)


![image](https://github.com/nithish467/FindMaximum/assets/150232274/c66c6be6-dc39-4269-8793-4dab678fcc1a)






## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
