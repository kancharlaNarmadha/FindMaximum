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

i)
# To find the maximum of marks using the list method sort.

Developed by: KANCHARLA NARMADHA

RegisterNumber: 212222110016
```
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
```

ii)	
# To find the maximum marks using the list method max().

Developed by: KANCHARLA NARMADHA

RegisterNumber: 212222110016
```
def max_marks(marks):
    large = max(marks)
    return large
```

iii)  
# To find the maximum marks without using builtin functions.

Developed by: KANCHARLA NARMADHA

RegisterNumber: 212222110016
```

def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max=i
    return max        


```
## Sample Input and Output

![output](./img/max_marks1.jpg) 

## Output:

## i) To find the maximum of marks using the list method sort.

![pyth output 3a](https://github.com/kancharlaNarmadha/FindMaximum/assets/119559316/39520969-66ad-4de5-be9e-1a1d72aadc11)




## ii) To find the maximum marks using the list method max()



![pyth output 3 2 a](https://github.com/kancharlaNarmadha/FindMaximum/assets/119559316/4ade6f1b-2cbb-4146-9daa-fdc79aaca8cd)




## iii) To find the maximum marks without using builtin functions.
 
![pyth output 3 3 a](https://github.com/kancharlaNarmadha/FindMaximum/assets/119559316/5534ee69-8b88-4754-a968-544169bc54ab)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
