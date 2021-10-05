#1ex
num = int(input('Please enter your number here: '))
if num < 60:
    print(f' {num//86400} д, {num//3600} ч, {num//60} м, {num//s} с')
if num > 60 and num <= 3600:
    m = num // 60
    S = num % 60
    s = S // 1
    print(f'{num // 86400} д, {num // 3600} ч, {m} м, {s} с')
if num > 3600 and num < 86400:
    h = num // 3600
    M = num % 3600
    m = M // 60
    S = M % 60
    s = S // 1
    print(f'{num//86400} д, {h} ч, {m} м, {s} с'),
if num > 86400:
    d = num // 86400
    H = num % 86400
    h = H // 3600
    M = H % 3600
    m = M // 60
    S = M % 60
    s = S // 1
    print(f'{d} д,{h} ч,{m} м,{s} с')
#3ex
num = 0
while num <= 100:
    num += 1
    if num % 100 >= 10 and num % 100 <= 14:
      print(f'{num} Процентов')
    elif num % 10 >= 2 and num % 10 <= 4:
      print(f'{num} Процента')
    elif num % 10 == 1 and num != 10:
      print(f'{num} Процент')
    else:
      print(f'{num} Процентов')
