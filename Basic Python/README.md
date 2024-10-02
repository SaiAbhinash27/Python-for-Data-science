
# Installation and Basic Python

1. Python installation
2. Basic Python
 - Data types
 - Variables
 - Operators
 - Print statements
 - Variable Ip address
 - Libraries
 - Built in functions
 - type conversions

# Python Installation:

### Download Python Installer:

1. Go to the official Python website.
2. Navigate to the Downloads section.
3. Download the latest version of Python for Windows (usually a
exe installer).

### Run the Installer:

1. Once downloaded, double-click the installer .exe file.
2. nsure to check the box "Add Python to PATH" during installation to make Python accessible from the command line.
3. Click "Install Now" to begin the installation.

### Verify Installation:

1. Open Command Prompt (cmd) or PowerShell.
2. Type python --version to check if Python is installed correctly and to see the installed version.

*IDEs and Text Editors: Choose an IDE (e.g., PyCharm, VS Code) or a text editor (e.g., Sublime Text, Atom) to write and execute Python code.

# Basic Python

# Variables
- variable is reserved memory location to store the values given by the user.
-Variable is an identifier used to hold the value
- the variable will store the data in RAM (temporary memory).
-In python we dont need to specify the type of variable becuase python is loosely typed language. 


#### Naming Rules

1. Variable name sholud not start with number (always use alphabets or underscore(_).
2. phython is very case sensitive for example 'Sai' is differnt ffrom 'sai'
3. Varibble always should be in single word if you want to use multiple words use '_' b/w the the words exaple: Sai_Abhinash
4. The below mention epunctuations are not allowed in variable name: !@#$%^&*()-+=:;'",<>./?`~
#####Examples:
- var_1 = 'python' 
- var_2 = 123
#### Variable declaration:
Python allows to assign a value to multiple varibles and multiple values to multiple varibles in a singlr statement which is also known as multiple assignment.

##### assign single value to multiple variables:
- a=b=c=27
##### assign multiple values to single variable:
- a,b,c = 27,18,17



### Data types
1. Integer (int)
2. Float (float)
3. String (str)
4. List
5. Tuple
6. Set 
7. Dictionary

#### Integer
int or integer is a whole number (positive or negative) without decimals of unlimited length.
Example: 
x=10,
y=2024

#### Float
Float or floating point number is a number either positive or negative containing atleast one or more decimals. Example: x= 1.1, y=2.1.

#### String

- In python stribgs are created by enclosing the characters or sequence of characters in quotes.
- python allows us to use single quotes, double quotes or triple quotes.
##### Example: 
- Str_1 = '123'
- Str_2= "Virat"
##### Common Python String Built-in Functions

1. **`len()`**  
   **Definition:** Returns the number of characters in a string.  
   **Example:** `len("hello")` returns `5`.

2. **`.lower()`**  
   **Definition:** Converts all characters in the string to lowercase.  
   **Example:** `"Hello".lower()` returns `"hello"`.

3. **`.upper()`**  
   **Definition:** Converts all characters in the string to uppercase.  
   **Example:** `"Hello".upper()` returns `"HELLO"`.

4. **`.strip()`**  
   **Definition:** Removes leading and trailing whitespace from the string.  
   **Example:** `" Hello ".strip()` returns `"Hello"`.

5. **`.replace(old, new)`**  
   **Definition:** Replaces all occurrences of the substring `old` with `new`.  
   **Example:** `"Hello world".replace("world", "Python")` returns `"Hello Python"`.

6. **`.find(sub)`**  
   **Definition:** Returns the lowest index of the substring `sub` if found; otherwise, returns `-1`.  
   **Example:** `"Hello".find("e")` returns `1`.

7. **`.count(sub)`**  
   **Definition:** Returns the number of occurrences of the substring `sub` in the string.  
   **Example:** `"banana".count("a")` returns `3`.

8. **`.split(separator)`**  
   **Definition:** Splits the string into a list of substrings based on the specified separator. If no separator is specified, it splits on whitespace.  
   **Example:** `"Hello, world".split(", ")` returns `["Hello", "world"]`.

9. **`.join(iterable)`**  
   **Definition:** Concatenates the elements of an iterable (like a list) into a single string, using the string as the separator.  
   **Example:** `", ".join(["apple", "banana", "cherry"])` returns `"apple, banana, cherry"`.

10. **`.startswith(prefix)`**  
    **Definition:** Returns `True` if the string starts with the specified prefix; otherwise, returns `False`.  
    **Example:** `"Hello".startswith("H")` returns `True`.

11. **`.endswith(suffix)`**  
    **Definition:** Returns `True` if the string ends with the specified suffix; otherwise, returns `False`.  
    **Example:** `"Hello".endswith("o")` returns `True`.

12. **`.capitalize()`**  
    **Definition:** Capitalizes the first character of the string and makes all other characters lowercase.  
    **Example:** `"hello world".capitalize()` returns `"Hello world"`.

13. **`.title()`**  
    **Definition:** Capitalizes the first character of each word in the string.  
    **Example:** `"hello world".title()` returns `"Hello World"`.

14. **`.swapcase()`**  
    **Definition:** Swaps the case of all characters in the string (uppercase to lowercase and vice versa).  
    **Example:** `"Hello".swapcase()` returns `"hELLO"`.

15. **`.isalpha()`**  
    **Definition:** Returns `True` if all characters in the string are alphabetic; otherwise, returns `False`.  
    **Example:** `"Hello".isalpha()` returns `True`.








