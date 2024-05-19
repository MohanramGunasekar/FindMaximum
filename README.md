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
def max_marks(lst):
    lst.sort()
    MAX=lst[-1]
    return MAX


```

ii)	# To find the maximum marks using the list method max().
```Python

def max_marks(marks):
    large=max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(lst):
    lst.sort()
    MAX=lst[-1]
    return MAX


```



## Output:
![Screenshot 2024-05-19 140303](https://github.com/MohanramGunasekar/FindMaximum/assets/139841812/559c3081-a6b1-4f86-8f2b-898734825514)
![Screenshot 2024-05-19 140310](https://github.com/MohanramGunasekar/FindMaximum/assets/139841812/6eb0e775-f41f-4011-bc0a-ce75dc766897)
![Screenshot 2024-05-19 142548](https://github.com/MohanramGunasekar/FindMaximum/assets/139841812/144ee1bd-0c60-4616-859c-388767eca5fe)
![Screenshot 2024-05-19 142554](https://github.com/MohanramGunasekar/FindMaximum/assets/139841812/be074644-738c-4772-acf4-593ea0fb13a2)
![Screenshot 2024-05-19 142736](https://github.com/MohanramGunasekar/FindMaximum/assets/139841812/06790b52-2efc-4dae-a22b-61306c24d37b)
![Screenshot 2024-05-19 142744](https://github.com/MohanramGunasekar/FindMaximum/assets/139841812/0f6e7ae6-5c36-4652-bf60-393a11adb96e)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
