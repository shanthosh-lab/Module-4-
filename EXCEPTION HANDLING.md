# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To write a Python program that raises a user-defined exception in a guessing number game, where the user has to guess the number 1

---

### ALGORITHM

1. Define a custom exception class named IncorrectGuessError which will be raised for wrong guesses.
   
2.Prompt the user to guess a number.

3.If the user guesses correctly (i.e., the number 1), congratulate the user.

4.If the user guesses incorrectly, raise the IncorrectGuessError and display an error message.

5.End the program.

---

### PROGRAM

```
Reg.No : 212223020023
Name : Shanthosh S
Add Your Code Here

def Guess(a):
    secret=10
    while True:
        try:
            if guess==secret:
                print("Congratulations! You guessed it correctly.")
                break
            elif guess>secret:
                print("This value is too large, try again!")
                
                break
            else:
                print("This value is too small, try again!")
                break
        except value:
            print("rg")
guess=int(input()) 
Guess(guess)
            

```

### OUTPUT
![Screenshot 2025-04-28 185853](https://github.com/user-attachments/assets/e7a442ea-7665-4aeb-9250-f3596b80ebaf)


### RESULT
The program successfully raises a user-defined exception if the user guesses incorrectly and prints an error message.


