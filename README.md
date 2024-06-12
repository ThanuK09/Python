# Python
Integer, float
tuple-cant be changed   list-can be changed
conditions - 


largest of string, consonents, nd vowels
reverse of number

Variable - value do not change
need not to be declared, case sensitive
casting-changing from one data type to another

assigning single value-x=y=z=1
assigning multiple values-x, y, z=1,2,3

fruits={"apple","mango","banana"}
a,b,c=fruits

globlal variable-It can be called outside a function
datatype-tells what kind of values it holds
collection-tuples,list
type-shows the datatype. print(type(a))

complex number-number followed by imaginary value

String:
a="My name is Sharmitha"
print(a)
Triple quote

a="Sharmi"
print(a[3])

for i in a:
print(i)
Output: S
	H
	A
	R
	M
	I

print(len(a))


Operator-symbols which takes two or more operands and peforms operation
operand- variable involved in an operation
Assignment operator
Arithmetic:+,*,-,/,%
Logical:and,or,not(true to false/false to true)
Bitwise:Bitwise OR,Bitwise AND,Right Shift,Left Shift,XOR
Comparison : ==,>,<,>=,<=,=!
Binary 
Identity


a=10
b=20
if(a>b):
    #print("a is greater")
else:
    print("b is greater")

List: fruits=["Mango","Apple","Orange"]
print(fruits)
print(fruits[1])  Output:Apple
print(fruits[0:1])
To add an item-append

a=["Dosa","Roti"]
b=["tea","coffe"]
a.remove("Dosa")
print(a)
b.pop(1)
print(b)

To find the occurrences of a number in an array
#arr=[]
n=int(input("Enter size of array "))
for i in range(0,n):
    element=int(input("Enter element of array "))
    arr.append(element)
print(" array: ",array)

n=int(input("Enter element to check: "))
print(n," has occurred ",array.count(n),"times")

addition without using arithmetic operations
a=10
b=3
result=a-(-b)
print(result)

To find missing elements
arr=[]
#n=int(input("enter the size of array"))
#for i in range(0,n-1):
    element=int(input("Enter element of array "))
    arr.append(element)
    arr.sort()
print(" array: ",arr)
for i in range(1,len(arr)+1):
    if i not in arr:
        print("missing element is",i)

Second largest:
 rr=[]
n=int(input("enter the size of array"))
for i in range(0,n):
    element=input("Enter element of array ")
    arr.append(element)
    sorted_list=arr.sort()
    second_largest=sorted_list[-2]
    print("Second largest element is:", second_largest)


To divide two numbers without using operator

def divide(dividend, divisor):
    if divisor == 0:
        raise ValueError("Cannot divide by zero")

    quotient = 0
    sign = 1 if (dividend < 0) == (divisor < 0) else -1  # Determine the sign of the result

    dividend = abs(dividend)
    divisor = abs(divisor)

    while dividend >= divisor:
        dividend -= divisor
        quotient += 1

    return sign * quotient


dividend=int(input("enter the number"))
divisor=int(input("enter the number"))
result = divide(dividend, divisor)
print(f"The result of dividing {dividend} by {divisor} is {result}")
