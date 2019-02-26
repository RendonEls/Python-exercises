### Lists

Starting with the following list...

```py
planeteers = ["Earth", "Wind", "Captain Planet", "Fire", "Water"]
```

Access the second value in `planeteers`.

```py
planeteers[1]
```

Add "Heart" to the end of `planeteers`.

```py
 planeteers.append("Heart")
```

Remove "Captain Planet" from the list.

```py
planeteers.pop(2)
```

Combine `planeteers` with `rangers = ["Red", "Blue", "Pink", "Yellow", "Black"]` and save the result in a variable called `heroes`.

```py
 rangers = ["Red", "Blue", "Pink", "Yellow", "Black"]
 heros = planeteers + heros
```

Alphabetize the contents of `heroes` using a function.

```py
 sorted(heros)
```

Randomize the contents of `heroes` using a function. [The Python documentation might help](https://docs.python.org/2/library/random.html).

```py
from random import shuffle
shuffle(heros)
```

#### Bonus

Select a random element from `heroes` using a function. [The Python documentation might help](https://docs.python.org/2/library/random.html).

```py
from random import choice
choice(heros)
```

### Dictionaries

Initialize a dictionary called `ninja_turtle` with the properties `name`, `weapon` and `radical`. They should have values of "Michelangelo", "Nunchuks" and a true boolean, respectively.

```py
ninja_turtle = {
  "name": "Michelangelo",
  "weapon": "Nunchuks",
  "radical": True,
}
```

Add a key `age` to `ninja_turtle`. Set it to whatever numerical value you'd like.

```py
ninja_turtle["age"] = 10
```

Remove the `radical` key-value pair from `ninja_turtle`.

```py
del ninja_turtle["radical"]
```

Add a key `pizza_toppings` to `ninja_turtle`. Set it to an list of strings (e.g., `["cheese", "pepperoni", "peppers"]`).

```py
ninja_turtle["pizza_toppings"] = ["cheese", "pepperoni", "peppers"]
```

Access the first element of `pizza_toppings`.

```py
# Your answer here
```

Produce an list containing all of `ninja_turtle`'s keys using a function. [The Python documentation might help](https://docs.python.org/3/tutorial/datastructures.html).

```py
# Your answer here
```

Produce a list containing all of `ninja_turtle`'s values using a function.

```py
# Your answer here
```

#### Bonus

Write a function that prints out each key-value pair in the following format - "KEY is equal to VALUE". [The Python documentation might help](https://docs.python.org/3/tutorial/datastructures.html).

```py
# Your answer here
```