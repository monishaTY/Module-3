# Exp.No:3a
## STRING - FIND AND REPLACE

### AIM  
To write a Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user.

### ALGORITHM

1. Begin the program.  
2. Input the original string `str1` and the word to be replaced `replace_str`.  
3. Ask the user to input the new replacement word `str2`.  
4. Use the `replace()` method in Python to replace all occurrences of `replace_str` in `str1` with `str2`.  
5. Store the modified string in `str3`.  
6. Display the original string (`str1`) and the modified string (`str3`).  
7. Terminate the program.

### PROGRAM
```
def replacestr(m, n):
    r=input()
    print("The old string is",m)
    
    print("the new string is",m.replace(n,r))
```
### OUTPUT
![image](https://github.com/user-attachments/assets/f65effa4-5015-451f-8f66-7a8fd296b475)

### RESULT
Thus a Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user has been implemented and executed.
