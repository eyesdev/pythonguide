Python Guide by Jakub!

Hello! Welcome to my guide! Let's start with simple functions.


This function will print something to the console (the text inside there):


```python
print("This text will be written in the console!")```

Now let's make some variables (values). A variable is a value just like in maths! Kind of like numberone = 1.


Also, before we do that, you might be wondering what this hashtag thing is. This thing is called a comment. You can use this to make comments on your code. You can make a comment by putting a hashtag then space and write whatever you want!


Continuing with what we were doing, let's make a variable:

```python
firstten = 10```

You do not only have to use ints (numbers) to make a variable! You can store anything! For example:

```python
message = "Welcome to my program!"```

We can use this and put it anywhere; the text is stored in the variable "message".

```python
print(message) # This will print "Welcome to my program!" (value of the variable).```

Now, let's do something more! Now, I am going to introduce inputs. In Python, inputs are the data provided by the user during program execution, captured using the input() function. Now, let's use it!

```python
input("What is your name?")```

Now, you might think, "Why is this useful if we don't know how to get the value of the user's answer?" We can do something like this:

```python
useranswer = input("What is your name? ")```

The user's answer will be stored in the variable "useranswer". Let's use this!

```python
print(useranswer)```

This will just print the user's name. Let's spice this up a little! If we want to do something like "My favourite name is (the value of useranswer)", we can do this in 2 ways!


Strategy 1:

```python
print("My favourite name is", useranswer)```

Strategy 2 (more efficient):

```python
print(f'My favourite name is {useranswer}')```

Strategy 2 is more efficient because, as you see, variables are selected by {variable name}. With Strategy 2, you can also use the variable in the middle of the text. For example:

```python
print(f'My favourite name is {useranswer}! It just sounds so nice!')```

Forgot to say, you can fit multiple lines into one print like this:

```python
print('''

1
2
3
4


''')```

We can also use if loops, so if an input is equal to something, we can run a function!

```python
if useranswer == "Jakub":
    print("Wow! What a great name!! I have the same name :))")```

Now, let's make a main menu in Python using all this info we learned!

```python
print("Main menu!")
print('''

[1] Print "Hello World"
[2] Store your answer into a variable called "test"


''')

option = input(">> ")

if option == "1":
    print("Hello World!")
elif option == "2":
    funny = input("Put in your input! ")```

Now let's learn about pip.


Pip is a program already imported into Python (if you added pip to path while installing) to install external packages made by people like you! For example, if we go to the command prompt located in this folder and we type `pip install {package name}`, we can install that package! I will be showing you a package named "Colorama" which can print or make inputs with colored text! So if we run `pip install colorama` and it finishes installing, we can type this!

```python
from colorama import Fore```

Then we can print some text using print(Fore.{the color you want in capital letters} + "Your Text!"). Here is an example:

```python
print(Fore.BLUE + "This is some nice blue text!")```

We can use Colorama to make colored text! Now there's a package that is already imported to Python when you install it, the name is os! To import it, simply type this:

```python
import os```

Now, let's use os to run command prompt commands, yes you can do that! For example, os.system("the command you want to run"). Now look at me using it!

```python
os.system("color a") # (color a changes all the printed text (using print only without colorama) to green!)
os.system("curl parrot.live") # (curl parrot.live runs a command that shows an animated dancing parrot, usually used in custom discord emojis!)```

These are the basics of Python! Now try to make a program. Just make a file named yourfilename.py (HAS TO END WITH .PY OR IT WON'T RUN AS PYTHON), and you are ready to make a program in Python! Good luck with your Python journey!
