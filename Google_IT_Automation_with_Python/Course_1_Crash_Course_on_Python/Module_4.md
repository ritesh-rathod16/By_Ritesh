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

Lists in Python are defined using square brackets, with the elements stored in the list separated by commas: **my_list = ["This", "is", "a", "list"]**. You can use the **len()** function to return the number of elements in a list: **len(my_list)** would return **4**. You can also use the **in** keyword to check if a list contains a certain element. If the element is present, it will return a True boolean(a boolean is a data type that can have one of two values: True or False). If the element is not found in the list, it will return False. For example, **"This" in my_list** would return True in our example. Similar to strings, lists can also use indexing to access specific elements in a list based on their position. You can access the first element in a list by doing **my_list[0]**, which would allow you to access the string **"This"**.

In Python, lists and strings are quite similar. They’re both examples of sequences of data. Sequences have similar properties, like (1) being able to iterate over them using **for loops**; (2) support indexing; (3) using the **len** function to find the length of the sequence; (4) using the plus operator **+** in order to concatenate; and (5) using the **in** keyword to check if the sequence contains a value. Understanding these concepts allows you to apply them to other sequence types as well.

# Review: Modifying the contents of a list

This reading contains the code used in the instructional videos from [**Modifying the contents of a list**](https://www.coursera.org/learn/python-crash-course/supplement/v07vB/modifying-lists)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.

![Screenshot 2025-03-13 191313](https://github.com/user-attachments/assets/cfbfdbc1-c339-42b3-8ed4-34a0535e3828)
![Screenshot 2025-03-13 201919](https://github.com/user-attachments/assets/ec14e5ff-1696-4475-a455-83d416aeecec)
![Screenshot 2025-03-13 201951](https://github.com/user-attachments/assets/207c7de3-7301-4c34-bf5d-fad7a90dd303)
# Review: Lists and tuples

This reading contains the code used in the instructional videos from [**Lists and tuples**](https://www.coursera.org/learn/python-crash-course/lecture/jxAkv/lists-and-tuples)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![image](https://github.com/user-attachments/assets/fe0abed8-1635-4c9c-8b7b-188e0002a366)
![image](https://github.com/user-attachments/assets/4ac6aa55-53e8-4d81-96f6-9bf84b69829c)
# Tuples

As we mentioned earlier, strings and lists are both examples of sequences. Strings are sequences of characters, and are immutable. Lists are sequences of elements of any data type, and are mutable. The third sequence type is the tuple. Tuples are like lists, since they can contain elements of any data type. But unlike lists, tuples are immutable. They’re specified using parentheses instead of square brackets.

You might be wondering why tuples are a thing, given how similar they are to lists. Tuples can be useful when we need to ensure that an element is in a certain position and will not change. Since lists are mutable, the order of the elements can be changed on us. Since the order of the elements in a tuple can't be changed, the position of the element in a tuple can have meaning. A good example of this is when a function returns multiple values. In this case, what gets returned is a tuple, with the return values as elements in the tuple. The order of the returned values is important, and a tuple ensures that the order isn’t going to change. Storing the elements of a tuple in separate variables is called unpacking. This allows you to take multiple returned values from a function and store each value in its own variable.

# Review: Iterating over lists and tuples

This reading contains the code used in the instructional videos from [**Iterating over lists and tuples**](https://www.coursera.org/learn/python-crash-course/lecture/M7Dbr/iterating-over-lists-and-tuples)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![image](https://github.com/user-attachments/assets/67cbc50a-45f8-4392-b396-8daa5da52e66)

# Iterating Over Lists Using Enumerate

When we covered *for* loops, we showed the example of iterating over a list. This lets you iterate over each element in the list, exposing the element to the for loop as a variable. But what if you want to access the elements in a list, along with the index of the element in question? You can do this using the **enumerate()** function. The enumerate() function takes a list as a parameter and returns a tuple for each element in the list. The first value of the tuple is the index and the second value is the element itself.

# Review: List comprehensions
![image](https://github.com/user-attachments/assets/bcbfed74-686f-4fb9-8dd4-ad0d9f0f9007)

This reading contains the code used in the instructional videos from [**List comprehensions**](https://www.coursera.org/learn/python-crash-course/lecture/J9gYw/list-comprehensions)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.

![image](https://github.com/user-attachments/assets/20af468e-d509-47e3-a764-525b3b0edead)

# List Comprehension Examples
You can create a list from an iterable using a for loop, which is a useful way to iterate over an iterable:
![image](https://github.com/user-attachments/assets/6f531c3a-951c-43b7-a39f-5c32ca3cf97f)
There is also a more streamlined way to do this by using a list## **For** **loop vs. list comprehension**

The two code blocks below compare performing the same process using a list comprehension and a **for** loop. The line **[x*2 for x in range(1,11)]** is a simple list comprehension. This single line of code iterates over a range from 1 to 10, multiplies each element in the range by 2, and ultimately creates a new list from all multiples of 2 from 2 to 20.

The second block of code below is a for loop designed to carry out the same function as the list comprehension. The **for** loop, however, requires three lines of code.comprehension. A list comprehension allows you to create a new list from an iterable in a single line. This line achieves the same result as the previous for loop, but in a more concise way:


**new_list = [do_something(thing) for thing in list_of_things]**

List comprehensions can be used with tuples in Python, too. Here is an example of a list of tuples. In this example each tuple will contain the numbers 1, 2, and 3. This code will create 5 sets of (1,2,3).
![image](https://github.com/user-attachments/assets/fda9baa8-96bc-4fd7-bd2d-57834440542d)
## **List comprehension with conditional statement**

You can also use conditionals with list comprehensions to build even more complex and powerful statements. You can do this by appending an **if** statement to the end of the list comprehension. For example, **[x for x in range(1,101) if x % 10 == 0]** generates a new list containing all the integers divisible by 10 from 1 to 100. The **if** statement evaluates each value in the range from 1 to 100 to check if it’s evenly divisible by 10. If it is, the number is added to a new list.
![image](https://github.com/user-attachments/assets/12e09945-2d1a-4082-a8d3-80accab19073)
List comprehensions can be really powerful, but they can also be complex, resulting in code that’s hard to read. Be careful when using them, because they might make it more difficult for someone else looking at your code to easily understand what the code is doing. It is a best practice to add descriptive comments about any list comprehensions used in your code. This helps to communicate the purpose of list comprehensions to other coders. Comments will also help you remember the goal of the code when performing future code additions and maintenance.

## **Practice exercise**

This exercise walks you through how to write a list comprehension to create a list of squared numbers (n*n or n**2). It needs to return a list of squares of consecutive numbers between “start” and “end” *inclusively*. For example, squares(2, 3) should return a list containing [4, 9].

1. The function receives the variables “start” and “end” through the function parameters.
2. In the **return** line, start by entering the list brackets that will contain the list comprehension.
3. Between the brackets [ ]:
    a. Enter the arithmetic expression to square a variable “n”.
    b. To the right of the square expression, write a **for** loop that iterates over “n” in a **range()** from the “start” to “end” variables.
    c. Ensure the “end” range value is included in the **range()** by adding 1 to it.
4. Run your code to see if it works! If needed, the solution to this code is included in the “Study Guide: List Operations and Methods” reading under “Skill Group 2” (list comprehensions).
![image](https://github.com/user-attachments/assets/9c09acd3-edcd-42f0-96a2-d75eb15d780a)
# Study Guide: List Operations and Methods

This study guide provides a quick-reference summary of what you learned in this lesson and serves as a guide for the upcoming practice quiz.

In the [Lists and Tuples video](https://www.coursera.org/learn/python-crash-course/lecture/jxAkv/lists-and-tuples), you learned about the differences between lists and tuples, how to modify the contents of a list, how to iterate over lists and tuples, how to use the enumerate() function, and how to create list comprehensions.

## **Knowledge**

### **Common sequence operations**

Lists and tuples are both sequences and they share a number of sequence operations. The following common sequence operations are used by both lists and tuples:

- **len(sequence)** - Returns the length of the sequence.
- **for element in sequence** - Iterates over each element in the sequence.
- **if element in sequence** - Checks whether the element is part of the sequence.
- **sequence[x]** - Accesses the element at index of the sequence, starting at zero
- **sequence[x:y]** - Accesses a slice starting at index [x], ending at index [y-1]. If is omitted, the index will start at 0 by default. If [y] is omitted, the len(sequence) will set the ending index position by default.
- **for index, element in enumerate(sequence)** - Iterates over both the indices and the elements in the sequence at the same time.

Because integers are not iterable, they need to be converted to a range as such:
![image](https://github.com/user-attachments/assets/ad977574-e7ea-4c1f-8157-7c50f33abb1c)
### **List-specific operations and methods**

One major difference between lists and tuples is that lists are mutable (changeable) and tuples are immutable (not changeable). There are a few operations and methods that are specific to changing data within lists:

- **list[index] = x** - Replaces the element at index [n] with x.
- **list.append(x)** - Appends x to the end of the list.
- **list.insert(index, x)** - Inserts x at index position [index].
- **list.pop(index)** - Returns the element at [index] and removes it from the list. If [index] position is not in the list, the last element in the list is returned and removed.
- **list.remove(x)** - Removes the first occurrence of x in the list.
- **list.sort()** - Sorts the items in the list.
- **list.reverse()** - Reverses the order of items of the list.
- **list.clear()** - Deletes all items in the list.
- **list.copy()** - Creates a copy of the list.
- **list.extend(other_list)** - Appends all the elements of other_list at the end of list
- **map(function, iterable)** - Applies a given function to each item of an iterable (such as a list) and returns a map object with the results
- **zip(*iterables)** - Takes in iterables as arguments and returns an iterator that generates tuples, where the i-th tuple contains the i-th element from each of the argument iterables.

### **Tuple use cases**

Remember, there are a number of cases where using a tuple might be more suitable than other data types:

- Protecting data: Because tuples are immutable, they can be used in situations where you want to ensure the data you have cannot be changed. This can be particularly helpful when dealing with sensitive or important information that should remain constant throughout the execution of a program.
- Hashable keys: Because they're immutable, tuples can be used as keys on dictionaries, which can be useful for complex keys.
- Efficiency: Tuples are generally more memory-efficient than lists, making them advantageous when dealing with large datasets.

### **The tuple()** **operator**

The **tuple()** operator is used to convert an iterable (like a list, string, or set) into a tuple. Let's see an example:
![image](https://github.com/user-attachments/assets/e24163ce-ee5c-4022-9149-2bf42de83421)
This can sometimes lead to confusion, particularly when tuples are used in function calls or with operators that also use parentheses.

### **Tuples with mutable objects**

Although tuples themselves are immutable, they can contain mutable objects, such as lists. This means that although the tuple cannot be modified (for example, you can't add or remove elements), the mutable elements within the tuple can be changed.
![image](https://github.com/user-attachments/assets/3570c279-3f29-4ce0-8da5-57f2232c3914)
### **Returning multiple values from functions**

One of the most useful aspects of tuples in Python is their ability to return multiple values from a function. This allows a function to produce more than one result, providing flexibility and improving code readability.

Here's an example:
![image](https://github.com/user-attachments/assets/9139ea1f-3190-4dce-a7d1-0dc0c3d5c822)
In the above function, the four arithmetic calculations are returned as a tuple, which can be assigned to a single variable (result), or "unpacked" into multiple variables:
![image](https://github.com/user-attachments/assets/2cef150d-e2f1-428c-b779-cdbc99c3464f)
This is a powerful feature that makes Python functions extremely versatile.

### **List comprehensions**

A list comprehension is an efficient method for creating a new list from a sequence or a range in a single line of code. It is a best practice to add descriptive comments about any list comprehensions used in your code, as their purpose can be difficult to interpret by other coders.

- **[expression for variable in sequence]** - Creates a new list based on the given sequence. Each element in the new list is the result of the given expression.
    - Example: **my_list = [ x*2 for x in range(1,11) ]**
- **[expression for variable in sequence if condition]** - Creates a new list based on a specified sequence. Each element is the result of the given expression; elements are added only if the specified condition is true.
    - Example: **my_list = [ x for x in range(1,101) if x % 10 == 0 ]**

Note that tuples do not have comprehensions but a similar functionality can be achieved with:

**tuple(i for i in (1, 2, 3))**

### **When to use** **for** **loops or list comprehensions**

In Python, list comprehensions are generally used for creating new lists from existing ones in a concise and readable manner, especially when the task involves simple transformations or filtering of elements.

**for** loops are more versatile and are preferred when the operation is more complex, requires multiple lines of code, involves statements other than expression (like **print**, **pass**, **continue**, **break**), or when you need to iterate over a list without creating a new one.

## **Coding skills**

### **Skill Group 1**

- Use a **for** loop to modify elements of a list.
- Use the **list.append()** method.
- Use the **string.endswith()** and **string.replace()** methods to modify the elements within a list.
### **Skill Group 2**

- Use a list comprehension to return values
![image](https://github.com/user-attachments/assets/119d2d10-2488-4844-89c3-ae685a32df9e)
### **Skill Group 3**

- Use a list comprehension to modify elements of a list.
- Use the **string.replace()** method within a list comprehension.
- Use the **string[index]** method within a list comprehension.
![image](https://github.com/user-attachments/assets/347030cb-6f03-4e79-bfa5-37cb5252a7c4)
### **Skill Group 4**

- Use the **string.split()** method to separate a string into a list of individual words.
- Iterate over the new list using a for loop.
- Modify each element in the list by slicing the element’s string at a given [1:] index position and appending the substring to the end of the element.
- Convert a list back into a string.
![image](https://github.com/user-attachments/assets/7a62a128-4dfc-4b63-8977-f22297d71115)
### **Skill Group 5**

- Use the **string.join()** method to concatenate a string that provides a list name and its elements.
![image](https://github.com/user-attachments/assets/68387a09-d4d5-4f00-8421-ef5a76de72b5)
### **Skill Group 6**

- Use **map()** and convert the map object to a list so we can print all the results at once.
![image](https://github.com/user-attachments/assets/e534933a-ee16-41a5-9826-4c5b2b7c4c0b)
### **Skill Group 7**

- Use **zip()** to combine a list of names and ages into a list of tuples, and print all the tuples at once
![image](https://github.com/user-attachments/assets/9582337f-3230-4e7b-88ae-416a6728275f)
## **Resources**

For additional information about list and tuple operations and methods, please visit:

- [Common Sequence Operations](https://docs.python.org/3/library/stdtypes.html#sequence-types-list-tuple-range) - Official python.org documentation for list, tuple, and range sequence operations.
- [Lists](https://docs.python.org/3/library/stdtypes.html#lists) - Official python.org documentation for list operations and methods.
- [Tuples](https://docs.python.org/3/library/stdtypes.html#tuples) - Official python.org documentation for tuple operations and methods

# Review: What is a dictionary?

This reading contains the code used in the instructional videos from [**What is a dictionary?**](https://www.coursera.org/learn/python-crash-course/lecture/AsGUr/what-is-a-dictionary)

## **Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![image](https://github.com/user-attachments/assets/794d5d92-4100-4984-b35c-f8ad43cb83b7)
# Dictionaries Defined

Dictionaries are another data structure in Python. They’re similar to a list in that they can be used to organize data into collections. However, data in a dictionary isn't accessed based on its position. Data in a dictionary is organized into pairs of keys and values. You use the key to access the corresponding value. Where a list index is always a number, a dictionary key can be a different data type, like a string, integer, float, or even tuples.

When creating a dictionary, you use curly brackets: **{}**. When storing values in a dictionary, the key is specified first, followed by the corresponding value, separated by a colon. For example, **animals = { "bears":10, "lions":1, "tigers":2 }** creates a dictionary with three key value pairs, stored in the variable animals. The key "bears" points to the integer value 10, while the key "lions" points to the integer value 1, and "tigers" points to the integer 2. You can access the values by referencing the key, like this: **animals["bears"]**. This would return the integer 10, since that’s the corresponding value for this key.

You can also check if a key is contained in a dictionary using the **in** keyword. Just like other uses of this keyword, it will return True if the key is found in the dictionary; otherwise it will return False.

Dictionaries are mutable, meaning they can be modified by adding, removing, and replacing elements in a dictionary, similar to lists. You can add a new key value pair to a dictionary by assigning a value to the key, like this: **animals["zebras"] = 2**. This creates the new key in the animal dictionary called zebras, and stores the value 2. You can modify the value of an existing key by doing the same thing. So **animals["bears"] = 11** would change the value stored in the bears key from 10 to 11. Lastly, you can remove elements from a dictionary by using the **del** keyword. By doing **del animals["lions"]** you would remove the key value pair from the animals dictionary.
# Review: Iterating over the contents of a dictionary

This reading contains the code used in the instructional videos from [**Iterating over the contents of a dictionary.**](https://www.coursera.org/learn/python-crash-course/lecture/PBuyf/iterating-over-the-contents-of-a-dictionary)

**Introduction**

This follow-along reading is organized to match the content in the video that follows. It contains the same code shown in the next video. These code blocks will provide you with the opportunity to see how the code is written, allow you to practice running it, and can be used as a reference to refer back to.

You can follow along in the reading as the instructor discusses the code or review the code after watching the video.
![image](https://github.com/user-attachments/assets/13b073a2-81be-43d8-a45e-045e3a406e4c)
![image](https://github.com/user-attachments/assets/91ed7843-fc7f-4ea5-9ac3-adf58eb8322f)
# Use while loops and if else statements for dictionaries

You’ve learned that **if** statements are used as a form of decision making. **If** statements tell your computer to perform a conditional execution based on the value of an expression. Using else in conjunction with an if statement allows your computer to evaluate for multiple conditions and run a statement if other conditions are **false**. In other words, **else** is the condition that runs if all other statements are not **true**.

You’ve also learned that **while** loops instruct your computer to continuously execute your code based on the value of a condition, but it will only continue to execute as long as the evaluation statement is **True**. Once that statement is no longer **True**, the loop exits and the next line of code will be executed.

In this reading, you will learn about using **while** loops and **if else** statements for dictionaries, and see examples demonstrating the benefits of using them in your Python code.

## **while** **loops**

Dictionaries are used to organize elements into collections using pairs of keys and values. But what do you do when you need to search a collection of data for a value? That’s where **while** loops come in. A **while** loop will iterate through conditions until one comes up **False**, unlike a **for** loop, which will iterate through the entire dictionary, one row at a time. Consider the following example:

**for item in someDictionary:**


versus:

**while someDictionary:**



Notice the difference between the **for** loop and the **while** loop—unlike the **for** loop, the **while** loop does not require calling a variable to act as a counter, or the “item” variable in the **for** loop. **for** loops anticipate a specific structure—like a list—and when called, will iterate through the entire list, until it gets to the end.  **while** loops can be used more universally when the structure of your data set is more ambiguous.

## **if else** **statements**

**if else** statements are useful if you want to find and check for specific values and perform specific actions based on the result. Consider the following example:
![image](https://github.com/user-attachments/assets/9470fb37-eddd-4628-b1e7-b8e78848656e)
The goal here is to search if the key “banana” exists in the dictionary. The first line determines the key, “banana,” which is what we want to search for in the dictionary. The second line uses an if statement to search for the key within the dictionary and prints the value of that particular key **if** the condition is **True**. The **else** statement will return that the key was not found in the dictionary if the condition is **False**. As an example, this code block will return “The value of banana is 3” or “banana is not found in the dictionary” when it is run.

## **Key takeaways**

**while** loops and **if else** statements are methods you can use to search for values within a dictionary. If you want to search through an entire dictionary quickly to find a value, use a **while** loop. If you want to search through a dictionary to find and check a value, use an **if else** statement to return the value and perform specific actions based on the result.
![image](https://github.com/user-attachments/assets/a65cc594-1a27-49a5-b41c-caf9c08c4378)

# Study Guide: Dictionary Methods
This study guide provides a quick-reference summary of what you learned in this lesson and serves as a guide for the upcoming practice quiz. 

In the Dictionary segment, you learned about the properties of the Python dictionary data type, how dictionaries differ from lists, how to iterate over the contents of a dictionary, and how to use dictionaries with lists and strings.

Knowledge
Python dictionaries are used to organize elements into collections. Dictionaries include one or more keys, with one or more values associated with each key. 

Syntax
![image](https://github.com/user-attachments/assets/8587462e-f43e-431e-ab96-b883b68c2b71)
## Operations

- **len(dictionary)** - Returns the number of items in a dictionary.
- **for key in dictionary** Iterates over each key in a dictionary.
- **for key, value in dictionary.items()** Iterates over each key,value pair in a dictionary.
- **if key in dictionary** - Checks whether a key is in a dictionary.
- **dictionary[key]** - Accesses a value using the associated key from a dictionary.
- **dictionary[key] = value** Sets a value associated with a key.
- **del dictionary[key]** Removes a value using the associated key from a dictionary.

## Methods

- **dictionary.get(key, default)** Returns the value corresponding to a key, or the default value if the specified key is not present.
- **dictionary.keys()** Returns a sequence containing the keys in a dictionary.
- **dictionary.values()** Returns a sequence containing the values in a dictionary.
- **dictionary[key].append(value)** - Appends a new value for an existing key.
- **dictionary.update(other_dictionary)** - Updates a dictionary with the items from another dictionary. Existing entries are updated; new entries are added.
- **dictionary.clear()** Deletes all items from a dictionary.
- **dictionary.copy()** Makes a copy of a dictionary.

# Dictionaries versus Lists

Dictionaries are similar to lists, but there are a few differences:

## Both dictionaries and lists:

- are used to organize elements into collections;
- are used to initialize a new dictionary or list, use empty brackets;
- can iterate through the items or elements in the collection; and
- can use a variety of methods and operations to create and change the collections, like removing and inserting items or elements.

## Dictionaries only:

- are unordered sets;
- have keys that can be a variety of data types, including strings, integers, floats, tuples;.
- can access dictionary values by keys;
- use square brackets inside curly brackets { };
- use colons between the key and the value(s);
- use commas to separate each key group and each value within a key group;
- make it quicker and easier for a Python interpreter to find specific elements, as compared to a list.

### Dictionary Example:
![image](https://github.com/user-attachments/assets/5aa1c376-dbec-43dc-b11f-42b1c1d86bf6)
## Lists only:

- are ordered sets;
- access list elements by index positions;
- require that these indices be integers;
- use square brackets [ ];
- use commas to separate each list element.

### **List Example:**
![image](https://github.com/user-attachments/assets/229bd081-0616-4df5-b881-974451fc16ec)
# Coding skills

### **Skill Group 1**

- Iterate over the key and value pairs of a dictionary using a **for** loop with the **dictionary.items()** method to calculate the sum of the values in a dictionary.
![image](https://github.com/user-attachments/assets/87b53448-c98a-470f-b505-b91cee7a6c8c)
### **Skill Group 2**

- Concatenate a value, a string, and the key for each item in the dictionary and append to the end of a new listusing the **list.append(x)** method.
- Iterate over keys with multiple values from a dictionary using nested **for** loops with the **dictionary.items()** method.
![image](https://github.com/user-attachments/assets/b51d9346-dd19-45e4-955e-6eaf61d0395b)
**Skill Group 3**

- Use the **dictionary[key] = value** operation to associate a value with a key in a dictionary.
- Iterate over keys with multiple values from a dictionary, using nested **for** loops and an **if**statement, and the **dictionary.items()** method.
- Use the **dictionary[key].append(value)** method to add the key, a string, and the key for each item in the dictionary.
![image](https://github.com/user-attachments/assets/37df016a-7f34-4e9c-a43e-5cbe7492bafe)
# Resources

For additional information about dictionaries, please visit:

- [Mapping Types — dict](https://docs.python.org/3/library/stdtypes.html#mapping-types-dict) Official python.org documentation for dictionary methods
- [Python Dictionaries](https://www.w3schools.com/python/python_dictionaries.asp) - Tutorial with interactive code blocks for practicing using dictionary methods and operations
# What Is a Method?

In Python, methods are behaviors associated with object parameters that modify the state of that object. They are essentially functions that belong to a specific instance of a class. This means that calling a method on a list, for example, only modifies that instance of the list, and not all lists globally.

Methods in Python fall into several categories:

- Instance methods
- Class methods
- Static methods

## **Instance methods**

**Instance methods** are the most common type of methods in Python. You define instance methods within a class by creating functions inside the class definition. When you instantiate instances of a class, those individual instances can have their methods called so the program can control and modify those instances directly. Instance methods can take a parameter called **self**, which represents the instance the method is being executed on, that allows you to access attributes of the instance using dot notation, like **self.name**, which will access the name attribute of that specific instance of the class object. When you have variables that contain different values for different instances, these are called instance variables.

## **Class methods**

**Class methods**, on the other hand, are called for the class itself instead of an instance. They are marked with a **@classmethod** decorator and take a **cls** parameter that points to the class—and not any specific instance—when the method is called. One common use-case for class methods is to create and modify data structures that contain records for all instances of a class. Usually, programmers make a list inside the class definition, and methods to add instances of the class to that list in order to keep track of that class.

## **Static methods**

Lastly, static methods, marked with a **@staticmethod** decorator, do not take a self or a **cls** parameter. Static methods behave like plain functions, except that you can call them directly from the class. It is important to note that you do not have to actually instantiate the class, the methods just reside in there. This is because class definitions are themselves an object (i.e., an instance of abstract base class), which reduces overhead and allows functions to be encapsulated in an easy-to-use encapsulation. Programmers use static methods when the method does not need to access any instance or class-specific data.

## **Choosing a method type**

The type of method you choose to use—instance, class, or static—depends on what data the method needs to access. Think of these methods as different tools in your toolbox, each with a different use-case depending on the data you need to work with.

- Instance methods are for individual object data
- Class methods for shared data,Static methods for related tasks that don't need to access or modify any object or class data

## **Key takeaways**

Remember, methods in Python are a way to bundle behavior with objects, allowing you to interact with and modify the state of those objects. However, static methods offer a way to bundle functions together, to be used in general on any other type of object. Bundling functions together helps organize functions in a clean manner and helps package them for reuse in other coding projects.
# Constructors and Other Special Methods (Optional)

As you have been learning, you can use a class in Python to bundle data and functionality together. When you create a new class, you create a new type of object.

## Creating an instance of a class

Each time you create an instance of a class, Python calls a special class method the constructor. The constructor’s job is to set up the object, meaning that instance of the class, so it’s ready to be used. Usually this means initializing some variables and doing other simple housekeeping.

When writing a Python class, you define a method called **__init__** to be your constructor. The special name tells Python to use that method as the constructor. Just like any other method, the constructor can take arguments. When making an argument to the class, the first constructor must always be **self**.

Here’s a simple example of a constructor that initializes an object’s variables.
![image](https://github.com/user-attachments/assets/019d2f30-c0a4-441f-9549-7194a379fd00)
## Modify variables

If we wanted to make our Apple class more flexible, we could allow the user to specify the color and flavor as arguments when creating the object. We can modify our constructor to take those arguments and use them:
![image](https://github.com/user-attachments/assets/94e465e5-af8a-4449-a439-565db8a70264)
## Other special methods

As you might expect, Python classes have many other special methods. Most of these have default implementations provided by the Python standard library, but you are free to override the behavior of any of them. Like the **__init__** constructor, special methods begin and end with a double underscore, and this is called **dunder method**. The word “dunder” combines the “d” in double and the “under” in **unders**core.

For example, the **__str__** special method controls how your object is converted to a string representation for output. When you **print()** something, Python calls the object’s **__str__()** method and outputs whatever that method returns. In most cases, the default output is just the class name and a memory location:

**>>> print(honeycrisp)
<__main__.Apple object at 0x7ffa68d78970>**

Let’s override the **__str__** method to be more useful for apples:
![image](https://github.com/user-attachments/assets/009672e3-8151-448c-9254-c33a2b9f684d)
Here are some of the other special methods you can override in your own classes:

- **__len__** returns the length of the object or collection.
- **__contains__** tests whether the object contains an item.
- **__eq__** tests whether two objects are equal.

## Key takeaways

A constructor (such as **__init__**) is a special class method that sets up the object in Python. When making an argument to a class, the first constructor must always be **self**. Python classes have many special methods available in the standard library. These methods can be overridden using the method called **dunder method**.
# Special Methods
Instead of creating classes with empty or default values, we can set these values when we create the instance. This ensures that we don't miss an important value and avoids a lot of unnecessary lines of code. To do this, we use a special method called a constructor. Below is an example of an Apple class with a constructor method defined.
![image](https://github.com/user-attachments/assets/dc403430-0925-4fd4-afbe-da4072ae9cbf)

When you call the name of a class, the constructor of that class is called. This constructor method is always named __init__. You might remember that special methods start and end with two underscore characters. In our example above, the constructor method takes the self variable, which represents the instance, as well as color and flavor parameters. These parameters are then used by the constructor method to set the values for the current instance. So we can now create a new instance of the Apple class and set the color and flavor values all in go:
![image](https://github.com/user-attachments/assets/f21849ab-0a01-47aa-a42b-0d8e440d9d72)
In addition to the __init__ constructor special method, there is also the __str__ special method. This method allows us to define how an instance of an object will be printed when it’s passed to the print() function. If an object doesn’t have this special method defined, it will wind up using the default representation, which will print the position of the object in memory. Not super useful. Here is our Apple class, with the __str__ method added:
![image](https://github.com/user-attachments/assets/0f8be863-ff65-475b-9c53-01010eaded2a)
Now, when we pass an Apple object to the print function, we get a nice formatted string:
![image](https://github.com/user-attachments/assets/87587340-799f-4fb3-a1f4-f39997d117d2)
This apple is red and its flavor is sweet

It's good practice to think about how your class might be used and to define a __str__ method when creating objects that you may want to print later.

# Methods as special operators

You have already learned about methods and how they are just functions that belong to a class. They define the behavior that an object of the class can perform. Special operators are specific symbols or keywords that are built-in and provide special behavior when used with certain data types or objects. In your class, you can define methods to implement or override the standard behavior of Python operators, thus creating methods as special operators.

In this reading you will learn about the different types of special operators, how to override the standard operators and embed them in your code, and see examples along the way.

## **Different types of special operators**

Python supports a variety of different operators that you can use in your code to make life easier for you. Some of the more common operators are:

- Arithmetic operators. These include **+** (addition),  (subtraction),  (multiplication), **/** (division), and ***** (exponentiation).
- Comparison operators. These include **==** (equality), **!=** (inequality), **<** (less than), and **>=** (greater than or equal to)
- Logical operators. These include **and**, **or**, and **not**.
- Assignment operators. These include **=** (simple assignment), **+=** (addition assignment), and **%=** (modulo assignment)

**Note:** This is not an all-inclusive list, but different examples of common operators that you would use in Python.

## **Performing special operations**

Every special operator has a corresponding **dunder method** that implements the operation. In Python, you denote a dunder method by placing double underscores at the beginning and end of the name; in fact, the term “dunder” comes from this use of **d**ouble **unders**cores. You can change how an operator behaves with an instance of your object by overriding the implementation. Let’s look at an example:

**class Triangle:**

**def __init__(self, base, height):**

**self.base = base**

**self.height = height**

In this example, the **Triangle** class has a method **__init__()**which is called a constructor and is used to initialize the object’s attributes.

**def area(self):**

**return 0.5 * self.base * self.height**

This part of the code, area(self) method, computes the area of the triangle based on its height and base length.

**def __add__(self, other):**

**return self.area() + other.area()**

This method overrides the + operator to "add" two triangles together.

**triangle1 = Triangle(10, 5)**

**triangle2 = Triangle(6, 8)**

**print("The area of triangle 1 is", triangle1.area())**

**print("The area of triangle 2 is", triangle2.area())**

**print("The area of both triangles is", triangle1.area() + triangle2.area())**

The output of this problem is:

**The area of triangle 1 is 25.0**

**The area of triangle 2 is 24.0**

**The area of both triangles is 49.0**

Putting it all together, this is what the code should look like:

![image](https://github.com/user-attachments/assets/86f325cb-3629-48c1-90a3-f6c453ac412b)
For a full list of operators and the method names you can use to override their behavior, view this resource:

- [Mapping operators to functions](https://docs.python.org/3/library/operator.html#mapping-operators-to-functions)

## **Key takeaways**

Python allows you to override or implement standard operations in your code to make your code cleaner for yourself and others to read. Being able to override certain behaviors allows you to control the output of your code and provides flexibility in how you write code.
# Study guide: Classes and methods (optional)

In the past few videos, we’ve seen how to define **classes** and **methods** in Python. Here, you’ll find a run-down of everything we’ve covered, so you can refer to it whenever you need a refresher.

## **Defining classes and methods**
![image](https://github.com/user-attachments/assets/b6e1b0b4-6af4-420b-9e7a-ed7dff903aef)
## **Classes and instances**

- Classes define the behavior of all instances of a specific class. In Python, the code defining a class is, itself, an object; classes can be used without instantiating a single object, such as when using static methods
- Remember, each variable of a specific class is an instance or object.
- In Python, "getters and setters" are methods used for controlling access to an object's attributes. The getter method retrieves the value of an attribute, while the setter method sets or changes the attribute's value, often including some sort of validation or modification to the data before setting the value.
- You can access an instance's attribute, like **name**, by calling self.name within the class methods, or **<instance>.name** outside the class, where **<instance>** is the specific instance of the class you're working with.Objects can have attributes, which store information about the object.
- You can make objects do work by calling their methods.
- The first parameter of the methods, **(self)**, represents the current instance.
- Methods are just like functions, but they can only be used through a class.
- You can use class methods in conjunction with a class variable to track the number of instances of a class, incrementing the class variable each time an instance is created in the class's **__init__** method.

## **Special methods**

- Special methods start and end with **__**.
- Special methods have specific names, like **__init__** for the constructor or **__str__** for the conversion to string.
- The methods **__str__** and **__repr__** allow you to define human-readable and unambiguous string representations of your objects, respectively.
- By defining methods like **__eq__**, **__ne__**, **__lt__**, **__gt__**, **__le__**, and **__ge__**, you can control how **objects** of your **class** are compared.

## **Documenting classes, methods, and functions**

- You can add documentation to **classes**, **methods**, and **functions** by using **docstrings** right after the definition. Like this:
![image](https://github.com/user-attachments/assets/28cf1449-a49d-4328-aa10-2f9469080542)
A great way to use docstrings is to have an example of using the function, with its expected output.
![image](https://github.com/user-attachments/assets/8fd64feb-99c7-4e35-a34e-96bd986365e4)
When in an interactive Python section, you can display docstrings with:
![image](https://github.com/user-attachments/assets/1aab0f9a-2a8b-487e-b384-f99a7c9913d4)
Or in your code code you can retrieve it and use it in your program just as you would with any other string:
![image](https://github.com/user-attachments/assets/549fd59b-4de6-4cd9-95f7-b8ba84add09a)
Reference: Data model
# Glossary terms from course 1, module 4

## **Terms and definitions from Course 1, Module 4**

**Dictionaries:** A data type used to organize elements into collections, taking the form of pairs of keys and values

**List comprehensions:** Create new lists based on sequences or ranges

**String:** A data type used to represent a piece of text. sequences of characters and are immutable

**Tuples:** Sequences of elements of any type that are immutable, written parentheses instead of square brackets
# Study Guide: Module 4 Graded Quiz

It is time to prepare for the Module 4 Graded Quiz. Please review the following items from this module before beginning the quiz. If you would like to refresh your memory on these materials, please also revisit the Study Guides located before each practice quiz in Module 4: [Study Guide: Strings](https://www.coursera.org/learn/python-crash-course/supplement/ydyIo/study-guide-strings),  [Study Guide: Lists Operations and Methods](https://www.coursera.org/learn/python-crash-course/supplement/sbRdF/study-guide-lists-operations-and-methods), and [Study Guide: Dictionary Methods](https://www.coursera.org/learn/python-crash-course/supplement/Cc19J/study-guide-dictionary-methods).

# Knowledge

- How to output a list of the keys in a Python dictionary.
- How to determine the output of a string index range used on a string.
- Determine what a list should contain after the .insert() method is used on the list.
- How to replace a specific word in a sentence with the same word in all uppercase letters.
- How to use a dictionary to count the frequency of letters in a string.

## 

## Operations, Methods, and Functions

- **String Methods, Operations, and Functions**
    - .upper()
    - .lower()
    - .split()
    - .format()
    - .isnumeric()
    - .isalpha()
    - .replace()
    - string index [ ]
    - len()
- **List Operations and Methods**
    - .reverse()
    - .extend()
    - .insert()
    - .append()
    - .remove()
    - .sort()
    - list comprehensions [ ]
    - list comprehensions with if condition
- **Dictionary Operations and Methods**
    - .items()
    - .update()
    - .keys()
    - .values()
    - .copy()
    - dictionary[key]
    - dictionary[key] = value

# Coding Skills

## **Skill 1:** Using **string** methods

- Separate numerical values from text values in a string using **.split()**.
- Iterate over the elements in a string.
- Test if the element contains letters with **.isalpha()**.
- Assign the elements of the split string to new variables.
- Trim any extra white space using **.strip()**.
- Format a string using **.format()** and **{ }** variable placeholders
 ![image](https://github.com/user-attachments/assets/987504d6-1f21-4e25-909c-8b135fcf184d)
- Use the len() function to measure a string.
![image](https://github.com/user-attachments/assets/af157665-8eeb-4348-b847-757f2336eb98)
## **Skill 2:** Using **list** methods

- Reverse the order of a list using the **.reverse()** method.
- Combine two lists using the **.extend()** method.
![image](https://github.com/user-attachments/assets/d0ccc514-b555-4076-8501-6ae7611331c1)
## **Skill 3:** Using a **list comprehension**

- Use a list comprehension as a shortcut for creating a new list from a range.
- Include a calculation with a **for** loop **in** a **range** with 2 parameters (lower, upper+1).
![image](https://github.com/user-attachments/assets/46255a11-7595-49cc-a80c-d0abaea89de2)
- Use a list comprehension [ ] with a for loop and an if condition.
![image](https://github.com/user-attachments/assets/7ee5ddf9-46cc-4149-900d-b90716c7e812)
## **Skill 4:** Using **dictionary** methods

- Iterate through the keys and values of a dictionary.
- Return the keys and values in a formatted string using the .format() function.
![image](https://github.com/user-attachments/assets/9ee80aab-6912-435a-a127-210fa8976e3d)
- Create a copy of a dictionary.
- Iterate through the values of the new dictionary.
- Change each value in the new dictionary, while keeping the same keys.
![image](https://github.com/user-attachments/assets/150a198e-9bd6-4308-9b3a-68ebbdad5f4d)
# Reminder: Correct syntax is critical

Using precise syntax is critical when writing code in any programming language, including Python. Even a small typo can cause a syntax error and the automated Python-coded quiz grader will mark your code as incorrect. This reflects real life coding errors in the sense that a single error in spelling, case, punctuation, etc. can cause your code to fail. Coding problems caused by imprecise syntax will always be an issue whether you are learning a programming language or you are using programming skills on the job. So, it is critical to start the habit of being precise in your code now.

No credit will be given if there are any coding errors on the automated graded quizzes - including minor errors. Fortunately, you have 3 optional retake opportunities on the graded quizzes in this course. Additionally, you have unlimited retakes on practice quizzes and can review the videos and readings as many times as you need to master the concepts in this course.

Now, before starting the graded quiz, please review this list of common syntax errors coders make when writing code.

**Common syntax errors:**

- Misspellings
- Incorrect indentations
- Missing or incorrect key characters:
    - Parenthetical types - ( curved ), [ square ], { curly }
    - Quote types - "straight-double" or 'straight-single', “curly-double” or ‘curly-single’
    - Block introduction characters, like colons - :
- Data type mismatches
- Missing, incorrectly used, or misplaced Python reserved words
- Using the wrong case (uppercase/lowercase) - Python is a case-sensitive language

## 

# Resources

For additional Python practice, the following links will take you to several popular online interpreters and codepads:

- [Welcome to Python](https://www.python.org/shell/)
- [Online Python Interpreter](https://www.onlinegdb.com/online_python_interpreter)
- [Create a new Repl](https://repl.it/languages/python3)
- [Online Python-3 Compiler (Interpreter)](https://www.tutorialspoint.com/execute_python3_online.php)
- [Compile Python 3 Online](https://rextester.com/l/python3_online_compiler)
- [Your Python Trinket](https://trinket.io/python3)
 #                                                           >>>> YOU HAVE SUCCESSFULLY COMPLETED MODULE 4 <<<<
