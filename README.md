# 09-May_AssQ
These are the answers in a readme file.
﻿

Q1. Create one variable containing following type of data:

(i) string:
str = "Hello, World!"

(ii) list:
lst = [1, 2, 3, 4, 5]

(iii) float:
flt = 3.14

(iv) tuple:
tup = (1, 2, 3, 4, 5)

Q2. Given are some following variables containing data:

(i) varl = ''
(ii) var2 = '[DS, ML, Python]'
(iii) var3 = [ 'DS', 'ML', 'Python']
(iv) var4 = 1.

What will be the data type of the above given variable.
ans> 1 --> string
     2 --> string
     3 --> list
     4 --> integer


Q3. Explain the use of the following operators using an example:
(1)/   --> 4/2=2
(ii)%  --> 5%2=1
(iii)// --> 5//2=2
(iv)** --> 3**2=9


Q4. Create a list of length 10 of your choice containing multiple types of data. Using for loop print the element and its data type.

lst= [123, 'hello', True, 'hola', str, 8+7j, 'p+_aswrd123', ',./[]=-)(*&^%$#@~``', 'if_inside_braces', "then_7_khoon_maaf"]
for i in lst:
    print (type(i))


Q5. Using a while loop, verify if the number A is purely divisible by number B and if so then how many times it can be divisible.

def count_divisions(A, B):
    count = 0
    while A % B == 0:
        A = A // B
        count += 1
    return count

A = 100
B = 5

divisions = count_divisions(A, B)
print(f"A is divisible by B {divisions} times")


Q6. Create a list containing 25 int type data. Using for loop and if-else condition print if the element is divisible by 3 or not.

data_list = [2, 5, 9, 12, 15, 18, 21, 24, 27, 30, 33, 36, 39, 42, 45, 48, 51, 54, 57, 60, 63, 66, 69, 72, 75]

for num in data_list:
    if num % 3 == 0:
        print(f"{num} is divisible by 3")
    else:
        print(f"{num} is not divisible by 3")


Q7. What do you understand about mutable and immutable data types? Give examples for both showing this property.

Mutable data types are those that can be modified or changed after they are created, while immutable data types are those that cannot be modified once they are created.
List: A list in Python can be modified by adding, removing, or changing its elements.
Tuple: A tuple in Python is an immutable sequence, and its elements cannot be modified.
