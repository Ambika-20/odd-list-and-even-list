# odd-list-and-even-list
#To store odd numbers in odd list and even numbers in even list
oddnum = []
evennum = []
n = int(input("Enter num:"))
for i in range(1,n):
    if i%2 == 0:
        evennum.append(i)
    else:
        oddnum.append(i)
print("oddlist:",oddnum)
print("evenlist:",evennum)
