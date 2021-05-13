

# Python-Resource-for-Beginners


<h2 id='top'>Index</h2>

<a href="#intro">1. Python Introduction</a>

<a href="#install">2. Python Installation</a>

<a href="#list">3. Python Syntax </a>

<a href="#list">4. Python Comments</a>

<a href="#list">5. Python Variables and Data Type</a>

<a href="#list">6. Python Operators</a>

<a href="#list">7. Python String</a>

<a href="#list">8. Python String Formatting</a>

<a href="#list">9. Python Lists</a>

<a href="#list">10. Python Tuples</a>

<a href="#list">11. Python Sets</a>

<a href="#list">12. Python Dictionaries</a>

<a href="#list">13. Python Booleans</a>

<a href="#list">14. Python For Loops</a>

<a href="#list">15. Python While Loops</a>

<a href="#list">16. Python If...Else</a>

<a href="#list">17. Python Functions</a>

<a href="#list">18. Python Lambda </a>

<a href="#list">19. Python Arrays</a>

<a href="#list">20. Python Classes,Objects & Methods</a>

<a href="#list">21. Python Inheritance </a>

<a href="#list">22. Python Iterators</a>

<a href="#list">23. Python Scope</a>

<a href="#list">24. Python Modules</a>

<a href="#list">25. Python Dates</a>

<a href="#list">26. Python Math</a>

<a href="#list">27. Python JSON</a>

<a href="#list">28. Python RegEx</a>

<a href="#list">29. Python PIP</a>

<a href="#list">30. Python Try...Expect</a>

<a href="#list">31. Python User Input</a>


<h3 id='intro'>1. Python Introduction</h3>

 This project include all python related materials for newbies where  anyone can learn basic python programming.


<h3>1.1 What is Python?</h3>

Python is a programming language. It was created by Guido van Rossum, and released in 1991.

<strong>Basically It is used for:</strong> 

<li>web development (server-side)</li>
<li>software development</li>
<li>mathematics</li>
<li>system scripting,</li>
<li>Data Science & Machine Learning.</li>


<hr>

<h3 id="install">2. Python Installation</h3>

PCs and Macs will have python already installed. However,if you find that, you do not have python installed on your computer, then you can download it for free from the following website: https://www.python.org/. For running code experiments and editing, a preferable platform is   Jupyter Notebook (Anaconda3). It's user-friendly, and it has already been built in the latest python version. For downloading follow this website: https://www.anaconda.com/products/individual#Downloads

<a href="#top">Back to Index </a>
<hr>
<h3>Python Syntax </h3>

Python Indentation

<a href="#top">Back to Index </a>
<hr>
<h3 id='list'>7. Python String</h3>

Anything inside a single coat or a double coat is called a string. A string is a text. In Python, strings can be declared in two ways (excluding docstring). With a single coat or with a double coat. For example: 

`'Hello' is the same as "Hello"`

<h4>Assign String to a Variable</h4>

`Input: a = "Hello"` 
<br>
`       print(a)   `
<br>
`Output: a = Hello`

<h4>String Length</h4>

A string is a collection of different characters. We can also access different characters from strings according to the index. But how do you know how many characters there are in a string? To get the length of a string, use the len() function. For example:

` a = "Hello World!"`
<br>
`print(len(a))`

<h4>Strings are Lists</h4>

 Python does not have a character data type, a single character is simply a string with a length of 1.Square brackets can be used to access elements of the string. For example: 
 
`a = "Hello World!"`
<br>
`print(a[1])`
<br>
`Output : e `

<h4>Looping Through a String</h4>

Since strings are arrays, we can loop through the characters in a string, with a for loop. For Example:

`for x in "Apple"`
<br>
`print(x)`


<h4>Slicing String</h4>

return a range of characters by using the slice syntax.Specify the start index and the end index, separated by a colon, to return a part of the string. For Example:

Get the characters from position 2 to position 5 (not included):

` a = "Hello, World!"`
<br>
`print(b(2:5))`


<h4>Slice From the Start</h4>

By leaving out the start index, the range will start at the first character. Get the characters from the start to position 5 (not included), For example:

` a = "Hello, World!"`
<br>
`print(b(:5))`


<h4>Slice From the End</h4>

By leaving out the end index, the range will go to the end.Get the characters from position 2, and all the way to the end.For example:

` a = "Hello, World!"`
<br>
`print(b(3:))`


<h4>Negative Indexing</h4>

Use negative indexes to start the slice from the end of the string,For example:

` a = "Hello, World!"`
<br>
`print(b(-5:-2))`

<h4>Modify Strings: Upper Case</h4>

Python has a set of built-in methods that we can use on strings. The upper() method returns the string in upper case. For example:

` a = "Hello, World!"`
<br>
`print(a.upper())`

<h4>Modify Strings: Lower Case</h4>

The lower() method returns the string in lower case.For example:

` a = "Hello, World!"`
<br>
`print(a.lower())`


<h4>Modify Strings: Remove Whitespace</h4>

Whitespace is the space before and/or after the actual text, and very often you want to remove this space.The strip() method removes any whitespace from the beginning or the end. For example:

` a = "Hello, World!"`
<br>
`print(a.strip())`


<h4>Modify Strings: Replace String</h4>

The replace() method replaces a string with another string, For example:

` a = "Hello, World!"`
<br>
`print(a.replace("H","J"))`

<h4>Modify Strings: Split String</h4>

The split() method splits the string into substrings if it finds instances of the separator. For example:

` a = "Hello, World!"`
<br>
`print(a.split(","))` # returns ['Hello', ' World!']

<a href="#top">Back to Index </a>
<hr>




<h3 id='list'>10. Python Lists</h3>
Lists are used to store multiple items in a single variable.

Lists are one of 4 built-in data types in Python used to store collections of data, the other 3 are Tuple, Set, and Dictionary, all with different qualities and usage.

<strong>Lists are created using square brackets:</strong>

`thislist = ["apple", "banana", "cherry"]`
<br>
`print(thislist)`


	

<a href="#top">Back to Index </a>
<hr>


