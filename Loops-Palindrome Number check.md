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
