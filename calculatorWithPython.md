```python
def add(x, y):
    return x+y

def substract(x, y):
    return x-y

def multiply(x, y):
    return x*y

def divide(x, y):
    if y != 0:
        return x/y
    else:
        return("y is not be 0")


num1 = float(input())
num2 = float(input())

print("Addition:", add(num1, num2))
print("Substraction:", substract(num1, num2))
print("Multiplication:", multiply(num1, num2))
print("Division:", divide(num1, num2))
```
