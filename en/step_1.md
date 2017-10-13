The purpose of a **for loop** is to repeat code for every item in a list. It can also be used to repeat code a number of times. 

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

Notice that `range(5)` returns a list of numbers starting from 0 and stopping at 4 (one less than 5). Sometimes it's useful to start counting from 1 instead of 0. 

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
