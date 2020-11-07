03
==

First task
----------

Make a program called `random.py` that does the following:

- Print a random number. It must be different every time you run the program.

<details>
  <summary>Help</summary>
  Okay, that was a difficult task. You're supposed to fail it.

  It's not easy to write all code you ever need yourself. Programmers sometimes
  use their time helping each other by creating code and sharing it, so that
  others don't have to write this code as well. When they do this, they are
  creating something called a "library".

  A library is like a pre-made ingredient in a food dish. It's ready to use, so
  you don't have to make it yourself.

  Python is famous for having a lot of libraries, and many good ones.
  It's very normal to use libraries in Python.

  To use a library, the `import` code is used.

  For example, to import functions from the "math" library, do this:

  ```
  import math

  a = 9.9
  result = math.ceil(a)
  print(result)
  ```

  Or to import only the `ceil` function from `math`, do:

  ```
  from math import ceil

  a = 9.9
  result = ceil(a)
  print(result)
  ```
</details>

Second task
-----------

Make a program called `import-random.py` that does the following:

- Import the [`random`](https://docs.python.org/3/library/random.html) library
- Use the [`randrange`](https://docs.python.org/3/library/random.html#random.randrange) function to get a random number
- Make a variable (call it anything you want to) and set it's value to a random number from 1 to 100.
- Print the variable.
