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

