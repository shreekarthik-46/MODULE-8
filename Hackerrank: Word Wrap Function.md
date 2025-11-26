#  Hackerrank : #  Python Word Wrap Function

This Python program defines a function that **wraps a long string into multiple lines**, ensuring each line does not exceed a specified width.

---

##  Aim

To write a Python function that takes a long string and a specified width, and returns the string formatted with line breaks such that each line has **at most the given width**.

---

##  Algorithm

1. **Start** the program.
2. Define a function `wrap(string, max_width)`:
   - Create an empty list `wrapped_lines` to store parts of the string.
   - Loop through the string using steps of `max_width`.
   - In each iteration, extract a substring of length `max_width`.
   - Append this substring to the list.
3. Join the list with `\n` to create the final string.
4. Return the result.
5. **End** the program.

---


##  Program
```
def fun(s,cc=0,cv=0):
    v='aeiouAEIOU'
    for i in s:
        if i in v:
            cc+=1
        else:
            cv+=1
    print("Number of Vowels:",cc)
    print("Number of Consonants:",cv)
s=input()
```


## Sample Output

![wordwrap](https://github.com/user-attachments/assets/447262e0-a264-45ce-85fa-a71b07943321)


## Result
Thus a Python function that takes a long string and a specified width, and returns the string formatted with line breaks such that each line has **at most the given width** is created


