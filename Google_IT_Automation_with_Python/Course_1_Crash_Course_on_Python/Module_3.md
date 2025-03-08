# MODULE 3 >>

# Review: What is a while loop?

This reading contains the code used in the instructional videos from [**What is a while loop?**](https://www.coursera.org/learn/python-crash-course/lecture/8xMRD/what-is-a-while-loop)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![Screenshot 2025-03-06 161153.png](<https://media-hosting.imagekit.io//aa683ad4c69e422d/Screenshot%202025-03-06%20161153.png?Expires=1835865724&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=YP8T~YshX7j3olQHtVLXMFotrZsPbWuPJczYVLRGMV-YIEZSIxVAefztMyKVbM-YSMxx4L664FdGRoGp6nLAy7~mrmCoXw87pPSxTACfSTXXYBuHMsoYmAA6l-pqrEyQ06c7q8fm9jVquD3hqGMGorZfXWC6Es2WVPpYpFxCeJi7q8SY3v97xF~iHXj5~04CHBbUeiK1bHlq4n5DV3y72l0BkQ5c8Gz5BC-E1NHN8QYuKTtakDqtxIFOM93ospntWZ58mxs3L4NjxmOXOg4BoXcmfspQ~wSrrFT1LAjWjkEsMkrWDsJqc34MdZnfIr1caGfI73wtnbgjDUYbG-q8rw__>)

# Anatomy of a While Loop

A *while* loop will continuously execute code depending on the value of a condition. It begins with the keyword *while,* followed by a comparison to be evaluated, then a colon. On the next line is the code block to be executed, indented to the right. Similar to an *if* statement, the code in the body will only be executed if the comparison is evaluated to be true. What sets a *while* loop apart, however, is that this code block will keep executing as long as the evaluation statement is true. Once the statement is no longer true, the loop exits and the next line of code will be executed.
# 
This reading contains the code used in the instructional videos from [**More while loop examples**](https://www.coursera.org/learn/python-crash-course/lecture/wXvhG/more-while-loop-examples)
## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. You will find additional information throughout the guide to explain the purpose of each concept covered, why the code is written in a certain way, and tips for running the code. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![Screenshot 2025-03-07 102819.png](<https://media-hosting.imagekit.io//4cbd1a8627294e86/Screenshot%202025-03-07%20102819.png?Expires=1835931580&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=cGnXf6I5~Ow49qom4PKf~lDvUqwwH4A0qfuy5Wk8nnVqy8-35oGhixnKacfVqk~bUcUgA7w3b1ChBwdSVg936-nXAoLbynhT7eiZukpa~mDwdS4uUaZ5DhrZD1gISvhRqFbrZERIvKuEtZ1wWzIT5GSbPJVTYdkwDhIatjzWTjuuZIVSbQ6vm-TfaD3ZkVjH80s~29PTcieK335HrQic6zk4TP6znRiX2eeaV7UQWc2UWxVGhFrCLrTLKL-MS2KBTjZRlQ7PBrkt6bjvItHzOjNY5KZVfoi13b6VA-V73l8m9ZHDH31cecZ1qw-ZTeBrlvmqKI52G0~T-ZvfAT8sfg__>)
## **About this code**

The username variable is assigned the value returned by the get_username() function. The while loop starts. The loop will continue to iterate as long as the value of the username variable is not valid. The print() function prints the message "Invalid username". The username variable is assigned the value returned by the get_username() function. The while loop ends.

The code you provided will give an error because the **valid_username()** function is not defined. The **while** loop will try to call the **valid_username()** function on line 3, but the function does not exist.
# Review: Why initializing variables matters

This reading contains the code used in the instructional videos from [**Why initializing variables matters**](https://www.coursera.org/learn/python-crash-course/lecture/oRAfO/why-initializing-variables-matters)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. You will find additional information throughout the guide to explain the purpose of each concept covered, why the code is written in a certain way, and tips for running the code. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![Screenshot 2025-03-07 104151.png](<https://media-hosting.imagekit.io//9da29eadd8c440b9/Screenshot%202025-03-07%20104151.png?Expires=1835932315&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=KhLrPBAXkrkl3G3RYUaLwGbJ4AbqWc6xmaRZpUiqWfyhMcBbc2~zzrt~dTV0LGbPzELEsZGxPP7Bli9makIeVdr~2bxYLsGsp1lp7LlNeFgWvR7AGKOrw5PgQsV5BPA~XcjbRaf7zT9IVE6KI7hq~n2ZbSbZaKQuE~Z2eArkKCOKD~tlFOt7oO68sNIt6lUFqD3NOaZY6KlW3td8KIeOtCrSjNuI6a3VaICUOM3cqtyWKS6ccN9zIpbhwlX2moynj6YTubYp~OrZaslbNBLUvt6KxlaoeNSWpw8Kpzh3~MQTRQuLIaK2U~hKEAUlg40eif918wJAo2Chmx0dZFYpdQ__>)
## About this code

This code contains an error in intent only; it will not give an error when the code is run. The problem here is that **x** needs to be reassigned back to **1**. In this code, **x** is never reassigned back to **1** before the second **while** loop, so **x** is equal to **10** from the previous operation. The second **while** loop thus never executes at all.
# Review: Infinite loops and how to break them

This reading contains the code used in the instructional videos from [**Infinite loops and how to break them**](https://www.coursera.org/learn/python-crash-course/lecture/qt7y9/infinite-loops-and-how-to-break-them).

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. You will find additional information throughout the guide to explain the purpose of each concept covered, why the code is written in a certain way, and tips for running the code. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![Screenshot 2025-03-07 105436.png](<https://media-hosting.imagekit.io//cc198f665bd74383/Screenshot%202025-03-07%20105436.png?Expires=1835933080&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=UUk3FB4y~MheriU1Vao3lpNLrAx8YP5Z~uRCSTY0MSTTKxjD0H5J-W1Ln57d2VUen4xZY0fwS8152-UDo-5-G3zaKeSx83HKZdTgoYBLKwtozEaX5an~OB2ySK4EKmERuERzsMVxowIJ11pm8l26bx0zkMdeceKyPf6BEoPtp0qqmA4Iul1Xos0GKd1OAwjC37BD10GYmQV2U218Z0KE20akMbhGHFgZEOECDFQIhtBCFIA7rSsxQLL1C-GIQq1NJYAbaXX7mGoTF16BP7Sz4477p26TNxA5GG2nHrHszrMOVXVWuJGumqRfwFBvapyG4BzEO5H5pMznVz7JQQKpng__>)
## About this code

This code block is an example snippet of code. In your code, you could have an infinite loop that looks something like this. In Python, we use the break keyword which you can see here to signal that the current loop should stop running. We can use it not only to stop infinite loops but also to stop a loop early if the code has already achieved what's needed.

# Study guide: while loops

This study guide provides a quick-reference summary of what you learned in this segment and serves as a guide for the upcoming practice quiz.

In the **while** loops segment, you learned about the logical structure and syntax of **while** loops. You also learned about the importance of initializing variables and how to resolve infinite **while** loops with the **break** keyword.

## **while** **loops**

A **while** loop executes the body of the loop while a specified condition remains **True**. They are commonly used when there’s an unknown number of operations to be performed, and a condition needs to be checked at each iteration.

Syntax:
![Screenshot 2025-03-08 232745.png](<https://media-hosting.imagekit.io//38eb829dd4c34018/Screenshot%202025-03-08%20232745.png?Expires=1836064784&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=dJzM4JUSqmx0n9rlhb4BvsqclhjhUA0B74UMQUZ9lDSkdEomtdLumm4Bb69NaGZ-VoeQGIufubLlPc~~fBi2~ki8oPW9eG5r4aq2yppSFaja70lRAnsPSN1CLkUtL3u0-MqMiLNzwit1MjSipo-Hrzzu6RWYg7NEu4RcLPgWtzUZzEbW7qDWPZIXy4ysduap4aAkF773tJCk-RPUIngGvmmXzUNJRgPD-4QG8yg3aYxzNPEJi6OElmmNHjNbdwa9jI4vkvnJ-Hh9x89F9-yf6CLB2zx43LGi3vlYBkJt9jgVNipe8Fo~9YY-M1WiUtTLro8Zv40Qae4gnoWc9CZULw__>)
Example while loop
![Screenshot 2025-03-08 233306.png](<https://media-hosting.imagekit.io//c8b77c8faba94bff/Screenshot%202025-03-08%20233306.png?Expires=1836064993&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=qt-Q2aBpS31mtxbM3C5nLuNY~e7LNYUQqgDpT1KwCFBWe9oBliw20I1Ll7BRjxaLsIKL55Y58oWzDq7Xx19Wxs06WIcANpvf6m-IZSDrF-3RolG5x6TRW72lahp8bDsXMM~F5bZ1rCMl-YySS7oUti~t6EAOD5wJ9eepTxZpRdgikuZGzF~DrEuO4fnUyZb4GhDlVUrpiRbKiPxpMlPFsaPY5RizUt94RLRMgJeEQmXUkeuv43W4VsZfREPTlnHcVtoRsXSG03ATlSwgC5aq2Pej8emHzMVClmnYUw8iOESsecn~KhXdCvWAbBERjIa8U0Bn1DIS6GSCX0zqAnPg9w__>)
## **Common errors in Loops**

If you get an error message on a loop or it appears to hang, your debugging checklist should include the following checks:

- **Failure to initialize variables**. Make sure all the variables used in the loop’s condition are initialized before the loop.
- **Unintended infinite loops**. Make sure that the body of the loop modifies the variables used in the condition, so that the loop will eventually end for all possible values of the variables. You can often prevent an infinite loop by using the break keyword or by adding end criteria to the condition part of the **while** loop.

## **Terms**

- **while loop** - Tells the computer to execute a set of instructions while a specified condition is **True**. In other words, **while** loops keep executing the same group of instructions until the condition becomes **False**.
- **infinite loop** - Missing a method for exiting the loop, causing the loop to run forever.
- **break** - A **break** statement in Python provides a way to exit out of a loop before the loop's condition is false. Once a break statement is encountered, the program's control flow jumps out of the loop and continues executing the code after the loop.
- **pass** - A **pass** statement in Python is a placeholder statement which is used when the syntax requires a statement, but you don't want to execute any code or command.

## **Math concepts on the practice quiz**

The coding problems on the upcoming practice quiz will involve a few math concepts. Don’t worry if you are rusty on math. You will have plenty of support with these concepts on the quiz. The following is a quick overview of the math terms you will encounter on the quiz:

- **prime numbers** Integers that have only two factors, which are the number itself multiplied by 1. The first ten prime numbers are 2, 3, 5, 7, 11, 13, 17, 19, 23 and 29. Each of these prime numbers can be evenly divided only by itself and 1.
- **prime factors** - Prime numbers that are factors of an integer. For example, the prime numbers 2 and 5 are the prime factors of the number 10 (2x5=10). The prime factors of an integer will not produce a remainder when used to divide that integer.
- **divisor** - A number (denominator) that is used to divide another number (numerator). For example, if the number 10 is divided by 5, the number 5 is the divisor.
- **sum of all divisors of a number** - The result of adding all of the divisors of a number together.
- **multiplication table** - An integer multiplied by a series of numbers and their results formatted as a table or a list. For example:

4x1=4

4x2=8

4x3=12

4x4=16

4x5=20

## **Coding skills**

The following are sample skill areas to study for **while** loops.

### Skill group 1

- Initialize a variable
- Use a **while** loop that runs while a specific condition is true
- Ensure the **while** loop will not be an infinite loop
- Increment a value within a **while** loop
- ![Screenshot 2025-03-08 233505.png](<https://media-hosting.imagekit.io//9f3fc8d086ef454a/Screenshot%202025-03-08%20233505.png?Expires=1836065109&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=SxEAPpJujKo5pujkASgd-IqpHvJ5LjUSbms1DjYvzAVbSFKDYn3K5jCC8bcG~NiyyT2GSYQgkL~ipkgFNJNmwmVmfL4OUQMMQ0zrdfW7qRKZ4r7MPdiUNFlwO8xBakyVBMs2~wO8Wxg8BxNvZ~WXPA89wU6vn643N26zOdLnuODPJ2WkdvqCPMz3-sGa7RjQQl-nLGBSL5wMpuzgBBUZZ3Vm2YXITLJGw4-ub6~N6CJ-c4SGFqSB4I5XBwfNcnRpQZHECNqRUFRl8JwtZslNdjTvq2718R4Gdagx-YJ3H5DWGbjWFdrIhDOKotLkbk-FGTWdkB-aI6ctVx6Qvtci4A__>)
### Skill group 2

- Initialize variables to assign data types before they are used in a **while** loop
- Use the **break** keyword as an exit point for a **while** loop
![Screenshot 2025-03-08 233636.png](<https://media-hosting.imagekit.io//96e7d45e8adb4577/Screenshot%202025-03-08%20233636.png?Expires=1836065205&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=I8yvy-c8GECAzdggRTFzVA~uCc4MQ1mEZ-se~f5yBlv3yJo22fd~ZlXaV133uurzJuoTf8sAnj3f2ShjCgs4--rSvvXHt-dxxA5VXBIyUZDKyjvHk2NoPT9xRqPTlcS8Hh5j~Lo~aHNpA1MmuiiM108tCU36170~--0KsWt7t1kk9EbtEtgZdG2l5d~TiIdtQ3d0~3hkgckDgUYgniAUVKutF8OyWqqhEtUGDKk-ApWs5uYOA04YbJmgiVwKttq3tvlrZx6jI1rsHSDD~rVQkgy7s7Hh0ThfLBkciLQrQg7reebOHi0kn7i6Oqwn8A~2JqgIBKDT61hv9sgyW13sFQ__>)
## **Python practice information**

For additional Python practice, the following links will take you to several popular online interpreters and codepads:

- [Welcome to Python](https://www.python.org/shell/)
- [Online Python Interpreter](https://www.onlinegdb.com/online_python_interpreter)
- [Create a new Repl](https://repl.it/languages/python3)
- [Online Python-3 Compiler (Interpreter)](https://www.tutorialspoint.com/execute_python3_online.php)
- [Compile Python 3 Online](https://rextester.com/l/python3_online_compiler)
- [Your Python Trinket](https://trinket.io/python3)
