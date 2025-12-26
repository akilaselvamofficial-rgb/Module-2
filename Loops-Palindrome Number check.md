## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
n=int(input())
n1=n
pal=n
rev=0
while n>0:
    r=n%10
    rev=rev*10+r
    n=n//10
if pal==rev:
    print("The given number",n1,"is a Palindrome")
else:
    print("The given number",n1,"is not a palindrome")
```
## Output
![WhatsApp Image 2025-12-26 at 7 26 17 PM](https://github.com/user-attachments/assets/e36a66cb-453b-4e2b-9189-69703678ba97)


## Result

Thus, the given python program has been executed successfully
