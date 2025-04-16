# Ex.No: 3 To check the number is prime or not and inspect for failures.
 
### DATE:  16-04-2025                                                                     
### REGISTER NUMBER : 212222040045
### AIM: 
Write a python program to check the number is prime or not and inspect for failures.
 
### Algorithm:
1. Start the program.
2. Get the number to be checked from the user.
3. If the number is less than or equal to 1, return "Not Prime".
4. If the number is 2, return "Prime".
5. Start the iteration from 3, For each iteration:
6. If the number is divisible by the current iteration value, return "Not Prime".
7. If the number is not divisible by any value from 2 to the square root, return "Prime".
8. Stop the program.

### Program:
```
def is_prime(n):
    if n <= 1:
        return False
    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            return False
    return True

try:
    number = int(input("Enter a number: "))
    if is_prime(number):
        print(f"{number} is a prime number.")
    else:
        print(f"{number} is not a prime number.")
except ValueError:
    print("Invalid input. Please enter an integer.")
```

### Output:

![image](https://github.com/user-attachments/assets/2b13aa4a-6f6b-48c3-83b9-800c6c68a0a8)




### Result:
Thus, the python program to check the number is prime or not is implemented and the output is verified successfully.
