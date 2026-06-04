# Exp.No:18  
## FILES - MERGE THE CONTENT IN A FILE

---

### AIM  
To write a Python program that merges the content of two files into a third file.

---

### ALGORITHM

1. Begin the program.
   
2.Open the first file and read its contents.

3.Open the second file and read its contents.

4.Create a third file where the contents of both files will be written.

5.Write the contents of the first file to the third file.

6.Write the contents of the second file to the third file.

7.Close all files.

8.End the program.

---

### PROGRAM
Reg no: 212223020023
Name: Shanthosh S

```

def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)


def merge_files(file1_path, file2_path, output_file_path):
    with open(file1_path,"r") as f:
        t=f.read()
    with open(file2_path,"r") as f:
        t1=f.read()
    with open(output_file_path,"w") as f:
        f.write(t+t1)
        


def read_file(file_path):
    with open(file_path, 'r') as file:
        return file.read()

```


### OUTPUT

![Screenshot 2025-04-28 190600](https://github.com/user-attachments/assets/29c18c0e-7864-446d-8b5c-d2851832916e)


### RESULT
The program successfully merges the contents of two files into a third file.

