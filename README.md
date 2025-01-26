from math import *
# hello world in python
print("Hello, Python in VS Code!")

#Drawing shape with python

print ("   / |")
print ("  /  |")
print (" /   |")
print ("/____|")

#variable and datatypes with python
#variable a container that we can use to store data values
character_name = "John"
character_age = "29"
print("There was once a man named " + character_name + ",")

#assigning new value to variable
character_name = "Mike"
print("he was " + character_age + " years old.")
print(character_name  + " is tall.")

#different types of data we can store in variables strings,numbers and boolean
character_age = 40 #no need to put quotes 
#boolean value
isMale= False
#working with strings
print("Giraffe\nAcademy") #\n is a new line character
print("Giraffe\"Academy") #escape character

phrase = "Giraffe Academy"
print(phrase + " is cool")
print(phrase.lower().islower())
print(phrase.upper().isupper())
print(len(phrase))
print(phrase[0])
print(phrase.index("G"))
print(phrase.replace("Giraffe", "Elephant"))

#working with numbers
print(2)
print(3.9)
print(-4)
print(3 + 4.5)

#converting numbers to strings
my_num = 5
print(str(my_num) + " my favourite number")

#math operations

print(10 % 3) #modulo operator
print(10 // 3) #floor division operator
print(10 ** 3) #exponentiation operator
print(abs(-10)) #absolute value
print(pow(3,2)) #power function
print(max(4,6)) #maximum value
print(min(10,10)) #minimum value
print(round(10.5)) #rounding off

#getting input from users
name = input("Enter your name: ")
age = input("Enter your age: ")
print ("Hello " + name + " Your age " + age)

#building a basic calculator in python
num1 = input("Enter a number: ")
num2 = input("Enter another number: ")
result =int (num1) + int(num2) # use float instead of int for decimal numbers
print(result)

#mad libs game
color = input("Enter a color: ")
plural_noun = input("Enter a plural noun: ")
celebrity = input("Enter a famous person: ")
print("Roses are " + color)
print( plural_noun + " are blue")
print ("I love " + celebrity)

#lists in python
friends = ["Kevin", "Karen", "Jim", "Oscar", "Toby"]
print(friends)
print(friends[0]) #Kevin
print(friends[-1]) #toby

#lists functions
luckyNumbers = [4, 8, 15, 16, 23, 42]
friends = ["Kevin", "Karen", "Jim", "Oscar", "Toby"]
friends.extend(luckyNumbers)
friends.append("Creed")
friends.insert(1, "Kelly")
friends.remove("Jim")
friends.clear()
friends.pop()# pop an item off  of the list
friends.index("Kevin") #index of the item

print(friends) 
#tuples
