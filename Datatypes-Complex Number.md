# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
# Read two integers
real = int(input("Enter real part: "))
imag = int(input("Enter imaginary part: "))

# Create complex number
c = complex(real, imag)

# Print results
print("Complex number:", c)
print("Real part:", c.real)
print("Imaginary part:", c.imag)

## Output
<img width="1919" height="969" alt="image" src="https://github.com/user-attachments/assets/0a66dbe4-8637-4fd5-b6d3-6888c2ca567a" />

## Result
