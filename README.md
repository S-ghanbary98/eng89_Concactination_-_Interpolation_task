# String Interpolation and Concatenation

- In this task the user inputs a name. The program then inputs that name via both interpolation and concatenation.

## concatenation

- User Inputs there name and the result is concatenated onto a welcome message. The users first letter in their name is also capitalized.
```python
name = input("What is your first name?")
print("Hi" + " " + name.capitalize() + ", " + "welcome to python!!")
```

## concatenation

- User Inputs there name and the result is added onto a welcome message using the built in method format. The users first letter in their name is also capitalized.
```python
full_name = input("What is your full name?")
print("Hi {} {}, welcome to python!!".format(full_name.split()[0].capitalize(), full_name.split()[1].capitalize()))
```