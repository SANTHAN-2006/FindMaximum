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
## Programs:
```
# Program to mark the maximum of marks using the list method sort
# Developed by: Santhan Kumar
# RegisterNumber: 23004568

def max_marks(marks):
    marks.sort()
    maximum = marks[-1]
    return maximum


# Program to find the maximum marks using the list method max().
# Developed by: Santhan Kumar
# RegisterNumber: 23004568

def max_marks(marks):
    maximum = max(marks)
    return maximum


# Program to the maximum marks without using builtin functions.
# Developed by: Santhan Kumar
# RegisterNumber: 23004568

def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
![image](https://github.com/SANTHAN-2006/FindMaximum/assets/80164014/0842d37b-3b28-492b-bbed-d72646785833)


## Output:
![image](https://github.com/SANTHAN-2006/FindMaximum/assets/80164014/71efb848-fa07-41b1-96a4-8f850c07a853)

![image](https://github.com/SANTHAN-2006/FindMaximum/assets/80164014/7801c78a-90d4-4a58-82a1-c6b383403639)

![image](https://github.com/SANTHAN-2006/FindMaximum/assets/80164014/ab4c2a19-eac4-4732-9cda-5532bd47cbf8)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
