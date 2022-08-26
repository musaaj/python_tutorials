#Python Syntax


##Modules
modules are collections of related objects and their functions/commands. Modules provides us with ready made solutions to commonly encounter coding problems

##Objects
Python is an object oriented programming language. You can read about object oriented programming by doing simple Google search. However, understand objects to be what we call to do a particular work for us. Like in real life we have several objects in python

to create object you usually create a name for it like this [object_name] = class_name()

for example
```Python
t = turtle.Turtle();
```

In the above example t is the name of object of class Turtle you created. You can now use to do a task for you.

note: in the above example the name can be any name as long as it start with an english alphabet.

##Functions/Commands
functions or commands are what an object can do for you. some objects do not have function at al while others can have multiple functions. For example a number object does not have a function while a turtle objects has several commands

To call an object command you type the name of the object, then type . then type the name of the command then type ( then type )

Example
```Python
t.penup()
```

#Agurment
Arguments are informations with give to functions. By rules every function has a defined number of arguments it accept. Some functions do not need arguments though

Example
```Python
t.forward(100)
t.penup()
t.goto(10, 20)
```

From the above you can note that we use ',' to seperate arguments.


Let's round up with a complete example
```Python
#Program to draw parallel lines
import turtle

t = turtle.Turtle();
t.forward(100)
t.penup()
t.goto(0, -10);
t.pendown()
t.forward(100)
```
