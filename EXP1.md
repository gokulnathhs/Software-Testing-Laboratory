# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 19/03/2025                                                                  
### REGISTER NUMBER : 212222040045

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

### i.)do…while: 

```
def display():
     start=input("Enter a positive value for START: ")
      end=input("Enter a positive value for END: ")
      if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=‘ ‘)
            if start<end:
                start+=1
            else:
                break
      else:
        print("Enter a valid positive number.") 
  display() 
```

### ii.) while…do 

```
start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
     start=int(start)
     end=int(end)
     while start<end:
          print(start)
          start+=1
else:
   print("Enter a valid positive number.")

```

### iii.) switch 

```
def switch(): 
    switcher = { 
        0: "even", 
        1: "odd" 
    }
    
    n = input('Enter a value for N: ')
    
    try: 
        n = int(n) 
        print(switcher[n % 2]) 
    except ValueError: 
        print("Enter a valid number.") 

switch()

```

### iv.) if else

```
def compare():
  a=input("Enter a value for A: ")
  b=input("Enter a value for B: ")
  try:
     a=int(a)
     b=int(b)
     if a>b:
        print("A is greater than")
     elif a<b:
        print("B is greater than")
     else:
        print("A is equal to B")
  except ValueError:
        print(“Enter a valid number.”) 

```

### v.) for

```
def iterate():
    string=input("Enter a string: ") for
    i in string:
       print(ord(i),end=" ")
iterate() 
```














### Output:

### i.)do…while: 

![STL EX01 (a) OUTPUT](https://github.com/user-attachments/assets/9a8f4b9c-d372-484a-b0f2-6ced35765083)

### ii.) while…do 

![STL EX01 (b) OUTPUT](https://github.com/user-attachments/assets/99e1f3bb-7990-460e-9d4b-4937f01392ed)

### iii.) switch 

![STL EX01 (c) OUTPUT](https://github.com/user-attachments/assets/a2a1ee35-6c9e-400c-9fcd-d87b5456d592)

### iv.) if else

![STL EX01 (d) OUTPUT](https://github.com/user-attachments/assets/d98ce0d1-55ca-4615-9111-d2f97f821bb0)

### v.) for 

![STL EX01 (e) OUTPUT](https://github.com/user-attachments/assets/7c5170fb-e5f1-44b3-81c8-a48ae8bb8576)

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.
