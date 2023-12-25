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

#Program to mark the maximum of marks using the list method sort
#Developed by: P PARTHIBAN
#RegisterNumber: 23007965

def max_marks(marks):
    
    marks.sort()
    return marks[-1]



```

ii)	# To find the maximum marks using the list method max().
```Python
 
#Program to find the maximum marks using the list method max().
#Developed by: P PARTHIBAN
#RegisterNumber: 23007965

def max_marks(marks):
    return max(marks)

```

iii) # To find the maximum marks without using builtin functions.
```Python

#Program to the maximum marks without using builtin functions.
#Developed by: P PARTHIBAN
#RegisterNumber: 23007965

def max_marks(list1):
    max=list1[0]
    for i in list1:
       if i>max:
           max=i
    return max


```
## Sample Input and Output
![Screenshot 2023-12-25 220023](https://github.com/23007965/FindMaximum/assets/138971238/2fb32390-cc40-4656-b920-ff709cedf08d)

![Screenshot 2023-12-25 220106](https://github.com/23007965/FindMaximum/assets/138971238/09747ed4-14e7-4fa5-93a4-da4302e68197)

![Screenshot 2023-12-25 220132](https://github.com/23007965/FindMaximum/assets/138971238/f45df43a-7740-415d-9e46-3860ee3d149a)

## Output:
![Screenshot 2023-12-25 220057](https://github.com/23007965/FindMaximum/assets/138971238/90e519ad-1126-4250-808d-ad124e8e71e2)

![Screenshot 2023-12-25 220057](https://github.com/23007965/FindMaximum/assets/138971238/c752e6be-01f9-4738-81bc-5fc2f129831f)

![Screenshot 2023-12-25 220146](https://github.com/23007965/FindMaximum/assets/138971238/7cc160cf-be0b-413c-8881-05178343c63d)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
