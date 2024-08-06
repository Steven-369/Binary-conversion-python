# Binary-conversion-python
num=int(input("enter number"))
if num<0:
    is_num=True
    num=abs(num)
else:
    is_num=False
result=""
if num==0:
    result="0"
while num>0:
    result=str(num%2)+result
    num=num//2
print(result)
