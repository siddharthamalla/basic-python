# basic-python
variables
price = 34 integer
rating = 4.5 floar 
is_publsiched boolean it can true or False

comments
we use # for python as commnent

Input we recieve user input from the user as 
input()

int() is added to change it into int form otherwise it will be string

strings
for eg ("") or('')
we can gget individual character using string[0] and so on.

string[1,5] it will select all the charaacter from 1 to 4 excluding 5

we can use formatted strings to dynamically insert values into our strings
name = 'sid'
message = f'HI, my name is {name}'

.upper .lower .title
.find  .replace('p','q')

Arithmetic Operators
plus minus multiply divide float return // int
% return the reminder of the dividion
x**y ie x to the power y
augmented assignment operator 
x = x + 10
x =+ 10

operator precedence:
parenthesis
exponentaiation
multipicai=tion / division
addition and substraction
 if statements:
     print()
elseif statment:
    print()
else
   print()

   Logical operation

   comparision operators
   a > b
   a >= b
   a < b
   ..................

   loops

   while condition:

       for condition
          for i in range(a,b)
            range (a,b,c)

    lists can add and do formatted string
    numbers = [1, 2, 3, 4, 5]

    number.append(5) add 5 to the end
    .insert(1,5) inset=rt 5 ro 1 postion
    .remove(9) remove 9
     .pop() remove last position
     .clear() clear all items
     .index(9) return the indexx
     .sort() sort the list
     .reversed() reverse the list
     .copy() returns the copy of the list


Tuples
they are like read only list you cannot do any thing just like list


Dictionaries:
customer = {
 “name”: “John Smith”,
 “age”: 30,
 “is_verified”: True 
}

Function
we use function break up our  code into small chunk. these chunk are easier to understand and maintain. 

def greet_user(name):
    print(f"hi {name}")

greet_user("John")

Parameters they are passed throuh the funtion
- postional arguement value passed through function must be in postional order

- keyword arguement doesnot matter

Exceptions 
they are erors that  crash our programs

try:
    condition

Exception
    print()

Classes
We use classes to define new types
class Point:
    def __init__(self, x, y):-

