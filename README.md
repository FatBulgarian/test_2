# test_2
# second_try
num = int(input())
for i in range(1, num +1):
    for u in range(0, i):
        print(f'*', end='')
    print()
for i in range(num -1, 0, -1):
    for u in range(0, i):
        print(f'*', end='')
    print()
