# letupgrade
assignment3
sum=0
num=1
while num < 11:
    sum=sum+num
    print(sum)
    num=num+1
1
3
6
10
15
21
28
36
45
55
In [10]:
num=int(input('enter the number: '))
if num > 1:
    for i in range(2,num):
        if (num%i)==0:
            print(f'{num} is not a prime number')
            break
        else:
            print(f'{num} is a prime number')
            break
else:
    print(f'{num} is not a prime number')
enter the number: 10
10 is not a prime number
