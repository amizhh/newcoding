# calculator program
def add(x, y):
    return  x + y 
def subtract(x, y):
    return x - y
def multiply(x, y):
    return x * y
def divide(x, y):
    return x / y
print("select one")
select = int(input("select 1, 2, 3, 4 : "))

x = int(input("Enter x: "))
y = int(input("Enter y; "))
if select == 1:
    print (add(x, y))

elif select == 2:
    print (subtract(x, y))

elif select == 3:
    print (multiply(x, y))

elif select == 4:
    print (divide(x, y))
else:
    print("Invalid input") 
