# Exp.No:16  
## DICTIONARY - Sorting the Dictionary 

---

### AIM  
To write a Python program that sorts the keys and values in alphabetical order based on dictionary values.

---

### ALGORITHM

1. Begin the program.
   
2.Define a dictionary with keys and corresponding values.

3. Sort the dictionary by values in alphabetical order using the sorted() function.
   
4.Display the sorted dictionary.

5.End the program.

---

### PROGRAM

```
#Reg.No : 212223020023
#Name : Shanthosh S
#Add Your Code Here

dict = {2: 56, 1: 2, 5: 12, 3: 323, 4: 24, 6: 18}

sort_dict = sorted(dict.items(), key=lambda item: item[1])


print('Keys and Values sorted in alphabetical order by the value')
print(sort_dict)



```

### OUTPUT
![Screenshot 2025-04-28 185320](https://github.com/user-attachments/assets/1a13d188-edf7-4167-8a49-de57f6b75fe6)



### RESULT
The program successfully sorts the dictionary by its values in alphabetical order and displays the sorted dictionary.


