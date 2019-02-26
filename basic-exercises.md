### Assorted Data Types

#### What are the outputs and/or side effects of the following code snippets?

* Make a guess before testing your answer.
* "Error out" is a valid answer choice.
* Also include a sentence on why you chose your answer.

```py
2 ** 3
```
```text
8
```

```py
((16 / 4) * (2 + 1)) ** 2
```

```text
144.0
```

```py
("a milli " + "a milli") * 3
```

```text
'a milli a millia milli a millia milli a milli'
```

```py
("a milli " * 4) / 2
```

```text
TypeError: unsupported operand type(s) for /: 'str' and 'int'
```

```py
my_favorite_number = 13
print("My favorite number is: " + my_favorite_number)
```

```text
----> 2 print("My favorite number is: " + my_favorite_number)

TypeError: must be str, not int
```

```py
my_favorite_number = 13
print("My favorite number is: {}".format(my_favorite_number))
```

```text
My favorite number is: 13
```

### Truthiness and Falsiness

#### Which of these evaluate as `false` in Python? Mark all that apply.

```text
[x] False
[x] 0
[x] ""
[x] None
[x] [ ] (empty list)
```

#### What are the outputs and/or side effects of the following code snippets?

* Make a guess before testing your answer.
* "Error out" is a valid answer choice.
* Also include a sentence on why you chose your answer.

```py
no_name = ""
if no_name:
    print("My name is: " + no_name)
```
```text
nothing
```

```py
no_name = None
if no_name:
    print("My name is: " + no_name)
```

```text
nothing
```

```py
age = 21
if age:
    print("My age is: " + age)
```
```text
TypeError: must be str, not int
```

```py
age = input()
if age:
    print("My age is: " + age)
```

```text
My age is: 21
```

### Conditionals

Write the code for the following exercise inside of the `app.py` located in this repo. Run/test your code using `python app.py` in the Terminal.

#### Write FizzBuzz in Python!

Fizz-Buzz is a classic coding exercise that you can create using your knowledge of conditionals and loops. Implement code that does the following...

* Counts from 1 to 100 and prints out something for each number.
* If the number is divisible by 3, print `"Fizz"`.
* If the number is divisible by 5, print `"Buzz"`.
* If the number is divisible by both 3 and 5, print `"FizzBuzz"`.
* If the number does not meet any of the above conditions, just print the number.

Your output should look something like this...
```
1, 2, Fizz, 4, Buzz, Fizz, 7, 8, Fizz, Buzz, 11, Fizz, 13, 14, Fizz Buzz, 16, 17, Fizz, 19, Buzz, Fizz, 22, 23, Fizz, Buzz, 26, Fizz, 28, 29, Fizz Buzz, 31, 32, Fizz, 34, Buzz, Fizz, ...
```

<details>
  <summary><strong>We haven't covered loops yet, so to get you started...</strong></summary>

  ```py
    for number in range(1, 101):
     # Your code goes in here.
  ```