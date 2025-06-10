# day-3-python-intro


---

### ✅ Easy Level

#### **1. Even or Odd**

```python
num = int(input("Enter a number: "))
# Write code to check if the number is even or odd
# Print "Even number" or "Odd number"
```

#### **2. Check Age Group**

```python
age = int(input("Enter your age: "))
# Print "Child" if age < 13
# Print "Teenager" if age is between 13 and 19 (inclusive)
# Print "Adult" otherwise
```

#### **3. Temperature Checker**

```python
temp = float(input("Enter the temperature in °C: "))
# If temp < 10 → "It's cold"
# If temp between 10 and 25 → "It's moderate"
# If temp > 25 → "It's hot"
```

---

### 🔁 Medium Level

#### **4. Login Check**

```python
username = input("Enter username: ")
password = input("Enter password: ")
# If username is 'admin' and password is 'python123'
# Print "Access granted"
# Else print "Access denied"
```

#### **5. Grade Evaluator**

```python
score = int(input("Enter your score (0-100): "))
# 90-100: A
# 80-89: B
# 70-79: C
# 60-69: D
# <60: F
# Print the corresponding grade
```

#### **6. Multiple of Both 3 and 5**

```python
num = int(input("Enter a number: "))
# If divisible by both 3 and 5 → "FizzBuzz"
# If only by 3 → "Fizz"
# If only by 5 → "Buzz"
# Else → "Not divisible by 3 or 5"
```

---

### 🧠 Harder Level

#### **7. Password Strength Checker**

```python
password = input("Enter your password: ")
# If password is at least 8 characters and contains '!'
# Print "Strong password"
# If at least 8 characters but no '!' → "Add a special character"
# If less than 8 characters → "Password too short"
```

#### **8. Guess the Secret Word**

```python
secret = "python"
guess = input("Guess the secret word: ")
# If guess equals secret → "Correct!"
# If guess comes before secret alphabetically → "Too early!"
# If guess comes after secret alphabetically → "Too late!"
```

#### **9. Compare Three Numbers**

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))
# Print the largest number
# No need to use max() or any built-in function
```

#### **10. Emergency Level (colored version)**

```python
from stringcolor import cs
level = input(cs("Enter level (low, medium, high, critical): ", "#1e90ff"))

# "low" → green message
# "medium" → yellow message
# "high" → orange message
# "critical" → red message
# anything else → brown warning

# Use if/elif/else and cs(), no dicts or lists
```

---

