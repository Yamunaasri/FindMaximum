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

'''
Program to mark the maximum of marks using the list method sort
Developed by: T S Yamunaasri
RegisterNumber: 21222240117
'''
def max_marks(marks):
marks.sort(reverse=True)
return marks[0]

```

ii)	# To find the maximum marks using the list method max().
```Python

'''
Program to find the maximum marks using the list method max().
Developed by: T S Yamunaasri
RegisterNumber: 21222240117
'''
def max_marks(marks):
return max(marks)

```

iii) # To find the maximum marks without using builtin functions.
```Python

'''
Program to the maximum marks without using builtin functions.
Developed by: T S Yamunaasri
RegisterNumber: 21222240117
'''
def max_marks(list1):
max=list1[0]
for i in list1:
if(max<i):
max=i
return max

```
## Output:
![Screenshot 2023-06-15 000147](https://github.com/Yamunaasri/FindMaximum/assets/115707860/34c6b045-6ad5-45be-8e25-f119fa27e02c)

![Screenshot 2023-06-15 000156](https://github.com/Yamunaasri/FindMaximum/assets/115707860/fde32ebc-e5b8-45ba-b61a-16f3952cdac8)

![Screenshot 2023-06-15 000247](https://github.com/Yamunaasri/FindMaximum/assets/115707860/e8c205a3-24ea-494a-ad3c-211bf723b937)

![Screenshot 2023-06-15 000255](https://github.com/Yamunaasri/FindMaximum/assets/115707860/194b5f99-5ce2-414f-b902-27b4ea6ba256)

![Screenshot 2023-06-15 000346](https://github.com/Yamunaasri/FindMaximum/assets/115707860/b05d7933-c4ae-4c2b-9249-c27e4690fc86)

![image](https://github.com/Yamunaasri/FindMaximum/assets/115707860/28b5085d-9834-4760-a556-5279be7f36ba)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
