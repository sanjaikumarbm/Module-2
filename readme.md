# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
a = 16

b = bin(a)
print(b)
   
## Output
<img width="905" height="126" alt="image" src="https://github.com/user-attachments/assets/12c75e75-e28f-4e46-aec9-ccaea7118689" />


## Result
Thus, The Python program to convert the number 16 into its binary representation using built-in Python functions was executed successfully.
# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
    def result(a,b):     
    c = a % b

    print(c)         
    a = int(input())
  
    b = int(input())     

    result(a,b)          

## Output
<img width="761" height="240" alt="image" src="https://github.com/user-attachments/assets/7ffa3e63-14fa-474d-9400-b9f525f227e2" />


## Result
Thus, The Python program that defines a function which accepts two values and returns their modulo using the % operator was executed successfully.
# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
    a = int(input()) 
    b = int(input())

    sum = lambda a,b: a+b

    print(sum(a,b))

## Output
<img width="1068" height="200" alt="image" src="https://github.com/user-attachments/assets/4334a352-b03e-4d21-ac49-325797d581b6" />


## Result
Thus, The Python program that defines a lambda function which takes two arguments a and b, and returns their sum was executed successfully.
# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
     def print_pascals_triangle_formula(num_rows):

    for n in range(num_rows):
    val = 1
    row_list = []
    for k in range(n + 1):
         row_list.append(str(val))
         val = val * (n - k) // (k + 1)

     row_str = " ".join(row_list)
     max_width = len(" ".join(map(str, [1] * num_rows)))
     print(row_str.center(max_width))

     n = int(input())
    print_pascals_triangle_formula(n)

## Sample Output
<img width="790" height="537" alt="image" src="https://github.com/user-attachments/assets/354ed3d4-14b2-4c2f-9780-91c9d32e6bb5" />


## Result
Thus, The Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user was executed successfully.

## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * ev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
    num = int(input("ENTER A NUMBER :"))
    temp = num
    rev = 0
    while temp > 0:
      rev = (10 * rev) + temp % 10
      temp = temp // 10
    if rev == num :
      print(f"The given number {num} is Palindrome")
    else:
      print(f"The given number {num} is not Palindrome")
## Output
<img width="615" height="316" alt="image" src="https://github.com/user-attachments/assets/e9f5307c-da88-4159-a598-d35e4d043b19" />


## Result
Thus, The Python program that checks whether a given number is a palindrome using loops was executed successfully.
