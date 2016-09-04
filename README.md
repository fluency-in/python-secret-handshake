# Python: Secret Handshake

Write a program that will take a decimal number, and convert it to the appropriate sequence of events for a secret handshake.

> There are 10 types of people in the world: Those who understand
> binary, and those who don't.

You and your fellow cohort of those in the "know" when it comes to
binary decide to come up with a secret "handshake".

```
1 = wink
10 = double blink
100 = close your eyes
1000 = jump


10000 = Reverse the order of the operations in the secret handshake.
```

Here's a couple of examples:

Given the input 9, the function would return the array
["wink", "jump"]

Given the input "11001", the function would return the array
["jump", "wink"]


The program should consider strings specifying an invalid binary as the
value 0.

To run a test file, pass it as an argument to the `python` command:

    python hello_world_test.py

If you want to stop the tests after the first failure, then you can use the pytest library.

Install pytest with pip:

    pip install pytest

Run the tests with the `py.test` command using the `-x` flag to exit after the first failure.

    py.test -x hello_world_test.py

## Source

Bert, in Mary Poppins [http://www.imdb.com/character/ch0011238/quotes](http://www.imdb.com/character/ch0011238/quotes)

This exercise is from the [Python][python] track on [Exercism][exercism]

[exercism]: http://exercism.io
[python]: http://exercism.io/languages/python



