#  Hackerrank:Runner-Up Score Finder in Python

##  AIM:
To write a Python program that takes a list of scores from participants and finds the **runner-up score** (i.e., the second-highest score), eliminating any duplicates.

---

##  ALGORITHM:

1. **Start**
2. Create a variable `n` and get its value from the user (number of participants)
3. Read the list of `n` scores from the user using `input().split()` and convert them to integers
4. Store the scores in a list
5. Use `set()` to remove any duplicate scores
6. Convert the set back to a list and sort it in ascending order
7. Print the second-last element of the sorted list (i.e., the runner-up score)
8. **Stop**

---

##  PROGRAM:
```
n=int(input())
student_marks={}
for _ in range(n):
    line=input().split()
    name,scores=line[0],line[1::]
    scores=map(float,scores)
    student_marks[name]=scores
query_name=input()
marks=0
for i in student_marks[query_name]:
    marks=marks+i
avg=marks/3
print("%.2f"%avg)
```



## OUTPUT

![runup](https://github.com/user-attachments/assets/43879367-be84-44a7-b7f0-31d8c6fad51a)

## RESULT
Thus a Python program that takes a list of scores from participants and finds the **runner-up score** (i.e., the second-highest score), eliminating any duplicates is created.
