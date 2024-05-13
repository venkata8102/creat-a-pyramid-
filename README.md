"""
Program : Write a program in Python to print the table of numbers ?
2*1=2
2*2=4
"""


number = int(input("Enter a number : "))
result = 0


for i in range(1, 11):
    result = number * i
    print(number,"*",i,"=",result)
