Задача 10
n = int(input())
count_zero = 0
count_one = 0
for i in range(n):
x = int(input())
if x == 0:
count_zero += 1
else:
count_one += 1
if count_one > count_zero:
print(count_zero)
else:
print(count_one)

Задача 12
x = int(input())
y = int(input())
for i in range(x):
for j in range(y):
if x == i + j and y == i * j:
print(i, j)
