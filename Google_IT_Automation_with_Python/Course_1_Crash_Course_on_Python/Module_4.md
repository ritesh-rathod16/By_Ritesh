# Module 4 >>

# Review: What is a string?

This reading contains the code used in the instructional videos from [**What is a string?**](https://www.coursera.org/learn/python-crash-course/lecture/XOjeS/what-is-a-string)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![Screenshot 2025-03-09 155035.png](<https://media-hosting.imagekit.io//e71958b434bc4446/Screenshot%202025-03-09%20155035.png?Expires=1836123643&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=sH3LIgWlighSQE315bAE9tN6VH7DEVh1p1DSfgtO~duITYHSNPB6KCgP-vSaWYbgYdWqsJifQ0MJajmDApi1-0MQo3mIPO-DDBy7KZYELwZB7thaRuLfgIo3rZlgNrKvIjw6S-MKZZow60P6T0-O2i7znH1oOYfN8cneuxsj60svpd-SxTxPVVbAjmY2ewB3YLulHIj-6bOLRE1eNvZNaUW-eMXi5KsQb9YdhhCiYWeznRq73izJ5r1K6EyJVAJnbcNgr8Dv7P~9sYNadsyMxk-9c~x9g5YqNoo~Zin7V6wqZj~d1i53Z~TI~tri7goK1riY0FvyQ6wdK79v9b7rKQ__>)
![Screenshot 2025-03-09 155207.png](<https://media-hosting.imagekit.io//b1f43d10160e4b7d/Screenshot%202025-03-09%20155207.png?Expires=1836123733&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=kOnpgbQ2oBBxbWkW4YzL2nuITZoaoTZxsNrh4HsjshQyys7pyXmo8VYO7IdkjGEPALDKFafMXFsBd5~jh1sXw0y5C1sJD-F7S5gAawEPdYtGyXYGYf-P9DhqppXcxAzX88RQOnbWRuBgoX8r9rmi6AdVKSfugP9xWWejmjV~yGezsj4C8ZOP0cZdqKCBdpIgZaWErkQXLz9r-msQ2TvaI4xZ5D1ngA1dcDZeoUETB-XlCR0U3OUaNAYtbIhBw5Jpu~KFk2sNnNtjf9xOEsRUQLzqNb1tDvrJcdeUJ2yKTOVoV-f93kpLuf4KeCJf7MSXHnLMi3QVuN1YsC0M7~gShA__>)
# Review: The parts of a string

This reading contains the code used in the instructional videos from [**The parts of a string**](https://www.coursera.org/learn/python-crash-course/lecture/9xgmF/the-parts-of-a-string)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![Screenshot 2025-03-09 155445.png](<https://media-hosting.imagekit.io//2b4721b7e9154e17/Screenshot%202025-03-09%20155445.png?Expires=1836124012&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=uRAjWcfaQKeY5xEuzZtGa9ttXUXzkovTW-C--vsvBf3vtaPeCWkehc-WmvUSTlao66LvTlmDTz7H45k3eQj0sM7z4pEtaE0x4CKRxJJKqcGQ3LkIZcbZZJo6zhezq8BQAEG~EtpASXd4CilTfAzd6JHD3eG8V3LUzCoXVLzghCJMddwLUN8xHBo65gW-ZRyZ22gELk2UksSW6px3~XrFKphGnkb0tapk~QOdxapAjqI759CUMzXV9MwH-Bc~8qjUTjDcqI7wY1dXHilWIXMCWRTRPolvXNMy4~OLBWaYG8OOsqeS1B4IWRHBrP-5xdGapO8IqMBpDtQqLqH9gI10Rg__>)
![Screenshot 2025-03-09 155732.png](<https://media-hosting.imagekit.io//668e318c2b074517/Screenshot%202025-03-09%20155732.png?Expires=1836124063&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=qlyv3lMsZ3Pf7tYUGIH8kg6xCIdewNnHbjls4inaUYLbeBYhfLnKDpCGXiaKhyzVZUUk3ntyQO1oIRd6MzAXWFdojW0xNHpmnGsmonU3pD8Q5M3Vfkzpmg3SwEsOQ8e8xkYxLzNXGXWRrRm2jhLkLQF1z9rPtCcTPY9jnVsRdZ7mtydVemMOy~yiVQl3wNHuz-qkW8zkPkAAOvaMGDfnWuFWcmSonMIYIvmQmciqxDBiCR9LQ6ekVTZpOoAnVDez38jJBVo3CitV~8y8dZA1mH~JzEhTXAGAb4XRizpbmbeGw2eBScBoS0xajKmsDI5ustAol3EE1qGUeCZs5NZrrA__>)
# String Indexing and Slicing

String indexing allows you to access individual characters in a string. You can do this by using square brackets and the location, or index, of the character you want to access. It's important to remember that Python starts indexes at 0. So to access the first character in a string, you would use the index [0]. If you try to access an index that’s larger than the length of your string, you’ll get an **IndexError**. This is because you’re trying to access something that doesn't exist! You can also access indexes from the end of the string going towards the start of the string by using negative values. The index [-1] would access the last character of the string, and the index [-2] would access the second-to-last character.

You can also access a portion of a string, called a slice or a substring. This allows you to access multiple characters of a string. You can do this by creating a range, using a colon as a separator between the start and end of the range, like [2:5].

This range is similar to the range() function we saw previously. It includes the first number, but goes to one less than the last number. For example:

**>>> fruit = "Mangosteen"
>>> fruit[1:4]
'ang'**

The slice *includes* the character at index 1, and *excludes* the character at index 4. You can also easily reference a substring at the start or end of the string by only specifying one end of the range. For example, only giving the end of the range:

**>>> fruit[:5]
'Mango'**

This gave us the characters from the start of the string through index 4, *excluding* index 5. On the other hand this example gives is the characters *including* index 5, through the end of the string:

**>>> fruit[5:]
'steen'**

You might have noticed that if you put both of those results together, you get the original string back!

**>>> fruit[:5] + fruit[5:]
'Mangosteen'**

Cool!
# Review: Creating new strings

This reading contains the code used in the instructional videos from [**Creating new strings**](https://www.coursera.org/learn/python-crash-course/lecture/2OlJR/creating-new-strings)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![Screenshot 2025-03-09 160221.png](<https://media-hosting.imagekit.io//48ed7230944d4f2b/Screenshot%202025-03-09%20160221.png?Expires=1836124345&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=VTNrysyKt0y9GZJrs1KgOc9I4arXWSFiyqqPeksnHo92o9rICbT9ivlhpuCjaGH~Vt6B3wxLeqHW5dx3TuSPycm70a6EuH08JYmHHFmJrdV~AAoCwk0j1yjxxTJsZ9sbbGalp8UV7DLQi0C8Y-cxVj-X-GhuNy92qe~ajuFJYlyVIa2TWCw4lA9xLFigGKIHyyzG~2ifdJmx77tTbmmKVodr9tL8HBPKc7cvalkIYNsRDoLOOX-RNZlk7g19re~mGC-CNe2RaPRS5HILLzYcmQnUKVmvFMDDxg~RAXJr-BuXLlk~DhyD0M-BrI6bQi1T9grCmUteQE8lKE8qFhnOyQ__>)
![Screenshot 2025-03-09 160309.png](<https://media-hosting.imagekit.io//f0f070cf14bf46b2/Screenshot%202025-03-09%20160309.png?Expires=1836124391&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=AchfR8UWMcWKtA63t3ktwCDEQLK8qDBlIqbHosboZFAY3dWwDF-HRB9UP32gijqcXE4cJaLnd3bZ8LnPk9QxYSu-TQMLS4DbkMfI91GkhCLzF5qFREZv~YbDQxP0ODNxZvRERcCZ8a1v4AJcglQYztB-coaS7rK7QJKliLBLJHLqg0xeYmbPQsJ6rqHVjwv3ICLkcs-x~qR6venIKSWajeIY57auW4fXiltCN-Lrs1PI~hw4ZJ7QCYMMqIDOtqa4h~v30aXsWwBQeDA7iqn5LcGdh~zfS-2apDf4Zbjjn0Zr6x18VtYtyRnvHBWRMo43jy35Z-QGo-yAbB4YGUIqvw__>)
# Basic String Methods

In Python, strings are immutable. This means that they can't be modified. So if we wanted to fix a typo in a string, we can't simply modify the wrong character. We would have to create a new string with the typo corrected. We can also assign a new value to the variable holding our string.

If we aren't sure what the index of our typo is, we can use the string method *index* to locate it and return the index. Let's imagine we have the string **"lions tigers and bears"** in the variable **animals**. We can locate the index that contains the letter **g** using *animals.index("g")*, which will return the index; in this case 8. We can also use substrings to locate the index where the substring begins. *animals.index("bears")* would return 17, since that’s the start of the substring. If there’s more than one match for a substring, the index method will return the first match. If we try to locate a substring that doesn't exist in the string, we’ll receive a **ValueError** explaining that the substring was not found.
![Screenshot 2025-03-09 160508.png](<https://media-hosting.imagekit.io//f2c2122c469e4559/Screenshot%202025-03-09%20160508.png?Expires=1836124509&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=b~Y9lACsG9chZ2XlT6Ite9ByL6BbgLhnVVJx3JOAjeAjHylKZYFSKq8Ra9jeEMskYNUwQclL~iLZoKdEZrbWJDHvnwqsUJsWhkfqgEV4euT~IygWQ43Ec9korcOSXcrKGMZz8Hq1DIIAu-mI~wdIK0PbLAkFNiVxRbqobjel6iH4ULJ8CVLyX9qAog1RyeSp4oYm~ue~fDfIwku6fYNu45RtjUjkJJ0NiuiuFGNWWaaeFG7ZmGzm~kp43ALu2Xseh5vlUxB-cl86phinXOCZ0cI~I0gMAgNANWoLNoeNOZd4EJTscaDBzBdUtAql4X-HY03JJKuqDPxuOidbGEDlcw__>)
We can avoid a ValueError by first checking if the substring exists in the string. This can be done using the in keyword. We saw this keyword earlier when we covered for loops. In this case, it's a conditional that will be either True or False. If the substring is found in the string, it will be True. If the substring is not found in the string, it will be False. Using our previous variable animals, we can do "horses" in animals to check if the substring "horses" is found in our variable. In this case, it would evaluate to False, since horses aren’t included in our example string. If we did "tigers" in animals, we'd get True, since this substring is contained in our string.
![Screenshot 2025-03-09 160812.png](<https://media-hosting.imagekit.io//cd186b0e309c4ea1/Screenshot%202025-03-09%20160812.png?Expires=1836124694&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=fIseIGH4wiqPdWLW5MRAs-E6CTCvpFWyEGac9jXsUqaQyukZY3~kocuWUP96rRWTeL3pQyvlrptjpHlH1AXNv4MlvQIYeVmU1YVpoNSFqQnJC8SkzAYCyviwLADkCXKnHZnBErt8AcAtNHbTTp8pLz9ufUyDhvSpVNu4Y~DVDDIXvAzPhwgl6wKKNtjL4dWx981LttCwfUDraX89J5mzK7GBv2YRgB6W1~3IsGaW0X6SpJwXsiq0hs80xWSnyyBC1Wyjl1FIfFLgkSElNxR9pe564VRLrBHVkx7VJWITCPcjSSL57qhBI3UtqEvCg7MoVqMP8PG4dscAogiCw0Q8ng__>)
# Review: More string methods

This reading contains the code used in the instructional videos from [**More string methods**](https://www.coursera.org/learn/python-crash-course/lecture/45PT2/more-string-methods)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![Screenshot 2025-03-09 161255.png](<https://media-hosting.imagekit.io//836c41f2897d4fbe/Screenshot%202025-03-09%20161255.png?Expires=1836124976&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=piP~j0-mXho0YDg~CX-SOJkeSNaQt34t3I6F-i0QvapoPMTOym-QxnjDldk40It9yI48r7-HAO~ydGa0uflYK66is4yMBlQV38ZHbofXHGl97ZZWr8SiagJR5cI3ogvNtlp6mCxDOdRIhvfqN1oNqLpH8MOU2soxy5NlC1u05rDZDXJTV-ZRXDaR1XhgAgEkFEz4jEUpDAx5MO8JYH0NknWoVQXb450DzskAIJaHiJiFYtX1B9UZkNkpNYVDDcD0REUOFE7BOkr-SuTh8uZ-0bQjcrwrCgEYZYIsZiSLVT5vn3qONeZf~4zqos5ijZmQE0otZptP73GnWCE09pyefA__>)
![Screenshot 2025-03-09 161425.png](<https://media-hosting.imagekit.io//cdc1226d54e84710/Screenshot%202025-03-09%20161425.png?Expires=1836125067&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=MlYLsVjmMWU5OKHLrWGw45P4BcWAQSZyNOC07VEgRmDCA949jwnneMT6vnwJ9NtJVFCnCFEL0rE6STZPlU4PQx~EjlW3V5o3BG5aeGuG2zwDx1bef1y9B1vfyPsCFXfFy7Y3D5XoRaNi7DEloP74oH9GMXcUhVt8CQQ0v4nvTlQa~AmgjD5bjrUAwoqjIXkiX~R7XrW4vfS8iOodqocDUcN8GbwEru2snf07OFDMQtenw9Ct5~o4R3BjNAbQvOar4jPRALKWIv3mnXzsYEqwAd6hGuCgYVowyiMvxiHqkXtAfqpHoSk9dXsuaecUnI8uTLfnPT2iNfu9MFcMi9oqCA__>)
![Screenshot 2025-03-09 161508.png](<https://media-hosting.imagekit.io//280bef7a716e425e/Screenshot%202025-03-09%20161508.png?Expires=1836125109&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=ppwqvEPTVIJn20bYQyeeLYguwmnPGIcumCwiP5aS4iFC-y3Yx3fBnpc25dHr5xefAT2j0iaVEy6DlgQeoZS4dUnvmF4~kTsMbDQ5Fo3WYOTApP1pnZlHU0IACvxblYf~CK3wQ1Wj~Oi1GEW7eqdNPEnxw5rJWa35f80ppu8kQrkngXB3ULQoUCS9zXC-4Vcewjv-pGXsW9ofSH4FgJ6hSz0aWmH5XkKqvuCLgxRPhSu4-w4yuv5SpnLzXhOM1wSyeKWwqKpvBQv1A74NtbSxwnI74Hc7SVJcndvVl~lHkV25T840O8pO-tmH7IJBlGIh-UloKy0AMwAnh~H9QIcHwg__>)
# Advanced String Methods

We've covered a bunch of String class methods already, so let's keep building on those and run down some more advanced methods.

The string method **lower** will return the string with all characters changed to lowercase. The inverse of this is the **upper** method, which will return the string all in uppercase. Just like with previous methods, we call these on a string using dot notation, like **"this is a string".upper()**. This would return the string **"THIS IS A STRING"**. This can be super handy when checking user input, since someone might type in all lowercase, all uppercase, or even a mixture of cases.

You can use the **strip** method to remove surrounding whitespace from a string. Whitespace includes spaces, tabs, and newline characters. You can also use the methods  **lstrip** and **rstrip** to remove whitespace only from the left or the right side of the string, respectively.

The method **count** can be used to return the number of times a substring appears in a string. This can be handy for finding out how many characters appear in a string, or counting the number of times a certain word appears in a sentence or paragraph.

If you wanted to check if a string ends with a given substring, you can use the method **endswith**. This will return True if the substring is found at the end of the string, and False if not.

The **isnumeric** method can check if a string is composed of only numbers. If the string contains only numbers, this method will return True. We can use this to check if a string contains numbers before passing the string to the **int()** function to convert it to an integer, avoiding an error. Useful!

We took a look at string concatenation using the plus sign, earlier. We can also use the **join** method to concatenate strings. This method is called on a string that will be used to join a list of strings. The method takes a list of strings to be joined as a parameter, and returns a new string composed of each of the strings from our list joined using the initial string. For example, **" ".join(["This","is","a","sentence"])** would return the string **"This is a sentence"**.

The inverse of the join method is the **split** method. This allows us to split a string into a list of strings. By default, it splits by any whitespace characters. You can also split by any other characters by passing a parameter.
# Review: Formatting strings

This reading contains the code used in the instructional videos from [**Formatting strings**](https://www.coursera.org/learn/google-beginning-your-python-journey/lecture/cx2nU/formatting-strings)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![Screenshot 2025-03-09 161742.png](<https://media-hosting.imagekit.io//534aefb86d694dd4/Screenshot%202025-03-09%20161742.png?Expires=1836125264&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=mdnZvP2eN6cXFRfVuYnJp~GVFg~-xmkKkSpYOWbKOQxdk4AXXz-gjN-JXexSr-KvG3bLbbsoiaIhOZRqTrUxvuZcODj0Z9bG9U9ldLGm9QFWTGMZjStLkBoiScLz3Swt3qkdi7Qq5vXgYtb42rwJKk6D8PoPfmfst5~jcVlX50MP~YWSGlpFuZntJWM8oRoKWchFSuWx7dMvESih1C-gs~TZr4oXm8LHwSRmc~TnkRyGy-MN8~rg4FhRHhrUdxAIdDjz5qjv1ryXzQo2JknESAmA6zgHH~HXxC5Rg0JmmcfGTciInTuME-aZcIv8iHRE9DMdrDGvldDBJkLWkiaEaA__>)
# String Formatting

You can use the **format** method on strings to concatenate and format strings in all kinds of powerful ways. To do this, create a string containing curly brackets, **{}**, as a placeholder, to be replaced. Then call the format method on the string using *.format()* and pass variables as parameters. The variables passed to the method will then be used to replace the curly bracket placeholders. This method automatically handles any conversion between data types for us.

If the curly brackets are empty, they’ll be populated with the variables passed in the order in which they're passed. However, you can put certain expressions inside the curly brackets to do even more powerful string formatting operations. You can put the name of a variable into the curly brackets, then use the names in the parameters. This allows for more easily readable code, and for more flexibility with the order of variables.

You can also put a formatting expression inside the curly brackets, which lets you alter the way the string is formatted. For example, the formatting expression **{:.2f}** means that you’d format this as a float number, with two digits after the decimal dot. The colon acts as a separator from the field name, if you had specified one. You can also specify text alignment using the greater than operator: **>**. For example, the expression **{:>3.2f}** would align the text three spaces to the right, as well as specify a float number with two decimal places. String formatting can be very handy for outputting easy-to-read textual output.
# String Reference Guide

In Python, there are a lot of things you can do with strings. In this study guide, you’ll find the most common string operations and string methods.

## String operations
![image](https://github.com/user-attachments/assets/18a6e1e9-e27f-4ce9-93f1-7e4d81c991e1)
![image](https://github.com/user-attachments/assets/3fe652f5-5288-410b-9c65-0ad3c7349c58)
![image](https://github.com/user-attachments/assets/0c6b4893-ef7b-44dc-bb69-a7d1e095f896)
![image](https://github.com/user-attachments/assets/6567f65e-3b0e-4da3-a547-4d2fb8665607)
![image](https://github.com/user-attachments/assets/ee17a0dd-4de1-4b72-a397-0c2f11a1d4c2)
The String methods page in the Python documentation has a more complete list of the available string methods.
# Formatting strings reference guide

Most programs eventually need to provide some kind of output or feedback to the user. Formatting the output makes it easier to read.

For example, imagine you are working in a farmer’s market and need to generate receipts for your customers. You need to weigh the items, calculate the total price for each item (weight times the price per pound), and then add sales tax to the subtotal. Your first attempt might look like this:
![image](https://github.com/user-attachments/assets/93ad01b3-9970-4427-92f9-ec17d408adc1)
If you run the above code, you’ll notice the output looks a bit messy:

**Subtotal: 27.245**

**Sales Tax: 1.8049812500000002**

**Total: 29.049981250000002**

We’d much prefer the output to look like a real register receipt:

**Subtotal:     $27.25**

**Sales Tax:    $ 1.80**

**Total:        $29.05**

The way to do this in Python is by formatting strings in your output.

Python offers different ways to format strings. In the [Formatting Strings video](https://www.coursera.org/learn/python-crash-course/lecture/cx2nU/formatting-strings), we explained the **format()** method. In this reading, we'll highlight three different ways of formatting strings. For this course you need to know only the **format()** method. But on the internet, you might find any of the three, so it's a good idea to know that the others exist.

## **Using the** **format()** **method**

The **format()** method takes a string containing special placeholders, called the format string, and replaces the special placeholder characters **{}** with the value of the arguments you pass. The arguments are converted to strings if they weren’t already. The number of arguments you pass must exactly match the number of placeholders in the format string:
![image](https://github.com/user-attachments/assets/40cd4c16-77da-4aee-98b8-b04479b78441)
**You are buying 3.0 pounds of peaches at 2.99 per pound.**

You can also consume the arguments to **format()** in any order you want by specifying the index inside the placeholder. As with lists and arrays, the index always starts with 0. You can even use an index more than once. Here you can see we’re using the second argument twice.
![image](https://github.com/user-attachments/assets/1ac13315-f473-4acc-bbfc-0a2e333bf4b5)
**Peaches are 2.99 per pound, and you have 3.0 pounds of peaches.**

A third option for the placeholders is to use field names instead of indexes. This can make your code much more readable.

![image](https://github.com/user-attachments/assets/f7137fe9-4311-41c6-89a9-f1885af5bf65)
**Peaches are 2.99 per pound, and you have 3.0 pounds of peaches.**

Python also gives you many options to control the appearance of the output. Remember the messy output from the first example? You can have Python automatically round things up to the nearest penny and produce nice output by using a *formatting expression*. In the example below, the code tells Python to round up the numbers to two decimal places.

![image](https://github.com/user-attachments/assets/e3924f8d-f469-4f61-9d36-9e4f7591d506)
**Subtotal:     $    27.25**

**Sales Tax:    $     1.80**

**Total:        $    29.05**

Everything inside the placeholder after the “**:**” colon is part of the formatting expression. The expression “**:10,.2f**” means “make the output 10 characters wide, use digit separators if the amount is over 1000, output no more than 2 digits after the decimal, and expect the input to be a floating-point decimal number”.

The following table gives you some more examples of formatting expressions:

**Formatting expressions**

![image](https://github.com/user-attachments/assets/0f70913d-cdad-4966-9041-15865de141c8)
Check out the official documentation for [all available expressions](https://docs.python.org/3/library/string.html#format-specification-mini-language).

## **Formatted string literals (Optional)**

The formatted string literal feature, added in Python 3.6, isn’t used a lot yet. Again, it's included here in case you run into it in the future, but it's not needed for this or any upcoming courses.

A formatted string literal or **f-string** is a string that starts with '**f**' or '**F**' before the quotes. These strings might contain **{}** placeholders using expressions like the ones used for **format()** method strings.

The important difference between **f-strings** and the **format()** method is that f-strings take the value of the variables from the current context, instead of taking the values from parameters.

Examples:

>>> name = "Micah"

>>> print(f'Hello {name}')

Hello Micah

>>> item = "Purple Cup"

>>> amount = 5

>>> price = amount * 3.25

>>> print(f'Item: {item} - Amount: {amount} - Price: {price:.2f}')

Item: Purple Cup - Amount: 5 - Price: 16.25

Check out the official documentation for [f-strings](https://docs.python.org/3/reference/lexical_analysis.html#f-strings).

## **Old string formatting (Optional)**

The **format()** method was introduced in Python 2.6. Before that, the **% (modulo)** operator could be used to get a similar result. Although this method is **no longer recommended** for new code, you might come across it in someone else's code. This is what it looks like:

**"base string with %s placeholder" % variable**

The **% (modulo)** operator returns a copy of the string where the placeholders indicated by **%** followed by a formatting expression are replaced by the variables after the operator.

To replace more than one value, you need to supply the values as a tuple. The formatting expression must match the value type.

**"base string with %d and %d placeholders" % (value1, value2)**

Variables can also be replaced by name using a dictionary syntax (you’ll learn about dictionaries in an upcoming video).

**print("%(var1)d %(var2)d" % {"var1":value1, "var2":value2})**

The formatting expressions are mostly the same as those of the **format()** method.

**"Item: %s - Amount: %d - Price: %.2f" % (item, amount, price)**

Check out the official documentation for [old string formatting](https://docs.python.org/3/library/stdtypes.html#old-string-formatting).
# Study Guide: Strings

This study guide provides a quick-reference summary of what you learned in this lesson and serves as a guide for the upcoming practice quiz. The string readings in this section are great syntax guides to help you on the Strings Practice Quiz.

In the Strings segment, you learned about the parts of a string, string indexing and slicing, creating new strings, string methods and operations, and formatting strings.

## **Knowledge**

### **String Operations and Methods**

- **.format()** - String method that can be used to concatenate and format strings.
    - **{:.2f}** Within the .format() method, limits a floating point variable to 2 decimal places. The number of decimal places can be customized.
- **len(string)** - String operation that returns the length of the string.
- **string**String operation that accesses the character at index of the string, where indexing starts at zero.
- **string[x:y]** - String operation that accesses a substring starting at index and ending at index [y-1]. If x is omitted, its value defaults to 0. If y is omitted, the value will default to len(string).
- **string.replace(old, new)** - String method that returns a new string where all occurrences of an old substring have been replaced by a new substring.
- **string.lower()** String method that returns a copy of the string with all lowercase characters.

## **Coding skills**

### **Skill Group 1**

- Use a **for** loop to iterate through each letter of a string.
- Add a character to the front of a string.
- Add a character to the end of a string.
- Use the **.lower()** string method to convert the case (uppercase/lowercase) of the letters within a string variable. *This method is often used to eliminate cases as a factor when comparing two strings. For example, all lowercase “cat” is not equal to “Cat” because “Cat” contains an uppercase letter. To be able to compare the two strings to see if they are the same word, you can use the .lower() string method to remove capitalization as a factor in the string comparison.*


![image](https://github.com/user-attachments/assets/e5904f65-683b-4053-a4de-c1d9d2f8c1f3)
![image](https://github.com/user-attachments/assets/f481de21-8eb3-4db1-b485-d8ae6a1fdebc)
### **Skill Group 2**

- Use the **format()** method, with **{}** placeholders for variable data, to create a new string.
- Use a formatting expression, like **{:.2f}**, to format a float variable and configure the number of decimal places to display for the float.
![image](https://github.com/user-attachments/assets/9073f807-ca47-4ba7-bd69-a41c1894b0ab)
### **Skill Group 3**

- Within the **format()** parameters, select characters at specific index positions from a variable string.
- Use the **format()** method, with **{}** placeholders for variable data, to create a new string.

![image](https://github.com/user-attachments/assets/a6753a45-823b-4248-b44e-bd89870d09f1)
### **Skill Group 4**

- Use the **.replace()** method to replace part of a string.
- Use the **len()** function to get the number of index positions in a string.
- Slice a string at a specific index position.
![image](https://github.com/user-attachments/assets/5c0123f1-3f3b-4c5a-9a4a-f21d40070eba)
## **Python practice information**

For additional Python practice, the following links will take you to several popular online interpreters and codepads:

- [Welcome to Python](https://www.python.org/shell/)
- [Online Python Interpreter](https://www.onlinegdb.com/online_python_interpreter)
- [Create a new Repl](https://repl.it/languages/python3)
- [Online Python-3 Compiler (Interpreter)](https://www.tutorialspoint.com/execute_python3_online.php)
- [Compile Python 3 Online](https://rextester.com/l/python3_online_compiler)
- [Your Python Trinket](https://trinket.io/python3)

# Review: What is a list?

This reading contains the code used in the instructional videos from [**What is a list?**](https://www.coursera.org/learn/python-crash-course/lecture/DoC7j/what-is-a-list)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![image](https://github.com/user-attachments/assets/4bd45ac3-370d-4bfa-8f56-4f426f379a0a)
![image](https://github.com/user-attachments/assets/b29ac0c4-6a8d-48e8-ad0d-c5a2b0a57dcd)
![image](https://github.com/user-attachments/assets/b5d2f782-80f3-4b19-a834-df3c025f5177)
# Lists Defined

Lists in Python are defined using square brackets, with the elements stored in the list separated by commas: **my_list = ["This", "is", "a", "list"]**. You can use the **len()** function to return the number of elements in a list: **len(my_list)** would return **4**. You can also use the **in** keyword to check if a list contains a certain element. If the element is present, it will return a True boolean. If the element is not found in the list, it will return False. For example, **"This" in my_list** would return True in our example. Similar to strings, lists can also use indexing to access specific elements in a list based on their position. You can access the first element in a list by doing **my_list[0]**, which would allow you to access the string **"This"**.

In Python, lists and strings are quite similar. They’re both examples of sequences of data. Sequences have similar properties, like (1) being able to iterate over them using **for loops**; (2) support indexing; (3) using the **len** function to find the length of the sequence; (4) using the plus operator **+** in order to concatenate; and (5) using the **in** keyword to check if the sequence contains a value. Understanding these concepts allows you to apply them to other sequence types as well.

# Review: Modifying the contents of a list

This reading contains the code used in the instructional videos from [**Modifying the contents of a list**](https://www.coursera.org/learn/python-crash-course/supplement/v07vB/modifying-lists)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.

![image.png](attachment:71ad997e-e6f7-44d8-ba2d-011dc09c9f4d:image.png)

![image.png](attachment:7237bb55-e11d-4660-9384-b394bc555a1a:image.png)

![image.png](attachment:5e50df94-510b-4508-980d-23d1061ee99b:image.png)
