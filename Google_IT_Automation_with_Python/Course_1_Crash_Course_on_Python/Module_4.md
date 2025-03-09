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

- **len(string)** - Returns the length of the string

![image](https://github.com/user-attachments/assets/18a6e1e9-e27f-4ce9-93f1-7e4d81c991e1)

