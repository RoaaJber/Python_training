Python_training 
for i in [5, 4, 3, 2, 1]:
    print(i)

for i in range(5):
    print(i)

my_dict = {'a': 1, 'b': 2, 'c': 3}
for key, value in my_dict.items():
    print(key, value)

    >>>> Function to: calculate takes two parameters int1 and int2, both of which are expected to be integers (int type).
Calculations:
sum_results and diff .
=================================================================================++
for i in [5, 4, 3, 2, 1]:
    print(i)

for i in range(5):
    print(i)

my_dict = {'a': 1, 'b': 2, 'c': 3}
for key, value in my_dict.items():
    print(key, value)

>>>> here we have a 3 for loops:
>>>> for i in [5, 4, 3, 2, 1]:
    print(i)
>>>> it will print the value of i that related to the list to give the below output:
5
4
3
2
1
>>>> the other for loop will be the following:
>>>> for i in range(5):
    print(i)
>>>> range (5) will print the sequence numbers from 0-4 which is the range of 5.
0
1
2
3
4

>>>> the third one will be the following:
>>>> my_dict = {'a': 1, 'b': 2, 'c': 3}
for key, value in my_dict.items():
    print(key, value)
a 1
b 2
c 3 
>>>> 

=======================================================================================++
n = 5
while n > 0:
    print(n)
    n = n - 1

x = 5
y = 0
condition = x > y
while condition:
    print(f'x: {x}, y: {y}')
    print('x is greater than y')
    y = y + 1
    condition = x > y
>>>
>>>

=============================================================================================++
def outer_function(x):
    def inner_function(y):
        return x + y
    return inner_function


closure = outer_function(10)
two_adder = outer_function(2)
four_adder = outer_function(4)
#result = closure(5)
#print(result)  # Output: 15
two_adder(6)
#print(outer_function(10))
print(two_adder(5), four_adder(5) , closure (3))

>>> how can i call a function? by calling the function name and passing an argument to the saved variables,
>>> so if i need to call the outer function i can call just the adder(which already saved the value of x) , and am putting a value for the (y) to pass the argument to y in the inner function
>>>
>>> here is another example:
>>>def outer_function(x):
    def inner_function(y):
        return x + y
    return inner_function

closure = outer_function(10)
result = closure(5)
print(result)  # Output: 15  
