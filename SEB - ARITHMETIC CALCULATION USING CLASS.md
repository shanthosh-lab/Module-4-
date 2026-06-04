# Exp.No:20  
## SEB - ARITHMETIC CALCULATION USING CLASS AND IF-ELSE

---

### AIM  
To write a Python program using a class to perform multiplication and floor division based on user choice using if, elif, and else statements.

---

### ALGORITHM

1. Begin the program.
   
2.Define a class named CSE.

3.Create a method setvalues() to set the values of a and b.

4.Define a method mul() to perform multiplication of a and b.

5.Define a method div() to perform floor division of a by b.

6.Use a loop to present a menu with choices:

      1 → multiplication
      
      2 → floor division
      
      0 → exit
      
      any other input → "Invalid choice"

7.Execute the method based on user choice using if, elif, and else.

8.End the program. 


---

### PROGRAM
Reg no: 212223020023
Name: Shanthosh S

```
class CSE:
    def setvalues():
        global a
        global b
        a=int(input())
        b=int(input())
    def add(a,b):
        return a*b
    def div(a,b):
        return int(a/b)
CSE.setvalues()
while(1):
    c=int(input())
     
    if c==1:
        print("Result: ",CSE.add(a,b))
    elif c==2:
        print("Result: ",CSE.div(a,b))
    elif c==0:
        print("Exiting!")
        break
    else:
        print("invalid choice")


```

### OUTPUT
![Screenshot 2025-04-28 191759](https://github.com/user-attachments/assets/8ab13db0-4b90-4299-88b6-00036bfa4453)


### RESULT
The program successfully performs multiplication and floor division based on user choice using a class and conditional statements, and terminates successfully when the user selects exit
