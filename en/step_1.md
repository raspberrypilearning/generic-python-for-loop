### Python - while loop

The purpose of a **for loop** is to repeat code for every item in a list. It can also be used to repeat code a number of times. 

#### For loop over a list
Here is an example of a **for loop** which will print each item in a list. 

```python
animals = ["fox", "wolf", "panda", "squirrel"]

for animal in animals:
  print(animal)
```

The output is:
```
fox
wolf
panda
squirrel
```

Notice that the `print` line of code is slightly further to the right. This is called __indentation__ - the line is __indented__ to show that it is inside the loop. Any lines of code inside the loop will be repeated.


#### For loop over a simple range

We often need to repeat a loop a number of times. In Python the `range` function returns a list of numbers that can be used in a `for` loop. 

```python
for i in range(5):
  print(i)
```

The output is:
```
0
1
2
3
4
```

Notice that `range(5)` returns a list of numbers starting from 0 and stopping at 4 (one less than 5).

#### For loop over a range starting from 1

Sometimes it's useful to start counting from 1 instead of 0. 

```python
for i in range(1, 6):
  print(i)
```

The output is:
```
1
2
3
4
5
```

Notice that the second input to `range` needs to be 6 to keep counting up to 5. 