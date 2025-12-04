# Overtime-pay

ovpay=0
sum=0
for i in range(1,11):
    print("Enter Working Hours of Emp ",i,":")
    h=int(input())
    if(h>40):
        extra=h-40
        ovpay=extra*12
        print("Over time pay of emp ",i," is ",ovpay)
        sum=sum+ovpay
    else:
        print("No Overtime Pay")
print("Total Overtime Pay of all employees : ", sum)

Output:

Enter Working Hours of Emp  1 :
17
No Overtime Pay
Enter Working Hours of Emp  2 :
47
Over time pay of emp  2  is  84
Enter Working Hours of Emp  3 :
43
Over time pay of emp  3  is  36
Enter Working Hours of Emp  4 :
42
Over time pay of emp  4  is  24
Enter Working Hours of Emp  5 :
37
No Overtime Pay
Enter Working Hours of Emp  6 :
18
No Overtime Pay
Enter Working Hours of Emp  7 :
24
No Overtime Pay
Enter Working Hours of Emp  8 :
52
Over time pay of emp  8  is  144
Enter Working Hours of Emp  9 :
32
No Overtime Pay
Enter Working Hours of Emp  10 :
45
Over time pay of emp  10  is  60
Total Overtime Pay of all employees :  348
