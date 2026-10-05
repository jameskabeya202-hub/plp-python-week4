#question 1: welcome.py
    # runned code
def welcome(name):
    return "Hello, " + name + "! Welcome to PLP."

print(welcome("Amina"))
print(welcome("Brian"))
print(welcome("Fatuma"))
#outcome
Running] python -u "c:\Users\Admin\Desktop\plp-python-week4\welcome.py"

[Done] exited with code=0 in 2.106 seconds

[Running] python -u "c:\Users\Admin\Desktop\plp-python-week4\welcome.py"

[Done] exited with code=0 in 3.183 seconds

[Running] python -u "c:\Users\Admin\Desktop\plp-python-week4\welcome.py"
Hello, Amina! Welcome to PLP.
Hello, Brian! Welcome to PLP.
Hello, Fatuma! Welcome to PLP.

[Done] exited with code=0 in 0.83 seconds

#toolbox.py
def double(number):
    return number * 2
def is_pass(score):
    return score >= 50
def greet(name, greeting="Hello"):
    return greeting + ", " + name + "!"
print(double(7))
print(double(10))
print(is_pass(80))
print(is_pass(20))
print(greet("Amina"))
print(greet("Brian", "Habari"))

#outcome
[Running] python -u "c:\Users\Admin\Desktop\plp-python-week4\toolbox.py"
14
20
True
False
Hello, Amina!
Habari, Brian!

[Done] exited with code=0 in 0.611 seconds

[Running] python -u "c:\Users\Admin\Desktop\plp-python-week4\toolbox.py"


