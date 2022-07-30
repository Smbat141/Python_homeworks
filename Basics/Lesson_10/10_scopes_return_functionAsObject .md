# 10. scopes, return, function as object

## Chapter 1
### 1. Scopes


```python
# 1. Scopes

# custom_sum = 0
# number = 10
# for i in range(number):
#     custom_sum += i
# print(custom_sum)

# custom_sum = 0 
# def get_sum():
#     number = 10
#     for i in range(number):  # ask question to students
#         custom_sum += i
#     print(custom_sum)
    
# get_sum()

# custom_sum = 0 
# def get_sum():
#     custom_sum = 100000
#     print(custom_sum)
    
# get_sum()
# print(custom_sum)

# custom_sum = 0
# def get_sum():
#     global custom_sum
#     number = 10
#     for i in range(number):
#         custom_sum += i
#     print(custom_sum)
    
# get_sum()


# def get_sum():
#     number = 10
#     print(number)
    
# get_sum()
# print(number)
```

## Chapter 2
### 1. Return


```python
# 2. Return

# def f1():
#     print("hello Vardan")
# f1()

# def reverse_list(some_list):
#     for i in range(len(some_list)//2):
#         some_list[i], some_list[-i - 1] = some_list[-i - 1], some_list[i]
#     print(some_list)

# numbers = [1, 2, 3, 4, 5]
# reverse_list(numbers)
# print(numbers)

# def f1():
#     return "hello Vardan"

# some_text = f1()
# print(some_text)


# def reverse_list(some_list):
#     new_list = some_list.copy()
#     for i in range(len(new_list)//2):
#         new_list[i], new_list[-i - 1] = new_list[-i - 1], new_list[i]
#     return new_list

# asc_numbers = [1, 2, 3, 4, 5]
# desc_numbers = reverse_list(asc_numbers)
# print(asc_numbers)
# print(desc_numbers)

# def f1(some_text, count):
#     some_text *= count
#     return some_text or None

# print("returned value:", f1("hello world ", 4))

# def f1(number): # speak about flag
#     number_square = number**2
#     number_cube = number**3
#     return number_square, number_cube

# square, cube = f1(2)
# print(square, cube)


# def f1(number): # speak about flag
#     '''
#     this method return number square and cube
#     '''
#     number_square = number**2
#     number_cube = number**3
#     return number_square, number_cube

# square, cube = f1(2)
# print(square, cube)
# help(f1)
```

## Chapter 3
### 1. functon as first class object
### 2. lambda functions

```python
# 1. functon as first class object
# def dai_pyatь():
#     return 5

# def sum_pyatь():
#     print(dai_pyatь() * 2)

# sum_pyatь()

# def dai_pyatь():
#     return 5

# x = dai_pyatь
# # x()

# def sum_pyatь(get_sum):
#     print(get_sum() * 2)
    
# sum_pyatь(x)
```

    custom

