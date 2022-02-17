# 17-02-2022-assignment-2
a=-1
b=1
sum=0
n=int(input("Enter the n:"))
for i in range(1,n+1):
    c=a+b
    print(c)
    sum=sum+c
    a=b
    b=c
print("sum is",sum)


output:
Enter the n:25
0
1
1
2
3
5
8
13
21
34
55
89
144
233
377
610
987
1597
2584
4181
6765
10946
17711
28657
46368
sum is 121392
