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

# Review: What is a for loop?

This reading contains the code used in the instructional videos from [**What is a for loop?**](https://www.coursera.org/learn/python-crash-course/lecture/C9zN4/what-is-a-for-loop)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![Screenshot 2025-03-09 120954.png](<https://media-hosting.imagekit.io//f0980c3831354106/Screenshot%202025-03-09%20120954.png?Expires=1836110402&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=ly3bJoTA~iyuAzKMrFMjKsLYI4UlLao8~~GFjKtBnQiJB9X2EBHUB7NEl2Kbpx-1bSCuno2dKHT5kdTCwMoAyehZ49m4Q~1rcgQK6SaLuLVuBZgVyQW86drUUeGwNyuYsDjaAQn6kDm9mwMLjOWJXjWdXYV77ot3SJR8jYBJb1eF3rZJtS~5np3JFeZfqGUK-7kI9ucDPMz00QtNdc~tSx4BqCycekv4qF4EJjg3qXfRsWasObC5vVjv0R6hDdenKZ5R1XuQiXuqqWPBZlSviqVBYJygCM68VmgGwzWpOEt6oC1kg0-B3boKaDTrEcdwekE9L8x-9XA1mOoKu4LCYQ__>)
# Review: More for loops examples

This reading contains the code used in the instructional videos from [**More for loops examples**](https://www.coursera.org/learn/google-beginning-your-python-journey/lecture/00vRH/more-for-loop-examples)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![Screenshot 2025-03-09 121557.png](<https://media-hosting.imagekit.io//2afd0548242d495a/Screenshot%202025-03-09%20121557.png?Expires=1836110761&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=Af4QW34kQfiqJLH9fZcW1EQgh30y0kDuRthp382SK4R0iC~sBJqKHaENdPbhPZfimP5bHO7hRF4UTInx-BvG9Oaq11liYb2sSXX7hbQ6lDg7SGzzD8YvMdh1tXT0CQRK2uWcvjYfx1VBD6AqJa7PYDG2FcNa~9hfe3AjdDbtC63lkNMCTHC~ghUhMeT6JDR1AOquEs-WZnsiIdMjXYTLmZfCdcfO-L~wgF3RNL74SKhFdfdK4bnQjO71NcjqwodVyN8g2bxBIKx87mrb9Aqq1cCM~syij8GOeA3bqh7m3fo9YRVJYRK-eg-IYHnTmAsDEg0GloOm1SSm2FCHUNTIDA__>)
## About this code

This code first defines a variable product and initializes it to 1. Then, it uses a for loop to iterate over the range of numbers from 1 to 9. In each iteration of the loop, the variable n is assigned the current number in the range. The code then multiplies product by n. This means that after the first iteration, product will be equal to 1 * 1 = 1. After the second iteration, product will be equal to 1 * 2 = 2. And so on.

The loop will terminate when the value of n is 9. At this point, the value of product will be 1 * 2 * 3 * ... * 9 = 362880.
![Screenshot 2025-03-09 121802.png](<https://media-hosting.imagekit.io//f3f15998d8804480/Screenshot%202025-03-09%20121802.png?Expires=1836110891&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=fJDxF-XO6KAE7yRZsTMwtZfTzBW9Qltt-qKgvKt7aCCCrlJbHLHIKTtZaBz~4VgxM-Q5asn3eU~YLHFHzUTLOKrBs78t~cW920Cu3AUeKXSZjy5rcBo9z1Ou9aNMA1DXXIoSroHJqOyFZ2pLwy1tQd2h~G8NK0~vTzMpgTRyR7xRjOfUNL04p7ny~aLy2htMAgiIv4Udnm2wLqt-mdoaq-3F~Av8AhPXsac-xC82QLRrEPZIqLZ8WQsK3jCIPZnkMZD--Di1Zf5AQQDpD6YRS0pAka4J6NGduSCEX4blHFuWPapmVa0LBE3Dn4JCFvOdVy96MR8uKqZo~QYcjerBcA__>)
# A Closer Look at the Range() Function

The **in** keyword, when used with the **range()** function, generates a sequence of integer numbers, which can be used with a **for** loop to control the start point, the end point, and the incremental values of the loop.

**Syntax:**
![Screenshot 2025-03-09 122426.png](<https://media-hosting.imagekit.io//1eb331552ef04610/Screenshot%202025-03-09%20122426.png?Expires=1836111267&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=qJ-hp3rSSGX4WiDp1uL4KkweRgiOnQsiWm~fWpwITKA7BKS~5Ux8xUM5LIuiCAiB2tRC2SP3ZNmcJ3ZczEqRSA~ByGriskIlflTerir9R9PvQVr4kZEhPi7JBJWnlXQZ3SnfJ7G345gl~NJUBvLNHlXG~iVFdXfHNulCJbnBeSNsDWYiXYztFtnhXTJY-PUQzHXFjJ50y6w00vCcJ4Ud399opuAzY2OWPRI98gKv-tGZOtyZZjAJcml4rqseJEsnf1oX0l78JT1MIl0H2jhdkxKRpS7g1Dc6JvC8ytK6lxhyBkmkpVBqCwrtUHcQ9Cs4t7q3IHzzyguBV~3H9JHKEA__>)
The range() function uses a set of indices that point to integer values, which start at the number 0. The numeric values 0, 1, 2, 3, 4 correlate to ordinal index positions 1st, 2nd, 3rd, 4th, 5th. So, when a range call to the 5th index position is made using range(5) the index is pointing to the numeric value of 4.
![Screenshot 2025-03-09 122531.png](<https://media-hosting.imagekit.io//d650f6e156304f32/Screenshot%202025-03-09%20122531.png?Expires=1836111332&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=e2wqB4ta54D5KlDGDBtGTYxrEXd2OI5duyEXsmafgbtDxB6OPT9qsj0usqWoVWVPuuNgRJdUgffW71NFPFkcBVJAK1D3GLw8xHaPZ3mFGjHw8UXYJm0aN58E8wNCT~46hBUoJCGwmVcqCGxuE9CYnAvpr~o05TwIIubjzRwGYaTxqOxvmCcuHQSR-4vINltCWsFmYzU5icRQC1ADrMzPIIJHobvrS14XYcWY8Ai0mvyiR~O7sbjFVVDgTn9Xzb016DQHZVclohGLVvMosEDx04rlGDhl5C4Bp0FNqUzI9NhhHfREaU1z0K6SSzbAZzNv2oanqiIXmJlilDBuNSpBUA__>)
The **range()** function can take up to three parameters:  **range(start, stop, step)**

**Start** 
The first item in the **range()** function parameters is the starting position of the range. The default is the first index position, which points to the numeric value 0. This value is included in the range.

**Stop**
The second item in the **range()** function parameters is the ending position of the range. There is no default index position, so this index number must be given to the **range()** parameters. For example, the line **for n in range(4)** will loop 4 times with the **n** variable starting at 0 and looping 4 index positions: 0, 1, 2, 3. As you can see, **range(4)** (meaning index position 4) ends at the numeric value 3. In Python, this structure may be phrased as “the end-of-range value is *excluded* from the range.” In order to include the value 4 in  **range(4)**, the syntax can be written as **range(4+1)** or **range(5)**. Both of these ranges will produce the numeric values 0, 1, 2, 3, 4.

**Step**
The third item in the **range()** function parameters is the incremental step value. The default increment is +1. The default value can be overridden with any valid increment. However, note that the loop will still end at the end-of-range index position, regardless of the incremental value. For example, if you have a loop with the range: **for n in range(1, 5, 6)**, the range will only produce the numeric value 1. This is because the incremental value of 6 exceeded the ending point of the range.

## Practice Exercise

You can use the code block below to test the values of **n** with various **range()** parameters. A few suggestions to test are:

**range(stop)**

- range(3)
- range(3+1)

**range(start, stop)**

- range(2, 6)
- range(5,10+1)

**range(start, stop, step)**

- range(4, 15+1, 2)
- range(2*2, 25, 3+2)
- range(10, 0, -2)
![Screenshot 2025-03-09 122945.png](<https://media-hosting.imagekit.io//bc863f5333ca44df/Screenshot%202025-03-09%20122945.png?Expires=1836111589&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=pwng8Tp-X-UC6r4Ddx2fGQt6W0vVuZTbmYNy8IG0HSDzRwPbeknPvmAFMarN5c80Ruw8zKJejSIeWAGAwhpwFx3EZiK-F6UjwYy7oCbegABaRdVz8Nyp7x7Vk2OpCl8SJhl-58HxH1CMBhtQlA76zS6b4-TERtus5l3uQVWiV~EGyvsWaC4otBsD9w6EnpqYwfMQ-BX3d0Gssa94q9WMb6PRGCeetzR0xsMWQNgetyWGel9ZU4~DFmT~qV2FZYY22zqAPo~s~r6rwNp6ERdQd7ABpZRKzrWI3-5yLuRfe110UFGPX9lvcKQRIqzJedQLlJuYeThB1X0Lou~LJX16Gw__>)
## Examples of the range() function in code:

**Example 1**
![Screenshot 2025-03-09 123043.png](<https://media-hosting.imagekit.io//932934ca14d247ed/Screenshot%202025-03-09%20123043.png?Expires=1836111644&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=vuOmk9j9KxmNY5d8-G1ziuLIRrTfNNiyAQ7YTTgOFDhsCqfIO6sqBbDRI66zoHDmcqu4ZAgtlBh4laclTwCUWhAXNLX8YEEdQ6Aw5S5R4Q8JKYaesZcp4wpZChD4nuIStDX3ao-rw5YR~IWja7lxKhofho2nKDFC5m0w~kBDlFYyl9MccURKcIpRQEpo~G5~N3DYcz2JXwi5CA-Y9yYCu-Dyk77CFWNEVthLsQjCQsCP5NxSXbqZ7KInkgNwGgzi6PL2HGmHDsIIC0TlJuloMqUl3vL4rPhlyDet9WTByvSL8rUXxwBoK9ZBTRpFi7OP4EfSJEeSEDeUomeWSCIA9A__>)
 **Example 2**
 ![Screenshot 2025-03-09 123244.png](<https://media-hosting.imagekit.io//ab7f1f946ef246da/Screenshot%202025-03-09%20123244.png?Expires=1836111769&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=cQxB60MVlbcuDmZ9FonpX6pBapYkotN1RcrPnxojwoQnJLLEkbxZtIKVRWmPmnuLg9UhCK6htT3dbM3iQLxJwnjLwM5Ty2fekEC~pFbW3Gf5vilh9cZeDJStCR3AnzC~TfxC4CoRMu8liW2jeGbf41UTXchJrK-mhyXqhFFr1~LzqEAgIPFhtmOlPx0s1mJ5nL~OabVB5UDdKGs~HPCGvoRsN-dO6Otj409nfT79h7L~MeyYZQ0Z4OlTjjqyQHaJqWPF0r5RiAKJowzUnzjAnvCdOpNgetyliRmR0i4faVU4CGzoiYxCadxMUNCIN6uPiTXPXJnRLWrXgPql7ulUaw__>)
 **Example 3**
 ![Screenshot 2025-03-09 123403.png](<https://media-hosting.imagekit.io//77fec9b47b1146e0/Screenshot%202025-03-09%20123403.png?Expires=1836111845&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=B2jtPV-fGVuL-G5PwAvK25NpulHo251e2ZsbSfeK2T9K-9bKrKt9bsjV~4LQ4z~O3wesE7byveRHp6hSd5sPI4ytVQHNf~ycZOanDrd986HtAwJw82cT41TfRgYq7xR-rPxVI64PdRzzY3w8W0na4p3pv2OC27dLWFjupTPC92EKRO-p-UD0KwKJnuoFGqEnze5h69FrjXkwfcbNqdH84Pq70dWk5rgNpRjXfEOuPs7Y3WPAsuZoELUseZ0j9lAcqdVMNjPpKk~vBkDB6klDNwp37p3N-DEOeu7~oCfrEf~YfPz4sG~BLDtcUJVP8D0oXE4hTw6mZxH-9K6x3gwy~w__>)
 # Key takeaways

The roles of the **range(start, stop, step)** function parameters are:

- **Start** - Beginning of range
    - value included in range
    - default = 0
- **Stop** - End of range
    - value excluded from range (to include, use stop+1)
    - no default
    - must provide the ending index number
- **Step** Incremental value
    - default = 1

# Resources for more information

- [Python range() function](https://www.geeksforgeeks.org/python-range-function/) - This site provides some helpful visualizations for the range index positions. It also offers multiple **for** x **in** **range()** examples and practice exercises.

For additional Python practice, the following links will take you to several popular online interpreters and codepads:

- [Welcome to Python](https://www.python.org/shell/)
- [Online Python Interpreter](https://www.onlinegdb.com/online_python_interpreter)
- [Create a new Repl](https://repl.it/languages/python3)
- [Online Python-3 Compiler (Interpreter)](https://www.tutorialspoint.com/execute_python3_online.php)
- [Compile Python 3 Online](https://rextester.com/l/python3_online_compiler)
- [Your Python Trinket](https://trinket.io/python3)
- # Review: Nested for loops

This reading contains the code used in the instructional videos from [**Nested for loops**](https://www.coursera.org/learn/python-crash-course/lecture/f7w6D/nested-for-loops)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![Screenshot 2025-03-09 124047.png](<https://media-hosting.imagekit.io//131ce00be431403d/Screenshot%202025-03-09%20124047.png?Expires=1836112250&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=d~~FaBTeAPLxWNh0qXBPuDocoAUaFw6kf-H~8r0xRIR6xXk6y9zTnnY-QzgBZSu2cmy9D2yzqW6TDK~SxHAFm0QL2SJTGqA73rRM7MGRigIyt~Oc2laYjiYhGifr9TJSIew6dUt9rA6hhkiCYFiplEBcB7pMiHn329WsNnpXd1VXQrS5YFOmVB8Na2aDezqrc5srqLpSBvCZ-uNuq9GMVUjy7Z3dz3Cq314I5RI1iHE-hwvTWv~g13sZRXXaEZodQHvjhwuzcm2-W4r7W932TuFWxm6pkx0FQ1vsRkxLnEvDJK5izXMQHjR9SpjbGKepfS7osi39dqMF~8gkgbPSZA__>)
# Strings and for loops

Over the past few modules we’ve been talking about using loops and their syntax in Python. As you have seen, a loop is an instruction that repeats multiple times as long as the condition set forth in the loop is met. You use loops to repeat a block of code. For example, if you want to send users an invitation, asking them to subscribe every time they open a new project, you would use a loop.

In this reading, you will learn the basics about **for** loops and how you can use them with strings.

## **For** **Loop Recap**

As a reminder, **for** loops enable you to iterate over a sequence of values, such as numbers, names, or lines in a file. You can even iterate over a list of strings.

## **What are strings?**

At the beginning of this course we identified strings as one of the basic data types used by Python and other programming languages. Strings represent a sequence of characters and are often used to display output to the user.

You can recognize a string because it’s surrounded by single or double quotes like the following examples:

"Hello world."

‘Ostriches can’t fly.’

"567.89"

**Pro tip**: You can’t mix single and double quotes in the same string or you’ll get a syntax error.

**Note**: In the examples above, Python does not consider “567.89” a number. It is a string because it is surrounded by quotes.

## **Using** **for** **loops with strings**

In an earlier video, you learned that a **for** loop iterates over the items in a collection until each item in the collection has been looped over.

**Pro tip:** Every **for** loop can also be written as a while loop.

Let’s see what that looks like. In the example below, we’re using a **for** loop to print out the characters in the string “Hello.”

**>>> greeting = "Hello"**

**>>> for c in greeting:**

**>>>   print("The next character is: ", c)**

**The next character is: H**

**The next character is: e**

**The next character is: l**

**The next character is: l**

**The next character is: o**

Notice that the **for** loop will stop iterating after the “o” is printed. You can also use **for** loops with Python’s **range ()** function to generate a series of numbers, which you can see in the following example:

**>>> for i in range(0, 3):**

**>>>   print("The next value is:", i)**

**The next value is 0**

**The next value is 1**

**The next value is 2**

Practically every Python script you write will use strings, which we’ll talk about in more detail in Module 4. For now, it’s enough for you to know that they are immutable. In other words, once you create a string, it can’t be changed. But you can use **for** loops to create a new string.

You can use **for** loops with strings to perform tasks and functions such as:

- Reading text from a file
- Searching for a value or specific data in a document or spreadsheet

**Pro tip:**  If you modify or update a collection of items you are using with a **for** loop, make sure you modify your **for** loop as well.

## **Key takeaways**

The real power of **for** loops is that they allow you to repeat sequences of any kind of data, not just a range of numbers or letters. They can help you find and use data faster. Over the next several videos and readings, you’ll get a chance to see what else you can do with loops and strings.
# Looping over a String

Looping over a string allows programmers to examine each character within a string individually, gather information about its occurrences, and perform a given operation. There are multiple ways to loop over a string—some ways are more beneficial than others—and which one you choose depends on the information you need.

In this reading, you will learn about looping over a string, how to do it, and see some examples along the way.

## **Looping over a string**

To loop over a string means to start with the first character in a string and iterate over each character until the end of the string. Strings are objects that contain a sequence of single-character strings. Yes, a single letter is classified as a string in Python. For example, **string[0]** is considered a string even though it is just a single character.

**Note**: Python does not use characters as a type like other programming languages do; it just supports strings with a length of 1.

### **for** **Loop**

The most direct—and common—way to loop over a string is to use the **for** loop. Let’s look at an example:
![Screenshot 2025-03-09 125354.png](<https://media-hosting.imagekit.io//cfa3f76aa6d54acb/Screenshot%202025-03-09%20125354.png?Expires=1836113037&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=nRHX3MsrOMDtYwQJreC3OGzKr9u0rCu6AOp7I1sVaTsIs8aM2zoQlulOYqF3HlUFtEI-MJ3AkaKFGsjPoJK3f9C~i0i6A~Wk6AuoFWGWupad4rMxF9ihR3aRlaR66Nles-VixHuMty1jTHn4C5kZlJWNodj5YyFycQoQoqwfNphkxUZaEoEBOz1hKHhdSEkBzA9-Wxc3j2Lq-sCcE9BCHWwPjpefMHQ0KxM9toIEiDgxOVdEhawImurWwMpMxjexIfcFUtj36cCgddAvntj~r~F4Vds1tRiJ32E9y9fP~ZfeCgFo7ze84iWAP3LlNzpLHygqrTZeEWxCxXcn-9pMzg__>)
Notice that **greeting** is defined as the string **'Hello'**. The loop begins with **char = 0**, which is the first element in the string. It directly calls the elements of the string and prints each element on a new line, resulting in the output below:

**H**

**e**

**l**

**l**

**o**

What if you don’t want the elements of the string but the position of the string instead? You’re in luck because Python can work that magic too
![Screenshot 2025-03-09 125535.png](<https://media-hosting.imagekit.io//b7ae40571b784259/Screenshot%202025-03-09%20125535.png?Expires=1836113137&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=A7xTr6yKhI2UX9l6DQsDobsMSFOr8e8pSu7xCzJOCXdD4TUgy95pezgmqYW5DHHcLFDlbkgcqNEqxrlI9Lonj~Ot~UorsWbm~GjxDHX41WiQG7TbseZf7znbe2dLJNLN1onckPbbZsGxqYLvsQJseDXsII3ha9Zj37-05MU5styPyGS~dS~fJFT3X~qhYEDuEZDyZYH5D0T97pv0tKy45dIV4HvKKflKL8GfnIc1NFW4KZ-~FXgyUyr-m~APDozbGNju1BcYgJaaQ2D2~MVXm-Nm8CrWo4TwFR~F0qSVl5~EwXCtNQzH34Hn4rCKTsZpx7HgvlRkrnAWFsW1V2sDGQ__>)
**len(greeting)** is an integer that tells Python how many characters are in the string. But because it’s an integer, you need to convert it to an iterable sequence by using the **range()** function. This loop does the same thing as the loop above, but instead of printing elements, it prints integers resulting in the output below:

**0**

**1**

**2**

**3**

**4**

### **while** **loop with indexing**

This **while** loop is the more “common” **while** loop that programmers often use. This type of loop involves an index variable to represent the current position within the sequence. Most of the time, this will start with 0 for the initial iteration. Let’s take a look at an example:
![Screenshot 2025-03-09 125843.png](<https://media-hosting.imagekit.io//457c7f23135a47f4/Screenshot%202025-03-09%20125843.png?Expires=1836113326&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=0KPR4b9c4Qz66DaZwVxw6SdyJTDSurcsaG-CaVlLaunnYbQtVH0sL88XYRYqEMP2EzsVpCQjwUuOp9nJkLXCzE4F-SKV10ysDHlam9ofXc5EgmLCWOjxG6NPFXYD6cRPCGwfR74BkHMc6l1dNMSTqnb4nszJsgdFf0mnqhyva~HM-AyMSXQhFdpSap6K4GAS0Fqfs3P3vd8vxgGAu6KnhkSmkrVWVfCtMiyMr1MwcHEAg7QqLTcTLX7Uqs-KiYnIQsLzJWJiGVNmfQe5SfSvltoplc4bNW2qniJ-abagsp2txDyc7XyVMZ5U9~KDlAIm7zUloICTGDFZseRig6f1Fg__>)
The initial index value is 0, and the **while** loop continues to execute as long as the index variable is less than the length of the **len(greeting)**. At each iteration, Python prints the value at the current index position **(greeting[index])**. Then, Python increments the index by 1 **(index += 1)** to move to the next position. The output of this example is:

**H**

**e**

**l**

**l**

**o**

**Pro Tip:** In any **while** loop, you can add conditional statements and stop the iteration process early so that the loop does not examine every character.

### **while** **loop with slicing**

Using a **while** loop with slicing accomplishes the same thing that a **while** loop with indexing does—like the example you explored above—this is just another way to write a **while** loop. You use this **while** loop in combination with string slicing to iterate over a portion of a sequence. Remember, it’s up to you to choose the method for looping over a string based on your level of comfort. There are multiple ways to write lines of code to execute the same result. Let’s explore how a **while** loop with slicing results in the same output.
![Screenshot 2025-03-09 125843.png](<https://media-hosting.imagekit.io//457c7f23135a47f4/Screenshot%202025-03-09%20125843.png?Expires=1836113326&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=0KPR4b9c4Qz66DaZwVxw6SdyJTDSurcsaG-CaVlLaunnYbQtVH0sL88XYRYqEMP2EzsVpCQjwUuOp9nJkLXCzE4F-SKV10ysDHlam9ofXc5EgmLCWOjxG6NPFXYD6cRPCGwfR74BkHMc6l1dNMSTqnb4nszJsgdFf0mnqhyva~HM-AyMSXQhFdpSap6K4GAS0Fqfs3P3vd8vxgGAu6KnhkSmkrVWVfCtMiyMr1MwcHEAg7QqLTcTLX7Uqs-KiYnIQsLzJWJiGVNmfQe5SfSvltoplc4bNW2qniJ-abagsp2txDyc7XyVMZ5U9~KDlAIm7zUloICTGDFZseRig6f1Fg__>)
This **while** loop continues to run as long as the index variable is less than the length of the string, which is determined by using **len(greeting)**. With each iteration, a substring of length 1 is extracted using **(greeting[index:index+1])** and printed. Then, the index is incremented by 1 **(index += 1)** to move to the next position. The output is:

**H**

**e**

**l**

**l**

**o**

### **List comprehensions**

List comprehensions are a concise way to create lists in Python. Let’s look at an example:
![Screenshot 2025-03-09 130041.png](<https://media-hosting.imagekit.io//900da89983b94def/Screenshot%202025-03-09%20130041.png?Expires=1836113442&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=2j~xfVSTSTx54ByAmwnZX~VkjKrRNjmpMM1f1DwKFafO8orBmF4VxFuUePobjVfzmwsmc9A35X6w6mYVu5czQUrUn3o6xyYfyhX9Vw1zwvyKUo6jx0dhbfu4ETYOqaadx1LYFwv9BF~UOynbvSwlZmvrxHFtnlMLzKazCn9DfvgvHiPzU3pv~1CaBDEh9puTfXPCf4-ixlHoi8DWSrNfSlfL4WDpmkAoVHgo3KC6UC9a8Clhy8aj0XLdPwZtiHW0YlDyBeaewa77LBwV8WBq-d6kw~-tkooXLSlzsxkK6s6QRvtK2A0hLkWqfg6EBKSuUuU3cLEdLBc2cG5DroUJ6A__>)
This example starts with a list of numbers. The second line of code defines the type of transformation you want to execute on each element in the original list. In this case, you’re using this line of code to create a new list called **squared_numbers** and apply **x ** 2** to square each element in the **numbers** list. The result of each squared element is then printed in a new list:

**[1, 4, 9, 16, 25]**

**Note:** List comprehensions can include conditional statements and nested loops, which allows for additional filtering of elements based on specific called conditions.

## **Additional advanced string loop techniques**

There are additional ways to loop over a string in Python that you should learn, practice, and master. These additional looping techniques include the generator functions, **map()**,  and **zip()**. The **map()** and **zip()** functions are extremely powerful string manipulation tools that demonstrate functional programming concepts. To learn more about these advanced techniques, see these resources:

- [Python - map() function](https://www.tutorialsteacher.com/python/python-map-function)
- [Python zip() method](https://www.tutorialsteacher.com/python/zip-method)

**Pro Tip:**  Looping over multiple strings at once can push the limits of **for** loops. Because of this, it’s important to be aware of other alternatives to simplify a **for** or **while** loop.

## **Key takeaways**

When you loop over a string, you are able to examine each individual element in the string and manipulate it how you’d like. A **for** loop iterates over each element, and a **while** loop allows you to add conditional statements and stop the iteration process early. As you saw in this reading, there are a variety of methods to loop over a string. It’s up to you to familiarize yourself with each technique and write code according to the advantages and disadvantages of each.
# Slice and Join Strings

You’ve been learning all about strings. Now it’s time to learn how to extract parts of a string—what we call “slicing” a string—or create a longer string by joining two or more strings together.

Slicing a string is just like taking a slice out of a homemade apple pie. When it comes to strings, slices can be as small or as big as you want. If you want to put two or more of those slices back together, you join them together end-to-end—in Python speak, you “concatenate” them—to make one bigger, single string.

In this reading, you will learn when to slice and join strings, how to do it, and see some examples along the way.

## **What is slicing and joining strings?**

When you **slice** a string, you extract a subset of the original string—sometimes referred to as indexing a string. **Joining** strings is the process of linking two or more strings together to create a bigger string.

## **How to slice strings**

Bracket notation, **[ ]**, is used to specify the start of the index, ending index, or both. If you do not include the starting index, then the slice contains everything from the beginning of the string to the ending index. This is the same if you do not include the ending index. Let’s look at a couple of examples:

**Pro tip:** Remember that the indexes in Python start with 0, and not 1.
![Screenshot 2025-03-09 130604.png](<https://media-hosting.imagekit.io//9e30deda2cdf46b4/Screenshot%202025-03-09%20130604.png?Expires=1836113768&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=pvQZmgb4Bg00Q8GtViJ2CIyfBfoICEVCrX6r2BGneGt9NsnWxU62IItisDiH9~yrkysOZmj0Zs6Glt96N2tuGuA6x3ZkqjwCobnDYAmxENP5-0KennwGQ6Y54xMWAwvOrznsMzj2FJmqnBu0Y5nO13uL4lYZfgEeyUcplvjiB4Np0kXrsR5mIFFOwMv-wQQVtAz1OxjdJtq3ubKwMHshJE0OYxeUWZKOO-XMy8C0llk54PNXiue838mnEBEkcr3vK0wXSdy0Q5-uJdBfq5md9EQ~HDzQpzTWo3gzXTLBGHpsJgEA~IIUXwIx5ZYwR12NYl7Zb9L2zhLgTZMfxlFvHA__>)
**Note:** When you specify an ending index, Python slices everything up to, but not including the ending index. Notice in the second example the ending index is 8, but the characters sliced are 4–7.

If your index is negative, Python counts back from the end of the string instead of the beginning.
![Screenshot 2025-03-09 130852.png](<https://media-hosting.imagekit.io//7652f5405118414d/Screenshot%202025-03-09%20130852.png?Expires=1836113951&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=nz6sjtHPkE6sU84SSX1WNaVlithocklXqrCQtg70qFqFHc6OnxJUe-VfmrY-4C6L4LyyhOSSMztpuvBn-sGDhiJcIgvsiyWr4DugMNKUphw3Pj7oscge6d7Nh0JfTrKrAqUED2bHfR67gQB7tdUgEcEIIcK9vXVKts9cGNC1C03xYPTF4s67navRTEofBkkPBeaCHvaBoBhE3ISPV0kwf6QKUJ-r1XL7i-MlAdfUncYt7r8Y4qyegdrgR097U~qHC02Wi~sJJll7yKARp0jgHZILkhJk1CmpMWG6wUGw8NVBP8259q7ngCtcVeXY-lqnB3r0ttHQm4LZfuCIqrrnxg__>)
If your index is beyond the end of the string, Python returns an empty string.
 ![Screenshot 2025-03-09 130907.png](<https://media-hosting.imagekit.io//e0e06ff4234c44b1/Screenshot%202025-03-09%20130907.png?Expires=1836113951&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=xfB-JVocJLMtnUxBqmqhx7bsf-heaDvFcWSf4ynU-ogH8ObYy7O5G9lT6kFidm5~TiZihLNjLzaRq5qM4HYW9QfSbSnt2eFsRN7J-rrfMTUdjr6bAhSnFT6L4a7utx3cf33iwAEhhmkmIDAaAAdeYBYJZjg3KfKc7FYBReA2Rt4GnxVCJFz2PfDGlR8I2tM81rXjnmTcwkfyL01r-VrxgSOoQOUlaVgMd6LPM~qGh79WV9fRfOj3r1YDhKKg6gmkVUV1~aE0L-Qcet20DpUJBCGX4~Qe9ToQpbHqCbZDh6-1aM-IVWe5mTWw5zpSnQ05h3z1LcgHbjq~frtJIQ6jOA__>)
 An optional way to slice an index is by the stride argument, indicated by using a double colon. This allows you to skip over the corresponding number of characters in your index, or if you’re using a negative stride, the string prints backwards.
 ![Screenshot 2025-03-09 131154.png](<https://media-hosting.imagekit.io//6ae18d584cb04dce/Screenshot%202025-03-09%20131154.png?Expires=1836114115&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=Mm1EywsFkMETmEZbJPRizUZPP13WqzeMR9m9mEcTJq7dlka82ckP61S2pJ2y2E-uTFQxkjk4E7yqOmaiipql3e70n1bKwhWUlKZgEy2BqZUrJuvVlGu7MG0UgF0RBG~1waHHbNiQHSGMj7jSHu6hivU7pN86nGeih9Dg5boecMm7eVel0o5RmgytBjK5Od5LAntwJRgQIO0-lwV8daFJIlarI~AE~p1p48ik019yHZBhrij0cscwS0SSEF~knUs8S31u92yx8jWkKmUZBNSYtSMWCyqbMlLFXzB~aQTF1qdLybCkBy01fTXXT3Vhmlht9bViypcdKX3cCvMoMTkMEQ__>)
 ## **How to join strings**

To join strings in Python, you use the plus operator, **+** , just as if you were adding two numbers together. The following example joins three strings together.
![Screenshot 2025-03-09 131457.png](<https://media-hosting.imagekit.io//dcc4a11872864857/Screenshot%202025-03-09%20131457.png?Expires=1836114306&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=pelhMtv26dTZgtaTRDOsMyCtkKJ8LWe-0zyuQpPmdn5FhwvBmrKRCtKIIE91Pk6du-0T4a92JPTnNDhzgfDqLt22HJzt7kBCZRjta4b1od5ojOIkwzxsRf4WQAqdlTM2lUNAvPL7D50R4spzLethqizbJvWkThcD-ZlnbZC0urFUGzaEPeIeqzAoZmpMAMokSVLiyOqGXShgTP6IGQ9pfIuQ80vHKw8QPOUKYuz~jKZuyhlAVWmcKxdYMfAOeavOBKJwc21lzASXS3oFejLhuVC5tYsCtsSuMmP7ZQ4bOGbxdaZO3ngGpg4220SLicyKO6ic1YrHCvXHLaFwdFLObg__>)
You can also use the join() method, which is very useful when you want to concatenate elements from a list of strings with a specific delimiter. In the following example, we have a list of strings called greetings and we join them with a space using .join(greetings). The join() method concatenates all the strings in the list greetings, and places a space between each string.
![Screenshot 2025-03-09 131604.png](<https://media-hosting.imagekit.io//17d1e2ce23dd4123/Screenshot%202025-03-09%20131604.png?Expires=1836114366&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=pGKuB9-4qAOe~UYwQIjQBYTw-GnIJeQ0pSG42Sv3gQ~B8VWEt5aJjvYhwjzjmCeb9L71wloOmfLqoGRl8Ivb7OqLTJF2ni~I3drn39gF9F1mKLbOKuzeyxv~ZfBQNTxMeUpWIwTAhMK1vLu1UpwsdyMgx2SmFLWSw4H6auTiyQU2Mki~5m0Hr2B0FH3pvEmCCOJCSS4lrF~IVUfPfMxisfBHgQbfO5GfZYymhjJfydEFWOeoyXlYp~3wDR6Q-1wHHqyEqXIZDUPUaw6eiEGHGCXQssatOjnZZPLQTa9YLN0pIY~jpJBNknx6eAlHWTXGfDdX8JTJC~xRalRmbJ5mWA__>)
## **How to combine slicing and joining strings**

Now you know how to slice strings and join strings. Now, let’s put the two operations together by taking an unformatted phone number, **2025551212**, and return it as a properly formatted U.S. number. In this example, we’ll use **phonenum** to refer to the unformatted phone number. You can define a function **format_phone()** to perform the whole operation. Here is a breakdown of the steps.

![Screenshot 2025-03-09 131822.png](<https://media-hosting.imagekit.io//617e3eb50a444c42/Screenshot%202025-03-09%20131822.png?Expires=1836114505&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=HQgVnVqvOqdiBt8yjb-VTEZSXlmGn4ZdStYFODXmNzx-BUs-JHdaW1jfCuNnKbT8PGjfxSvhuepFj9VoKh-5-wuxQRUPQibyrubi380uQCQQP0xCg-97GwdPFDiB9-xZDTPWZ8W0hOoj5LCqb0xm8bc57Q2a75j4FoMxgJLpCBfxeLJGCClE-MupXXN1R3aku8A8ovRgeaZIy~GTF04t4JstIZAMwd~VqV5BcDGYAqDF-piYc~fi3DcaCX4WeN5K6UVjhmLZvonv80r0B5uK6xEhDL0BGEKxeFZ5mpQ8JrcG7I~g16jrgcF7n8snI3PTmUkHKw~8YQ0f5bplq5ONCA__>)
![Screenshot 2025-03-09 131919.png](<https://media-hosting.imagekit.io//d66f790be8c24411/Screenshot%202025-03-09%20131919.png?Expires=1836114561&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=IOrgeOTtnJT2G3mrqqPbm9v-6wAuq23BrBeMUcKOOm3j9Zls~VZ-0mOuEHdpi8JE1b3B57W-l61we6psvNzos6rqf9rXZ9Ru5DE0a4mjavFQbWPYl8OgwSwN3VK~rNcur9o9QDRtOcNhbPxTGJYW5CA-CPBRVNSqHEUP1YDDBTzrhYXq9VedyuJVfMXm0LeNvLPRi5yU2DrZ4Lu-A~RoTa4vj2sCLxkmSkem9xMpZQPVuY~Ot9HHcCwqaGBlqOEeCLg6cyGgEcCSsmBhS~xI6uvgNivNZQN04kJ9GOHHwrvvVPJtQqzEamok4h9DASsCrCmnenrbpYsG0b9y5pUnHw__>)
## **Key takeaways**

Slicing and joining strings can be beneficial to correctly format numbers, making it easier to manipulate data in a more efficient and meaningful way. Slicing strings allows you to access individual characters of a string by specifying the index. The index can be as long or as short as you like—you can even have a negative index, if counting backwards is your thing! Joining strings allows you to add two or more strings together, which is beneficial when needing to create a sentence or even properly format different numbers.
# Review: Common errors in for loops

This reading contains the code used in the instructional videos from [**Common errors in for loops**](https://www.coursera.org/learn/python-crash-course/lecture/8XtCn/common-errors-in-for-loops)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![Screenshot 2025-03-09 132253.png](<https://media-hosting.imagekit.io//f99123f979824d32/Screenshot%202025-03-09%20132253.png?Expires=1836114778&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=cOfBrKP1ZBIZnjD2og3ATe~-JhKKKXj7EylWJ7VTrDTEhbeGcmRfntCXQGH0IGl4HTIwi7F5WVOfusYDUncUZtNj3ZbvhNyQbLlgEnyEAzkzOPTR6GomHi5Jqj4FBzNNleLwwsnL1myKQgw5VGTokIBtc3qEl7fnyi6x4RTcAm75naMSDuU055Vg-5VJ8nwy3bYvBDNWYvvpr7y6Z1B2joB3ZANKmkrjryh3ynzKXZMGPL7kU2M5agtgjMDDFKooL34EztSHFRPgYavC83ele14opAWxWDAl2Sf6iXaxDcPwP86qHaQM9DVzaBxVygDl1JYPgKLAgGPcPo5UOHR4yg__>)
![Screenshot 2025-03-09 132333.png](<https://media-hosting.imagekit.io//0c8ab7a196df4ea0/Screenshot%202025-03-09%20132333.png?Expires=1836114815&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=HNHlRgRs3S6yNtEB5m7MHvezLzNccZhEqbqwIkeIbjWWOFaHMYN2b58P4j6zQLplZFzk3GWQFylG28U71EvClJjE3yUp11qty0SrR7DD0oqkWKoUYK3FLEahHs8lHKSvigg0BcS8reSyDBUw~S5fZQefbEE0141cvwdlDSew44AKPPUlQI3JqsfMm5Q2dF7QRzQZRP~SDzkXywyiWcsPVDXs9-1~dPhp2pwH~t1eXnrT8gzN~hh1epZ7GvSz0NWan8NQX5uktCu4ynLzNk9Tg~JeHBbenwQyG18aFbJT5i5FpabsiogFHw~Y3VmcJSOFZsyE032K~pYu4xxY1Jj-ng__>)
# Study Guide: for Loops

## Study guide: **for** loops

This study guide provides a summary of what you learned in this segment and serves as a guide for the upcoming practice quiz.

In the **for** Loops segment, you learned about the logical structure and syntax of **for** loops. You took a closer look at the **range()** function. You learned about nested **for** loops and complex nested **for** loops with **if** statements. You also learned how to fix common errors in **for** loops.

## **for** Loops vs. **while** Loops

**for** loops and **while** loops share several characteristics. Both loops can be used with a variety of data types, both can be nested, and both can be used with the keywords break and continue. However, there are important differences between the two types of loops:

- **while** loops are used when a segment of code needs to execute repeatedly while a condition is true
- **for** loops iterate over a sequence of elements, executing the body of the loop for each element in the sequence

An important distinction is that **for** loops are suited for objects that have iterable structures. So lists, strings, ranges of integers. Individual integers are not iterable, but can be looped over by the use of the range() function, which is covered below. While loops do not iterate per se, rather they watch a truth condition

### Syntax

The syntax of a **for** loop with the in keyword:
![Screenshot 2025-03-09 133422.png](<https://media-hosting.imagekit.io//e708b6b7e63e430e/Screenshot%202025-03-09%20133422.png?Expires=1836115465&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=UjrMQkBpMP84HCGIw2JGWjMdBVTTfrG017I8KXuDlZLrq2bM4txMEoKx7C2TrJQDlWMc5gJOYjghuB6PBFY-ZkCtXzqSbcWp98kxN~EhR3ziO7f-SwRNzPTqqqwUzsdMmURMipLNVrRWf1Z2PAYeIhpu5lhK16ast0UYCifza4oWsUDEB1oC~hZW8XbvsKfj2LRttdMqYQtU9OLuWWJwX1BS7nWSkEal0WZK99etpGLVWjIuvZ7b7-2oTA-2SNc9siWlL8Sf6Rv2dLPK3HRFl7-024TLkLPP8e6Rp89f2KawO0Ij1AGM35dnKvx0dnhXAbkGeUd8lH~-g1b4OuIOEw__>)
### Common **for** Loop Structures

**for** Loop with **range()**

The in keyword with the **range()** function generates a sequence of integer numbers, which can be used with a **for** loop to configure the iterations of the code. The range of numbers [0, 1, 2] correlates to ordinal index positions (1st, 2nd, 3rd), rather than the cardinal (quantity) values of the numbers 0, 1, and 2. For example, range(5) means the five index positions in the range [0, 1, 2, 3, 4].

The **range()** function can take up to three parameters. The roles of the three possible **range(x,y,z)** parameters are:

- **x = Start** - Starting index position of the range
    - Default index position is 0.
    - The starting index position is included in the range.
    - Example syntax: **range(2, y, z)** or **range(x+3, y, z)**
- **y = Stop** - Ending index position of range
    - No default index position. Must include the ending index position in the **range()** parameters.
        - Example syntax: **range(y)**
    - The value of the ending index position is excluded from the range.
    - To include the ending index number, use the expression: **y+1 (index + 1)**
        - Example syntax: **range(x, y+1, z)**
        - Alternatively, if **y** = 10, you can write: **range(x, 11, z)**
- **z = Step** - Incremental value

Example of a **for** loop with the in keyword and the **range()** function:
![Screenshot 2025-03-09 133528.png](<https://media-hosting.imagekit.io//9152c8f658b44602/Screenshot%202025-03-09%20133528.png?Expires=1836115530&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=KkkN9zyyIYJfTmGZLxb9VpBukWkFPBBVvjz2Q~Ve0di-VyniVjpKg486y29AcCnUM1i7ig0~~p-xjGGJAVWXyWvGw4vtXmSU7QmViJ~IZlnQV--fn1YTSeLzY~nny5j43ZFWZjS-rTsZccIzvnw568GboBxceIIh9ISECaaZ23t53Z0X4fuhPLUpu7EC0v248QZ0aEstOKFj75-CbZSRpjYAUTQqfSBlc4q8g-CchT7WcCswOUQuPc3uX0SEmv~JVI7NVjDWRyNzR9Ja-8U0uE7hDAHAarUxYr~6b0pvNLPRckXdkDEreG1qXZW8~tfG6sAw1cS-hZeKvI~3guxxYA__>)
## Common pitfalls when using the **range()** function:

- Forgetting that **the upper limit of a range() isn’t included** in the range.
- **Iterating over non-sequences**. For example, strings are iterable letter by letter, but not word by word.

Example of a **range()** function where the value of the upper limit of the range is excluded:
![Screenshot 2025-03-09 133933.png](<https://media-hosting.imagekit.io//2107c4cfc51242b6/Screenshot%202025-03-09%20133933.png?Expires=1836115775&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=lJNtYZcVN~9kzNBRu-abhsociFg~f0wULWltUVPmzjnsmTR1pnDyGwTTv3FqGVOIc1PzVw4GxSCh4Gwu4NLsfH7rJS28wNb8TFoLCmaKlI0pDZ2Da9lADVjDVtoryjBZTl4IEY7bZkiiiIL--Fd6Qa~8OAD8f8K6ViaFKQ-2TUEI1MHkMju8x4Uo9Gusohl3p03Bm4DaaO9R26gUVGmgVrQUUK6RI6ZCnCzYbg8dv~bgBBpL79Wki8j5ujY4K1Z8TgwsH1M0EYJrsSt5RaQG33wpsnrKYf5wYPX5KJi1Dl~-YIVbHs6TiVRWfhzQMBuzz12cKn-vo8y-9SjqTobjvQ__>)
## Nested **for** Loops

The syntax of nested **for** loops:
![Screenshot 2025-03-09 134229.png](<https://media-hosting.imagekit.io//457361139f8543ff/Screenshot%202025-03-09%20134229.png?Expires=1836115950&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=bUvzlRy4~dTKV5Bcicr0GpX-K~tjK9UI2yHGd8blHlng0Ot6nMsTyeXu0HvtpilvAXEoJxv5BZM71Rxb0MAZdcAP5dgRlwGBm6lcKI0Rp6W2Z2S4sL7TUJIt-M8EGAWZiDucWU9NXVIyWA1j5OrvzlU4i8yAAJ3IgGWaQJcZEQvk87z5Ot3blCC4GE2IPCV~p7Hmis5Mp5cQCpfhuMi6Hkpk8Tn5IgPi8mbbR2AKFoCTWvRtfY2mrDGTQPHYp9n~JQe9L-bJkq2XDjy2IJ-Uxzafqy4j~TAeIAI6k~qaLEij4DfB6IT8d2qYgHyL6gyD31lyLyox1eL5U~6bXp-z~w__>)
## **for** loop with nested if Statement

The syntax of a **for** Loop with nested if Statement:
![Screenshot 2025-03-09 134334.png](<https://media-hosting.imagekit.io//d0b53e327b454ea9/Screenshot%202025-03-09%20134334.png?Expires=1836116015&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=Z1Aj5du0SrDkXdGZaCCCQfp4fYAUMQU-RRWYHZ8kDWLfc27h3JdK442Y9k0VdqAUe51517tOH4Venpb6pGvnj7mYgvx4Pw59c5r2USywskXCI-TGjD1830hW2-9PqVXVhDyeFnreD9FEJWNJYen1LHaQ1aiyCMedJ2FUBHW97aP1558nSHzsGjL0AF26cGBQo9MBQBoHU4~ZEW-fOsIVh83LukSxTK7A7cPaT-bg6COig3iVVry3SxdtU6Ozgk3coVBYaN4m~2oBnw4fwc5HnlhPMcy~aQn3T1PkjFr~trM~5moIme86ds~JJ-obM8geb9Alx1vZUKv~PlDoujklSg__>)
## List comprehensions

It is important to know that loops can be avoided sometimes; as you progress, you will develop a sense of when and how to do so. The concepts **for** loops are similar between other languages, but in Python, **list comprehensions** provide a concise way to create lists based on existing lists or sequences.

Here is a concrete example for better understanding. Let's say you have a sequence of numbers and you want to create a new list containing only the even numbers from the sequence.
![Screenshot 2025-03-09 134840.png](<https://media-hosting.imagekit.io//2c8313646a594d6b/Screenshot%202025-03-09%20134840.png?Expires=1836116323&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=IT95Wb1f~M6fcPGS7MoRvdHMlpJSYLyXwq9ERB-HLlbZnA-NmajZ4YC0P4kkr1KFxhZMlI7tPA-4y41-g7iAR7aTr6ouQG9kDLFUlIvRZiucqTTIHnajJCtspB~5HC2qqBgZITGYtlj4~8XZ-W4Ts5MRfR5FGR5pDY2VkpxsAzlRQ3y-Jv-~IZTu-zBRWIi3gC803Id44Si58C4in8WF5mG1yxcH781RU-2cYN1hTaA-ORuhLLPNFu2AAsym3nusEGRICY46MUYy2F2Ff6GYV7Q104j6XZQeoFajIu~DYi5531HGvRwaGtUZp28ED0r5VJiKRN4YjxL8BWixLn8~SQ__>)
Both of these pieces of code will create a list of even numbers from 0 to 10: [0, 2, 4, 6, 8]. The list comprehension version does this in a single, compact line. These “one-liners” are very useful and dramatically reduce overhead.

An example of a useful one-liner is:
![Screenshot 2025-03-09 135611.png](<https://media-hosting.imagekit.io//5fdbdc18cd834166/Screenshot%202025-03-09%20135611.png?Expires=1836116781&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=ay3dyAr9Pl~Pxg7KW7M9P6Waws7EtIxXA-L0y5Ilny1C3WdE3JjC17wlAWzZ1nwE9Jh967fbrC64axp-IUxKA9ESV8vKkVEylGX3CG96ntdzJGhV9alunyiCOA7WlGS0iMQpRGwEV8nWnFGbqq1MjTbbmxMYr1EiTL2V~shhGZsB~07H-GPPWi4hemjAmlY4Vx6u2t8ry9YmAOUaT~yU9PBowGN-hPLTRXj5ZKPUKNii2sQNQ7sm1ukGwB-cKk5IL8gUZ4f2G9-ANqE2Q1QewVaHFRqpg93M4~vIsbZ9pE0nxqs2mvPq6xHxMF03nDqVAsj67SP7rQA86jcr3E2FyQ__>)
This prints “*” 8 times. The number can be replaced by an integer variable, and to do this with a loop would be several lines of code and run more slowly.  

# Review: What is recursion?

This reading contains the code used in the instructional videos from [**What is recursion?**](https://www.coursera.org/learn/python-crash-course/lecture/7T0ET/what-is-recursion-optional)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![Screenshot 2025-03-09 141233.png](<https://media-hosting.imagekit.io//6ce33e1cffe54fb6/Screenshot%202025-03-09%20141233.png?Expires=1836117755&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=GPk6DuwVpKaHv5G8ZfA8sToV4Xe-z~FR2PoFHLFF7EYVn91ZFJPNtk~mbMdnU9jFJsLzcopwx1ES-yoHbpTo6izm38YxSMq9gDigcKRH8C9R6CDT8GK6L7og9UifI5WzGqjHpG7vWORXioa3FQI0LGudGu8Ly2vqxJHvuYQz16fTS1cJggXRtW3LIIiz7-89O7kNulNAGx5h66LC~ALK9rNv0rneD9zC1ZfV90ruwn9A9D3gGjWMrl56dyJkcq4ZiHR3jRuGUvu3-h~AKUGt4NT9Fves9HksNo2cOe4y5qg-O8OuT-5bETemsgj5vTCAIgf9P2lyIQJyVo1U-uzCsg__>)
# Review: Recursion in Action in the IT context

This reading contains the code used in the instructional videos from [**Recursion in the IT context**](https://www.coursera.org/learn/python-crash-course/lecture/pQhjw/recursion-in-action-in-the-it-context)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![Screenshot 2025-03-09 141655.png](<https://media-hosting.imagekit.io//ee404bd9bda34c59/Screenshot%202025-03-09%20141655.png?Expires=1836118016&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=qSOYCRTWBsnnwG9Ba8wVso0EVN0PcL7p755zUlbVgte2sBJhg70xmBV0eJ802mRMlIuDjeqbCsI7kCEnaxCfIF2d9U~W1Dkafm5Wr65N8M~P~BHIYuDBBXVDn--VJ8d2KHsDNzGgIV5HbryZpDboaJZLhYOlY~yCbdwJkl4qJn3E2gFhO6SN1jJ2IcKsL0YO7LER5Ko2wt9vLhZzwhLt7ABPj-C5yH8W7v7kFdl8BJvyAfHgnkk5dzKLAD6OhmpaUBxnHZJgNTyQTPrqFFZXGr7O5k5DLvCp~MgDo2n0LcLWyhLir2KlKrD2QW4ANUQwFF9AqOWudSGQvrG8q4CSkg__>)
# Additional Recursion Sources

## Additional Recursion Sources

In the past videos, we visited the basic concepts of recursive functions.

A recursive function must include a recursive case and base case. The recursive case calls the function again, with a different value. The base case returns a value without calling the same function.

A recursive function will usually have this structure:
![Screenshot 2025-03-09 142117.png](<https://media-hosting.imagekit.io//492dc763f2ac45f0/Screenshot%202025-03-09%20142117.png?Expires=1836118282&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=CdkW-JUt3j64OuNt7bk8KOXtFYFjie7CNLzpySq5px60rrn4gIkEYBUt3j4Ry43UlnuoLaNSzXYba~~3lyHerw692Hbzr5TYJbqQZFs3r7vaShMEyysDsh4Sr1S7PaWgDS0buXTXmQFL4IM2iJl4zVjFoEGo3QFIqDg9jkQR2KORb4npvFrey-nmTz24g3Z0UxYFT~5WTb6H2KPA9CkhlA6M~KNGeYv19wUcZDs5OMMz0Uqg7H50bunTf~WM8EUpzVaE0O0Rot5vX642OA8779oA2nrJkLhWlLtqQ31cTKlAULjNeQBVqbMh-wqVdYl-iHg98LL0KfnrJdo6B6eGwg__>)
For more information on recursion, check out these resources:

- [Wikipedia Recursion page](https://en.wikipedia.org/wiki/Recursion)
- See what happens when you [Search Google for Recursion](https://www.google.com/search?q=recursion)
# Glossary terms from course 1, module 3

## **Terms and definitions from Course 1, Module 3**

**Break:** A way to exit out of a loop before the loop's condition is false

**Control statements:** Programming constructs that direct the flow of execution of a program by allowing you to make decisions, repeat actions, or choose between different code paths based on specific conditions.

**For loop:** This executes a block of code for a specified number of iterations or over a collection of items.

**Infinite loop:** A sequence that is missing a method for exiting the loop, causing the loop to run forever

**Iterators**: Variables that allow you to loop through a collection one item at a time

**Loop:** A sequence that makes the computer do repetitive tasks

**Programming:** The process of writing a program to behave in different ways

**Pass:** A placeholder statement which is used when the syntax requires a statement, but you don't want to execute any code or command

**Recursion:** The repeated application of the same procedure to a smaller problem

**While loop:** This is used when a segment of code needs to execute repeatedly while a condition is true
Study Guide: Module 3 Graded Quiz
It is time to prepare for the Module 3 Graded Quiz. Please review the following items from this module before beginning the Module 3 Graded Quiz. If you would like to refresh your memory on these materials, please also revisit the 
while
 Loop Study Guide 
and the 
for
 Loop Study Guide
 located before the Practice Quizzes in Module 3. You will not be tested on the Recursion lesson content, which is optional in this module.

Knowledge
Terms
variables - Know how to properly initialize or increment a variable. You will also need to recognize a coding error due to the failure to properly initialize or increment a variable.

infinite loops - Know how to recognize infinite loops and use common solutions to prevent them. For example, check loop conditions, ranges, iterators, control statements, etc. to ensure that at least one of these controls are in place to prevent an infinite loop.

iterators - Know the various options available for iterating a variable (e.g., using assignment operators, using the third range() function parameter). You will also need to analyze where the iteration should occur. A misplaced iterator could produce the wrong output or create an infinite loop.  

control statements - Know how and when to use the break and continue control statements to prevent infinite loops.  


Common Functions
range() Function Parameters - Know the roles of the three possible range(x, y, z) function parameters:

x Start of Range (included)

y End of Range (excluded index) 

To include the end of range index, use the expression y+1

The end of range must be included in the range() parameters.

z Incremental value

Example 1: range(4, 12+1, 2)

This example creates a range that starts at 4 and ends at 12 (without the +1, the range would end at 11). 

The third parameter increments the range iteration by 2, as opposed to the default increment of 1. The  range(4, 12+1, 2) expression would produce the values: 4, 6, 8, 10, 12 

Example 2: range(10, 2-1, -2)

This example creates a range that starts at 10 and ends at 2-1, with a decremental value of -2. When counting down, to include the value of the end of the range index, use -1 (end of range minus 1). This range produces the sequence: 10, 8, 6, 4, 2 


print() Function Default Behavior - Know the default behavior of the print() function is to insert a new line character after the print statement runs.

To override the insertion of the new line character and replace it with a space, add end=" " as the last item in the print() parameters. This makes it possible to add the next print output to the same line, separated by a space. You might use this technique when a print() function is part of a for or while loop. Example syntax:  print(x+1, end=" ")

Coding Skills
Skill 1: Using for loops with the range() function

Use a for loop with the range() function with the end-of-range value included in the range.
![Screenshot 2025-03-09 144154.png](<https://media-hosting.imagekit.io//a280d1d5e8614737/Screenshot%202025-03-09%20144154.png?Expires=1836119515&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=d4THeVyfZLtzUJKOk84EJRVW1dzlv8gquQDIrw3uyOzC3p8ZXq3jOg6dRbCkIKgH7UuuJinKX1F1Ok2FQh~3dVDWf6rfs70F2ekDr3ERlGYefrskbb7yYWJHCEFTJJ-4bQe1ykknVRFHvAsS7EwopjwYFBFXrRD86GO9u5trGtxRuciWMh4H8yYRW0jP8EEimgerywX~zP2hAYDQPyIUDLBsMdgL9CNAS~O~kSzX-bbAjoGYIllFCw731Ry1xFmpYHztOfs3GEd8wzhx88QlcqI5luFd-6PmtRNWFuZ8BhqZKjbyPXzwbUmGp00Pyh8YXIg8bbAA8PivJmFqqGrAZQ__>)
- Use a set of nested for loops with the range() function to create a matrix of numbers. 

- Include the upper range value in the range() function using end+1.
![Screenshot 2025-03-09 144307.png](<https://media-hosting.imagekit.io//5f6a9e5bf5b641d3/Screenshot%202025-03-09%20144307.png?Expires=1836119589&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=X5aefkLRb43mvzq7gbl61R78twRsHUcuFtSAEBcbKObZzFVVaQV~XJUrMzE3Uw7rYu6r4IIjUWOOpxfqoh3~s2LCfApbRqWxSyI7yYrxoW~w9Qb~R9Z0qgKZKFd1Fj~ugCZSDsNZUxukib78Xf6tRGdi6VuOQ-aDY3EUPXVxLJ0Ya-Vb0tPeUSLkoir1VZDGBw~Qb5qFsl9-YBEhbsIoOz4JMgnhQWTpxvj8VAv5wJmAv6ysuZy-OLXSL3ONPYQ7QAPMP6~w8t7FLv1thA4sw8TNZUIcVvurRyEvuADTxnnvSdk1x3Ty~eCREf~k90vBx9d0qwCBNJIEeg3-LZc2bQ__>)

- Predict the final value of a nested for loop with range() functions.
![Screenshot 2025-03-09 144433.png](<https://media-hosting.imagekit.io//a3ce58412b0b486e/Screenshot%202025-03-09%20144433.png?Expires=1836119675&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=dZzaV~Zvtltx~V9JvyQCjmiBGQist2EHDd-UPmvV2hVhqTIzQJgAhhXRQI73WCYNrdSWGmc3XEc7W~RAHi-WQOmn55yfB~rUV~WbbX7FEJXfIWBs20ujCZJTRTxgylqjjXXXP0FDCYNjiinQr1M2pbgkpMjNfLy~-hyjHe1uCLKr1VvNgsnbmyhm3Fhd9eCSyyoYf3-ctH~vyz6n4wsDLT2rrh1nU9yBlOIcxhTp1oHGvM8cAabSHnV3nkrYEKWzLRwqJLB7v~lTaNtiUfdoumNw-zDQo3zpi5cgY2TtQ5SrCTueZfxPAt2aYdQqlc2m3ZyDC5zEviqgd2OqGwNqvA__>)
- Find and fix an error in a for loop with range() function.
![Screenshot 2025-03-09 144800.png](<https://media-hosting.imagekit.io//a1c35a43e42d4481/Screenshot%202025-03-09%20144800.png?Expires=1836119884&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=QLa1vj6wUsr~~Thb3Z9RipRA8jp~3L88KFiGbt7kzBZFmZg8A381zr~MmmC3OxvoSGOhkZoTJ2wdAAdaHXj4m-Q5XykTMJUW--nRs6y1slptETO8QqQgE3hw3yuKaK87ksacsFMyAAsoRHStLL4-G-ldcvxEe-qY~0C~ptbFdw7X9LMH~T2FGmGHnGzaIU3LxjAFJknxWC1aXR2978OVpyb~oIXbp68uxjzlW9Rahb0bkvvS456RsCYMFAnAMB~qxgqSjq-e9~VmUVrmWdPX665ZMQhP7GH4AdhYn04tqiAQaagFuXb7vA9SakccOhm11r41IBEmjEPVyEAd3Q6rhQ__>)
## **Skill 2:** Using **while** loops

- Use a **while** loop to print a sequence of numbers .
![Screenshot 2025-03-09 145046.png](<https://media-hosting.imagekit.io//9cc059c400054d01/Screenshot%202025-03-09%20145046.png?Expires=1836120049&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=S0QKsHHLPO-AkbG3LRLNFyhH8uJ4Glr4QKYyaYT7cHWcVaTWCQ~YTOc703Q-CicFfm2~trpWj~E10sKiMsTRzLK5Xq215uuc3bxafnZTkgy4pgv-rzV5ufAaHsIFk5J-pOIfTpZO0U0WVmb5IMjNxMMKqObt2f2X01uBDMdpXpW5nEaf314QZqZQE6goMu09XJNNkeFg6YShigu0AJGLCLM35ujKcJacFKqMstK0YM3hzvMkRp5-zKd3qsb8MrPoJWeGmxf-6t~Ext9BoqNy52geMSkdCV2TR9Uh9UggLHlx0djD-KOSh0ZdYSLjZB9E1SQPU2zUHqNpRiySMgieLQ__>)
-  Use a while loop to count the number of digits in a numerical value
![Screenshot 2025-03-09 145152.png](<https://media-hosting.imagekit.io//9c1bb3fcd9db4d43/Screenshot%202025-03-09%20145152.png?Expires=1836120118&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=sXvm28AkwNkrMDCVpzC-Yqsg~rk0Lcn4PxaagB88nnrTJfqODzOWTzfwrlO0eTM7ULkiDN9-V7WUKXOegEixV5-4K0xs3g8wCzhSWK0kS3X13f4ySUNm3~Uv2fXvATsbf8DibnkxdPS4yZmWsWkZ4U3UJsCM7XR03~saYhLALLNDAHt05p9QPoDVguml05tQSptretr9XfKbc3K7s~pnczF6tEcK1lhIcl-JYX7efCC93zv76rxBR7K8FQuFYqVvnAGiGsbOH88H4jCRMpV75HAcoI9Xc7A3JA2twwoOCP4VIBdFUV0YrMJ6CsrJvIv2U7seEIBQa-KUW4c5pp-~wQ__>)
## **Skill 3:** Using **while** loops with **if-else** statements

- Use a function to accept two variable integers.
- Use nested **if-else** statements and **while** loops to count up or count down from the first variable to the second variable.
![Screenshot 2025-03-09 145358.png](<https://media-hosting.imagekit.io//d7fd3ce148904c78/Screenshot%202025-03-09%20145358.png?Expires=1836120241&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=Bq7StnZbPldwWFMhSBUNBRMxkCUTIY4lG4rOeckUoA9z54w7T-RiUlWauOK84DGS0KrK6pMorWluNJfGyak0jDqYSpOma6cbL7bcQ8eL~bBGogHautwMoZAlXku2z4VX1Q8-W-h1yFyC8v1IlUmkPRBEZAFnR-pnAtsxhyQ4Y2tLqM758VsVZH~kpIlJvYGIDe9-Z6Ud-0C5guh0VU4Astt5XBc81XRMM0ybgZ4ardTTxvgrUQGd9yo7YY5bcyDoNRmFU8IYvwvfMRy25vaIOm7gBHZq-bAflt60L~B7iYX8MibjoBIPac7pH2j8gxQEiAVNA3PGirzz3JKFKa7PRg__>)
![Screenshot 2025-03-09 145330.png](<https://media-hosting.imagekit.io//4f30ba14599e42f9/Screenshot%202025-03-09%20145330.png?Expires=1836120254&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=JdyT6rZ77ikjqEt0P3iX1SsQLiJxdQ1S6k742TNur2TGhgrk6xe0sR4FA24BBQAo7cweB31vH7zYB7RFW~7vDxsz8JNu896HmtYQtEfSsaYvZpBhQLlANyWjJRa8~tAYb8hK1MwOfRbFgUuiZXPbuXECR72b0vkYK8n01XY9c6laM12XVbYACBLmUKWP7mbc7Pj6QT-A44clNfNBzdqz7ia3BT6-pm-eIVWIqvgLcRMlRS1DBjtWi0dZYlhql6-63j6QosABjpFQUc15It6U7UBRNKkfV~ZEz1Uwq3XNk5LZlwqSlWX-~j2kxvN3V3xhUqeitQevlJl342gdR~guzQ__>)
![Screenshot 2025-03-09 145718.png](<https://media-hosting.imagekit.io//4ff90c473e9e4078/Screenshot%202025-03-09%20145718.png?Expires=1836120467&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=fbOnz66IALRFE9MSO-nr-NglSBd29TGOvA9eq1vMRNvuNLrtLiMA8Yz62ZEqgRbLQ9KAJyr~uGSXmw8-6rfWOhxvp-FS1uIbe0zIl2pZlPs7-KSGctbSTYmHEKg7NR1Mb5Z9LbA~R63MvU9T8g8IOu5gJeHq39qfh17PZUEMzC4dbrG6EYSu886mJB2tvAEF~TBua9nW8Cx~~g158jN37p3ld9FbWjzg0u89Fbh980jYy~UsinrUyGRyOGLKq5WQqs7nHsb6dllEYeZo2Jjbzvk0-FoXPSX49LHs9qI0Z6bI6daNUlMEJi36IKY2i0I~1NGFSyvo1sjELDVy2vu44Q__>)
# Reminder: Correct syntax is critical

Using precise syntax is critical when writing code in any programming language, including Python. Even a small typo can cause a syntax error and the automated Python-coded quiz grader will mark your code as incorrect. This reflects real life coding errors in the sense that a single error in spelling, case, punctuation, etc. can cause your code to fail. Coding problems caused by imprecise syntax will always be an issue whether you are learning a programming language or you are using programming skills on the job. So, it is critical to start the habit of being precise in your code now.

No credit will be given if there are any coding errors on the automated graded quizzes - including minor errors. Fortunately, you have 3 optional retake opportunities on the graded quizzes in this course. Additionally, you have unlimited retakes on practice quizzes and can review the videos and readings as many times as you need to master the concepts in this course.

Now, before starting the graded quiz, please review this list of common syntax errors coders make when writing code.

### **Common syntax errors:**

- Misspellings
- Incorrect indentations
- Missing or incorrect key characters:
    - Parenthetical types - ( curved ), [ square ], { curly }
    - Quote types - "straight-double" or 'straight-single', “curly-double” or ‘curly-single’
    - Block introduction characters, like colons - :
- Data type mismatches
- Missing, incorrectly used, or misplaced Python reserved words
- Using the wrong case (uppercase/lowercase) - Python is a case-sensitive language

# 

# Resources

For additional Python practice, the following links will take you to several popular online interpreters and codepads:

- [Welcome to Python](https://www.python.org/shell/)
- [Online Python Interpreter](https://www.onlinegdb.com/online_python_interpreter)
- [Create a new Repl](https://repl.it/languages/python3)
- [Online Python-3 Compiler (Interpreter)](https://www.tutorialspoint.com/execute_python3_online.php)
- [Compile Python 3 Online](https://rextester.com/l/python3_online_compiler)
- [Your Python Trinket](https://trinket.io/python3)
#                                                           >>>> YOU HAVE SUCCESSFULLY COMPLETED MODULE 3 <<<<
