# 1-n-Recursion
#print 1 to n numbers using recursion
def n_recursion(n1,n2):
    if n1 <= n2:
        print(n1)
        n_recursion(n1+1,n2)
n1=int(input("Start: "))
n2=int(input("Stop: "))
n_recursion(n1,n2)
