# Welcome to GitHub Desktop!

This is your README. READMEs are where you can communicate what your project is and how to use it.


AISHA ADAMS
#Assignment 1-Write a program to calculate the factorial of a number.

user_input= ""
while True:
    user_input =input("Please enter a number: \n")
    if user_input== 'end':
        break
    else:
        name =math.factorial(int(user_input))
        print(f"{name} is the factorial of {user_input}")

#Assignment 2- Use range() to count down from 5 to 1, printing each number on a separate line. After the loop, print 'Go!'.

for x in range(5, 0, -1):
    print(x)
print("Go!")

#Assignment 3- Use one range() to count down from 0 to 4, and another range() to count up from 4 to 0. Use zip() to loop through both ranges together. Print each pair of numbers out on a separate line in this format: '0 4', etc.

r=range(4, -1, -1)
a=range(0, 5, 1)
zipped=list(zip(r, a))
for z in zipped:
    print(z)

#Assignment 4- (a)Write a program to display the first 7 multiples of 7.
Use if and for loop with break

num=[0, 1, 2, 3, 4, 5, 6, 7]
counter= 0
while True:
    if counter==8:
        break
    else:
        for n in num:
            print(n *7)
        counter +=1
#Assignment 4- (b)Write a program in Python to reverse a word.

def reverse_word(word):
    return word[::-1]
input_word=input("Insert a word to reverse: ")
reversed_word = reverse_word(input_word)
print("output:", reversed_word)

#Assigment 5- Write a program that iterates through this string: “The quick brown fox jumps over the lazy dog”, creating a list of each letter that’s a vowel. Print the list of vowels.

sentence= "The quick brown fox jumps over the lazy dog"
vowel= ['a', 'e', 'i', 'o', 'u']
for sen in sentence:
    if sen not in vowel:
        continue
    print(sen)


class 5- week 3
#assignment 1- Write a function that prints the last digit of a number.
Prototype: def print_last_digit(number):
Returns the value of the last digit


def print_last_digit(number):
    last_digit = abs(number) % 10
    print(last_digit)
    return last_digit
print_last_digit(567)

#assignment 2 - Write a function that prints the numbers from 1 to 100 separated by a space.
For multiples of three print Fizz instead of the number and for multiples of five print Buzz.
For numbers which are multiples of both three and five print FizzBuzz.
Prototype: def fizzbuzz():
Each element should be followed by a space

def fizzbuzz():
    # Loop through numbers from 1 to 100
    for number in range(1, 101):
        if number % 3 == 0 and number % 5 == 0:
            print("FizzBuzz", end=" ")
        elif number % 3 == 0:
                  print("Fizz", end=" ")
        elif number % 5 == 0:
            print("Buzz", end=" ")
        else:
            print(number, end=" ")
assignment 3- 
i am stuck