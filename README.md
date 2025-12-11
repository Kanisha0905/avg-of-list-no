# avg-of-list-no
n=int(input("Enter the limit:"))
s=0
for i in range(1,n+1):
    print("Enter ",i,end='')
    a=int(input("th number:"))
    s=s+a
avg=s/n
print("The sum of entered numbers :",s)
print("The Average of entered numbers:",avg)

output:
Enter the limit:4
Enter  1th number:1
Enter  2th number:2
Enter  3th number:3
Enter  4th number:4
The sum of entered numbers : 10
The Average of entered numbers: 2.5
