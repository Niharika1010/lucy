#python file to print all prime numbers between 1 to 200
#lower boundary
l = 1
#upper boundary
u = 200
for i in range(l,u+1):
    #all prime numbers greater than 1
    if (i>1):
        for j in range(2,i):
            if (i % j) == 0:
                break
        else:
            print(i)
