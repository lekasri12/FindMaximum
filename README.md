# EXP-06-Find the maximum of a list of numbers
## Date:
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
DEVELOPED BY: G LEKA SRI
REGISTER NO:212223100025
def max_marks(array):
    array.sort()
    return array[-1]

```

ii)	# To find the maximum marks using the list method max().
```Python
DEVELOPED BY: G LEKA SRI
REGISTER NO:212223100025
def max_marks(array):
    return max(array)

```

iii) # To find the maximum marks without using builtin functions.
```Python
DEVELOPED BY: G LEKA SRI
REGISTER NO:212223100025
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1


```



## Output:
![Screenshot 2024-10-16 152336](https://github.com/user-attachments/assets/edc9e347-40bf-4a1f-9548-5b8dbbd87048)
![Screenshot 2024-10-16 152448](https://github.com/user-attachments/assets/011ed87e-81e3-4ce0-9f2e-874ad0e3e780)
![Screenshot 2024-10-16 152640](https://github.com/user-attachments/assets/6e1dafb3-af06-4f71-8355-de7bb2ba6aa0)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
