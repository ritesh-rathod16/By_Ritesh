# Module 2 >>

# Explore Python syntax

Python is a flexible programming language used in a wide range of fields, including software development, machine learning, and data analysis. Python is one of the most popular programming languages for data professionals, so getting familiar with its fundamental syntax and semantics will be useful for your future career. In this reading, you will learn about Python’s syntax and semantics, as well as where to find resources to further your learning.

## The Language of Python

People use language to communicate and give instructions to each other. Computers do the same thing, except computers use languages like Python, C++, and Java. So, in order to communicate instructions to the computer, programmers need to arrange ideas and concepts into a language it will understand.

Python syntax includes words that represent objects and commands, as well as punctuation that gives the words structure, hierarchy, and context. Together, the words and punctuation communicate ideas and processes; this is known as semantics. Semantics is the meaning conveyed by the syntax. The best way to learn syntax and semantics is through exposure. Practice coding and become familiar and comfortable with reading other people’s code. In addition, there are some general conventions that practitioners use to help maintain stylistic uniformity within the language.

Coding languages are similar to spoken languages in that they have a way to classify words according to their function. For example, English sentences are composed of nouns, verbs, prepositions, etc. Here are some of the basics:

- **Variables:** Represent data stored as strings, tuples, dictionaries, lists, and objects (note: future readings explain these categories)
- **Keywords:** Special words that are reserved for specific purposes and that can only be used for those purposes

![image.png](attachment:7fd0b2f1-7894-4857-b2a7-56dde7a3b521:image.png)

• **Operators:** Symbols that perform operations on objects and values

![image.png](attachment:abf9af28-d581-4f66-a11e-e95e83cc1259:image.png)

- **Expressions:** A combination of numbers, symbols, and variables to compute and return a result upon evaluation
- **Functions:** A group of related statements to perform a task and return a value

![image.png](attachment:5066cab4-3405-4c3f-aee4-d6e6a95e6b56:image.png)

- **Conditional statements:** Sections of code that direct program execution based on specified conditions

![image.png](attachment:34ef9f0e-6394-487b-a953-f6f637c29c36:image.png)

As you’ll surely discover, Python generates syntax errors for incorrectly used keywords and syntax.

```
Example:

```

![image.png](attachment:aaa7b77d-dc25-41c6-814c-a8e61f9b488d:image.png)

## Naming rules and conventions

When assigning names to objects, programmers adhere to a set of rules and conventions which help to standardize code and make it more accessible to everyone. Here are some naming rules and conventions that you should know:

- Names cannot contain spaces.
- Names may be a mixture of upper and lower case characters.
- Names can’t start with a number but may contain numbers after the first character.
- Variable names and function names should be written in snake_case, which means that all letters are lowercase and words are separated using an underscore.
- Descriptive names are better than cryptic abbreviations because they help other programmers (and you) read and interpret your code. For example, student_name is better than sn. It may feel excessive when you write it, but when you return to your code you’ll find it much easier to understand.

Tim Peters, a Python programmer, wrote this now-famous “poem” of guiding principles for coding in Python:

## The Zen of Python

- Beautiful is better than ugly.

- Explicit is better than implicit.

- Simple is better than complex.

- Complex is better than complicated.

- Flat is better than nested.

- Sparse is better than dense.

- Readability counts.

- Special cases aren't special enough to break the rules.

- Although practicality beats purity.

- Errors should never pass silently.

- Unless explicitly silenced.

- In the face of ambiguity, refuse the temptation to guess.

- There should be one—and preferably only one—obvious way to do it.

- Although that way may not be obvious at first unless you're Dutch.

- Now is better than never.

- Although never is often better than *right* now.

- If the implementation is hard to explain, it's a bad idea.

- If the implementation is easy to explain, it may be a good idea.

- Namespaces are one honking great idea -- let's do more of those!

Finally, it’s helpful to bookmark the [PEP 8 Style Guide for Python](https://peps.python.org/pep-0008/) so you can reference it as needed. This reading is limited in scope, and PEP 8 is a more exhaustive resource for style-related matters. PEP stands for Python Enhancement Proposals. These are a running catalog of ways to improve or standardize Python as a language. Because Python is open source, PEP offers a framework to guide developers and build consensus around ideas. It’s a useful and trusted resource.

## Key takeaways

Syntax and semantics are what give form and meaning to a language, including Python.  A large part of learning a new language is familiarizing yourself with its syntax and semantics. Much of this comes through exposure and practice, but there are a few guiding principles and resources that can help you along the way. If you learn the rules about naming objects and build a bank of resources that you can reference for guidance, you’ll surely make progress as a Python learner. As you get more familiar with Python, you’ll be able to communicate more efficiently with computers and do more with your data analysis tools!

# Resources for more information

Here are a few useful resources to help you get more familiar with Python:

- Python [Reference Library](https://docs.python.org/3/library/)
    - [Built-in Data types](https://docs.python.org/3/library/stdtypes.html)
    - [Built-in functions](https://docs.python.org/3/library/functions.html#built-in-functions)
- [Python operators](https://python-reference.readthedocs.io/en/latest/docs/operators/index.html)

# Review: Data types

This reading contains the code used in the instructional videos from [**Data Types**](https://www.coursera.org/learn/python-crash-course/lecture/l2J1I/data-types)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.

![image.png](attachment:993da275-f79c-4abe-9e8f-253a5b0779e4:image.png)

![image.png](attachment:23a64afa-e6a6-43ec-9bb6-4c707d3e529d:image.png)

# Annotating Variables by Type

Type annotation allows you to clearly communicate the argument types and return type of functions in your code. It’s like giving yourself and other developers hints about what kind of data the variable is supposed to hold. This has several benefits: It reduces the chance of common mistakes, helps in documenting your code for others to reuse, and allows integrated development software (IDEs) and other tools to give you better feedback.

In this reading, you will learn more about annotating variables by type and best practices.

## How to annotate a variable

Think of annotating a variable as if you were to put a label on a container—and anything in that container should hold what the label is describing. Let’s take a look at an example:

name: **str = "Betty"**

The variable name is declared using a colon (:) which is annotated with the type **str**, indicating that the name variable should hold a string value. And look, it does! Betty—or any name for that matter—is a string, and we know it’s a string because it is in quotes. Let’s look at another example where a variable holds an integer value.

**age: int = 34**

In this example, **age** is the variable, and **int** is the type annotation that provides you and other developers a hint that the age variable should store an integer value.

**Pro tip:** If a function expects a list of integers, you should annotate it as **List[int]**, not just **List**. Being specific with your types can catch more potential bugs and misunderstandings.

## Dynamic typing

Many languages, such as C# or Java, require you to declare variable types, but not Python. One of the great things about Python is that the type of variable can change over time as new values are assigned to it. For example:

**a = 3                  #a is an integer**

**a = "Hello world"      #a is now a string**

Dynamic typing allows programmers to write code more quickly and offers flexibility because you don’t have to explicitly declare the type of variable.

**Note:** Python decides which of the built-in types the variable is and, therefore, how it should behave. For more information, refer to this article on [Built-in types](https://docs.python.org/3/library/stdtypes.html).

## Duck typing

This form of typing comes from the saying, “If it walks like a duck and quacks like a duck, it must be a duck.” Python will infer the variable type at runtime and decide which behaviors are available to the given object.

**a = "Hello world"      #looks like a string**

## Annotating variables with type comments

Another way to annotate variables is to use type comments where the interpreter will ignore the comments.

**captain = "Picard"      # type: str**

**Note:** This way of annotating variables might be useful for cases when you need to know what types belong to which variables but do not want the overhead of using a line interpreter (linter) or IDE on this specific variable.

## Annotating variables directly

Let’s use the same example above to annotate a variable directly.

**captain: str = "Picard"**

**Note:** You might hear annotating variables directly called the more “modern” way to annotate a variable.

Another advantage is that you can use automated tools such as linters, or mypy, to check types to make code more resilient. Most modern IDEs, such as VS Code and JetBrains PyCharm, scan code for type annotations and can use it to help you write better code more quickly!

## How type annotations affect runtime behavior

Any time a library is called, or an IDE works to scan your code, more computational overhead is required.

**Pro tip:** Be strategic when annotating variables by type. This can add unnecessary overhead when overused.

Type annotation is less common with Python users in data science, as it can be burdensome to manually map data every time a new set of data comes in. On the other hand, when doing object-oriented programming or writing functions, using type annotations becomes extremely important because it helps clarify code since you are dealing with more than just the built-in types.

## Key takeaways

Annotating variables by type provides programmers with benefits to make the code easier to read and understand. Python provides different options on how to annotate variables, so choose how you want to annotate them. Just be cautious of over-annotating, creating unnecessary overhead to your code.

## Resources for more information

- Python built-in types https://docs.python.org/3/library/stdtypes.html

# Review: Expressions, numbers, and type conversions

This reading contains the code used in the instructional videos from [**Expressions, numbers, and type conversions**](https://www.coursera.org/learn/python-crash-course/lecture/dKIr2/expressions-numbers-and-type-conversions)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.

![image.png](attachment:906e0c54-c709-4d21-8610-57de89c0f8d4:image.png)

# Implicit vs explicit conversion

As we saw earlier in the video, some data types can be mixed and matched due to implicit conversion. Implicit conversion is where the interpreter helps us out and automatically converts one data type into another, without having to explicitly tell it to do so.

By contrast, explicit conversion is where we manually convert from one data type to another by calling the relevant function for the data type we want to convert to. We used this in our video example when we wanted to print a number alongside some text. Before we could do that, we needed to call the *str()* function to convert the number into a string. Once the number was explicitly converted to a string, we could join it with the rest of our textual string and print the result.

# Study guide: Expressions and variables

This study guide provides a quick-reference summary of what you learned in this lesson and serves as a guide for the upcoming practice quiz.

In the Expressions and Variables segment, you learned about expressions, variables, and the data types: string, integer, and float. You learned how to convert a value from one data type to another and you learned how to resolve a few common errors in Python.

## **Terms**

- **expression** - a combination of numbers, symbols, or other values that produce a result when evaluated
- **data types** - classes of data (e.g., string, int, float, Boolean, etc.), which include the properties and behaviors of instances of the data type (variables)
- **variable** - an instance of a data type class, represented by a unique name within the code, that stores changeable values of the specific data type
- **implicit conversion** - when the Python interpreter automatically converts one data type to another
- **explicit conversion** - when code is written to manually convert one data type to another using a data type conversion function:
    - **str()** - converts a value (often numeric) to a **string** data type
    - **int()** converts a value (usually a float) to an **integer** data type
    - **float()** - converts a value (usually an integer) to a **float** data type

## **Variables Annotated by Type**

Type annotations are optional in Python. They can be very helpful, though, because they make code easier to read. Annotations make the variable types clear to those reading the code. They can also help you catch errors during compilation. In the example below, we are using the typing module to annotate the different types of variables.

![image.png](attachment:319a10fe-a9d2-41f3-a54a-50b1ab318767:image.png)

## **Coding skills**

### **Skill Group 1**

- Use variables to store values
- Use basic arithmetic operators with variables to create expressions
- Use explicit conversion to change a data type from float to string

![image.png](attachment:a77e396b-2865-4fc6-b99a-7219b7ac7996:image.png)

### **Skill Group 2**

- Output multiple string variables on a single line to form a sentence
- Use the plus (+) connector or a comma to connect strings in a **print()** function
- Create spaces between variables in a **print()** function

![image.png](attachment:f991a5c5-26b5-4c27-8fa8-c67f0b209fa8:image.png)

### **Skill Group 3**

- Resolve TypeError caused by a data type mismatch issue
- Use an explicit conversion function

![image.png](attachment:9f095c80-4f16-46e6-a67e-04916897322e:image.png)

### **Skill Group 4**

- Resolve a ZeroDivisionError caused by an attempt to divide by 0

![image.png](attachment:c39aae11-7dc7-48d7-b02a-6ec0f187f49a:image.png)

## **Python practice information**

For additional Python practice, the following links will take you to several popular online interpreters and codepads:

- [Welcome to Python](https://www.python.org/shell/)
- [Online Python Interpreter](https://www.onlinegdb.com/online_python_interpreter)
- [Create a new Repl](https://repl.it/languages/python3)
- [Online Python-3 Compiler (Interpreter)](https://www.tutorialspoint.com/execute_python3_online.php)
- [Compile Python 3 Online](https://rextester.com/l/python3_online_compiler)
- [Your Python Trinket](https://trinket.io/python3)

# Review: Defining functions

This reading contains the code used in the instructional videos from [**Defining functions.**](https://www.coursera.org/learn/python-crash-course/lecture/Jzoz1/defining-functions)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
