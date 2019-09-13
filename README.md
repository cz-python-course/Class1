# Class1 - What is python, and what you can do with it
Before we dive in programming, let's understand what we can build with python, and later we start learning how python works.

# What Can I do with python?

Python can be used in a lot of fields. Games, Data science, computational vision, engineering, data science, big data, etc... Scientists and engineers often choose this language not onlybecause the learning proecess is easier that some other languages, but also because we don't always need to compile the program into an executable. We can also use it as an [interpreted language](https://en.wikipedia.org/wiki/Interpreted_language), making it easier for other people to understand what is being done and allowing other people to change it as needed. This makes python a good language to solve problems in science and engineer fields, and in fact those are the places where python really shine. Learning (the basics of)  python is not as hard as other languages, and it will allow you to start solving problems in a shorter period of time than it would take with other languages.

Python has a lot of tools built in, and you will probably not need to install libraries for the most tasks. But, when you need it, you will have a lot of libraries available for you to use. in [this github repository](https://github.com/uhub/awesome-python) you can find a list of some of the libraries you can use, but you have a lot of packages you can find, for most of the things you want to do, so remember to look up on the internet about libraries that you can use.

# How does python works?

Python is a language that can be [compiled or interpreted](https://www.lifewire.com/compiled-language-2184210). This means that you can choose the way you want to work with the language. 
The language also is [loosely typed](https://en.wikipedia.org/wiki/Strong_and_weak_typing). This means that you can assign different types of data to the same variable. If this is not making sense to you now, don't worry. It's a lot of things to understand in the beggining and it's common to have a lot of questions on your head.Let's start understanding what is a variable.

*Variable:* It's a way to store the information while the program is running. You can compare it with variables in math:

```python
x = 2
y = 4
```
We call the process of creating a variable "declaring the variable", and the process of giving a value for the variable "setting a value", "assigning a value", or "giving a value". Both processes can be made together, just like in the code above.

A variable can contain onle one information at time. In other languages, you also have to specify the type of the variable, and we cannot change it later. In those languages, you cannot use the variable to store numbers, and later use it to store a word, for example. In python we do not have this restriction, so we can reassign the value into something with a different type:

```python
x = 2
x = "hello world"
```
Although a strongly typed variable has some advantages, a loosely typed language is easier to work with data as is needed in science and engineering. This is one of the reason python is used in those fields.

## But what is a "type of data"?

Every information stored in a variable has a type. In python, Those are the most common types of data:

- *Boolean:* True or False
- *int:* whole numbers, positive, negative and zero.
- *float:* float points. NUmbers that are not int. In python, the decimal character is a dot (.), some examples are: 1.5223, -2.01234, 3.14, etc...
- *string:* Text. In python, we have to wrap those values in quotes (' or "). This way, the interpreter knows that it's a text string. We can use simple or double quotes to wrap the text we are creating. Both quotes have the same effect in python.
- *Objects:* Objects are instances of classes (we will see classes in the future, don't worry), and they are not a primitive type like the others, but they are really common as well.

## Comments

In python, when we put a pound sign (#) in the line, we are indicating that from that point until the end of the line, we are writing a comment in our code. The interpreter will ignore that part when running your code.
Comments were made so developers can write things in the code that other developers will understand. One of the best practices is to comment your code so other people can understand what it do.

```python
# The interpreter will ignore this entire line
print('hello') # the interpreter will ignore from the '#'until the end of the line
print('world')
#this line will also be ignored
```
