# lab2
import random

def neg_multiply(arr):
    product = 1
    for num in arr:
        if num < 0:
            product *= num
    return product

# Test üçün təsadüfi bir siyahı yaradırıq
n = 10  # Siyahının uzunluğu
arr = [random.randint(-12, 24) for _ in range(n)]

print("Siyahı:", arr)
result = neg_multiply(arr)
print("Mənfi ədədlərin hasil:", result)
