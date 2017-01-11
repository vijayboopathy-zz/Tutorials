# Python
## Numbers
### Basic math operators
3 + 2 ==> Addition
8 - 4 ==> Subtraction
2 * 3 ==> Multiplication
7 / 8 ==> Division
5 % 3 ==> Modulo (Reminder)
5 ** 3 ==> Exponent (5*5*5)

### Order:
BODMAS

## Variable Def:
### Numeric Def
var = 1
### String Def
var = "windows" (Always use double quotes)

## Strings
'Hey there! Howdy?'
"Vijay is an awesome programmer"
"I don\'t want to lose"
'I said, "What are you doing tomorrow?"'

## Functions
### Print
print('How is your day going?')
print(r'C:\Vijay\Desktop\newfolder') ==> Raw String (Print as is)
Raw strings are used to print file paths and stuff

### len
len(vijayboopathy) ==> 13
len(var) ==> variable length

## Slicing up Strings
user = "Vijayboopathy"
user[0] ==> V
user[-1] ==> y
user[0:5] ==> Vijay
user[5:] ==> boopathy
user[:6] ==> Vijayb
user[:] ==> Vijayboopathy

## Lists
### Create a list
poker = [1,5,7,4,3]
poker ==> [1,5,7,4,3]

### Slice a list
poker[2] ==> [7]
poker[1:3] ==> [5,7]

### Temporary append
poker + [3,5,9] ==> [1,5,7,4,3,3,5,9]

### Permanent append
poker = poker + [2,3]
poker ==> [1,5,7,4,3,2,3]

poker.append(7)
poker ==> [1,5,7,4,3,2,3,7]

### Re-assign values
poker[0:3] = [4,8,1]
poker ==> [4,8,1,4,3,2,3,7]

### Empty a list
poker[:] = []
