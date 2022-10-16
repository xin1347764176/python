# python
九九乘法表

i=1
j=1
while (i<=9):
    j=1
    while(j<=i):
        print("%d*%d=%d\t"%(j,i,i*j),end='')
        j+=1
    print("")
    i+=1





//for x in range
i=1
j=1
for i in range(1,10):
    for k in range(1,i+1):
        print("%d*%d=%d\t"%(i,k,i*k),end='')
    print()

