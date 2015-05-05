PyCalc
======

Note
----
This has been updated. The new version is called GoodCalc, and it works much better. https://github.com/dwizard/goodcalc

The better calculator in python. 

Features
--------

- /right number number number

Determines if 3 side lengths turn into a right triangle

- /sin number

Calculates sin(number), also can work for 

- /prime number

Calculates if a number is prime.

This is how it works:

    def prime(number):
      for i in range(2, int(sqrt(number))+1):
        if number%i == 0:
            return 0
      return 1
