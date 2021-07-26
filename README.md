import sys
number = int(input())
max_number = 0
min_number = 0
for number in range(number):
    more_numbers = int(input())
    if more_numbers > max_number:
        max_number = more_numbers
    if more_numbers < min_number:
        min_number = more_numbers
print(f"Max number: {max_number}")
print(f'Min number: {min_number}')

Напишете програма, която чете n на брой цели числа. Принтирайте най-голямото и най-малкото число сред въведените.
Примерен вход и изход
вход
изход

вход
изход
5
10
20
304
0
50
Max number: 304
Min number: 0

6
250
5
2
0
100
1000
Max number: 1000
Min number: 0
    
