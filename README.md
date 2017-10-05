# RubyPrac
#### Ruby is a powerful, flexible programming language you can use in web/Internet development, to process text, to create games, and as part of the popular Ruby on Rails web framework. Ruby is:

* High-level, meaning reading and writing Ruby is really easy—it looks a lot like regular English!

* Interpreted, meaning you don't need a compiler to write and run Ruby.

* Object-oriented, meaning it allows users to manipulate data structures called objects in order to build and execute programs.

* Easy to use. Ruby was designed by Yukihiro Matsumoto (often just called "Matz") in 1995. Matz set out to design a language that emphasized human needs over those of the computer, which is why Ruby is so easy to pick up.

# Data Types: Numbers, Strings, Booleans
#### In Ruby, your information (or data) can come in different types. There are three data types in Ruby that we're interested in right now: numbers, booleans (which can be true or false), and strings (words or phrases like "I'm learning Ruby!").

#### Computer programs exist to quickly analyze and manipulate data. For that reason, it's important to understand the different data types that we can use in programs.

#### Reminder: never use quotation marks (' or ") with booleans, or Ruby will think you're talking about a string (a word or phrase) instead of a value that can be true or false. It's also important to remember that Ruby is case-sensitive (it cares about capitalization).

# Variables 
#### One of the most basic concepts in computer programming is the variable. You can think of a variable as a word or name that grasps a single value. 

# Math
#### Ruby isn't limited to simple expressions; it can also do all the math you learned about in school.

#### Below are six arithmetic operators:
* Addition (+)
* Subtraction (-)
* Multiplication (*)
* Division (/)
* Exponentiation (**)
* Modulo (%)

####  Exponentiation raises one number (the base) to the power of the other (the exponent).
#### Modulo returns the remainder of division

# 'puts' and 'print'
#### The print command just takes whatever you give it and prints it to the screen. puts (for "put string") is slightly different: it adds a new (blank) line after the thing you want it to print.
#### No parentheses or semicolons needed!

# Everything in Ruby is an Object
#### Because everything in Ruby is an object, everything in Ruby has certain built-in abilities called methods. Think of methods as "skills" that certain objects have. For instance,strings (words or phrases) have built-in methods that can tell you the length of the string, reverse the string, and more.

# The '.length' Method
#### Methods are summoned using a `.`. If you have a string, `"I love espresso"`, and take the `.length` of it, Ruby will return the length of the string (that is, the number of characters—letters, numbers, spaces, and symbols). 

#### Taking the length of input can be useful if, for example, you want to make a website that takes credit card payments. Ruby can check to make sure the credit card number appears to be valid.

# '.upcase' & '.downcase'
#### Two more method are the `.upcase` and `.downcase` methods; it convert a string to ALL UPPER CASE or all lower case, respectively.